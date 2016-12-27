# Dockerized Deepdream: Generate ConvNet Art in the Cloud

I utilized the digital ocean cloud to perform the generation of deep dreamed images. Below is the original documentation of the project whose inspiration comes from the work done by the team at VisionAI.

### My goals for this project were :
- To understand the intricacies of interactions between my local machine and a cloud instance.
- To successfully train novel images from my local machine on the neural network model that resides in the cloud.
- To connect the cloud instance to my github so I can share my results.

#### Here are some of the results I got.

###### Original Image :
![image of snow]
(https://raw.githubusercontent.com/crikeli/DeepDream_Droplet/master/input1.png)

###### Deep Dreamed Image :
![deep dreamed image of snow]
(https://raw.githubusercontent.com/crikeli/DeepDream_Droplet/master/output1.png)


###### Original Image :
![image of golden gate bridge]
(https://raw.githubusercontent.com/crikeli/DeepDream_Droplet/master/input2.png)

###### Deep Dreamed Image :
![deep dreamed image of golden gate bridge]
(https://raw.githubusercontent.com/crikeli/DeepDream_Droplet/master/output2.png)

###### Original Image :
![image of skyline]
(https://raw.githubusercontent.com/crikeli/DeepDream_Droplet/master/input4.png)

###### Deep Dreamed Image :
![deep dreamed image of skyline]
(https://raw.githubusercontent.com/crikeli/DeepDream_Droplet/master/output4.png)
### Credits

The included Dockerfile is an extended version of
https://github.com/taras-sereda/docker_ubuntu_caffe

Which is a modification from the original Caffe CPU master Dockerfile tleyden:
https://github.com/tleyden/docker/tree/master/caffe/cpu/master

This dockerfile uses the deepdream code from:
https://github.com/google/deepdream

### License

MIT License.
