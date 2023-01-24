# Behavior-Detection-by-Pose-Estimation-in-Animals

Quantitative behaviour measurement plays an essential role in addressing the questions raised across neuroscience. It helps the experts understand if there is anything wrong or missing with our lives. Humans however display a multitude of complex behavioural patterns as compared to animals and this makes the task of behaviour detection easier in animals. 

In this research, we have proposed a method for predicting the mood/behaviour of certain pet animals using pose estimations. The method proposed while simple provides a robust solution for quantifying animal behaviour. 

Behaviour detection for animals finds its use in many applications like wildlife conservation, dairy farming and animal healthcare in general. A skeletal model was applied to a small real-world dataset containing images of dogs to generate annotations. This was done by using DeepPoseKit. These annotated images after some corrections were then compared to the original images through a CNN model. The hypothesis is that annotated images will provide better accuracy in identifying the correct behaviour category. The CNN model used three categories of behaviour shown by dogs, namely happy, alert and sad.

> ## To run the code:

1. Refer to the [DeepPoseKit](https://github.com/jgraving/DeepPoseKit) library on Github.
2. Download the source code.
3. Run the files in order: 
   - `DogPoseEstimation.ipynb` 
   - `DogPoseModelApplication.ipynb` 
   - `DogPosePrediction.ipynb` 
   - `BehaviorDetection.ipynb`
