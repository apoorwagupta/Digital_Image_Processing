


<!-- PROJECT LOGO -->
<br />
<div align="center">
  

  <h3 align="center">Classification of tumors from the breast cancer ultrasound images</h3>
  <a href="">
    <img  alt="Logo" width="80" height="80">
  </a>
  <p align="center">
    
    <hr>
    <br />
  </p>
</div>






<!-- ABOUT THE PROJECT -->
### About 
Breast cancer is the most common disease in women, accounting for nearly 1 in 3 cancers diagnosed in women in the United States, and is the second leading cause of cancer death in women. Breast cancer occurs as a result of abnormal cell growth in the breast tissue, commonly known as a tumour. A tumor is not synonymous with cancer – tumors can be benign (noncancerous), precancerous (precancerous) or malignant (cancerous).  Tests such as MRI, mammography, ultrasound, and biopsy are commonly used to diagnose breast cancer.This project uses binary classification and classifies a breast cancer tumor:

    * 1 = Malignant (Cancerous) 
    * 0 = Benign (Not Cancerous) 




### [!Dataset](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset)

The dataset utilised is the widely-utilized Breast Cancer Ultrasound dataset. There are 657 instances and 2 classes in it (benign and malignant). The distribution of classes is as follows: 210 malignant (34.5%) and 447 benign (65.5%) diseases.


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

