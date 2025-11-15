This repository contains my implementation of several Generative Adversarial Networks (GANs) trained on the CIFAR-10 dataset, as required for CPSC-8430 Homework 4.

The goal is to train a discriminator / generator pair using:
- **DCGAN**
- **Wasserstein GAN (WGAN)**
- **Auxiliary Classifier GAN (ACGAN)**

and then compare their performance using **generated images** and **Fréchet Inception Distance (FID)**.

---

## Repository structure

```text
HW4/
  dataset/           # CIFAR-10 data (not tracked in git if .gitignore is used)
  Results/           # Saved figures and numpy files from training & evaluation
  ACGAN.ipynb        # ACGAN training notebook
  DCGANwithFID.ipynb # DCGAN training + FID computation
  WGAN50epoch.ipynb  # WGAN training notebook
  FID_eval.ipynb     # Evaluation notebook (loads saved FIDs and plots/table)
  README.md
