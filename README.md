# skinsight-machine-learning
Machine Learning Model for SkinSight

**There are 2 models in this project**
- [Model Classification](https://github.com/C23-PS286-Capstone-Project/skinsight-machine-learning/blob/main/Notebook/SkinSight_Model.ipynb) (Used)
- [Model Detection](https://github.com/C23-PS286-Capstone-Project/skinsight-machine-learning/blob/main/Notebook/SkinSight_ModelV2.ipynb) (Not Implemented yet in server)

## How models work
### [Model Classification](https://github.com/C23-PS286-Capstone-Project/skinsight-machine-learning/blob/main/Notebook/SkinSight_Model.ipynb)
#### Dataset : https://susanqq.github.io/UTKFace/
This model predict age by face image. Just predict the image and if you want to know it's aging or not by compare between actual age and predicted age range
This model have 8 class such as : 
[0-2,
4-6,
8-13,
15-20,
25-32,
38-43,
48-53,
60-]

---

### [Model Detection](https://github.com/C23-PS286-Capstone-Project/skinsight-machine-learning/blob/main/Notebook/SkinSight_ModelV2.ipynb)
#### Dataset (annotated Pascal VOC) : https://universe.roboflow.com/phamphong/skin-tybfq/dataset/5 
This model detect wrinkle, skinredness, vascular, melasma, darkcircle on face. From this detection with some criteria this model can determine premature aging or not
