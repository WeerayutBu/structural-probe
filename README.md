# Structural Probes for GPT-2

Probing GPT-2 hidden states for syntactic structure using learned distance probes evaluated with UUAS.

## Setup

```bash
uv sync
source .venv/bin/activate
```

## Notebooks

- `train.ipynb` — train probe on toy sentences, saves `probe_B.pt`
- `visualize.ipynb` — visualize predicted vs. gold parse tree
- `probe.ipynb` — full training on UD English EWT, layer-wise UUAS
