# Awesome AI for Single Cell Data Analysis

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a repo holding papers on deep learning based methodology for single cell data analysis. This repo covers papers from a variety of sources, including conferences, conference workshops, journals, arxiv, bioRxiv, medRxiv and so on. 

These papers are categoried by methods, which can be seen in the following content table. Some papers target at on task of single cell data analysis while some aim at multiple tasks. We can basically tell from their titles.

Note: For convenience, AE and VAE based papers are all put under the category of generative models.


## Contributing
Please feel free to [pull requests](https://github.com/sallyqus/awesome-AI4SingleCell/pulls), email Sally (sally.qus@gmail.com) or join slack to add links. 

Slack: https://join.slack.com/t/singlecellomics/shared_invite/zt-ipv6eff4-zp1MiVxnj8pEiyGKnWqwCg

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#review-and-analysis-papers">1. Review and Analysis Papers</a></td></tr> 
<tr><td colspan="2"><a href="#deep-neural-networks">2. Deep Neural Networks </a></td></tr>
<tr>
    <td>&emsp;<a href="#anns">2.1 ANNs </a></td>
    <td>&ensp;<a href="#cnns">2.2 CNNs </a></td>
</tr>
<tr><td colspan="2"><a href="#generative-models">3. Generative Models </a></td></tr> 
<tr>
    <td>&emsp;<a href="#gan">3.1 GAN </a></td>
    <td>&ensp;<a href="#ae-vae">3.2 VAE </a></td>
</tr>
<tr><td colspan="2"><a href="#graph-neural-networks">4. Graph Neural Networks</a></td></tr> 
<tr><td colspan="2"><a href="#reinforcement-learning">5. Reinforcement Learning</a></td></tr> 
<tr><td colspan="2"><a href="#natural-language-processing">6. Natural Language Processing</a></td></tr> 
<tr><td colspan="2"><a href="#meta-learning">7. Meta Learning </a></td></tr>
<tr><td colspan="2"><a href="#neural-archetecture-search">8. Neural Architecture Search  </a></td></tr>
</table>



## [Review and Analysis Papers](#content)

1. **Bayesian deep learning for single-cell analysis.** Nat. Method 2018. [paper](https://www.nature.com/articles/s41592-018-0230-9.pdf?origin=ppub)

    *Gregory P. Way, Casey S. Greene.* 
    
1. **Deep learning: new computational modelling techniques for genomics.** Nat. Reviews Genetics 2018. [paper](https://www.nature.com/articles/s41576-019-0122-6.pdf)

    *Gökcen Eraslan, Žiga Avsec, Julien Gagneur, Fabian J. Theis*

1. **Parameter tuning is a key part of dimensionality reduction via deep variational autoencoders for single cell RNA transcriptomics.** Pac Symp Biocomput. 2019. [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6417816/pdf/nihms-999823.pdf)

    *Qiwen Gu, Casey S. Greene.*
    
1. **Emerging deep learning methods for single-cell RNA-seq data analysis.** Quantitative Biology 2019. [paper](https://link.springer.com/content/pdf/10.1007/s40484-019-0189-2.pdf)

    *Jie Zheng, Ke Wang.*
        
## [Deep Neural Networks](#content)   

### [ANNs](#content)

1. **ACTINN: automated identification of cell types in single cell RNA sequencing.** Bioinformatics 2019. [paper](https://academic.oup.com/bioinformatics/article-pdf/36/2/533/31962865/btz592.pdf)
   
    *Feiyang Ma, Matteo Pellegrini.* 

1. **Using neural networks for reducing the dimensions of single-cell RNA-Seq data.** NAR 2017. [paper](https://academic.oup.com/nar/article-pdf/45/17/e156/25366829/gkx681.pdf)
   
    *Chieh Lin, Siddhartha Jain, Hannah Kim, Ziv Bar-Joseph.* 

1. **DeepImpute: an accurate, fast, and scalable deep neural network method to impute single-cell RNA-seq data.** Genome Biology 2019. [paper](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1837-6)
   
    *Cédric Arisdakessian, Olivier Poirion, Breck Yunits, Xun Zhu & Lana X. Garmire.* 

### [CNNs](#content)

1. **Single-Cell Phenotype Classification Using Deep Convolutional Neural Networks.** Journal of Biomolecular Screening 2016. [paper](https://journals.sagepub.com/doi/pdf/10.1177/1087057116631284)
   
    *Oliver Dürr, Beate Sick.* 

1. **Single-cell ATAC-Seq in human pancreatic islets and deep learning upscaling of rare cells reveals cell-specific type 2 diabetes regulatory signatures.** Molecular Metabolism 2019. [paper](https://www.sciencedirect.com/science/article/pii/S2212877819309573#appsec1)
   
    *Vivek Rai, Daniel X. Quang, Michael R. Erdos, Darren A. Cusanovich, Riza M. Daza, Narisu Narisu, Luli S. Zou, John P. Didion, Yuanfang Guan, Jay Shendure, Stephen C.J. Parker, Francis S. Collins.* 
    
## [Generative Models](#content)   


### [GAN](#content)
1. **MAGAN: Aligning Biological Manifolds.** ICML 2018. [paper](http://proceedings.mlr.press/v80/amodio18a/amodio18a.pdf)
   
    *Matthew Amodio, Smita Krishnaswamy.* 

1. **wGAN: Generative adversarial networks simulate gene expression and predict perturbations in single cells.** bioRxiv 2018. [paper](http://proceedings.mlr.press/v80/amodio18a/amodio18a.pdf)
   
    *Arsham Ghahramani, Fiona M. Watt, and Nicholas M. Luscombe.* 

1. **scGen predicts single-cell perturbation responses.** Nat. Method 2019. [paper](https://www.nature.com/articles/s41592-019-0494-8.pdf)
   
    *Mohammad Lotfollahi, F. Alexander Wolf, Fabian J. Theis.* 

1. **cscGAN: Realistic in silico generation and augmentation of single-cell RNA-seq data using generative adversarial networks.** Nat. Comm. 2020. [paper](https://www.nature.com/articles/s41467-019-14018-z.pdf)
   
    *Mohamed Marouf, Pierre Machart, Vikas Bansal, Christoph Kilian, Daniel S. Magruder, Christian F. Krebs, Stefan Bonn.* 

1. **Super-OT: Optimal Transport using GANs for Lineage Tracing.** arxiv. 2020. [paper](https://arxiv.org/pdf/2007.12098.pdf)
   
    *Neha Prasad, Karren D. Yang, Caroline Uhler.*

1. **scIGANs: single-cell RNA-seq imputation using generative adversarial networks.** NAR 2020. [paper](https://academic.oup.com/nar/article-pdf/48/15/e85/33697370/gkaa506.pdf)
   
    *Yungang Xu, Zhigang Zhang, Lei You, Jiajia Liu, Zhiwei Fan, Xiaobo Zhou.*
    

### [AE VAE](#content)

1. **AutoImpute: Autoencoder based imputation of single-cell RNA-seq data.** Sci. Rep. 2018. [paper](https://www.nature.com/articles/s41598-018-34688-x.pdf)
   
    *Divyanshu Talwar, Aanchal Mongia, Debarka Sengupta & Angshul Majumdar.* 

1. **scvis: Interpretable dimensionality reduction of single cell transcriptome data with deep generative models.** Nat. Comm. 2018. [paper](https://www.nature.com/articles/s41592-018-0229-2.pdf)
   
    *Jiarui Ding, Anne Condon, Sohrab P. Shah.* 

1. **VASC: Dimension Reduction and Visualization of Single-cell RNA-seq Data by Deep Variational Autoencoder.** Genomics, Proteomics & Bioinformatics. 2018. [paper](https://www.sciencedirect.com/science/article/pii/S167202291830439X)
   
    *Dongfang Wang, Jin Gu.* 
    
1. **scVI: Deep generative modeling for single-cell transcriptomics.** Nat. Methods 2018. [paper](https://www.nature.com/articles/s41592-018-0229-2.pdf)
   
    *Romain Lopez, Jeffrey Regier, Michael B. Cole, Michael I. Jordan, Nir Yosef.* 
    
1. **scANVI: Probabilistic Harmonization and Annotation of Single-cell Transcriptomics Data with Deep Generative Models.** bioRxiv 2019. [paper](https://www.biorxiv.org/content/10.1101/532895v2.full.pdf)
   
    *Chenling Xu, Romain Lopez, Edouard Mehlman, Jeffrey Regier, Michael I. Jordan, Nir Yosef.* 

1. **SAVER-X: Data denoising with transfer learning in single-cell transcriptomics.** Nat. Methods 2019. [paper](https://www.nature.com/articles/s41592-019-0537-1.pdf)
   
    *Jingshu Wang, Divyansh Agarwal, Mo Huang, Gang Hu, Zilu Zhou, Chengzhong Ye, Nancy R. Zhang.* 
    
1. **CNNC: Deep learning for inferring gene relationships from single-cell expression data.** PNAS 2019. [paper](https://www.pnas.org/content/pnas/116/52/27151.full.pdf)
   
    *Ye Yuan, Ziv Bar-Josepha.* 

1. **scDeepCluster: Clustering single-cell RNA-seq data with a model-based deep learning approach.** Nat. Machine Intelligence 2019. [paper](https://www.nature.com/articles/s42256-019-0037-0.pdf)
   
    *Tian Tian, Ji Wan, Qi Song, Zhi Wei* 

1. **scScope: Scalable analysis of cell-type composition from single-cell transcriptomics using deep recurrent learning.** Nat. Methods 2019. [paper](https://www.nature.com/articles/s41592-019-0353-7.pdf)
   
    *Yue Deng, Feng Bao, Qionghai Dai, Lani F. Wu & Steven J. Altschuler.* 
 
1. **DCA: Single-cell RNA-seq denoising using a deep count autoencoder.** Nat. Methods 2019. [paper](https://www.nature.com/articles/s41467-018-07931-2.pdf)
   
    *Gökcen Eraslan, Lukas M. Simon, Maria Mircea, Nikola S. Mueller, Fabian J. Theis.* 
 
1. **SAUCIE: Exploring single-cell data with deep multitasking neural networks.** Nat. Methods 2019. [paper](https://www.nature.com/articles/s41592-019-0576-7.pdf)
   
    *Matthew Amodio, David van Dijk, Krishnan Srinivasan, William S. Chen, Hussein Mohsen, Kevin R. Moon, Allison Campbell, Yujiao Zhao, Xiaomei Wang, Manjunatha Venkataswamy, Anita Desai, V. Ravi, Priti Kumar, Ruth Montgomery, Guy Wolf, Smita Krishnaswamy* 

1. **trVAE: Conditional out-of-sample generation for unpaired data using trVAE.** arXiv 2019. [paper](https://arxiv.org/pdf/1910.01791.pdf)
   
    *Mohammad Lotfollahi, Mohsen Naghipourfar, Fabian J. Theis, F. Alexander Wolf.* 
    
1. **Multi-Domain Translation between Single-Cell Imaging and Sequencing Data using Autoencoders.** bioRxiv 2019. [paper](https://www.biorxiv.org/content/10.1101/2019.12.13.875922v1.full.pdf)
   
    *Karren Dai Yang, Anastasiya Belyaeva, Saradha Venkatachalapathy, Karthik Damodaran, Adityanarayanan Radhakrishnan, Abigail Katcoff, GV Shivashankar, Caroline Uhler.* 
    
1. **DESC: Deep learning enables accurate clustering with batch effect removal in single-cell RNA-seq analysis.** Nat. Comm. 2020. [paper](https://www.nature.com/articles/s41467-020-15851-3.pdf)
   
    *Xiangjie Li, Kui Wang, Yafei Lyu, Huize Pan, Jingxiao Zhang, Dwight Stambolian, Katalin Susztak, Muredach P. Reilly, Gang Hu, Mingyao Li* 

1. **scVAE: variational auto-encoders for single-cell gene expression data.** Bioinformatics 2020. [paper](https://academic.oup.com/bioinformatics/article/36/16/4415/5838187)
   
    *Christopher Heje Grønbech, Maximillian Fornitz Vording, Pascal N Timshel, Casper Kaae Sønderby, Tune H Pers, Ole Winther* 

1. **DISC: a highly scalable and accurate inference of gene expression and structure for single-cell transcriptomes using semi-supervised deep learning.** Genome Biology 2020. [paper](https://genomebiology.biomedcentral.com/track/pdf/10.1186/s13059-020-02083-3)
   
    *Nicholas J. Bernstein, Nicole L. Fong, Irene Lam, Margaret A. Roy, David G. Hendrickson, David R. Kelley.* 
    
1. **Solo: Doublet Identification in Single-Cell RNA-Seq via Semi-Supervised Deep Learning.** Cell Systems 2020. [paper](https://www.sciencedirect.com/science/article/pii/S2405471220301952)
   
    *Yao He, Hao Yuan, Cheng Wu, Zhi Xie.* 
    
## [Graph Neural Networks](#content)  

1. **Unsupervised generative and graph representation learning for modelling cell differentiation.** Sci. Rep.. 2020. [paper](https://www.nature.com/articles/s41598-020-66166-8.pdf)
   
    *Ioana Bica, Helena Andrés-Terré, Ana Cvejic, Pietro Liò * 

1. **Disease State Prediction From Single-Cell Data Using Graph Attention Networks.** CHIL. 2020. [paper](https://arxiv.org/pdf/2002.07128)
   
    *Neal G. Ravindra, Arijit Sehanobish, Jenna L. Pappalardo, David A. Hafler, David van Dijk* 
    
1. **SCGNN: scRNA-seq Dropout Imputation via Induced Hierarchical Cell Similarity Graph.** ICML CompBio Workshop. 2020. [paper](https://icml-compbio.github.io/2020/papers/WCBICML2020_paper_17.pdf)
   
    *Kexin Huang* 
    
1. **scDeepsort: Reference-free Cell-type Annotation for Single-cell Transcriptomics using Deep Learning with a Weighted Graph Neural Network.** bioRxiv. 2020. [paper](https://www.biorxiv.org/content/10.1101/2020.05.13.094953v2.full.pdf)
   
    *Xin Shao, Haihong Yang, Xiang Zhuang, Jie Liao, Yueren Yang, Penghui Yang, Junyun Cheng, Xiaoyan Lu, Huajun Chen, Xiaohui Fan* 
    
1. **GraphSCI: Imputing Single-cell RNA-seq data by combining Graph Convolution and Autoencoder Neural Networks.** bioRxiv. 2020. [paper](https://www.biorxiv.org/content/10.1101/2020.02.05.935296v1.full.pdf)
   
    *Jiahua Rao, Xiang Zhou, Yutong Lu, Huiying Zhao, Yuedong Yang* 
    
1. **GraphSCC: Accurately Clustering Single-cell RNA-seq data by Capturing Structural Relations between Cells through Graph Convolutional Network.** bioRxiv. 2020. [paper](https://www.biorxiv.org/content/10.1101/2020.09.02.278804v1.full.pdf)
   
    *Yuansong Zeng, Xiang Zhou, Jiahua Rao, Yutong Lu, Yuedong Yang* 
    
## [Reinforcement Learning](#content)   
## [Natural Language Processing](#content)  
1. **Representation Learning and Translation between the Mouse and HumanBrain using a Deep Transformer Architecture.** ICML CompBio Workshop 2020. [paper](https://icml-compbio.github.io/2020/papers/WCBICML2020_paper_29.pdf)
   
    *Minxing Pang, Jesper Tegner.* 
    
## [Meta Learning](#content)   
1. **MARS: discovering novel cell types across heterogeneous single-cell experiments.** Nat. Method 2020. [paper](https://www.nature.com/articles/s41592-020-00979-3)
   
    *Maria Brbić, Marinka Zitnik, Sheng Wang, Angela O. Pisco, Russ B. Altman, Spyros Darmanis, Jure Leskovec.* 

## [Neural Archetecture Search](#content)   
