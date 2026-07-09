# Machine Learning

Collection of machine learning models, experiments, and applications.

## Repository Structure

```
assets/         Images and static assets
checkpoints/    Training checkpoints
config/         Configuration files
data/
    raw/        Original datasets
    interim/    Intermediate datasets
    processed/  Processed datasets
    external/   Third-party datasets
logs/           Runtime logs
models/         Saved models and weights
notebooks/      Development notebooks
reports/        Figures, metrics, exported reports
src/            Source code
tests/          Unit tests
```

## Requirements

- Python 3.12+
- NVIDIA GPU (optional)
- CUDA-enabled TensorFlow environment

## Setup

Clone the repository.

```bash
git clone git@github.com:Whit31ister/<repository>.git
cd <repository>
```

Create a virtual environment.

```bash
python -m venv .venv
source .venv/bin/activate
```

or use the shared ML environment.

```bash
source ~/.venvs/ml/bin/activate
```

Install dependencies.

```bash
pip install -r requirements.txt
```

Launch Jupyter.

```bash
jupyter lab
```

or

```bash
jupyter notebook
```

## Notes

- Large datasets are not tracked by Git.
- Models, checkpoints, and generated reports should not be committed unless required.
- Development is performed in notebooks. Reusable code is moved into `src/`.

## License

MIT