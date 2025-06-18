# Generative Adversarial Networks

Two related assignments: **DCGAN / CGAN / WGAN-GP** on CIFAR-10 and **GANomaly**
for MNIST anomaly detection.

Built for an Artificial Neural Networks course assignment.

## What this project covers

- `gan/` — Generator/Discriminator training, sensitivity analysis, conditional GAN, WGAN-GP, t-SNE visualization
- `ganomaly/` — Autoencoder baseline and GANomaly training with ROC evaluation

## Project layout

| Path | Description |
|------|-------------|
| `gan/main.ipynb` | DCGAN, CGAN, and WGAN-GP experiments |
| `ganomaly/main.ipynb` | GANomaly anomaly detection |
| `Project_Description.pdf` | Assignment brief |
| `requirements.txt` | Python dependencies |

## Quick start

```bash
python -m venv .venv
.venv\Scripts\activate          # macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook gan/main.ipynb
```

CIFAR-10 and MNIST download automatically on first run. Notebook outputs are saved so plots render on GitHub.
