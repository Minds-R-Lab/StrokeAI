<div align="center">
<h1> StrokeAI </h1>

</div>



Authors: [Mohamed Mabrok](https://scholar.google.com/citations?user=DW4268EAAAAJ&hl=en&authuser=2),Yalda Zafari, [Mostafa Mabrok]() and [Essam Rashed](https://erashed.weebly.com/). 
</p>

This is a comprehensive review of the use of AI in stroke segmentation. Here, we include links to and summaries of datasets, papers , and model architectures made for the development stroke segmentation using AI. 

![image](https://github.com/user-attachments/assets/dc78b2e2-3dd9-49cb-bd87-80c51ad6aa3a)

## Datasets
![image](https://github.com/user-attachments/assets/3df2cb11-cb81-4d5d-a727-68a9ec5f227d)

- [ISLES Challenge Dataset](https://isles22.grand-challenge.org/dataset/)  
  A collection of medical imaging data focused on the segmentation of ischemic stroke lesions in brain MRI scans. It is widely used for developing and evaluating machine learning models in the field of medical image analysis, particularly for stroke diagnosis and treatment planning.

- [AISD Dataset](https://github.com/GriffinLiang/AISD)  
  Contains 397 non-contrast-enhanced CT (NCCT) scans of acute ischemic stroke with the interval from symptom onset to CT less than 24 hours.

- [ATLAS Dataset](https://fcon_1000.projects.nitrc.org/indi/retro/atlas.html)  
  Anatomical Tracings of Lesions After Stroke. A dataset containing manual segmentations of stroke lesions on T1-weighted MRI scans from chronic stroke patients.

- [BRATS Dataset](https://www.med.upenn.edu/cbica/brats2020/data.html)  
  A dataset mostly utilized for segmenting brain tumors but is sometimes used for stroke segmentation.

- [NIfTI-1](https://nifti.nimh.nih.gov/nifti-1/data)  
  Neuroimaging Informatics Technology Initiative.

- [APIS](https://arxiv.org/abs/2309.15243)  
  Provides images of two modalities, NCCT and ADC, with the aim of exploiting the complementary information between CT and ADC to improve the segmentation of ischemic stroke lesions.

- [TopCoW Challenge Data](https://topcow24.grand-challenge.org/data/)  
  The challenge data cohort was composed of patients admitted to the Stroke Center of the University Hospital Zurich (USZ) in 2018 and 2019. The inclusion criteria for the challenge data were: 1) both MRA and CTA scans were available for that patient; 2) at least the MRA or CTA allowed for an assessment of the CoW anatomy. The patients of the challenge cohort were admitted for or recovering from a stroke-related neurological disorder, including ischemic stroke, transient ischemic attack, stroke mimic, retinal infarct or amaurosis fugax, intracerebral hemorrhage, and cerebral sinus vein thrombosis.


## Architectures
![image](https://github.com/user-attachments/assets/85744e9a-a3a7-4e0d-885c-3a530c7bcd8d)

- [DeepMedic](https://github.com/deepmedic/deepmedic)  
  A deep multi-scale 3D convolutional neural network (CNN) designed for brain lesion segmentation, including stroke lesions.

- [ADNET](https://github.com/biomedical-data-analysis-laboratory/adnet-for-ais-segmentation)  
  Self-supervised training mechanism that is tailored to the task of ischemic stroke lesion segmentation by exploiting color-coded parametric maps.

- [SEAN](https://link.springer.com/chapter/10.1007/978-3-030-87234-2_41)  
  A symmetry enhanced attention network for acute ischemic infarct segmentation. Efficiently captures context information from the opposite side of the image by estimating long-range dependencies.

- [VCANET](https://github.com/Darko28/VCA-Net)  
  Presents a more brain alike model which mimics the anatomical structure of the human visual cortex.

- [SUNET](https://github.com/NIC-VICOROB/SUNet-architecture)  
  A deep learning architecture for acute stroke lesion segmentation and outcome prediction in multimodal MRI.

- [XNET](https://github.com/Andrewsher/X-Net)  
  A convolutional neural network for segmentation based on depthwise separable convolution and long-range dependencies.

- [UNET](https://github.com/zhixuhao/unet)  
  A convolutional network architecture for fast and precise segmentation of images.

- [Attention UNET](https://arxiv.org/abs/1804.03999)  
  An extension of U-Net that incorporates attention mechanisms to focus on the most relevant regions in the image, improving the accuracy of stroke segmentation.

- [VNET](https://arxiv.org/abs/1606.04797)  
  A 3D variant of U-Net designed for volumetric medical imaging segmentation.

- [ResNet](https://arxiv.org/abs/1512.03385)  
  A deep neural network architecture that uses residual learning with shortcut connections to effectively train very deep networks. (Has variants such as ResU-Net)

- [Mask DINO](https://github.com/IDEA-Research/MaskDINO)  
  This repository is the official implementation of the Mask DINO: Towards A Unified Transformer-based Framework for Object Detection and Segmentation (DINO pronounced `daɪnoʊ' as in dinosaur). Our code is based on detectron2. detrex version is opensource simultaneously.

- [DRA-NET](https://www.sciencedirect.com/science/article/abs/pii/S1361841520301559)  
  An advanced deep CNN architecture that aims to improve predictive performance and that allows for accurate and simultaneous prediction of both lesion types.

- [W-NET](https://www.sciencedirect.com/science/article/abs/pii/S0957417423011399)  
  A boundary-enhanced segmentation network for stroke lesions.

- [SAN-NET](https://www.sciencedirect.com/science/article/pii/S0010482523001828)  
  Learning generalization to unseen sites for stroke lesion segmentation with self-adaptive normalization.

- [SIGN](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_9)  
  Stroke lesion segmentation from low-quality and few-shot MRIs via similarity-weighted self-ensembling framework.


  
## Papers
**Segmentation of stroke lesions using transformers-augmented MRI analysis.** [24th April, 2024]  
*Ramsha Ahmed, Aamna AlShehhi, Naoufel Werghi, Mohamed L. Seghier*  
[PDF](https://onlinelibrary.wiley.com/doi/pdf/10.1002/hbm.26803)

**Application of Deep Learning Method on Ischemic Stroke Lesion Segmentation.** [29th April, 2024]  
*Yue Zhang, Shijie Liu, Chunlai Li, Jianyu Wang*  
[PDF](https://link.springer.com/article/10.1007/s12204-021-2273-9)

**Brain stroke classification and segmentation using encoder-decoder based deep convolutional neural networks.** [7th May, 2024]  
*Sercan Yalçın, Hüseyin Vural*  
[PDF](https://pubmed.ncbi.nlm.nih.gov/36055156/)

**CSNet: A new DeepNet framework for ischemic stroke lesion segmentation.** [14th May, 2024]  
*Amish Kumar, Neha Upadhyay, Palash Ghosal, Tamal Chowdhury, Dipayan Das, Amritendu Mukherjee, Debashis Nandi*  
[PDF](https://www.sciencedirect.com/science/article/pii/S0169260719324022?casa_token=rAO9pyYBzUgAAAAA:U1srWb2UdQHvErvIg-FJV8bIPEZettF0sB1KkeeXoBie4vpaFC7VEBrjvsJscOGXXzlXVJhShUI)

**Improvement of automatic ischemic stroke lesion segmentation in CT perfusion maps using a learned deep neural network.** [24th April, 2024]  
*Mohsen Soltanpour, Russ Greiner, Pierre Boulanger, Brian Buck*  
[PDF](https://www.sciencedirect.com/science/article/pii/S0010482521006430?casa_token=P8QiEV4Rr3YAAAAA:wA60yke6QBMfRdHk9JIEQFUcW88N7EJzQTg3YHj-ARjpe-IEfd8BdjFANLll1Et-n0eXoPXpDMM)

**Deep learning-based detection and segmentation of diffusion abnormalities in acute ischemic stroke.** [5th June, 2024]  
*Chin Fu Liu, Johnny Hsu, Xin Xu, Sandhya Ramachandran, Victor Wang, Michael I. Miller, Argye E. Hillis, Andreia V. Faria, The STIR and VISTA Imaging investigators*  
[PDF](https://www.nature.com/articles/s43856-021-00062-8)

**Internet of Medical Things—Based on Deep Learning Techniques for Segmentation of Lung and Stroke Regions in CT Scans.** [12th June, 2024]  
*Tao Han, Virgínia Xavier Nunes, Luís Fabrício De Freitas Souza, Adriell Gomes Marques, Iágson Carlos Lima Silva, Marcos Aurélio Araujo Ferreira Junior, Jinghua Sun, Pedro P. Rebouças Filho*  
[PDF](https://ieeexplore.ieee.org/abstract/document/9066845)

**Deep Learning for Hemorrhagic Lesion Detection and Segmentation on Brain CT Images.** [19th June, 2024]  
*Lu Li, Meng Wei, Bo Liu, Kunakorn Atchaneeyasakul, Fugen Zhou, Zehao Pan, Shimran A. Kumar, Jason Y. Zhang, Yuehua*  
[PDF](https://ieeexplore.ieee.org/abstract/document/9210782/)

**Brain stroke lesion segmentation using consistent perception generative adversarial network.** [22nd June, 2024]  
*Shuqiang Wang, Zhuo Chen, Senrong You, Bingchuan Wang, Yanyan Shen, Baiying Lei*  
[PDF](https://link.springer.com/article/10.1007/s00521-021-06816-8)

**A fast and fully-automated deep-learning approach for accurate hemorrhage segmentation and volume quantification in non-contrast whole-head CT.** [28th June, 2024]  
*Ali Arab, Betty Chinda, George Medvedev, William Siu, Hui Guo, Tao Gu, Sylvain Moreno, Ghassan Hamarneh, Martin Ester, Xiaowei Song*  
[PDF](https://www.nature.com/articles/s41598-020-76459-7)

**Attention convolutional neural network for accurate segmentation and quantification of lesions in ischemic stroke disease.** [30th June, 2024]  
*Liangliang Liu, Lukasz Kurgan, Fang-Xiang Wu, Jianxin Wang*  
[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1361841520301559)

**Acute and sub-acute stroke lesion segmentation from multimodal MRI.** [4th July, 2024]  
*Albert Clèrigues, Sergi Valverde, Jose Bernal, Jordi Freixenet, Arnau Oliver, Xavier Lladó*  
[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0169260719305899)

**Deep convolutional neural network for automatically segmenting acute ischemic stroke lesion in multi-modality MRI.** [7th July, 2024]  
*Liangliang Liu, Shaowu Chen, Fuhao Zhang, Fang-Xiang Wu, Yi Pan, Jianxin Wang*  
[PDF](https://link.springer.com/article/10.1007/s00521-019-04096-x)

**Machine Learning for Detecting Early Infarction in Acute Stroke with Non–Contrast-enhanced CT.** [12th July, 2024]  
*Wu Qiu, Hulin Kuang, Ericka Teleg, Johanna M. Ospel, Sung Il Sohn, Mohammed Almekhlafi, Mayank Goyal, Michael D. Hill, Andrew M. Demchuk, Bijoy K. Menon*  
[PDF](https://pubs.rsna.org/doi/full/10.1148/radiol.2020191193)

**EIS-Net: Segmenting early infarct and scoring ASPECTS simultaneously on non-contrast CT of patients with acute ischemic stroke.** [19th July, 2024]  
*Hulin Kuang, Bijoy K. Menon, Sung IL Sohn, Wu Qiu*  
[PDF](https://www.sciencedirect.com/science/article/abs/pii/S136184152100030X)

**Brain SegNet: 3D local refinement network for brain lesion segmentation.** [22nd July, 2024]  
*Xiaojun Hu, Weijian Luo, Jiliang Hu, Sheng Guo, Weilin Huang, Matthew R. Scott, Roland Wiest, Michael Dahlweid, Mauricio Reyes*  
[PDF](https://link.springer.com/article/10.1186/s12880-020-0409-2)

**RFDCR: Automated brain lesion segmentation using cascaded random forests with dense conditional random fields.** [28th July, 2024]  
*Gaoxiang Chen, Qun Li, Fuqian Shi, Islem Rekik, Zhifang Pan*  
[PDF](https://www.sciencedirect.com/science/article/pii/S1053811920301075)

**Brain tumor detection and classification using machine learning: a comprehensive survey.** [30th July, 2024]  
*Javaria Amin, Muhammad Sharif, Anandakumar Haldorai, Mussarat Yasmin, Ramesh Sundar Nayak*  
[PDF](https://link.springer.com/article/10.1007/s40747-021-00563-y)

**Multi-Receptive-Field CNN for Semantic Segmentation of Medical Images.** [5th August, 2024]  
*Liangliang Liu, Fang-Xiang Wu, Yu-Ping Wang, Jianxin Wang*  
[PDF](https://ieeexplore.ieee.org/abstract/document/9166618)

**DeepNeuro: an open-source deep learning toolbox for neuroimaging.** [12th August, 2024]  
*Andrew Beers, James Brown, Ken Chang, Katharina Hoebel, Jay Patel, K. Ina Ly, Sara M. Tolaney, Priscilla Brastianos, Bruce Rosen, Elizabeth R. Gerstner, Jayashree Kalpathy-Cramer*  
[PDF](https://link.springer.com/article/10.1007/s12021-020-09477-5)

**Multi-Feature Analysis for Automated Brain Stroke Classification Using Weighted Gaussian Naïve Bayes Classifier.** [19th August, 2024]  
*S. Jayachitra, A. Prasanth*  
[PDF](https://www.worldscientific.com/doi/abs/10.1142/S0218126621501784)

**Brain Stroke Segmentation Using Deep Learning Models: A Comparative Study.** [22nd August, 2024]  
*Ahmed Solimana, Yousif Yousifa, Ahmed Ibrahima, Yalda Zafari-Ghadima, Essam A. Rashed, Mohamed Mabrok*  
[PDF](https://arxiv.org/html/2403.17177v1)




## Review papers 
- [Deep learning models for ischemic stroke lesion segmentation in medical images: A survey](https://www.sciencedirect.com/science/article/pii/S0010482524005936)
- [Stroke Lesion Segmentation and Deep Learning: A Comprehensive Review](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10813717/)
