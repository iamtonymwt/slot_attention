# Slot Attention

## Requirements

- [Poetry](https://python-poetry.org/docs/)
- Python >= 3.8
- PyTorch >= 1.7.1
- Pytorch Lightning >= 1.1.4
- CUDA enabled computing device

Note: the model was run using a Nvidia Tesla V100 16GB GPU.

## Getting Started

Run `run.sh` to get started. This script will install the dependencies, download the [CLEVR](https://cs.stanford.edu/people/jcjohns/clevr/) dataset and run the model.

## Usage

```bash
python slot_attention/train.py
```

Modify `SlotAttentionParams` in `slot_attention/train.py` to modify the hyperparameters. See `slot_attenion/params.py` for the default hyperparamters.

## Acknowledgment
* Fork from this [repo](https://github.com/untitled-ai/slot_attention/tree/603787ddebde0e19ff9419e6a4e4311ce362956d)