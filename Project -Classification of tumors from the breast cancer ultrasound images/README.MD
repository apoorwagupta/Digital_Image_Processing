


<!-- PROJECT LOGO -->
<br />
<div align="center">
  

  <h3 align="center">Best-README-Template</h3>
  <a href="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.sciencedirect.com%2Fscience%2Farticle%2Fpii%2FS174680942030183X&psig=AOvVaw3YZbZlrzelWHn5P52Lcn0g&ust=1671220049265000&source=images&cd=vfe&ved=0CBAQjRxqFwoTCOCIyYCy_PsCFQAAAAAdAAAAABAm">
    <img  alt="Logo" width="80" height="80">
  </a>
  <p align="center">
    Classification of tumors from the breast cancer ultrasound images
    <hr>
    <br />
  </p>
</div>






<!-- ABOUT THE PROJECT -->
### About 
Breast cancer is the most common disease in women, accounting for nearly 1 in 3 cancers diagnosed in women in the United States, and is the second leading cause of cancer death in women. Breast cancer occurs as a result of abnormal cell growth in the breast tissue, commonly known as a tumour. A tumor is not synonymous with cancer – tumors can be benign (noncancerous), precancerous (precancerous) or malignant (cancerous).  Tests such as MRI, mammography, ultrasound, and biopsy are commonly used to diagnose breast cancer.This project classifies a breast cancer tumor using two training classification:

* 1= Malignant (Cancerous) - Present
* 0= Benign (Not Cancerous) -Absent




### [!Dataset][https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset]

The dataset utilised is the widely-utilized Breast Cancer Ultrasound dataset. There are 657 instances and 2 classes in it (benign and malignant). The distribution of classes is as follows: 210 malignant (34.5%) and 447 benign (65.5%) diseases.

 <a href = "data:image/png;base64,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"



<hr>


The flow of project is as follows: 

1. Identifying the problem and Data Sources

2. Applying Image Processing Techniques

    * Improving the images 
        - Histogram equalization: To improve the contrast in images. 
        - CLAHE: Adaptive histogram equalization (AHE) image processing technique used to improve contrast in images.
        - Bilateral Filter: Applied on gray scale image for de-noising.
        - Otsu’s Binarization: This image segmentation technique is used to partition the image into two groups of pixels based on a threshold value.   
    * Edge detection
        - Sobel Edge Detection:  used to find the approximate absolute gradient magnitude at each point in an input grayscale image.
        - Canny Edge Detection:  Canny algorithm uses four filters to detect horizontal, vertical and diagonal edges in the blurred image.  
    * Morphological Operations
        - Erosion: Morphological erosion removes floating pixels and thin lines,the remaining lines appear thinner and shapes appear smaller.
        - Dilation: Morphological dilation makes objects more visible and fills in small holes in objects.Lines appear thicker, and filled shapes appear larger. 
    * GLCM feature Extraction

3. Building model to predict whether breast cell tissue is malignant or Benign.
The data set was divided into two sections: 20% for testing and 80% for training. Seven conventional models were used.

    * Logistic regression
    * K-Nearest Neighbor 
    * Support Vector Machine 
    * Naive Bayes 
    * Decision Tree 
    * Random Forest 
    * Resnet50
   


<!-- ROADMAP -->
#### Notebook descriptions

- DIPpart1.ipynb : Image processing, feature extraction and 6 ML models.
- DIPPART2resnet50.ipynb : Implementing resnet 50 for the binary classification.

<hr>

#### Contributing
If you have a suggestion that would make this project better it would be greatly appreciated :)




<!-- 

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)
-->



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

