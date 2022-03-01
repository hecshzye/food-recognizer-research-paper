**Food-recognizer-research-paper**

- Food recognition model using `convolutional neural network` & `computer vision`. 

- The goal is to match or beat the DeepFood Research Paper - https://arxiv.org/abs/1606.05675

- Dataset used in this model is `food101` dataset from `Tensorflow datasets`.

Using **Mixed Pricision** and **TESLA T4 GPU** to achieve maximum accuracy without overfitting or excess time consumption during the training.

 - For more information about Nvidia Tesla T4 GPU - https://www.nvidia.com/en-us/data-center/tesla-t4/

 - Mixed Pricision - https://www.tensorflow.org/guide/mixed_precision

#### The  original research on arxiv:
 - https://arxiv.org/abs/1606.05675 focused on Computer-Aided Dietary Assesment.
 
   **It states the following concerns**
     - Worldwide, in 2014, almost 2 billion adults, 18+, were overweight. 
     - Of these, over 600 million were obese.
     - Accurately documenting dietary caloric intake is crucial to manage weight loss, but also presents challenges because most of the current methods for dietary        assessment must rely on memory to recall foods eaten.
     - The ultimate goal of the research is to develop a computer-aided techinical solutions to enhance and improve the accuracy of current measurements of dietary         intake.
     - The proposed system in this paper aims to improve the accuracy of dietary assessment by analyzing food images captured by mobile devices.
     - The key techinique innovation in this paper is the deep learning based food image recognitiion algorithms. Substantial research has demonstrated that digital        imaging accurately estimates dietary intake in many environments and it has many advantages over other methods.


## Accuracy Achieved = **79.999%**
## Accuracy achieved by DeepFood Research Paper = **77.4%**


**Successfully scored 79.999% accuracy for the computer vision model by beating the previous best score by DeepFood Research Paper**


Tensorboard logs at Tensoflow Developer site: https://tensorboard.dev/experiment/g0RluvzpQA2gxNYnilR5Zw/#scalars
