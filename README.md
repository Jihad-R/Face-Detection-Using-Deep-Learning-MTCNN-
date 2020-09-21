# Face-Detection-Using-Deep-Learning-MTCNN-
Demonstrating face detection using Multi-Task Convolutional Neural Network.
> The proposed CNNs consist of three stages. In the first stage, it produces candidate windows quickly through a shallow CNN. Then, it refines the windows to reject a large number of non-faces windows through a more complex CNN. Finally, it uses a more powerful CNN to refine the result and output facial landmarks positions. [source](https://arxiv.org/abs/1604.02878)

# Libraries used
* Matplotlib
* Mtcnn

# Demonstration 
MTCNN did quite well. The following are some of the result we have obtained. We can see that the model is able to detect faces of 3D animation, a group of people and a single subject
### Detecting a single face
![alt text](https://github.com/Jihad-R/Face-Detection-Using-Deep-Learning-MTCNN-/blob/master/test%201%20full.jpg)
### Detecting multiple faces
![alt text](https://github.com/Jihad-R/Face-Detection-Using-Deep-Learning-MTCNN-/blob/master/test%203%20full.jpg)
### Detecting an animated face
![alt text](https://github.com/Jihad-R/Face-Detection-Using-Deep-Learning-MTCNN-/blob/master/test%202%20full.jpg)

# Future Works 
* Improve the models performance by tweaking the weights 
* Add video face detection 

