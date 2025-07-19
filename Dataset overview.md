## Dataset Overview: 
We used the Semantic Segmentation of Aerial Imagery dataset from Kaggle for this blog. The dataset features high-resolution 
aerial imagery of Dubai, collected by MBRSC satellites, and annotated with pixel-wise semantic segmentation across six 
distinct classes.

The dataset consists of two types of files:

- **JPG images**: These are the original aerial photographs captured through satellite, representing the real visual input.  
- **PNG images**: These serve as the segmentation masks, where each pixel is labeled according to a predefined semantic class. These masks act as the ground truth for training and evaluating the model.

Each image has a corresponding mask with **pixel-wise alignment**, ensuring that the input and its label match perfectly.

- **Total Images**: 72  
- **Total Corresponding Masks**: 72  
- **Grouped Tiles**: 8 large composite tiles  
- **Image Type**: High-resolution RGB aerial imagery  
- **Annotation Type**: Per-pixel semantic segmentation masks  



###  Semantic Classes and Color Codes

| Class Name          | Description            | RGB Hex Code  | Color           |
|---------------------|------------------------|---------------|-----------------|
| Building            | Man-made structures    | `#3C1098`     | Indigo          |
| Land (unpaved area) | Bare ground/sand       | `#8429F6`     | Purple          |
| Road                | Streets and highways   | `#6EC1E4`     | Sky Blue        |
| Vegetation          | Trees, grass, crops    | `#FEDD3A`     | Golden Yellow   |
| Water               | Rivers, lakes, etc.    | `#E2A929`     | Mustard         |
| Unlabeled           | Background/undefined   | `#9B9B9B`     | Grey            |


### Sample images and masks

<img src="sample images/sample1.png" alt="Sample 1" width="400"/>

<img src="sample images/sample2.png" alt="Sample 2" width="400"/>

<img src="sample images/sample3.png" alt="Sample 3" width="400"/>

<img src="sample images/sample4.png" alt="Sample 4" width="400"/>

<img src="sample images/sample5.png" alt="Sample 4" width="400"/>







