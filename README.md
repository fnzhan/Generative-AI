# <p align=center>Multimodal Image Synthesis and Editing: A Survey</p>

[![arXiv](https://img.shields.io/badge/arXiv-2107.05399-b31b1b.svg)](https://arxiv.org/abs/2112.13592)
[![Survey](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) 
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 
[![GitHub license](https://badgen.net/github/license/Naereen/Strapdown.js)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
<!-- [![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org) -->
<!-- [![Documentation Status](https://readthedocs.org/projects/ansicolortags/badge/?version=latest)](http://ansicolortags.readthedocs.io/?badge=latest) -->

![Teaser](teaser.png)

<!-- ### TODO -->
<!-- - MISE Dataset for multimodel image synthesis and editing -->

This project is associated with our survey paper which comprehensively contextualizes the advance of the recent Multimodal Image Synthesis \& Editing (MISE) and formulates taxonomies according to data modality and model architectures.
<!-- For more details, please refer to: <br> -->

**Multimodal Image Synthesis and Editing: A Survey** » [[Paper](https://arxiv.org/abs/2112.13592)] <br>
[Fangneng Zhan](http://fnzhan.net/), [Yingchen Yu](https://yingchen001.github.io/), [Rongliang Wu](https://scholar.google.com.sg/citations?user=SZkh3iAAAAAJ&hl=en), [Jiahui Zhang](https://scholar.google.com/citations?user=DXpYbWkAAAAJ&hl=zh-CN), [Shijian Lu](https://scholar.google.com.sg/citations?user=uYmK-A0AAAAJ&hl=en)


## Table of Contents (Work in Progress)

**Methods:**
<!-- ### Methods: -->
- [Transformer-based Methods](#Transformer-based-Methods) 
  - [Image Quantizer](#Image-Quantizer)
- [NeRF-based Methods](#NeRF-based-Methods)
- [Diffusion-based Methods](#Diffusion-based-Methods)
- [GAN-Inversion Methods](#GAN-Inversion-Methods)
- [GAN-based Methods](#GAN-based-Methods)
- [Other Methods](#Other-Methods)

**Modalities:**
- [Text Encoding](#Text-Encoding)

**Datasets:**
- TODO



## Transformer-based-Methods

**ERNIE-ViLG: Unified Generative Pre-training for Bidirectional Vision-Language Generation**<br>
*Han Zhang, Weichong Yin, Yewei Fang, Lanxin Li, Boqiang Duan, Zhihua Wu, Yu Sun, Hao Tian, Hua Wu, Haifeng Wang*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2112.15283)] 
[[Project](https://wenxin.baidu.com/wenxin/ernie-vilg)]

**NÜWA: Visual Synthesis Pre-training for Neural visUal World creAtion**<br>
*Chenfei Wu, Jian Liang, Lei Ji, Fan Yang, Yuejian Fang, Daxin Jiang, Nan Duan*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2111.12417)] 
[[Code](https://github.com/microsoft/NUWA)] 
[[Video](https://youtu.be/C9CTnZJ9ZE0)]

**L-Verse: Bidirectional Generation Between Image and Text**<br>
*Taehoon Kim, Gwangmo Song, Sihaeng Lee, Sangyun Kim, Yewon Seo, Soonyoung Lee, Seung Hwan Kim, Honglak Lee, Kyunghoon Bae*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2111.11133)] 
[[Code](https://github.com/tgisaturday/L-Verse)] 
<!-- [[Video](https://youtu.be/C9CTnZJ9ZE0)] -->

**M6-UFC: Unifying Multi-Modal Controls for Conditional Image Synthesis**<br>
*Zhu Zhang, Jianxin Ma, Chang Zhou, Rui Men, Zhikang Li, Ming Ding, Jie Tang, Jingren Zhou, Hongxia Yang*<br>
NeurIPS 2021
[[Paper](https://arxiv.org/abs/2105.14211v3)] 
<!-- [[Project](https://compvis.github.io/imagebart/)] -->

**ImageBART: Bidirectional Context with Multinomial Diffusion for Autoregressive Image Synthesis**<br>
*Patrick Esser, Robin Rombach, Andreas Blattmann, Björn Ommer*<br>
NeurIPS 2021
[[Paper](https://openreview.net/pdf?id=-1AAgrS5FF)] 
[[Code](https://github.com/CompVis/imagebart)] 
[[Project](https://compvis.github.io/imagebart/)]

**Taming Transformers for High-Resolution Image Synthesis**<br>
*Patrick Esser, Robin Rombach, Björn Ommer*<br>
CVPR 2021
[[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Esser_Taming_Transformers_for_High-Resolution_Image_Synthesis_CVPR_2021_paper.pdf)] 
[[Code](https://github.com/CompVis/taming-transformers)] 
[[Project](https://compvis.github.io/taming-transformers/)]

**RuDOLPH: One Hyper-Modal Transformer can be creative as DALL-E and smart as CLIP**<br>
*Alex Shonenkov and Michael Konstantinov*<br>
arxiv 2022
[[Code](https://github.com/sberbank-ai/ru-dolph)]

**Generate Images from Texts in Russian (ruDALL-E)**<br>
[[Code](https://github.com/sberbank-ai/ru-dalle)]
[[Project](https://rudalle.ru/en/)]

**Zero-Shot Text-to-Image Generation**<br>
*Aditya Ramesh, Mikhail Pavlov, Gabriel Goh, Scott Gray, Chelsea Voss, Alec Radford, Mark Chen, Ilya Sutskever*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2102.12092)]
[[Code](https://github.com/openai/DALL-E)]
[[Project](https://openai.com/blog/dall-e/)]

**Compositional Transformers for Scene Generation**<br>
*Drew A. Hudson, C. Lawrence Zitnick*<br>
NeurIPS 2021
[[Paper](https://openreview.net/pdf?id=YQeWoRnwTnE)]
[[Code](https://github.com/dorarad/gansformer)]

**One-shot Talking Face Generation from Single-speaker Audio-Visual Correlation Learning**<br>
*Suzhen Wang, Lincheng Li, Yu Ding, Xin Yu*<br>
AAAI 2022
[[Paper](https://arxiv.org/abs/2112.02749)]

<br>

### Image-Quantizer

**[TE-VQGAN] Translation-equivariant Image Quantizer for Bi-directional Image-Text Generation**<br>
*Woncheol Shin, Gyubok Lee, Jiyoung Lee, Joonseok Lee, Edward Choi*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2110.04627)]
[[Code](https://github.com/wcshin-git/TE-VQGAN)]

**[ViT-VQGAN] Vector-quantized Image Modeling with Improved VQGAN**<br>
*Jiahui Yu, Xin Li, Jing Yu Koh, Han Zhang, Ruoming Pang, James Qin, Alexander Ku, Yuanzhong Xu, Jason Baldridge, Yonghui Wu*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2110.04627)]
<!-- [[Code](https://github.com/CompVis/taming-transformers)] -->

**[VQ-GAN] Taming Transformers for High-Resolution Image Synthesis**<br>
*Patrick Esser, Robin Rombach, Björn Ommer*<br>
CVPR 2021
[[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Esser_Taming_Transformers_for_High-Resolution_Image_Synthesis_CVPR_2021_paper.pdf)]
[[Code](https://github.com/CompVis/taming-transformers)]

**[Gumbel-VQ] vq-wav2vec: Self-Supervised Learning of Discrete Speech Representations**<br>
*Alexei Baevski, Steffen Schneider, Michael Auli*<br>
ICLR 2020
[[Paper](https://openreview.net/pdf?id=rylwJxrYDS)]
[[Code](https://github.com/pytorch/fairseq/blob/main/examples/wav2vec/README.md)]

**[VQ-VAE] Neural Discrete Representation Learning**<br>
*Aaron van den Oord, Oriol Vinyals, Koray Kavukcuoglu*<br>
NIPS 2017
[[Paper](https://proceedings.neurips.cc/paper/2017/file/7a98af17e63a0ac09ce2e96d03992fbc-Paper.pdf)]
[[Code](https://github.com/ritheshkumar95/pytorch-vqvae)]

**[VQ-VAE2 or EMA-VQ] Generating Diverse High-Fidelity Images with VQ-VAE-2**<br>
*Ali Razavi, Aaron van den Oord, Oriol Vinyals*<br>
NIPS 2019
[[Paper](https://proceedings.neurips.cc/paper/2019/file/5f8e2fa1718d1bbcadf1cd9c7a54fb8c-Paper.pdf)]
[[Code](https://github.com/rosinality/vq-vae-2-pytorch)]

**[Discrete VAE] Discrete Variational Autoencoders**<br>
*Jason Tyler Rolfe*<br>
ICLR 2017
[[Paper](https://arxiv.org/abs/1609.02200)]
[[Code](https://github.com/openai/DALL-E)]

**[DVAE++] DVAE++: Discrete Variational Autoencoders with Overlapping Transformations**<br>
*Arash Vahdat, William G. Macready, Zhengbing Bian, Amir Khoshaman, Evgeny Andriyash*<br>
ICML 2018
[[Paper](https://arxiv.org/abs/1802.04920)]
[[Code](https://github.com/xmax1/dvae)]

**[DVAE#] DVAE#: Discrete Variational Autoencoders with Relaxed Boltzmann Priors**<br>
*Arash Vahdat, Evgeny Andriyash, William G. Macready*<br>
NIPS 2018
[[Paper](https://arxiv.org/abs/1805.07445)]
[[Code](https://github.com/xmax1/dvae)]

<br>


## NeRF-based-Methods

**Zero-Shot Text-Guided Object Generation with Dream Fields**<br>
*Ajay Jain, Ben Mildenhall, Jonathan T. Barron, Pieter Abbeel, Ben Poole*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2112.01455)]
[[Project](https://ajayj.com/dreamfields)]

**CLIP-NeRF: Text-and-Image Driven Manipulation of Neural Radiance Fields**<br>
*Can Wang, Menglei Chai, Mingming He, Dongdong Chen, Jing Liao*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2112.05139)]
[[Code](https://github.com/cassiePython/CLIPNeRF)]
[[Project](https://cassiepython.github.io/clipnerf/)]


**AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis**<br>
*Yudong Guo, Keyu Chen, Sen Liang, Yong-Jin Liu, Hujun Bao, Juyong Zhang*<br>
ICCV 2021
[[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Guo_AD-NeRF_Audio_Driven_Neural_Radiance_Fields_for_Talking_Head_Synthesis_ICCV_2021_paper.pdf)]
[[Code](https://github.com/YudongGuo/AD-NeRF)]
[[Project](https://yudongguo.github.io/ADNeRF/)]
[[Video](https://www.youtube.com/watch?v=TQO2EBYXLyU)]



<br>


## Diffusion-based-Methods

**High-Resolution Image Synthesis with Latent Diffusion Models**<br>
*Robin Rombach, Andreas Blattmann, Dominik Lorenz, Patrick Esser, Björn Ommer*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2112.10752)]
[[Code](https://github.com/CompVis/latent-diffusion)]

**v objective diffusion**<br>
*Katherine Crowson*<br>
[[Code](https://github.com/crowsonkb/v-diffusion-pytorch)]

**GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models**<br>
*Alex Nichol, Prafulla Dhariwal, Aditya Ramesh, Pranav Shyam, Pamela Mishkin, Bob McGrew, Ilya Sutskever, Mark Chen*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2112.10741)]
[[Code](https://github.com/openai/glide-text2im)]

**Vector Quantized Diffusion Model for Text-to-Image Synthesis**<br>
*Shuyang Gu, Dong Chen, Jianmin Bao, Fang Wen, Bo Zhang, Dongdong Chen, Lu Yuan, Baining Guo*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2111.14822)]
[[Code](https://github.com/microsoft/VQ-Diffusion)]

**DiffusionCLIP: Text-Guided Diffusion Models for Robust Image Manipulation**<br>
*Gwanghyun Kim, Jong Chul Ye*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2110.02711)]

**Blended Diffusion for Text-driven Editing of Natural Images**<br>
*Omri Avrahami, Dani Lischinski, Ohad Fried*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2111.14818)]
[[Code](https://github.com/omriav/blended-diffusion)]



<br>



## GAN-Inversion-Methods 

**HairCLIP: Design Your Hair by Text and Reference Image**<br>
*Tianyi Wei, Dongdong Chen, Wenbo Zhou, Jing Liao, Zhentao Tan, Lu Yuan, Weiming Zhang, Nenghai Yu*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2112.05142)]
[[Code](https://github.com/wty-ustc/HairCLIP)]

**FuseDream: Training-Free Text-to-Image Generation with Improved CLIP+ GAN Space Optimization**<br>
*Xingchao Liu, Chengyue Gong, Lemeng Wu, Shujian Zhang, Hao Su, Qiang Liu*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2112.01573)]
[[Code](https://github.com/gnobitab/FuseDream)]

**StyleMC: Multi-Channel Based Fast Text-Guided Image Generation and Manipulation**<br>
*Umut Kocasari, Alara Dirik, Mert Tiftikci, Pinar Yanardag*<br>
WACV 2022
[[Paper](https://arxiv.org/abs/2112.08493)]
[[Code](https://github.com/catlab-team/stylemc)]
[[Project](https://catlab-team.github.io/stylemc/)]

**Cycle-Consistent Inverse GAN for Text-to-Image Synthesis**<br>
*Hao Wang, Guosheng Lin, Steven C. H. Hoi, Chunyan Miao*<br>
ACM MM 2021
[[Paper](https://dl.acm.org/doi/10.1145/3474085.3475226)]

**StyleCLIP: Text-Driven Manipulation of StyleGAN Imagery**<br>
*Or Patashnik, Zongze Wu, Eli Shechtman, Daniel Cohen-Or, Dani Lischinski*<br>
ICCV 2021
[[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Patashnik_StyleCLIP_Text-Driven_Manipulation_of_StyleGAN_Imagery_ICCV_2021_paper.pdf)]
[[Code](https://github.com/orpatashnik/StyleCLIP)]
[[Video](https://www.youtube.com/watch?v=PhR1gpXDu0w)]

**Talk-to-Edit: Fine-Grained Facial Editing via Dialog**<br>
*Yuming Jiang, Ziqi Huang, Xingang Pan, Chen Change Loy, Ziwei Liu*<br>
ICCV 2021
[[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Jiang_Talk-To-Edit_Fine-Grained_Facial_Editing_via_Dialog_ICCV_2021_paper.pdf)]
[[Code](https://github.com/yumingj/Talk-to-Edit)]
[[Project](https://www.mmlab-ntu.com/project/talkedit/)]

**TediGAN: Text-Guided Diverse Face Image Generation and Manipulation**<br>
*Weihao Xia, Yujiu Yang, Jing-Hao Xue, Baoyuan Wu*<br>
CVPR 2021
[[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Xia_TediGAN_Text-Guided_Diverse_Face_Image_Generation_and_Manipulation_CVPR_2021_paper.pdf)]
[[Code](https://github.com/IIGROUP/TediGAN)]
[[Video](https://www.youtube.com/watch?v=L8Na2f5viAM)]

**Paint by Word**<br>
*David Bau, Alex Andonian, Audrey Cui, YeonHwan Park, Ali Jahanian, Aude Oliva, Antonio Torralba*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2112.01573)]

<br>


## GAN-based-Methods

**Multimodal Conditional Image Synthesis with Product-of-Experts GANs**<br>
*Xun Huang, Arun Mallya, Ting-Chun Wang, Ming-Yu Liu*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2112.05130)]

**RiFeGAN2: Rich Feature Generation for Text-to-Image Synthesis from Constrained Prior Knowledge**<br>
*Jun Cheng, Fuxiang Wu, Yanling Tian, Lei Wang, Dapeng Tao*<br>
TCSVT 2021
[[Paper](https://ieeexplore.ieee.org/abstract/document/9656731/authors#authors)]

**TRGAN: Text to Image Generation Through Optimizing Initial Image**<br>
*Liang Zhao, Xinwei Li, Pingda Huang, Zhikui Chen, Yanqi Dai, Tianyu Li*<br>
ICONIP 2021
[[Paper](https://link.springer.com/chapter/10.1007/978-3-030-92307-5_76)]

<!-- **Image Synthesis From Layout With Locality-Aware Mask Adaption [Layout2Image]**<br>
*Zejian Li, Jingyu Wu, Immanuel Koh, Yongchuan Tang, Lingyun Sun*<br>
GCPR 2021
[[Paper](https://arxiv.org/pdf/2103.13722.pdf)]
[[Code](https://github.com/stanifrolov/AttrLostGAN)]

**AttrLostGAN: Attribute Controlled Image Synthesis from Reconfigurable Layout and Style [Layout2Image]**<br>
*Stanislav Frolov, Avneesh Sharma, Jörn Hees, Tushar Karayil, Federico Raue, Andreas Dengel*<br>
ICCV 2021
[[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Image_Synthesis_From_Layout_With_Locality-Aware_Mask_Adaption_ICCV_2021_paper.pdf)] -->

**Audio-Driven Emotional Video Portraits [Audio2Image]**<br>
*Xinya Ji, Hang Zhou, Kaisiyuan Wang, Wayne Wu, Chen Change Loy, Xun Cao, Feng Xu*<br>
CVPR 2021
[[Paper](https://arxiv.org/abs/2104.07452)]
[[Code](https://github.com/jixinya/EVP/)]
[[Project](https://jixinya.github.io/projects/evp/)]

**Direct Speech-to-Image Translation [Audio2Image]**<br>
*Jiguo Li, Xinfeng Zhang, Chuanmin Jia, Jizheng Xu, Li Zhang, Yue Wang, Siwei Ma, Wen Gao*<br>
JSTSP 2020
[[Paper](https://ieeexplore.ieee.org/document/9067083/authors#authors)]
[[Code](https://github.com/smallflyingpig/speech-to-image-translation-without-text)]
[[Project](https://smallflyingpig.github.io/speech-to-image/main)]

**MirrorGAN: Learning Text-to-image Generation by Redescription [Text2Image]**<br>
*Tingting Qiao, Jing Zhang, Duanqing Xu, Dacheng Tao*<br>
CVPR 2019
[[Paper](https://arxiv.org/abs/1903.05854)]
[[Code](https://github.com/qiaott/MirrorGAN)]

**AttnGAN: Fine-Grained Text to Image Generation with Attentional Generative Adversarial Networks [Text2Image]**<br>
*Tao Xu, Pengchuan Zhang, Qiuyuan Huang, Han Zhang, Zhe Gan, Xiaolei Huang, Xiaodong He*<br>
CVPR 2018
[[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_AttnGAN_Fine-Grained_Text_CVPR_2018_paper.pdf)]
[[Code](https://github.com/taoxugit/AttnGAN)]

**Plug & Play Generative Networks: Conditional Iterative Generation of Images in Latent Space**<br>
*Anh Nguyen, Jeff Clune, Yoshua Bengio, Alexey Dosovitskiy, Jason Yosinski*<br>
CVPR 2017
[[Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Nguyen_Plug__Play_CVPR_2017_paper.pdf)]
[[Code](https://github.com/Evolving-AI-Lab/ppgn)]

**StackGAN++: Realistic Image Synthesis with Stacked Generative Adversarial Networks [Text2Image]**<br>
*Han Zhang, Tao Xu, Hongsheng Li, Shaoting Zhang, Xiaogang Wang, Xiaolei Huang, Dimitris Metaxas*<br>
TPAMI 2018
[[Paper](https://arxiv.org/abs/1710.10916)]
[[Code](https://github.com/hanzhanggit/StackGAN-v2)]

**StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks [Text2Image]**<br>
*Han Zhang, Tao Xu, Hongsheng Li, Shaoting Zhang, Xiaogang Wang, Xiaolei Huang, Dimitris Metaxas*<br>
ICCV 2017
[[Paper](https://arxiv.org/abs/1612.03242)]
[[Code](https://github.com/hanzhanggit/StackGAN)]



<br>


## Other-Methods

**Language-Driven Image Style Transfer**<br>
*Tsu-Jui Fu, Xin Eric Wang, William Yang Wang*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2106.00178)]

**CLIPstyler: Image Style Transfer with a Single Text Condition**<br>
*Gihyun Kwon, Jong Chul Ye*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2112.00374)]
[[Code](https://github.com/paper11667/CLIPstyler)]



<br>



<br>



## Text-Encoding

**FLAVA: A Foundational Language And Vision Alignment Model**<br>
*Amanpreet Singh, Ronghang Hu, Vedanuj Goswami, Guillaume Couairon, Wojciech Galuba, Marcus Rohrbach, Douwe Kiela*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2112.04482)]
<!-- [[Code](https://github.com/paper11667/CLIPstyler)] -->

**Learning Transferable Visual Models From Natural Language Supervision (CLIP)**<br>
*Alec Radford, Jong Wook Kim, Chris Hallacy, Aditya Ramesh, Gabriel Goh, Sandhini Agarwal, Girish Sastry, Amanda Askell, Pamela Mishkin, Jack Clark, Gretchen Krueger, Ilya Sutskever*<br>
arxiv 2021
[[Paper](https://arxiv.org/abs/2103.00020)]
[[Code](https://github.com/OpenAI/CLIP)]
