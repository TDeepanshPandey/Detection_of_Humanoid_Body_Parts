# Detection of Humanoid Body Parts

During our CUDA lab, we designed a recurrent neural network which can classify head, trunk, hand and legs of a humanoid robot. For this task we downloaded lot of videos from youtube and our lab archives, then generated approx. 10k images from these videos and manually annotated these images.

*The visualization of the annotated images with original images can be seen below -*

![visualization](https://github.com/TDeepanshPandey/Detection_of_Humanoid_Body_Parts/blob/main/initial_visualization.png)


The model is designed from updating a preexsisting model as discussed in the paper [NimbRo-OP2X: Adult-Sized Open-Source 3D Printed Humanoid Robot](https://ieeexplore.ieee.org/document/8625038). We trained the model for **50 epochs**. 

We are able to get some real good predictions (red=head, yellow=trunk, blue=hand, green=leg) -

![good_example](https://github.com/TDeepanshPandey/Detection_of_Humanoid_Body_Parts/blob/main/good_predictions.png)

as well as bad predictions -

![bad_example](https://github.com/TDeepanshPandey/Detection_of_Humanoid_Body_Parts/blob/main/bad_predictions.png)

and was able to achieve an accuracy of **80%** The metrics is shown as below - 

![metrics](https://github.com/TDeepanshPandey/Detection_of_Humanoid_Body_Parts/blob/main/metrics.png)


Our final paper submission report is available here - [Report on my portfolio website](https://deepanshpandey.com/pdf/Dohbp.pdf)


