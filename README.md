# Face Disguise Dataset: <br />
Amarjot Singh , Devendra Patil,G Meghana Reddy and S.N.Omkar

If you use this dataset please cite:

Amarjot Singh, Devendra Patil, G Meghana Reddy and S.N Omkar <br />
"Disguised Face Identification (DFI) with Facial KeyPoints using Spatial Fusion Convolutional Network"
 IEEE International Conference on Computer Vision Workshops (ICCVW) 2017
 

The dataset contains 4000 images(2000 images each corresponding to simple and complex backgrounds dataset) recorded with male and female subjects aged from 18 years to 30 years. The dataset was collected in 8 different backgrounds,25 subjects and 10 different disguises. 
![fig-2](https://user-images.githubusercontent.com/16295218/31212989-87f47c26-a9c1-11e7-8e8f-104c8dcdca8d.jpg)

The disguises in the dataset are namely: 

1.Sun-glasses <br />
2.Cap <br />
3.Scarf <br />
4.Beard <br />
5.Glasses and cap <br />
6.Glasses and scarf <br />
7.Glasses and beard <br />
8.Cap and scarf <br />
9.Cap and beard <br />
10.Cap, glasses, and scarf <br />

The file joints.mat contains 14 joint locations for each image. joints.mat is a 14x2x2000 matrix file.For each image in the dataset there are 14(X,Y) pixel coordinates cooresponding to the 14 joint locations.joints.mat gives the ground truth location of each joint for both Complex and Simple Background images.For example, a 14x2x1 cell corresponds to the joint locations of the 1st image in complex and simple background dataset. <br />
![fig-1n](https://user-images.githubusercontent.com/16295218/31212987-81a48e88-a9c1-11e7-8595-a9ddd6ae5e64.jpg)

The ordering of the joints is as follows:

P1:Right Eyebrow outer point <br />
P2:Right Eyebrow inner point <br />
P3:Left Eyebrow inner point <br />
P4:Left Eyebrow outer point <br />
P5:Right Eye outer point <br />
P6:Right Eye middle point <br />
P7:Right Eye inner point <br />
P8:Right Eye inner point <br />
P9:Right Eye middle point <br />
P10:Right Eye outer point <br />
P11:Nose tip <br />
P12:Lip right end <br />
P13:Lip middle <br />
P14:Lip left end <br />



