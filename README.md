## Machine Learning Projects

### Project 2

+   使用VGG-16完成CIFAR-10数据集多类别分类任务

```python
├── train.ipynb    # 模型结构定义与训练过程，不同结构、不同学习率对比
├── feature.ipynb  # 模型加载后推断中间层特征图并进行可视化
├── feature_maps   # 保存t-SNE处理后的中间层特征图
│   ├── layer.dense_6.npy
│   ├── layer.dense_7.npy
│   ├── layer.max_pooling2d_10.npy
│   ├── layer.max_pooling2d_11.npy
│   ├── layer.max_pooling2d_12.npy
│   ├── layer.max_pooling2d_13.npy
│   └── layer.max_pooling2d_14.npy
├── images         # 实验结果图
│   ├── learning_rate.png
│   ├── structure.png
│   └── tsne.png
└── training_log   # 保存训练过程的history日志
    ├── history_VGG16_baseline_norm_0607
    ├── history_VGG16_baseline_norm_1e-2_0606
    ├── history_VGG16_baseline_norm_1e-2_nodecay_0606
    ├── history_VGG16_baseline_norm_1e-3_0606
    ├── history_VGG16_baseline_norm_1e-3_nodecay_0606
    ├── history_VGG16_baseline_norm_1e-4_0606
    ├── history_VGG16_baseline_norm_1e-4_nodecay_0606
    ├── history_VGG16_baseline_norm_remove_layer15_0607
    └── history_VGG16_baseline_norm_remove_layer15_layer2_0607
```

