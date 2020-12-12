# INF8953CE - Team Foo - Kaggle Competition

This work has been done for a Kaggle competition for the course INF8953CE, during fall of 2020 at
Polytechnic Montreal. The goal was to design a classification algorithm that can
automatically identify hand-drawn images. The dataset used is a variant of the google quick draw dataset with 31 classes.

## Code Requirements
In order to execute the code, the following libraries are needed:
Tensorflow, Keras, Numpy, Matplotlib, Pandas, Scikit-learn, OpenCV (cv2).

If they are all already installed, please discard this section.

If you have some of them missing, you can create a new environment in conda and then install the packages by following the instructions below:

 ```
 conda create -n yourenvironment python=3.8
 conda activate yourenvironment
 ```
 After that you can install all the needed packages by navigating to the source folder, opening the terminal, and running pip on the requirements.txt file:

 ```pip install -r requirements.txt```

 Then proceed to select this new environment as your jupyter notebook kernel.

## Dataset
The dataset used is a variant of the google quick draw dataset with 31 classes.
The dataset is available [here](https://www.kaggle.com/c/f2020-INF8953CE/data).

#### Labels
1) Apple :apple:
2) Empty 	
3) Moustache 👨
4) Mouth :lips:
5) Mug :coffee:
6) Nail 💅
7) Nose :nose:
8) Octagon :stop_sign:
9) Paintbrush :paintbrush:
10) Panda :panda_face:
11) Parrot :parrot:
12) Peanut :peanuts:
13) Pear :pear:
14) Pencil :pen:
15) Penguin :penguin:
17) Pillow 
18) Pineapple :pineapple:
19) Pool :swimmer:
20) Rabbit :rabbit:
21) Rhinoceros :rhinoceros:
22) Rifle :gun:
23) Rollerskates
24) Sailboat :sailboat:
25) Scorpion :scorpion:
26) Screwdriver 
27) Shovel :pick:
28) Sink :bath:
29) Skateboard :skateboard:
30) Skull :skull:
31) Spoon :spoon:
29) Squiggle 

## Classifier Implementations:

### 1) Convolutional Neural Network

### 2) k-Nearest Neighbors

### 3) Decision Tree

### 4) Random Forest Regressor

Please refer to the associated report for more information about the details of each implementation. 
 
### Procedure

1) Make sure you have installed all the librairies mentionned in the code requirements.
2) Get the dataset as mentioned above and place the `.npy` and `.csv` files in the same folder as the notebook source code.
3) Run all the notebook cells sequentially.
