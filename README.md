# BreastNet
A novel convolutional neural network model through histopathological images for the diagnosis of breast cancer

# Table of Contents

- [Model Architecture ](https://github.com/Goodsea/BreastNet#model-architecture)
     - [Sub-Modules](https://github.com/Goodsea/BreastNet#sub-modules)
     - [General Architecture](https://github.com/Goodsea/BreastNet#general-architecture)
- [Results](https://github.com/Goodsea/BreastNet#results)
     - [Training Graphs](https://github.com/Goodsea/BreastNet#training-graphs)
          - [40X Data  [Best Model - Graph]](https://github.com/Goodsea/BreastNet#40x-data-best-model-graph)
          - [100X Data [Best Model - Graph]](https://github.com/Goodsea/BreastNet#100x-data-best-model-graph)
          - [200X Data [Best Model - Graph]](https://github.com/Goodsea/BreastNet#200x-data-best-model-graph)
          - [400X Data [Best Model - Graph]](https://github.com/Goodsea/BreastNet#400x-data-best-model-graph)
          - [Combined Data - Benign/Malignant Classification [Best Model Graph]](https://github.com/Goodsea/BreastNet#combined-data---benignmalignant-classification-best-model-graph)
          - [Combined Data - Sub-Benign Diseases Classification [Best Model Graph]](https://github.com/Goodsea/BreastNet#combined-data---sub-benign-diseases-classification-best-model-graph)
          - [Combined Data - Sub-Malignant Diseases Classification [Best Model Graph]](https://github.com/Goodsea/BreastNet#combined-data---sub-malignant-diseases-classification-best-model-graph)
     - [Confusion Matrixes](https://github.com/Goodsea/BreastNet#confusion-matrixes)
          - [40X Data [Best Model Confusion Matrix & ROC Curve]](https://github.com/Goodsea/BreastNet#40x-data-best-model-confusion-matrix--roc-curve)
          - [100X Data [Best Model Confusion Matrix & ROC Curve]](https://github.com/Goodsea/BreastNet#100x-data-best-model-confusion-matrix--roc-curve)
          - [200X Data [Best Model Confusion Matrix & ROC Curve]](https://github.com/Goodsea/BreastNet#200x-data-best-model-confusion-matrix--roc-curve)
          - [400X Data [Best Model Confusion Matrix & ROC Curve]](https://github.com/Goodsea/BreastNet#400x-data-best-model-confusion-matrix--roc-curve)
          - [Combined Data - Benign/Malignant Classification [Best Model Confusion Matrix & ROC Curve]](https://github.com/Goodsea/BreastNet#combined-data---benignmalignant-classification-best-model-confusion-matrix--roc-curve)
          - [Combined Data - Sub-Benign || Sub-Malignant Diseases Classification [Best Model Confusion Matrix]](https://github.com/Goodsea/BreastNet#combined-data---sub-benign--sub-malignant-diseases-classification-best-model-confusion-matrix)
- [Best Pretrained Models](https://github.com/Goodsea/BreastNet#best-pretrained-models)
- [Requirements](https://github.com/Goodsea/BreastNet#requirements)
- [Training](https://github.com/Goodsea/BreastNet#training)
- [License](https://github.com/Goodsea/BreastNet#license)  
- [Citation](https://github.com/Goodsea/BreastNet#citation)  
     
# Model Architecture 
## Sub-Modules
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/base_blocks.png" align="left"></td>
  <td><img src="tmp/residual_block.png" align="right"></td>
  </tr>
</table>
<br>
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/attention_modules_1.png" align="left"></td>
  <td><img src="tmp/attention_modules_2.png" align="right"></td>
  </tr>
</table>
<br>

## General Architecture
<p align="center">
<img src="tmp/BreastNet_arch.png" width=600 height=600 align="center">
</p>
<br>

# Results
## Training Graphs

#### 40X Data [Best Model Graph]
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/40X - 4. FOLD - MODEL ACCURACY.jpg" height=300 align="left"></td>
  <td><img src="tmp/40X - 4. FOLD - MODEL LOSS.jpg" height=300 align="right"></td>
  </tr>
</table>

#### 100X Data [Best Model Graph]
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/100X - 4. FOLD - MODEL ACCURACY.jpg" height=300 align="left"></td>
  <td><img src="tmp/100X - 4. FOLD - MODEL LOSS.jpg" height=300 align="right"></td>
  </tr>
</table>

#### 200X Data [Best Model Graph]
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/200X - 3. FOLD - MODEL ACCURACY.jpg" height=300 align="left"></td>
  <td><img src="tmp/200X - 3. FOLD - MODEL LOSS.jpg" height=300 align="right"></td>
  </tr>
</table>

#### 400X Data [Best Model Graph]
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/400X - 4. FOLD - MODEL ACCURACY.jpg" height=300 align="left"></td>
  <td><img src="tmp/400X - 4. FOLD - MODEL LOSS.jpg" height=300 align="right"></td>
  </tr>
</table>

#### Combined Data - Benign/Malignant Classification [Best Model Graph]
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/ALL_DATA_TOGETHER - 5. FOLD - MODEL ACCURACY.jpg" height=300 align="left"></td>
  <td><img src="tmp/ALL_DATA_TOGETHER - 5. FOLD - MODEL LOSS.jpg" height=300 align="right"></td>
  </tr>
</table>

#### Combined Data - Sub-Benign Diseases Classification [Best Model Graph]
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/ALL_DATA_TOGETHER_BENIGN - 5. FOLD - MODEL ACCURACY.jpg" height=300 align="left"></td>
  <td><img src="tmp/ALL_DATA_TOGETHER_BENIGN - 5. FOLD - MODEL LOSS.jpg" height=300 align="right"></td>
  </tr>
</table>

#### Combined Data - Sub-Malignant Diseases Classification [Best Model Graph]
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/ALL_DATA_TOGETHER_MALIGNANT - 3. FOLD - MODEL ACCURACY.jpg" height=300 align="left"></td>
  <td><img src="tmp/ALL_DATA_TOGETHER_MALIGNANT - 3. FOLD - MODEL LOSS.jpg" height=300 align="right"></td>
  </tr>
</table>
<br>

## Confusion Matrixes
#### 40X Data [Best Model Confusion Matrix & ROC Curve]
<table width="100%" border="1">
  <tr>    
   <td><img src="tmp/40X - confusion matrix - 4. FOLD.jpg" height=300 align="left"></td>
   <td><img src="tmp/40X - ROC - 4. FOLD.jpg" height=300 align="right"></td>
  </tr>
</table>

#### 100X Data [Best Model Confusion Matrix & ROC Curve]
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/100X - confusion matrix - 4. FOLD.jpg" height=300 align="left"></td>
  <td><img src="tmp/100X - ROC - 4. FOLD.jpg" height=300 align="right"></td>
  </tr>
</table>

#### 200X Data [Best Model Confusion Matrix & ROC Curve]
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/200X - confusion matrix - 3. FOLD.jpg" height=300 align="left"></td>
  <td><img src="tmp/200X - ROC - 3. FOLD.jpg" height=300 align="right"></td>
  </tr>
</table>

#### 400X Data [Best Model Confusion Matrix & ROC Curve]
<table width="100%" border="1">
  <tr>  
  <td><img src="tmp/400X - confusion matrix - 4. FOLD.jpg" height=300 align="left"></td>
  <td><img src="tmp/400X - ROC - 4. FOLD.jpg" height=300 align="right"></td>
  </tr>
</table>

#### Combined Data - Benign/Malignant Classification [Best Model Confusion Matrix & ROC Curve]
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/ALL_DATA - confusion matrix - 5. FOLD.jpg" height=300 align="left"></td>
  <td><img src="tmp/All_Data - ROC - 5. FOLD.jpg" height=300 align="right"></td>
  </tr>
</table>

#### Combined Data - Sub-Benign || Sub-Malignant Diseases Classification [Best Model Confusion Matrix]
<table width="100%" border="1">
  <tr>    
  <td><img src="tmp/ALL_DATA_4_CLASS_BENIGN - confusion matrix - 5. FOLD.jpg" height=300 align="left"></td>
  <td><img src="tmp/ALL_DATA_4_CLASS_MALIGNANT - confusion matrix - 3. FOLD.jpg" height=300 align="right"></td>
  </tr>
</table>


# Best Pretrained Models
| Data Type | Fold | Accuracy | F1-Score | Pretrained Model Link |
| --- | --- | --- | --- | --- |
| 40X | 4/5 | 0.979 | 0.976 | <a href="https://drive.google.com/open?id=11zeJ1gxTNwLFYpLgJLhuB3dCQQumy8oe">GDrive[Best Model]</a> |
| 100X | 4/5 | 0.978 | 0.975 | <a href="https://drive.google.com/open?id=1gZEq-xnurwFmhqZ8oUqpM6ic-ZEX9hJ7">GDrive[Best Model]</a> |
| 200X | 3/5 | 0.985 | 0.982 | <a href="https://drive.google.com/open?id=1RpEXjN83oHfVfw6BNXV11sUWHCRQb1kP">GDrive[Best Model]</a> |
| 400X | 4/5 | 0.958 | 0.952 | <a href="https://drive.google.com/open?id=1c-nAOTuzhDyebH8ANKiO_12fxu1l3Pu0">GDrive[Best Model]</a> |
| Combined Benign/Malignant | 5/5 | 0.988 | 0.985 | <a href="https://drive.google.com/open?id=11p9RrkZz1c8WV-kuoVqIIeS3-9p0CC1I">GDrive[Best Model]</a> |
| Combined Sub-Benign | 5/5 | 0.955 | 0.950 | <a href="https://drive.google.com/open?id=1yysBT_QfPw_TwZb7q5zEiSjwFRRmyGRy">GDrive[Best Model]</a> |
| Combined Sub-Malignant | 3/5 | 0.928 | 0.920 | <a href="https://drive.google.com/open?id=1-aqYUC9bjfU80035rr-YuF42-Dqhxcw-">GDrive[Best Model]</a> |

# Requirements
- keras
- tensorflow
- albumentations
- matplotlib
- numpy
- Pillow
- scikit-image
- scikit-learn
- tqdm

# Training
Download and extract <a href="https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/">Breast Cancer Histopathological Database (BreakHis)</a> into "data" folder. Then choose the IPython Notebook to train and test the model.

# License 
This project is licensed under the Apache License 2.0 - see the <a href="LICENSE">LICENSE</a> file for details.

# Citation
```
M. Togaçar, K.B. Özkurt, B. Ergen et al., BreastNet: A novel ˘
convolutional neural network model through histopathological images for the diagnosis of breast
cancer, Physica A (2019), doi: https://doi.org/10.1016/j.physa.2019.123592 .
```
# Contact
If you have any questions about the research, feel free to ask! 
<hr>


```
E-mail: kutsal_baran@hotmail.com
```
