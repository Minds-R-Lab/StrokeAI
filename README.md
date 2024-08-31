# StrokeAI
This is a comprehensive review of the use of AI in stroke segmentation. Here, we include links to and summaries of datasets, papers , and model architectures made for the development stroke segmentation using AI. 
## Datasets
- [ISLES Challenge Datset](https://isles22.grand-challenge.org/dataset/), A collection of medical imaging data focused on the segmentation of ischemic stroke lesions in brain MRI scans. It is widely used for developing and evaluating machine learning models in the field of medical image analysis, particularly for stroke diagnosis and treatment planning.
- [AISD Dataset](https://github.com/GriffinLiang/AISD) Contains 397 Non-Contrast-enhanced CT (NCCT) scans of acute ischemic stroke with the interval from symptom onset to CT less than 24 hours.
- [ATLAS Dataset](https://fcon_1000.projects.nitrc.org/indi/retro/atlas.html), Anatomical Tracings of Lesions After Stroke, A dataset containing manual segmentations of stroke lesions on T1-weighted MRI scans from chronic stroke patients.
- [BRATS Dataset](https://www.med.upenn.edu/cbica/brats2020/data.html), A dataset mostly utilized for segmenting brain tumors, but is sometimes use for stroke segmentation.
- [NIfTI-1](https://nifti.nimh.nih.gov/nifti-1/data), Neuroimaging Informatics Technology Initiative
- [APIS](https://arxiv.org/abs/2309.15243) provides images of two modalities, NCCT and ADC, with the aim of exploiting the complementary information between CT and ADC to improve the segmentation of ischemic stroke lesions.
- [TopCoW Challenge Data](https://topcow24.grand-challenge.org/data/) The challenge data cohort was composed of patients admitted to the Stroke Center of the University Hospital Zurich (USZ) in 2018 and 2019. The inclusion criteria for the challenge data were: 1) both MRA and CTA scans were available for that patient; 2) at least the MRA or CTA allowed for an assessment of the CoW anatomy. The patients of the challenge cohort were admitted for or recovering from a stroke-related neurological disorder, including ischemic stroke, transient ischemic attack, stroke mimic, retinal infarct or amaurosis fugax, intracerebral hemorrhage, and cerebral sinus vein thrombosis.

## Architectures
- [DeepMedic](https://github.com/deepmedic/deepmedic)  A deep multi-scale 3D convolutional neural network (CNN) designed for brain lesion segmentation, including stroke lesions.
- [ADNET](https://github.com/biomedical-data-analysis-laboratory/adnet-for-ais-segmentation) "Self-supervised training mechanism that is tailored to the task of ischemic stroke lesion segmentation by exploiting color-coded parametric maps"
- [SEAN](https://link.springer.com/chapter/10.1007/978-3-030-87234-2_41) A symmetry enhanced attention network for acute ischemic infarct segmentation. "Efficiently captures context information from the opposite side of the image by estimating long-range dependencies."
- [VCANET](https://github.com/Darko28/VCA-Net) "Presents a more brain alike model which mimics the anatomical structure of the human visual cortex."
- [SUNET](https://github.com/NIC-VICOROB/SUNet-architecture) A deep learning architecture for acute stroke lesion segmentation and outcome prediction in multimodal MRI.
- [XNET](https://github.com/Andrewsher/X-Net) A convoluntional nerual network for "Segmentation Based on Depthwise Separable Convolution and Long-range Dependencies".
- [UNET](https://github.com/zhixuhao/unet) A Convolutional network architecture for fast and precise segmentation of images.
- [Attention UNET](https://arxiv.org/abs/1804.03999) An extension of U-Net that incorporates attention mechanisms to focus on the most relevant regions in the image, improving the accuracy of stroke segmentation.
- [VNET](https://arxiv.org/abs/1606.04797) A 3D variant of U-Net designed for volumetric medical imaging segmentation.
- [ResNet](https://arxiv.org/abs/1512.03385) A deep neural network architecture that uses residual learning with shortcut connections to effectively train very deep networks. (Has variants such as ResU-Net)
- [Mask DINO](https://github.com/IDEA-Research/MaskDINO) This repository is the official implementation of the Mask DINO: Towards A Unified Transformer-based Framework for Object Detection and Segmentation (DINO pronounced `daɪnoʊ' as in dinosaur). Our code is based on detectron2. detrex version is opensource simultaneously.
- [DRA-NET](https://www.sciencedirect.com/science/article/abs/pii/S1361841520301559) "An advanced deep CNN architecture that aims to improve predictive performance and that allows for accurate and simultaneous prediction of both lesion types."
- [W-NET](https://www.sciencedirect.com/science/article/abs/pii/S0957417423011399) "A boundary-enhanced segmentation network for stroke lesions"
- [SAN-NET](https://www.sciencedirect.com/science/article/pii/S0010482523001828) "Learning generalization to unseen sites for stroke lesion segmentation with self-adaptive normalization"
- [SIGN](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_9) "Stroke Lesion Segmentation from Low-Quality and Few-Shot MRIs via Similarity-Weighted Self-ensembling Framework"

  
## Papers
- [Segmentation of stroke lesions using transformers-augmented MRI analysis](https://onlinelibrary.wiley.com/doi/pdf/10.1002/hbm.26803)  
- [Application of Deep Learning Method on Ischemic Stroke Lesion Segmentation](https://link.springer.com/article/10.1007/s12204-021-2273-9)
- [Brain stroke classification and segmentation using encoder-decoder based deep convolutional neural networks](https://www.sciencedirect.com/science/article/pii/S001048252200676Xcasa_token=qCB2Xuh7r5wAAAAA:yPcNbf6uZ_mqa3AlEqAmCbcbGD8ijBN93x7OigP45qcMnPqJLm2prJavU3sroSyDxo6HXdtPGLg)
- [CSNet: A new DeepNet framework for ischemic stroke lesion segmentation](https://www.sciencedirect.com/science/article/pii/S0169260719324022?casa_token=rAO9pyYBzUgAAAAA:U1srWb2UdQHvErvIg-FJV8bIPEZettF0sB1KkeeXoBie4vpaFC7VEBrjvsJscOGXXzlXVJhShUI)
- [Improvement of automatic ischemic stroke lesion segmentation in CT perfusion maps using a learned deep neural network](https://www.sciencedirect.com/science/article/pii/S0010482521006430?casa_token=P8QiEV4Rr3YAAAAA:wA60yke6QBMfRdHk9JIEQFUcW88N7EJzQTg3YHj-ARjpe-IEfd8BdjFANLll1Et-n0eXoPXpDMM)
- [Deep learning-based detection and segmentation of diffusion abnormalities in acute ischemic stroke](https://www.nature.com/articles/s43856-021-00062-8)
- [Internet of Medical Things—Based on Deep Learning Techniques for Segmentation of Lung and Stroke Regions in CT Scans](https://ieeexplore.ieee.org/abstract/document/9066845)
- [Deep Learning for Hemorrhagic Lesion Detection and Segmentation on Brain CT Images](https://ieeexplore.ieee.org/abstract/document/9210782/)
- [Brain stroke lesion segmentation using consistent perception generative adversarial network](https://link.springer.com/article/10.1007/s00521-021-06816-8)
- [A fast and fully-automated deep-learning approach for accurate hemorrhage segmentation and volume quantification in non-contrast whole-head CT](https://www.nature.com/articles/s41598-020-76459-7)
- [Attention convolutional neural network for accurate segmentation and quantification of lesions in ischemic stroke disease](https://www.sciencedirect.com/science/article/abs/pii/S1361841520301559)
- [Acute and sub-acute stroke lesion segmentation from multimodal MRI](https://www.sciencedirect.com/science/article/abs/pii/S0169260719305899)
- [Deep convolutional neural network for automatically segmenting acute ischemic stroke lesion in multi-modality MRI](https://link.springer.com/article/10.1007/s00521-019-04096-x)
- [Machine Learning for Detecting Early Infarction in Acute Stroke with Non–Contrast-enhanced CT](https://pubs.rsna.org/doi/full/10.1148/radiol.2020191193)
- [EIS-Net: Segmenting early infarct and scoring ASPECTS simultaneously on non-contrast CT of patients with acute ischemic stroke](https://www.sciencedirect.com/science/article/abs/pii/S136184152100030X)
- [Brain SegNet: 3D local refinement network for brain lesion segmentation](https://link.springer.com/article/10.1186/s12880-020-0409-2)
- [RFDCR: Automated brain lesion segmentation using cascaded random forests with dense conditional random fields](https://www.sciencedirect.com/science/article/pii/S1053811920301075)
- [Brain tumor detection and classification using machine learning: a comprehensive survey](https://link.springer.com/article/10.1007/s40747-021-00563-y)
- [Multi-Receptive-Field CNN for Semantic Segmentation of Medical Images](https://ieeexplore.ieee.org/abstract/document/9166618)
- [DeepNeuro: an open-source deep learning toolbox for neuroimaging](https://link.springer.com/article/10.1007/s12021-020-09477-5)
- [Multi-Feature Analysis for Automated Brain Stroke Classification Using Weighted Gaussian Naïve Bayes Classifier](https://www.worldscientific.com/doi/abs/10.1142/S0218126621501784)
- [Brain Stroke Segmentation Using Deep Learning Models: A Comparative Study](https://arxiv.org/html/2403.17177v1)



## Review papers 
- [Deep learning models for ischemic stroke lesion segmentation in medical images: A survey](https://www.sciencedirect.com/science/article/pii/S0010482524005936)
- [Stroke Lesion Segmentation and Deep Learning: A Comprehensive Review](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10813717/)

