# LIA - Laboratorio di Intelligenza Artificiale
LIA - Laboratorio di Intelligenza Artificiale presso l'Università degli Studi di Parma (6 CFU).

```bash
.
├── assets
│   └── # images
├── notebooks
│   ├── lessons
│   │   └── # lessons' notebooks
│   └── personal
│       └── # personal notebooks
└── slides
```

---

# Development Environment
Create a virtual environment:
```bash
conda create --name machine-learning python=3.11
conda activate machine-learning
```

Install requirements:
```bash
pip install -r requirements.txt
pre-commit install
pre-commit install --hook-type commit-msg
```

Then, you can change the _Jupyter kernel_ setting the **Conda** environment as the new one.

## Contributors

<a href="https://github.com/unipr-org/LIA/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=unipr-org/LIA" />
</a>
