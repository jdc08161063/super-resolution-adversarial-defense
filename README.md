# super-resolution-adversarial-defense

This repository is an PyTorch implementation of the paper **"Image Super-Resolution as a Defense Against Adversarial Attacks"**.

We use wavelet denoising and image super resolution as pre-processing steps to defend images against adversarial attacks. If you find our work useful in your research or publication, please cite our work:

We provide scripts for reproducing all the results from our paper. You can check the efficacy of our defense on your own adversarial images.

## Dependencies
* Python 3.6
* PyTorch >= 0.4.0
* **imageio**
* tqdm


## Clone the repository
Clone this repository into any place you want.
```bash
git clone https://github.com/aamir-mustafa/super-resolution-adversarial-defense
cd super-resolution-adversarial-defense
```
##Files:

1. Wavelet_Denoising.py

## Quick start (Demo)
You can test our super-resolution algorithm with your own images. Place your images in ``test`` folder. (like ``test/<your_image>``) We support  **jpg** files.

Run the script in ``src`` folder.
```bash
cd src       # You are now in */Defense_WD_SR/src
sh super_resolution.sh
```

You can find the result images from ```experiment/test/``` folder.