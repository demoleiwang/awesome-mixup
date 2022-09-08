# awesome-mixup

This repo is a collection of AWESOME things about mixup, including papers, code, etc. Feel free to star and fork. We borrow a lot from [openmixup](https://github.com/Westlake-AI/openmixup), [awesome-domain-adaptation](https://github.com/zhaoxin94/awesome-domain-adaptation), and [PromptPapers](https://github.com/thunlp/PromptPapers).


![](https://img.shields.io/github/last-commit/demoleiwang/awesome-mixup?color=green) ![](https://img.shields.io/badge/PaperNumber-50-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 

<!-- * **[]()** x. x. [[code](x)] 

    *x* -->

### Basics
This section contains the exploration on the improvements aspects of raw mixup.

* **[mixup'18](https://arxiv.org/abs/1710.09412)** mixup: Beyond Empirical Risk Minimization. ICLR 2018. [[code](https://github.com/facebookresearch/mixup-cifar10)].

    *Hongyi Zhang, Moustapha Cisse, Yann N. Dauphin, David Lopez-Paz.*

* **[Manifold Mixup'19](https://arxiv.org/abs/1806.05236)** Manifold Mixup: Better Representations by Interpolating Hidden States. ICML 2019. [[code](https://github.com/vikasverma1077/manifold_mixup)] 

    *Vikas Verma, Alex Lamb, Christopher Beckham, Amir Najafi, Ioannis Mitliagkas, David Lopez-Paz, Yoshua Bengio*
    <details>
    <summary>Summary</summary>
    Deep neural networks excel at learning the training data, but often provide incorrect and confident predictions when evaluated on slightly different test examples. This includes distribution shifts, outliers, and adversarial examples. To address these issues, we propose Manifold Mixup, a simple regularizer that encourages neural networks to predict less confidently on interpolations of hidden representations.
    </details>
    
* **[AdaMixup'19](https://arxiv.org/abs/1809.02499)** MixUp as Locally Linear Out-Of-Manifold Regularization. AAAI 2019. 

    *Hongyu Guo, Yongyi Mao, Richong Zhang.*
    <details>
    <summary>Summary</summary>
    The power of MixUp, however, is primarily established empirically and its working and effectiveness have not been explained in any depth. In this paper, we develop an understanding for MixUp as a form of “out-of-manifold regularization”, which imposes certain “local linearity” constraints on the model’s input space beyond the data manifold.
    </details>

* **[CutMix'19](https://arxiv.org/abs/1905.04899)** CutMix: Regularization Strategy to Train Strong Classifiers with Localizable Features. ICCV 2019. [[code](https://github.com/clovaai/CutMix-PyTorch)] 

    *Sangdoo Yun, Dongyoon Han, Seong Joon Oh, Sanghyuk Chun, Junsuk Choe, Youngjoon Yoo.*
      

* **[SaliencyMix'21](https://arxiv.org/abs/2006.01791)** SaliencyMix: A Saliency Guided Data Augmentation Strategy for Better Regularization. ICLR 2021. [[code](x)] 

    *A F M Shahab Uddin and Mst. Sirazam Monira and Wheemyung Shin and TaeChoong Chung and Sung-Ho Bae.*


* **[]()** x. x. [[code](x)] 

    *x*

* **[NFM'22](https://arxiv.org/pdf/2110.02180.pdf)** Noisy Feature Mixup. ICLR 2022. [[code](https://github.com/erichson/NFM)] 

    *Soon Hoe Lim, N. Benjamin Erichson, Francisco Utrera, Winnie Xu, Michael W. Mahoney*

* **[CsaNMT'22](https://arxiv.org/pdf/2204.06812.pdf)** Learning to Generalize to More: Continuous Semantic Augmentation for Neural Machine Translation. ACL 2022. [[code](https://github.com/pemywei/csanmt)] 

    *Xiangpeng Wei, Heng Yu, Yue Hu, Rongxiang Weng, Weihua Luo, Jun Xie, Rong Jin.*

* **[AlignMix'22](https://arxiv.org/abs/2103.15375)** AlignMix: Improving representation by interpolating aligned features. CVPR 2022. [[code](https://github.com/shashankvkt/AlignMixup_CVPR22)] 

    *Shashanka Venkataramanan, Ewa Kijak, Laurent Amsaleg, Yannis Avrithis.*
    
* **[]()** x. x. [[code](x)] 

    *x*

* **[GenLabel'22](https://proceedings.mlr.press/v162/sohn22a/sohn22a.pdf)** GenLabel: Mixup Relabeling using Generative Models. ICML 2022. [[code](https://github.com/UW-Madison-Lee-Lab/GenLabel_official)] 

    *Jy-yong Sohn, Liang Shang, Hongxu Chen, Jaekyun Moon, Dimitris Papailiopoulos, Kangwook Lee.*
    
* **[AutoMix'22](https://arxiv.org/abs/2103.13027)** AutoMix: Unveiling the Power of Mixup for Stronger Classifiers. ECCV 2022. [[code](https://github.com/Westlake-AI/openmixup)]

    *Zicheng Liu, Siyuan Li, Di Wu, Zihan Liu, Zhiyuan Chen, Lirong Wu, Stan Z. Li.*

* **[]()** x. x. [[code](x)] 

    *x*

### Contrastive Learning with Mixup

* **[MixCo'20](https://arxiv.org/abs/2010.06300)** MixCo: Mix-up Contrastive Learning for Visual Representation. NeurIPSW. [[code](https://github.com/Lee-Gihun/MixCo-Mixup-Contrast)] 

    *MixCo: Sungnyun Kim, Gihun Lee, Sangmin Bae, Se-Young Yun.*
    
* **[MoCHi'20](https://arxiv.org/abs/2010.01028)** Hard Negative Mixing for Contrastive Learning. NeurIPS 2020. [[code](https://europe.naverlabs.com/mochi)] 

    *Yannis Kalantidis, Mert Bulent Sariyildiz, Noe Pion, Philippe Weinzaepfel, Diane Larlus.*
    
* **[i-Mix'21](https://arxiv.org/abs/2010.08887)** i-Mix A Domain-Agnostic Strategy for Contrastive Representation Learning. ICLR 2021. [[code](https://github.com/kibok90/imix)] 

    *Kibok Lee, Yian Zhu, Kihyuk Sohn, Chun-Liang Li, Jinwoo Shin, Honglak Lee.*
    
* **[FT'19](https://arxiv.org/abs/2108.02982)** Improving Contrastive Learning by Visualizing Feature Transformation. ICCV 2019 (Oral). [[code](https://github.com/DTennant/CL-Visualizing-Feature-Transformation)] 

    *Rui Zhu, Bingchen Zhao, Jingen Liu, Zhenglong Sun, Chang Wen Chen.*
    
* **[Core-tuning'21](https://arxiv.org/abs/2102.06605)** Unleashing the Power of Contrastive Self-Supervised Visual Models via Contrast-Regularized Fine-Tuning.  NeurIPS 2021. [[code](https://github.com/vanint/core-tuning)] 

    *Yifan Zhang, Bryan Hooi, Dapeng Hu, Jian Liang, Jiashi Feng.*
    
* **[MixSiam'22](https://arxiv.org/pdf/2111.02679.pdf)** MixSiam: A Mixture-based Approach to Self-supervised Representation Learning. AAAI 2022. 

    *Xiaoyang Guo, Tianhao Zhao, Yutian Lin, Bo Du.*
    
* **[Un-Mix'22](https://arxiv.org/abs/2003.05438)** Un-Mix: Rethinking Image Mixtures for Unsupervised Visual Representation. AAAI 2022. [[code](https://github.com/szq0214/Un-Mix)] 

    *Zhiqiang Shen, Zechun Liu, Zhuang Liu, Marios Savvides, Trevor Darrell, Eric Xing.*
    
    
* **[Metrix'22](https://www.semanticscholar.org/reader/a7721bf626f4996117dbb88b385be2e12462e7e6)** It Takes Two to Tango: Mixup for Deep Metric Learning. ICLR 2022. [[code](https://github.com/billpsomas/Metrix_ICLR22)] 

    *Shashanka Venkataramanan, Bill Psomas, Ewa Kijak, Laurent Amsaleg, Konstantinos Karantzalos, Yannis Avrithis.*

* **[ProGCL'22](https://arxiv.org/abs/2110.02027)** ProGCL: Rethinking Hard Negative Mining in Graph Contrastive Learning. ICML 2022. [[code](https://github.com/junxia97/ProGCL)] 

    *Jun Xia, Lirong Wu, Ge Wang, Jintao Chen, Stan Z.Li.*


### Semi-supervised Learning with Mixup

* **[ICT'19](https://arxiv.org/abs/1903.03825)** Interpolation Consistency Training for Semi-Supervised Learning. IJCAI 2019. [[code](https://github.com/vikasverma1077/ICT)] 

    *Vikas Verma, Kenji Kawaguchi, Alex Lamb, Juho Kannala, Yoshua Bengio, David Lopez-Paz*

* **[MixMatch'19](https://arxiv.org/abs/1905.02249)** MixMatch: A Holistic Approach to Semi-Supervised Learning. NeurIPS 2019. [[code](https://github.com/google-research/mixmatch)] 

    *David Berthelot, Nicholas Carlini, Ian Goodfellow, Nicolas Papernot, Avital Oliver, Colin Raffel.*
    
    

