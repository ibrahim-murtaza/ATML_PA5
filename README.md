## Pre-trained Model Weights

Due to file size constraints, pre-trained model weights for Task 3 are hosted separately:

**Download Link:** [Google Drive - PA5 Task 3 Weights](https://drive.google.com/drive/u/0/folders/1JsRxfpzsvgo-p-5QuXvX-U9Ap3-tbbJ7)

### Available Checkpoints:
- **Task 3.1:** USAE weights (`usae_ResNet_final.pth`, `usae_ViT_final.pth`, `training_logs.pt`)
- **Task 3.4:** Independent SAE weights (`independent_sae_resnet.pt`, `independent_sae_vit.pt`, `independent_saes.pt`)

### Setup Instructions:
1. Download the checkpoint files from the Google Drive link
2. Place them in `./checkpoints/` directory:
```
   ./checkpoints/
   ├── usae_ResNet_final.pth
   ├── usae_ViT_final.pth
   ├── training_logs.pt
   ├── independent_sae_resnet.pt
   ├── independent_sae_vit.pt
   └── independent_saes.pt
```
3. Run the analysis scripts (weights will be loaded automatically)

**Note:** If checkpoints are missing, the training scripts will automatically retrain from scratch.