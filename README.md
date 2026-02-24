# 🔬 Retinal Blood Vessel Segmentation
U-Net with ResNet-34 encoder trained on the FIVES fundus dataset.
- **Framework:** PyTorch + Segmentation Models PyTorch
- **Loss:** Dice + Tversky + Focal (combined)
- **Targets:** Dice ≥ 0.82, AUC ≥ 0.98