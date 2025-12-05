## Pre-trained Model Weights

Due to file size constraints, pre-trained model weights are hosted separately on Google Drive.

---

### **Task 2: LLM Alignment**

**Download Link:** [Google Drive - PA5 Task 2 Weights](https://drive.google.com/drive/folders/1Ai9BFI0nnOQ6WIf4pof-ymotBKDZjwXP)

#### Available Checkpoints:
- **DPO:** `model_dpo_final.pth`
- **Reward Model:** `model_reward_final.pth`
- **PPO Sparse:** `model_ppo_sparse_final.pth`
- **PPO Dense:** `model_ppo_dense_final.pth`
- **GRPO:** `model_grpo_final.pth`

#### Setup Instructions:
1. Download the checkpoint files from the Google Drive link
2. Place them in the pth_models directory of Task 2 (make one):
```
LLM_Alignment/pth_models
├── model_dpo_final.pth
├── model_reward_final.pth
├── model_ppo_sparse_final.pth
├── model_ppo_dense_final.pth
└── model_grpo_final.pth
```
3. Run the evaluation scripts (weights will be loaded automatically)

**Note:** If checkpoints are missing, the training scripts will automatically retrain from scratch.

---

### **Task 3: Universal Sparse Autoencoders**

**Download Link:** [Google Drive - PA5 Task 3 Weights](https://drive.google.com/drive/u/0/folders/1JsRxfpzsvgo-p-5QuXvX-U9Ap3-tbbJ7)

#### Available Checkpoints:
- **Task 3.1:** USAE weights (`usae_ResNet_final.pth`, `usae_ViT_final.pth`, `training_logs.pt`)
- **Task 3.4:** Independent SAE weights (`independent_sae_resnet.pt`, `independent_sae_vit.pt`, `independent_saes.pt`)

#### Setup Instructions:
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