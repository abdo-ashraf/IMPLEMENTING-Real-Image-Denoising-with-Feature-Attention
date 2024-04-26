# IMPLEMENTING-Real-Image-Denoising-with-Feature-Attention
## Hyperparameters:
  - BATCH_SIZE=64
  - seed = 6908
  - lr = 1e-04
  - epoch=5
  - image_patch_size = (40, 40, 3)

## Results I achieved:
### For RIDNET model:
  - PSNR of Noisy Image :  20.3 db
  - PSNR of Denoised Image :  26.3 db <br/>

Predictions of patches for RIDNET model
![3fe33736-e3fd-481a-b0bb-e07432796f00](https://github.com/abdo-ashraf/IMPLEMENTING-Real-Image-Denoising-with-Feature-Attention/assets/88582125/5fb51106-8e92-470e-b320-761fa1350932)<br/>

Predictions of patches for RIDNET model
![fa5a38ab-5f8e-4f96-a0f9-22b6bd8ac452](https://github.com/abdo-ashraf/IMPLEMENTING-Real-Image-Denoising-with-Feature-Attention/assets/88582125/4a0fc920-1712-48f8-943c-27885ba1bf63)<br/>

-----------------
### For DnCNN model:
  - PSNR of Noisy Image :  20.3 db
  - PSNR of Denoised Image :  22.4 db <br/>

Predictions of patches for DnCNN model
![31847587-65de-41b2-9f78-ce354f02320a](https://github.com/abdo-ashraf/IMPLEMENTING-Real-Image-Denoising-with-Feature-Attention/assets/88582125/e09f3877-6d68-45dd-9008-64e939dd0dea)<br/>

ONE full image example for DnCNN prediction
![291c7a80-60b9-4470-b830-553e88276b60](https://github.com/abdo-ashraf/IMPLEMENTING-Real-Image-Denoising-with-Feature-Attention/assets/88582125/20bed1dc-256a-4f16-b440-4cf0db6dd0c7)<br/>

## Comparison between my results and the results mentioned in the paper
- I will compare the results on BSD dataset as this is the only dataset that I could get.<br/>
Paper model results
![Screenshot 2024-04-27 002409](https://github.com/abdo-ashraf/IMPLEMENTING-Real-Image-Denoising-with-Feature-Attention/assets/88582125/773e4db5-954f-4049-aa73-88d561e5798f)<br/>
My results
![Screenshot 2024-04-27 012034](https://github.com/abdo-ashraf/IMPLEMENTING-Real-Image-Denoising-with-Feature-Attention/assets/88582125/804bb4c5-13c6-4d2a-b904-5ff753439344)<br/>

- my model performance is less than paper model because my model trained only on small datasets because of lack of data resources
- my model training procedure:
![image](https://github.com/abdo-ashraf/IMPLEMENTING-Real-Image-Denoising-with-Feature-Attention/assets/88582125/bac8e54e-f8b0-4b68-aaa5-b04b32afdf11)<br/>

