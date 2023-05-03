# Benchmarking Polyp Segmentation Methods in Narrow-Band Imaging Colonoscopy Images (Accepted for IEEE JBHI)

- ## Abstract
    > In recent years, there has been significant progress in polyp segmentation in white-light imaging (WLI) colonoscopy images, particularly with methods based on deep learning (DL). However, little attention has been paid to the reliability of these methods in narrow-band imaging (NBI) data. NBI improves visibility of blood vessels and helps physicians observe complex polyps more easily than WLI, but NBI images often include polyps with small/flat appearances, background interference, and camouflage properties, making polyp segmentation a challenging task. This paper proposes a new polyp segmentation dataset (PS-NBI2K) consisting of 2,000 NBI colonoscopy images with pixel-wise annotations, and presents benchmarking results and analyses for 24 recently reported DL-based polyp segmentation methods on PS-NBI2K. The results show that existing methods struggle to locate polyps with smaller sizes and stronger interference, and that extracting both local and global features improves performance. There is also a trade-off between effectiveness and efficiency, and most methods cannot achieve the best results in both areas simultaneously. This work highlights potential directions for designing DL-based polyp segmentation methods in NBI colonoscopy images, and the release of PS-NBI2K aims to drive further development in this field.

- ## Links to the DL methods that are compared in this paper

    |Method         |Link                                                                           |Method         |Link                                                       |
    |   -           | -                                                                             | -             | -                                                         |
    |U-Net          |[GitHub repo](https://github.com/milesial/Pytorch-UNet)                        |GMSRF-Net      |[GitHub repo](https://github.com/NoviceMAn-prog/GMSRFNet)  | 
    |FCN8s          |[GitHub repo](https://github.com/pochih/FCN-pytorch/blob/master/python/fcn.py) |Polyp-PVT      |[GitHub repo](https://github.com/DengPingFan/Polyp-PVT)    | 
    |PraNet         |[GitHub repo](https://github.com/DengPingFan/PraNet)                           |DCRNet         |[GitHub repo](https://github.com/PRIS-CV/DCRNet)           | 
    |ACSNet         |[GitHub repo](https://github.com/ReaFly/ACSNet)                                |ACENet         |-                                                          | 
    |MSNet          |[GitHub repo](https://github.com/Xiaoqi-Zhao-DLUT/MSNet-M2SNet)                |HSNet          |[GitHub repo](https://github.com/baiboat/HSNet)            | 
    |HarDNet-MSEG   |[GitHub repo](https://github.com/james128333/HarDNet-MSEG)                     |BCNet          |-                                                          | 
    |SANet          |[GitHub repo](https://github.com/weijun88/SANet)                               |LDNet          |[GitHub repo](https://github.com/ReaFly/LDNet)             | 
    |EU-Net         |[GitHub repo](https://github.com/rucv/Enhanced-U-Net)                          |ColonFormer-S  |[GitHub repo](https://github.com/ducnt9907/ColonFormer)    | 
    |UACANet-S      |[GitHub repo](https://github.com/plemeri/UACANet)                              |ColonFormer-L  |[GitHub repo](https://github.com/ducnt9907/ColonFormer)    | 
    |UACANet-L      |[GitHub repo](https://github.com/plemeri/UACANet)                              |ESFPNet        |[GitHub repo](https://github.com/dumyCq/ESFPNet)           | 
    |CCBANet        |[GitHub repo](https://github.com/ntcongvn/CCBANet)                             |FCBFormer      |[GitHub repo](https://github.com/ESandML/FCBFormer)        | 
    |LODNet         |[GitHub repo](https://github.com/midsdsy/LOD-Net)                              |SSFormer       |[GitHub repo](https://github.com/Qiming-Huang/ssformer)    | 


- ## Checkpoints of the models

    The checkpoints of the models above can be downloaded via [BaiduNetDisk](https://pan.baidu.com/s/1tzHOsuKlxCMCSD_UF9qg9Q), with an extraction code of `JrzX`. For each method, we have uploaded the checkpoints of all 5 trials.

- ## Prediction maps of the compared methods

    The prediction maps of the methods above can also be downloaded via [BaiduNetDisk](https://pan.baidu.com/s/1_1jsUoCVkuY4uJtx7CBN_g), with an extraction code of `Hy2z`. For each method, we have uploaded the prediction maps of all 5 trials.

- ## Evaluation of the models

    For all methods, we use the same evaluation tool from [the PraNet project](https://github.com/DengPingFan/PraNet) to evaluate their performance. Please refer to the `eval` folder and carefully read the README on the github repository.

- ## Access to the PS-NBI2K dataset

    Coming soon ...

- ## Citation
    If you want to use the database, please cite our paper
    ```
    @article{psnbi2k,
        author={Yue, Guanghui and Zhuo, Guibin and Li, Siying and Zhou, Tianwei and Du, Jingfeng and Yan, Weiqing and Hou, Jingwen and Liu, Weide and Wang, Tianfu},
        journal={IEEE Journal of Biomedical and Health Informatics}, 
        title={Benchmarking Polyp Segmentation Methods in Narrow-Band Imaging Colonoscopy Images}, 
        year={2023}
    }
    ```
