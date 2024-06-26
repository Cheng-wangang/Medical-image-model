5# Medical-image-model
这个项目包含一些常用且经典的网络架构整理，读研后期的才想起来整理，后期会不定时的更新。

- 整理这些网络架构有什么用？

  这些经典网络架构可以拿来做对比实验，也可以在网络的基础上进行修改缝合创新。

 
  
- 为什么不提供其他代码，例如预处理、模型训练、测试、评估等代码？

  每个人都应有自己的一个训练框架，你可以使用[nnUNet](https://github.com/MIC-DKFZ/nnUNet)的框架，也可以使用你任何熟悉的框架进行训练。
# 2024年5月20日
上传了医学图像分割领域的经典分割框架[TransUNet](https://github.com/Beckschen/TransUNet), 该项目代码可以直接使用，与原论文不一致的是：没有采用预训练的Vit进行初始化。仅复现了该网络的框架。可以在Config里面修改自己的配置。
## Acknowledgements
If you find 3D-TransUNet useful for your research and applications, please cite using this BibTeX:
```bibtex
@article{chen2023transunet3d,
  title={3D TransUNet: Advancing Medical Image Segmentation through Vision Transformers},
  author={Chen, Jieneng and Mei, Jieru and Li, Xianhang and Lu, Yongyi and Yu, Qihang and Wei, Qingyue},
  journal={arXiv preprint arXiv:2310.07781},
  year={2023}
}
```
# 2024年5月21日
上传了[TransBTS](https://github.com/Rubics-Xuan/TransBTS),该网络架构用于Brats脑肿瘤数据集的3D分割。可以在`model = BTS()`里面修改自己想要的参数.

上传了[AttUnet](https://github.com/ozan-oktay/Attention-Gated-Networks)，该网络是经典的医学图像分割框架。
## Acknowledgements
If you find TransBTS useful for your research and applications, please cite using this BibTeX:
```bibtex
@inproceedings{wang2021transbts,
  title={TransBTS: Multimodal Brain Tumor Segmentation Using Transformer},
  author={Wang, Wenxuan and Chen, Chen and Ding, Meng and Yu, Hong and Zha, Sen and Li, Jiangyun},
  booktitle={Medical Image Computing and Computer Assisted Intervention--MICCAI 2021: 24th International Conference, Strasbourg, France, September 27--October 1, 2021, Proceedings, Part I 24},
  pages={109--119},
  year={2021},
  organization={Springer}
}
@article{oktay2018attention,
  title={Attention u-net: Learning where to look for the pancreas},
  author={Oktay, Ozan and Schlemper, Jo and Folgoc, Loic Le and Lee, Matthew and Heinrich, Mattias and Misawa, Kazunari and Mori, Kensaku and McDonagh, Steven and Hammerla, Nils Y and Kainz, Bernhard and others},
  journal={arXiv preprint arXiv:1804.03999},
  year={2018}
}
```
# 2023年5月27日
上传了[SegMamba](https://github.com/ge-xing/SegMamba),运行该代码时请先装好`pytorch`，建议重新创建一个环境，然后按照官方的安装步骤安装依赖即可。
## Acknowledgements
```bibtex
@article{xing2024segmamba,
  title={Segmamba: Long-range sequential modeling mamba for 3d medical image segmentation},
  author={Xing, Zhaohu and Ye, Tian and Yang, Yijun and Liu, Guang and Zhu, Lei},
  journal={arXiv preprint arXiv:2401.13560},
  year={2024}
}
```
