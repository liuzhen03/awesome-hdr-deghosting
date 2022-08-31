# Awesome HDR Deghosting

A curated list of multi-frame HDR deghosting resources.

## Paper

| Year | Published | Paper | Code / Project Page | Keywords |
| :--------: | :--------: | :--------: | :--------: | :--------: |
| 2022 | ECCV | [Ghost-free High Dynamic Range Imaging with Context-aware Transformer](https://arxiv.org/abs/2208.05114) |[MegEngine](https://github.com/megvii-research/HDR-Transformer) </br> [PyTorch](https://github.com/liuzhen03/HDR-Transformer-PyTorch) | Transformer-based solution |
| 2022 | CVPRW | [NTIRE 2022 Challenge on High Dynamic Range Imaging: Methods and Results](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Perez-Pellitero_NTIRE_2022_Challenge_on_High_Dynamic_Range_Imaging_Methods_and_CVPRW_2022_paper.pdf) | - | Review of the NTIRE 2022 HDR Challenge |
| 2021 | arXiv | [Deep Learning for HDR Imaging: State-of-the-Art and Future Trends](https://arxiv.org/pdf/2110.10394.pdf) | - | Survey |
| 2021 | CVPR | [Labeled From Unlabeled: Exploiting Unlabeled Data for Few-Shot Deep HDR Deghosting](https://openaccess.thecvf.com/content/CVPR2021/papers/Prabhakar_Labeled_From_Unlabeled_Exploiting_Unlabeled_Data_for_Few-Shot_Deep_HDR_CVPR_2021_paper.pdf) | - | Few-shot |
| 2021 | CVPRW | [NTIRE 2021 Challenge on High Dynamic Range Imaging: Dataset, Methods and Results](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/papers/Perez-Pellitero_NTIRE_2021_Challenge_on_High_Dynamic_Range_Imaging_Dataset_Methods_CVPRW_2021_paper.pdf) | - | Review of the NTIRE 2021 HDR Challenge |
| 2021 | CVPRW | [ADNet: Attention-guided Deformable Convolutional Network for High Dynamic Range Imaging](https://arxiv.org/abs/2105.10697) | [PyTorch](https://github.com/liuzhen03/ADNet) | The winning method of the NTIRE 2021 HDR Challenge |
| 2021 | TIP | [HDR-GAN: HDR image reconstruction from multi-exposed ldr images with large motions](https://ieeexplore.ieee.org/document/9387148) | [Tensorflow](https://github.com/nonu116/HDR-GAN) | GAN-based |
| 2021 | ACM MM | [Progressive and Selective Fusion Network for High Dynamic Range Imaging ](https://arxiv.org/pdf/2108.08585.pdf) | - | - |
| 2020 | TIP | [Deep HDR Imaging via A Non-local Network ](https://ieeexplore.ieee.org/document/8989959) | - | Non-local |
| 2020 | ECCV | [Towards Practical and Efficient High-Resolution HDR Deghosting with CNN](https://www.researchgate.net/profile/Balraj-Ashwath-2/publication/346658902_Towards_Practical_and_Efficient_High-Resolution_HDR_Deghosting_with_CNN/links/5fcd1c0592851c00f856f2a3/Towards-Practical-and-Efficient-High-Resolution-HDR-Deghosting-with-CNN.pdf) | - | Practical and Efficient solution |
| 2019 | CVPR | [Attention-guided Network for Ghost-free High Dynamic Range Imaging](https://arxiv.org/abs/1904.10293) | [PyTorch](https://github.com/qingsenyangit/AHDRNet) |Attention-based |
| 2019 | WACV | [Multi-scale dense networks for deep high dynamic range imaging](https://ieeexplore.ieee.org/document/8658831) | -  | - |
| 2018 | ECCV | [Deep High Dynamic Range Imaging with Large Foreground Motions](https://arxiv.org/abs/1711.08937) | [Tensorflow](https://github.com/elliottwu/DeepHDR) | Non-flow based |
| 2017 | SIGGRAPH  | [Deep High Dynamic Range Imaging of Dynamic Scenes](https://people.engr.tamu.edu/nimak/Data/SIGGRAPH17_HDR_LoRes.pdf) | [Matlab](https://cseweb.ucsd.edu/~viscomp/projects/SIG17HDR/) | The first DL-based solution |


## Dataset

| Dataset | Amount | Usage | GT | Resolution |
| :--------: | :--------: | :--------: | :--------: |:--------: |
| Prabhakar et al. 2019 | 582 | train (366) + test (116) | Y  | 1500x1125 |
| Kalantari et al. 2017 | 89 | train (74) + test (15) | Y | 1500x1000 |
| Tursun et al. 2016 | 16 | test | N | 1024x682 |
| Sen et al. 2012 | 8 | test | N | 1350x900 |


