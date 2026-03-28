# Project

## Setup
```bash
uv sync
source .venv/bin/activate
```

## Verify GPU
```bash
python -c "import torch; print(torch.cuda.is_available())"
```
