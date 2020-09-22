# mlops_task_4

Problem Statement: Create a project using transfer learning solving various problems like Face Recognition, Image Classification, using existing Deep Learning models like VGG16, VGG19, ResNet, etc.
-------------------------------------------------------------------------------------------------------
Face recognition is a computer vision task of identifying and verifying a person based on a photograph of their face.If you create a model for face recognition you need a lot of resources like you need good CPU and RAM or a great GPU to train your model effectively and a good and effectively trained model means high cost. Otherwise the speed will be very slow and it will take a lot of time to train.
For this reason you can use a pre-trained model and add your own requirements to it so that the model is only trained according to your requirements and less time and memory will be used for training your model. MobileNet is one such pre-trained model in which you can add your requirements and the model would not take much time to train and will give you the required results. This adding of your requirements to a pre-trained model and then training it is called Transfer Learning.
MobileNet is a CNN architecture model for Image Classification and Mobile Vision.There are other models as well but what makes MobileNet special that it very less computation power to run or apply transfer learning to.
Steps:
1. Load the dataset and unzip it (In my case it is zipped data).
2. Load MobileNet Data.
3. Make the function that returns our FC Head.
4. Add our FC Head back onto MobileNet.
5. Load Face Recognition dataset.
6. Train the Model.
7.  Load the Classifier and test classifer on some test images.
All process's images are uploaded and Google Colab is used for the same task.
