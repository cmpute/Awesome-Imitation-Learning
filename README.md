# Awesome-Imitation-Learning: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome imitation learning (including inverse reinforcement learning and behavior cloning) resources, inspired by [awesome-php](https://github.com/ziadoz/awesome-php).

## Contribution 
Please feel free to send me [pull request](https://github.com/kristery/Awesome-Imitation-Learning/pulls) or email (d06922005@csie.ntu.edu.tw) to add links.

## Table of Contents

  - [Papers](#papers)
  - [Tutorials and Talks](#tutorials-and-talks)
  - [Blogs](#blogs)

## Papers

### General settings
  * [Generative Adversarial Imitation Learning](https://arxiv.org/abs/1606.03476), J. Ho et al., NIPS 2016
  * [Deep Q-learning from Demonstrations](https://arxiv.org/abs/1704.03732), T. Hester et al., AAAI 2018
  * [Third-Person Imitation Learning](https://arxiv.org/abs/1703.01703), B. Stadie et al., ICLR 2017
  * [Self-Imitation Learning](https://arxiv.org/abs/1806.05635), J. Oh., ICML 2018
  * [RAIL: Risk-Averse Imitation Learning](https://arxiv.org/abs/1707.06658), A. Santara et al., NIPS 2017
  * [An Algorithmic Perspective on Imitation Learning](https://www.nowpublishers.com/article/Details/ROB-053), T. Osa et al.
  * [Discriminator-Actor-Critic: Addressing Sample Inefficiency and Reward Bias in Adversarial Imitation Learning](https://arxiv.org/pdf/1809.02925.pdf), I. Kostrikov et al.
  * [Universal Planning Networks](https://arxiv.org/pdf/1804.00645.pdf), A. Srinivas et al.
  * [Imitation Learning from Imperfect Demonstration](https://arxiv.org/abs/1901.09387), Y. Wu et al., ICML 2019
  * [Learning to Search via Retrospective Imitation](https://authors.library.caltech.edu/92668/1/1804.00846.pdf), J. Song et al.
  * [Learning Plannable Representations with Causal InfoGAN](http://papers.nips.cc/paper/8090-learning-plannable-representations-with-causal-infogan.pdf), T. Kurutach et al., NIPS 2018
  * Random Expert Distillation: Imitation Learning via Expert Policy Support Estimation, R. Wang et al., ICML 2019

### Applications
  * [Learning Montezuma’s Revenge from a Single Demonstration](https://arxiv.org/pdf/1812.03381.pdf), T. Salimans., et al.
  * [ChauffeurNet: Learning to Drive by Imitating the Best and Synthesizing the Worst](https://arxiv.org/pdf/1812.03079.pdf), M. Bansal et al.
  * [Video Imitation GAN: Learning control policies by imitating raw videos using generative adversarial reward estimation](https://arxiv.org/pdf/1810.01108.pdf), S. Chaudhury et al.
  * [End-to-end Driving via Conditional Imitation Learning](https://arxiv.org/abs/1710.02410), F. Codevilla et al., ICRA 2018
  * [End-to-End Learning Driver Policy using Moments Deep Neural Network](https://ieeexplore.ieee.org/abstract/document/8664869), D. Qian et al., ROBIO 2018

### Survey papers
  * [Deep Reinforcement Learning: An Overview](https://arxiv.org/abs/1701.07274), Y. Li. 
  * [A Brief Survey of Deep Reinforcement Learning](https://arxiv.org/abs/1708.05866), K. Arulkumaran et al.
  * [Imitation Learning : A Survey of Learning Methods](http://www.open-access.bcu.ac.uk/5045/1/Imitation%20Learning%20A%20Survey%20of%20Learning%20Methods.pdf), A. Hussein et al.

### Cold-start methods
  * [One-Shot Imitation Learning](http://papers.nips.cc/paper/6709-one-shot-imitation-learning), Y. Duan et al., NIPS 2017
  * [Zero-Shot Visual Imitation](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w40/Pathak_Zero-Shot_Visual_Imitation_CVPR_2018_paper.pdf), D. Pathak et al., ICLR 2018
  * [One-Shot Hierarchical Imitation Learning of Compound Visuomotor Tasks](https://arxiv.org/pdf/1810.11043.pdf), T. Yu et al.

### Learning multi-modal behaviors
  * [Robust Imitation of Diverse Behaviors](http://papers.nips.cc/paper/7116-robust-imitation-of-diverse-behaviors), Z. Wang et al., NIPS 2017
  * [Multi-Modal Imitation Learning from Unstructured Demonstrations using Generative Adversarial Nets](http://papers.nips.cc/paper/6723-multi-modal-imitation-learning-from-unstructured-demonstrations-using-generative-adversarial-nets), K. Hausman et al., NIPS 2017
  * [InfoGAIL: Interpretable Imitation Learning from Visual Demonstrations](http://papers.nips.cc/paper/6971-infogail-interpretable-imitation-learning-from-visual-demonstrations), Y. Li et al., NIPS 2017
  * [Learning a Multi-Modal Policy via Imitating Demonstrations with Mixed Behaviors](https://arxiv.org/pdf/1903.10304), F Hsiao et al.

### Learning from multi-task demonstrations
  * [Shared Multi-Task Imitation Learning for Indoor Self-Navigation](https://arxiv.org/pdf/1808.04503.pdf), J. Xu et al.

### Hierarchical approaches
  * [Hierarchical Imitation and Reinforcement Learning](https://arxiv.org/abs/1803.00590), H. Le et al., ICML 2018
  * [OptionGAN: Learning Joint Reward-Policy Options using Generative Adversarial Inverse Reinforcement Learning](https://arxiv.org/pdf/1709.06683.pdf), P. Henderson et al., AAAI 2018
  * [Directed-Info GAIL: Learning Hierarchical Policies from Unsegmented Demonstrations using Directed Information](https://openreview.net/pdf?id=BJeWUs05KQ), M. Sharma et al., ICLR 2019
  * [CompILE: Compositional Imitation Learning and Execution](https://arxiv.org/pdf/1812.01483.pdf), T. Kipf., ICML 2019

### Learning from human preference
  * [Deep Reinforcement Learning from Human Preferences](http://papers.nips.cc/paper/7017-deep-reinforcement-learning-from-human-preferences), P. Christiano et al., NIPS 2017
  * [A Low-Cost Ethics Shaping Approach for Designing Reinforcement Learning Agents](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16195/15869), Y. Wu et al., AAAI 2018

### Learning from observations
  * [Imitation from Observation: Learning to Imitate Behaviors from Raw Video via Context Translation](https://arxiv.org/abs/1707.03374), Y. Liu et al.
  * [Observational Learning by Reinforcement Learning](https://arxiv.org/abs/1706.06617), D. Borsa et al.
  * Provably Efficient Imitation Learning from Observation Alone, W. Sun et al., ICML 2019
  * [Adversarial Imitation Learning from State-only Demonstrations](https://dl.acm.org/citation.cfm?id=3332067), F. Torabi et al., AAMAS 2019

### Model-based approaches
  * [End-to-End Differentiable Adversarial Imitation Learning](http://proceedings.mlr.press/v70/baram17a/baram17a.pdf), N. Baram et al., ICML 2017

### Behavior cloning
  * [Behavioral Cloning from Observation](https://arxiv.org/abs/1805.01954), F. Torabi et al., IJCAI 2018
  * [Causal Confusion in Imitation Learning](https://people.eecs.berkeley.edu/~dineshjayaraman/projects/causal_confusion_nips18.pdf), P. Haan et al., NIPS 2018
  * [Truly Batch Apprenticeship Learning with Deep Successor Features](https://arxiv.org/pdf/1903.10077), D. Lee et al.

### Imitation with rewards
  * [Leveraging Demonstrations for Deep Reinforcement Learning on Robotics Problems with Sparse Reward](https://pdfs.semanticscholar.org/8186/04245973bb30ad021728149a89157b3b2780.pdf), M. Vecerik et al.
  * [Reinforcement and Imitation Learning for Diverse Visuomotor Skills](https://arxiv.org/abs/1802.09564), Y. Zhu et al., RSS 2018
  * [Policy Optimization with Demonstrations](http://proceedings.mlr.press/v80/kang18a.html), B. Kang et al., ICML 2018
  * [Reinforcement Learning from Imperfect Demonstrations](https://arxiv.org/pdf/1802.05313.pdf), Y. Gao et al., ICML Workshop 2018
  * [Pre-training with Non-expert Human Demonstration for Deep Reinforcement Learning](https://arxiv.org/pdf/1812.08904.pdf), G. Cruz Jr et al.
  * [Sparse Reward Based Manipulator Motion Planning by Using High Speed Learning from Demonstrations](https://ieeexplore.ieee.org/abstract/document/8665328), G. Zuo et al., ROBIO 2018
  * [Reinforced Imitation in Heterogeneous Action Space](https://arxiv.org/pdf/1904.03438.pdf), K. Zolna et al.

### Multi-agent systems
  * [Independent Generative Adversarial Self-Imitation Learning in Cooperative Multiagent Systems](https://dl.acm.org/citation.cfm?id=3331837), X. Hao et al., AAMAS 2019

### Inverse reinforcement learning
  * [Maximum Entropy Inverse Reinforcement Learning](https://www.aaai.org/Papers/AAAI/2008/AAAI08-227.pdf), B. Ziebart et al., AAAI 2008
  * [A Connection Between Generative Adversarial Networks, Inverse Reinforcement Learning, and Energy-Based Models](https://arxiv.org/pdf/1611.03852.pdf), C. Finn et al., NIPS Workshop 2016
  * [Compatible Reward Inverse Reinforcement Learning](https://papers.nips.cc/paper/6800-compatible-reward-inverse-reinforcement-learning), A. Metelli et al., NIPS 2017
  * [Learning Robust Rewards with Adversarial Inverse Reinforcement Learning](https://arxiv.org/abs/1710.11248), J. Fu et al.
  * [Model-Free Deep Inverse Reinforcement Learning by Logistic Regression](https://link.springer.com/article/10.1007/s11063-017-9702-7), E. Uchibe
  * [Extrapolating Beyond Suboptimal Demonstrations via Inverse Reinforcement Learning from Observations](https://arxiv.org/abs/1904.06387), D. Brown et al. 

## Tutorials and talks
  * [2018 ICML](https://www.youtube.com/watch?v=6rZTaboSY4k) [(Slides)](https://sites.google.com/view/icml2018-imitation-learning/)
  * [Imitation learning basic (National Taiwan University)](https://www.youtube.com/watch?v=rOho-2oJFeA)
  * [New Frontiers in Imitation Learning (2017)](https://www.youtube.com/watch?v=4PnNlvPGbUQi)
  * [Unity Course](https://www.youtube.com/watch?v=uiutRBXfEbg)

## Blogs
  * [Introduction to Imitation Learning](https://blog.statsbot.co/introduction-to-imitation-learning-32334c3b1e7a)

### Materials
  * [Imitation Learning](http://ciml.info/dl/v0_99/ciml-v0_99-ch18.pdf)
  * [CMU Imitation Learning](https://katefvision.github.io/katefSlides/immitation_learning_I_katef.pdf)
  * [Deep Reinforcement Learning via Imitation Learning](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=10&cad=rja&uact=8&ved=2ahUKEwi7tJ_gvI_eAhXGE7wKHV7WDoUQFjAJegQICRAC&url=https%3A%2F%2Fbcourses.berkeley.edu%2Fcourses%2F1453965%2Ffiles%2F69855652%2Fdownload%3Fverifier%3D5DYZT6niDXA1pc4fTuIndZ1tpIsJeCmcicRgcpY2%26wrap%3D1&usg=AOvVaw2HHdnf9uYaJalo6t9kv46s), S. Levine

## Licenses
License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Yueh-Hua Wu](https://kristery.github.io/) has waived all copyright and related or neighboring rights to this work.
