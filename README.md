# StrokeAI
A Compilation of References to AI programs for Stroke Diagnosis.

## Datasets
- [ISLES Challenge Datset](https://isles22.grand-challenge.org/dataset/), A collection of medical imaging data focused on the segmentation of ischemic stroke lesions in brain MRI scans. It is widely used for developing and evaluating machine learning models in the field of medical image analysis, particularly for stroke diagnosis and treatment planning.
- [ATLAS Dataset](https://fcon_1000.projects.nitrc.org/indi/retro/atlas.html), Anatomical Tracings of Lesions After Stroke, A dataset containing manual segmentations of stroke lesions on T1-weighted MRI scans from chronic stroke patients.
- [BRATS Dataset](https://www.med.upenn.edu/cbica/brats2020/data.html), A dataset mostly utilized for segmenting brain tumors, but is sometimes use for stroke segmentation.
- [NIfTI-1](https://nifti.nimh.nih.gov/nifti-1/data), Neuroimaging Informatics Technology Initiative

## Architectures
- [DeepMedic](https://github.com/deepmedic/deepmedic)  A deep multi-scale 3D convolutional neural network (CNN) designed for brain lesion segmentation, including stroke lesions.
- [SUNET](https://github.com/NIC-VICOROB/SUNet-architecture) A deep learning architecture for acute stroke lesion segmentation and outcome prediction in multimodal MRI.
- [XNET](https://github.com/Andrewsher/X-Net) A convoluntional nerual network for "Segmentation Based on Depthwise Separable Convolution and Long-range Dependencies".
- [UNET](https://github.com/zhixuhao/unet) A Convolutional network architecture for fast and precise segmentation of images.
- [VNET](https://arxiv.org/abs/1606.04797) A 3D variant of U-Net designed for volumetric medical imaging segmentation.
- [ResNet](https://arxiv.org/abs/1512.03385) A deep neural network architecture that uses residual learning with shortcut connections to effectively train very deep networks. (Has variants such as ResU-Net)

  
## Papers
- [Segmentation of stroke lesions using transformers-augmented
MRI analysis](https://onlinelibrary.wiley.com/doi/pdf/10.1002/hbm.26803)  Accurate segmentation of chronic stroke lesions from mono-spectral magnetic resonance imaging scans (e.g., T1-weighted images) is a difficult task due to the arbitrary
shape, complex texture, variable size and intensities, and varied locations of the
lesions. Due to this inherent spatial heterogeneity, existing machine learning methods
have shown moderate performance for chronic lesion delineation. In this study, we
introduced: (1) a method that integrates transformers' deformable feature attention
mechanism with convolutional deep learning architecture to improve the accuracy and
generalizability of stroke lesion segmentation, and (2) an ecological data augmentation
technique based on inserting real lesions into intact brain regions. Our combination of
these two approaches resulted in a significant increase in segmentation performance,
with a Dice index of 0.82 (±0.39), outperforming the existing methods trained and
tested on the same Anatomical Tracings of Lesions After Stroke (ATLAS) 2022 dataset.
Our method performed relatively well even for cases with small stroke lesions. We validated the robustness of our method through an ablation study and by testing it on
new unseen brain scans from the Ischemic Stroke Lesion Segmentation (ISLES) 2015
dataset. Overall, our proposed approach of transformers with ecological data augmentation offers a robust way to delineate chronic stroke lesions with clinically relevant
accuracy. Our method can be extended to other challenging tasks that require automated detection and segmentation of diverse brain abnormalities from clinical scans.
