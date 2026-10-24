# EfficientSegLite-ECC

本仓库公开实验室条件下 ECC（工程水泥基复合材料）狗骨头试件的裂缝图像、对应标签和模型权重。

- `dataset/RGB/`：1,440 张原图，尺寸为 256 × 256。
- `dataset/Label/`：与原图一一对应的 1,440 张标签图。
- `model_save.pth`：模型权重。

原图与标签按同一子目录内的文件名配对：`<name>.png` 对应 `<name>_enhanced.png`。
