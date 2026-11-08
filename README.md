# Streaming Neural Audio Codec for Low-Latency Speech Communication

Official implementation for the paper **"Streaming Neural Audio Codec for Low-Latency Speech Communication"**, accepted at ICASSP 2025.

## Status

**Released.** The complete training code, evaluation scripts, configuration files
and pretrained checkpoints are publicly available in this repository.

## Repository layout

```
├── src/          core model and training code
├── data/         data preparation and splits
├── experiments/  experiment configurations
├── results/      evaluation tables and figures
├── notebooks/    analysis notebooks
└── tests/        unit tests
```

## Quick start

```bash
git clone https://github.com/knobbyintens/eg2580-streaming-neural-audio-codec.git
cd eg2580-streaming-neural-audio-codec
pip install -r requirements.txt
python src/train.py --config experiments/icassp2025.yaml
```

## Citation

```bibtex
@inproceedings{brooks2025streamingcodec,
  title={Streaming Neural Audio Codec for Low-Latency Speech Communication},
  author={Brooks, Stephen and others},
  booktitle={ICASSP 2025},
  year={2025}
}
```
