# awesome-mixup

This repo is a collection of AWESOME things about mixup, including papers, code, etc. Feel free to star and fork. We borrow a lot from [openmixup](https://github.com/Westlake-AI/openmixup), [awesome-domain-adaptation](https://github.com/zhaoxin94/awesome-domain-adaptation), and [PromptPapers](https://github.com/thunlp/PromptPapers).

Some of these papers are summarized with tables in Google Sheet. Please find the link here: [Summary(Restricted)](https://docs.google.com/spreadsheets/d/1U34nbDFy7GRU78ZKmgourSDZrFngc4QN_fIvgfSchek/edit?usp=sharing)


![](https://img.shields.io/github/last-commit/demoleiwang/awesome-mixup?color=green) ![](https://img.shields.io/badge/PaperNumber-39-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 

<!-- 
1. **[[]]()** x. x. [[code](x)] 

    *x* 

-->

### Basics
This section contains the exploration on the improvements aspects of raw mixup.

1. **[[mixup'18]](https://arxiv.org/abs/1710.09412)** mixup: Beyond Empirical Risk Minimization. ICLR 2018. [[code](https://github.com/facebookresearch/mixup-cifar10)].

    *Hongyi Zhang, Moustapha Cisse, Yann N. Dauphin, David Lopez-Paz.*

1. **[[Manifold Mixup'19]](https://arxiv.org/abs/1806.05236)** Manifold Mixup: Better Representations by Interpolating Hidden States. ICML 2019. [[code](https://github.com/vikasverma1077/manifold_mixup)] 

    *Vikas Verma, Alex Lamb, Christopher Beckham, Amir Najafi, Ioannis Mitliagkas, David Lopez-Paz, Yoshua Bengio*

    
1. **[[AdaMixup'19]](https://arxiv.org/abs/1809.02499)** MixUp as Locally Linear Out-Of-Manifold Regularization. AAAI 2019. 

    *Hongyu Guo, Yongyi Mao, Richong Zhang.*


1. **[[CutMix'19]](https://arxiv.org/abs/1905.04899)** CutMix: Regularization Strategy to Train Strong Classifiers with Localizable Features. ICCV 2019. [[code](https://github.com/clovaai/CutMix-PyTorch)] 

    *Sangdoo Yun, Dongyoon Han, Seong Joon Oh, Sanghyuk Chun, Junsuk Choe, Youngjoon Yoo.*


1. **[[AugMix'20]](https://arxiv.org/abs/1912.02781)** AugMix: A Simple Data Processing Method to Improve Robustness and Uncertainty. ICLR 2020. [[code](https://github.com/google-research/augmix)] 

    *Dan Hendrycks, Norman Mu, Ekin D. Cubuk, Barret Zoph, Justin Gilmer, Balaji Lakshminarayanan.*      
    

1. **[[SnapMix'21]](https://arxiv.org/pdf/2012.04846)** SnapMix: Semantically Proportional Mixing for Augmenting Fine-grained Data. AAAI 2021. [[code](https://github.com/Shaoli-Huang/SnapMix.git)] 

    *Shaoli Huang, Xinchao Wang, Dacheng Tao.* 
    
1. **[[PuzzleMix'20]](https://arxiv.org/abs/2009.06962)** Puzzle Mix: Exploiting Saliency and Local Statistics for Optimal Mixup. ICML 2020. [[code](https://github.com/snu-mllab/PuzzleMix)] 

    *Jang-Hyun Kim, Wonho Choo, Hyun Oh Song.*

1. **[[SaliencyMix'21]](https://arxiv.org/abs/2006.01791)** SaliencyMix: A Saliency Guided Data Augmentation Strategy for Better Regularization. ICLR 2021. [[code](x)] 

    *A F M Shahab Uddin and Mst. Sirazam Monira and Wheemyung Shin and TaeChoong Chung and Sung-Ho Bae.*

1. **[[CoMixup'21]](https://arxiv.org/abs/2102.03065)** Co-Mixup: Saliency Guided Joint Mixup with Supermodular Diversity. ICLR 2021. [[code](https://github.com/snu-mllab/Co-Mixup)] 

    *Jang-Hyun Kim, Wonho Choo, Hosan Jeong, Hyun Oh Song.*


1. **[[NFM'22]](https://arxiv.org/pdf/2110.02180.pdf)** Noisy Feature Mixup. ICLR 2022. [[code](https://github.com/erichson/NFM)] 

    *Soon Hoe Lim, N. Benjamin Erichson, Francisco Utrera, Winnie Xu, Michael W. Mahoney*

1. **[[AlignMix'22]](https://arxiv.org/abs/2103.15375)** AlignMix: Improving representation by interpolating aligned features. CVPR 2022. [[code](https://github.com/shashankvkt/AlignMixup_CVPR22)] 

    *Shashanka Venkataramanan, Ewa Kijak, Laurent Amsaleg, Yannis Avrithis.*
    
1. **[[TransMix'22]](https://arxiv.org/abs/2111.09833)** TransMix: Attend to Mix for Vision Transformers. CVPR 2022. [[code](https://github.com/Beckschen/TransMix)] 

    *Jie-Neng Chen, Shuyang Sun, Ju He, Philip Torr, Alan Yuille, Song Bai.*

1. **[[GenLabel'22]](https://proceedings.mlr.press/v162/sohn22a/sohn22a.pdf)** GenLabel: Mixup Relabeling using Generative Models. ICML 2022. [[code](https://github.com/UW-Madison-Lee-Lab/GenLabel_official)] 

    *Jy-yong Sohn, Liang Shang, Hongxu Chen, Jaekyun Moon, Dimitris Papailiopoulos, Kangwook Lee.*

1. **[[VLMixer'22]](https://arxiv.org/pdf/2206.08919.pdf)** VLMixer: Unpaired Vision-Language Pre-training via Cross-Modal CutMix. ICML 2022. [[code](x)] 

    *Teng Wang, Wenhao Jiang, Zhichao Lu, Feng Zheng, Ran Cheng, Chengguo Yin, Ping Luo*

1. **[[AutoMix'22]](https://arxiv.org/abs/2103.13027)** AutoMix: Unveiling the Power of Mixup for Stronger Classifiers. ECCV 2022. [[code](https://github.com/Westlake-AI/openmixup)]

    *Zicheng Liu, Siyuan Li, Di Wu, Zihan Liu, Zhiyuan Chen, Lirong Wu, Stan Z. Li.*


1. **[[TokenMix'22]](https://arxiv.org/abs/2207.08409)** TokenMix: Rethinking Image Mixing for Data Augmentation in Vision Transformers. ECCV 2022. [[code](https://github.com/Sense-X/TokenMix)]

    *Jihao Liu, Boxiao Liu, Hang Zhou, Hongsheng Li, Yu Liu*




### Contrastive Learning with Mixup

1. **[[MixCo'20]](https://arxiv.org/abs/2010.06300)** MixCo: Mix-up Contrastive Learning for Visual Representation. NeurIPSW. [[code](https://github.com/Lee-Gihun/MixCo-Mixup-Contrast)] 

    *MixCo: Sungnyun Kim, Gihun Lee, Sangmin Bae, Se-Young Yun.*
    
1. **[[MoCHi'20]](https://arxiv.org/abs/2010.01028)** Hard Negative Mixing for Contrastive Learning. NeurIPS 2020. [[code](https://europe.naverlabs.com/mochi)] 

    *Yannis Kalantidis, Mert Bulent Sariyildiz, Noe Pion, Philippe Weinzaepfel, Diane Larlus.*
    
1. **[[i-Mix'21]](https://arxiv.org/abs/2010.08887)** i-Mix A Domain-Agnostic Strategy for Contrastive Representation Learning. ICLR 2021. [[code](https://github.com/kibok90/imix)] 

    *Kibok Lee, Yian Zhu, Kihyuk Sohn, Chun-Liang Li, Jinwoo Shin, Honglak Lee.*
    
1. **[[FT'19]](https://arxiv.org/abs/2108.02982)** Improving Contrastive Learning by Visualizing Feature Transformation. ICCV 2019 (Oral). [[code](https://github.com/DTennant/CL-Visualizing-Feature-Transformation)] 

    *Rui Zhu, Bingchen Zhao, Jingen Liu, Zhenglong Sun, Chang Wen Chen.*
    
1. **[[Core-tuning'21]](https://arxiv.org/abs/2102.06605)** Unleashing the Power of Contrastive Self-Supervised Visual Models via Contrast-Regularized Fine-Tuning.  NeurIPS 2021. [[code](https://github.com/vanint/core-tuning)] 

    *Yifan Zhang, Bryan Hooi, Dapeng Hu, Jian Liang, Jiashi Feng.*
    
1. **[[MixSiam'22]](https://arxiv.org/pdf/2111.02679.pdf)** MixSiam: A Mixture-based Approach to Self-supervised Representation Learning. AAAI 2022. 

    *Xiaoyang Guo, Tianhao Zhao, Yutian Lin, Bo Du.*
    
1. **[[Un-Mix'22]](https://arxiv.org/abs/2003.05438)** Un-Mix: Rethinking Image Mixtures for Unsupervised Visual Representation. AAAI 2022. [[code](https://github.com/szq0214/Un-Mix)] 

    *Zhiqiang Shen, Zechun Liu, Zhuang Liu, Marios Savvides, Trevor Darrell, Eric Xing.*
    
    
1. **[[Metrix'22]](https://www.semanticscholar.org/reader/a7721bf626f4996117dbb88b385be2e12462e7e6)** It Takes Two to Tango: Mixup for Deep Metric Learning. ICLR 2022. [[code](https://github.com/billpsomas/Metrix_ICLR22)] 

    *Shashanka Venkataramanan, Bill Psomas, Ewa Kijak, Laurent Amsaleg, Konstantinos Karantzalos, Yannis Avrithis.*

1. **[[ProGCL'22]](https://arxiv.org/abs/2110.02027)** ProGCL: Rethinking Hard Negative Mining in Graph Contrastive Learning. ICML 2022. [[code](https://github.com/junxia97/ProGCL)] 

    *Jun Xia, Lirong Wu, Ge Wang, Jintao Chen, Stan Z.Li.*


1. **[[M-Mix'22]]()** M-Mix: Generating Hard Negatives via Multi-sample Mixing for Contrastive Learning. KDD 2022. [[code](https://github.com/Sherrylone/m-mix)] 

    *Shaofeng Zhang, Meng Liu, Junchi Yan, Hengrui Zhang, Lingxiao Huang, Pinyan Lu, Xiaokang Yang.* 



### Semi-supervised Learning with Mixup

1. **[[ICT'19]](https://arxiv.org/abs/1903.03825)** Interpolation Consistency Training for Semi-Supervised Learning. IJCAI 2019. [[code](https://github.com/vikasverma1077/ICT)] 

    *Vikas Verma, Kenji Kawaguchi, Alex Lamb, Juho Kannala, Yoshua Bengio, David Lopez-Paz*

1. **[[MixMatch'19]](https://arxiv.org/abs/1905.02249)** MixMatch: A Holistic Approach to Semi-Supervised Learning. NeurIPS 2019. [[code](https://github.com/google-research/mixmatch)] 

    *David Berthelot, Nicholas Carlini, Ian Goodfellow, Nicolas Papernot, Avital Oliver, Colin Raffel.*
    
    
### Mixup in NLP

1. **[[TMix'20]](https://aclanthology.org/2020.acl-main.194.pdf)** MixText: Linguistically-Informed Interpolation of Hidden Space for Semi-Supervised Text Classification. ACL 2020. [[code]](https://github.com/SALT-NLP/MixText)

   *Jiaao Chen, Zichao Yang, and Diyi Yang.*


1. **[[SL'20]](https://aclanthology.org/2020.emnlp-main.447.pdf)** Sequence-Level Mixed Sample Data Augmentation. EMNLP 2020.

   *Demi Guo, Yoon Kim, Alexander Rush.*
   
1. **[[BRMC'21]](https://aclanthology.org/2021.findings-acl.137.pdf)** Better Robustness by More Coverage: Adversarial and Mixup Data Augmentation for Robust Finetuning. ACL 2021.
 
   *Chenglei Si, Zhengyan Zhang, Fanchao Qi, Zhiyuan Liu, Yasheng Wang, Qun Liu, Maosong Sun.*

1. **[[HYPMIX'21]](https://aclanthology.org/2021.emnlp-main.776.pdf)** HYPMIX: Hyperbolic Interpolative Data Augmentation. EMNLP 2021. [[code](https://github.com/caisa-lab/hypmix-emnlp)] 

    *Ramit Sawhney, Megh Thakkar, Shivam Agarwal, Di Jin, Diyi Yang, Lucie Flek* 

1. **[[Multilingual Mix'22]](https://aclanthology.org/2022.acl-long.282.pdf)** Multilingual Mix: Example Interpolation Improves Multilingual Neural Machine Translation. ACL 2022. 

    *Yong Cheng, Ankur Bapna, Orhan Firat, Yuan Cao, Pidong Wang, and Wolfgang Macherey* 

1. **[[DMix'22]](https://aclanthology.org/2022.acl-short.67/)** DMIX: Adaptive Distance-aware Interpolative Mixup. ACL 2022. (SHORT) 

    *Ramit Sawhney, Megh Thakkar, Shrey Pandit, Ritesh Soun, Di Jin, Diyi Yang, Lucie Flek* 

1. **[[STEMM'22]](https://aclanthology.org/2022.acl-long.486.pdf)** STEMM: Self-learning with Speech-text Manifold Mixup for Speech Translation. ACL 2022. [[code](https://github.com/ictnlp/STEMM)] 

    *Qingkai Fang, Rong Ye, Lei Li, Yang Feng, Mingxuan Wang.* 
    
1. **[[CsaNMT'22]](https://arxiv.org/pdf/2204.06812.pdf)** Learning to Generalize to More: Continuous Semantic Augmentation for Neural Machine Translation. ACL 2022. [[code](https://github.com/pemywei/csanmt)] 

    *Xiangpeng Wei, Heng Yu, Yue Hu, Rongxiang Weng, Weihua Luo, Jun Xie, Rong Jin.*

1. **[[AUMS'22]](https://aclanthology.org/2022.acl-long.368.pdf)** On the Calibration of Pre-trained Language Models using Mixup Guided by Area Under the Margin and Saliency. ACL 2022. [[code](https://github.com/shreydesai/calibration)] 

    *Seo Yeon Park and Cornelia Caragea.* 
    
1. **[[XAIMix'22]](https://dl.acm.org/doi/pdf/10.1145/3533048)** Explainability-based mix-up approach for text data augmentation. TKDD. 

    *Soonki Kwon , Younghoon Lee.* 


1. **[[TreeMix'22]](https://aclanthology.org/2022.naacl-main.385.pdf)** TreeMix: Compositional Constituency-based Data Augmentation for Natural Language Understanding. NAACL 2022. [[code](https://github.com/magiccircuit/treemix)] 

    *Le Zhang, Zichao Yang, Diyi Yang.* 
