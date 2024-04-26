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
  - PSNR of Denoised Image :  27.5 db
![c1405a6e-912e-4958-9dca-b51a6e43c92a](https://github.com/abdo-ashraf/IMPLEMENTING-Real-Image-Denoising-with-Feature-Attention/assets/88582125/d00b7d40-e693-4e95-aca0-e5c301629021)
      Predictions of patches for RIDNET model
![9ee78f92-8e22-4b51-a4ec-70b552d3f235](https://github.com/abdo-ashraf/IMPLEMENTING-Real-Image-Denoising-with-Feature-Attention/assets/88582125/abc11f8d-ba88-46f7-b491-9413931a0758)
      ONE full image example for RIDNET prediction
-----------------
### For DnCNN model:
  - PSNR of Noisy Image :  20.3 db
  - PSNR of Denoised Image :  25.3 db
![download](https://github.com/abdo-ashraf/IMPLEMENTING-Real-Image-Denoising-with-Feature-Attention/assets/88582125/7d1dfef9-652e-4dba-9fbf-7465194a5422)
      Predictions of patches for DnCNN model
![download](https://github.com/abdo-ashraf/IMPLEMENTING-Real-Image-Denoising-with-Feature-Attention/assets/88582125/dcb32fd6-060c-467f-b347-f8efc7054583)
      ONE full image example for DnCNN prediction
## Comparison between my results and the results mentioned in the paper
- I cannot compare my model results with paper model results as I cannot access datasets of real noisy images that they used to evaluate the model, also I trained the model for 5 epochs only, so my model performance will be less than paper model performance.
