# INF8953CE - FOO Team - Kaggle Competition

This work has been done for a Kaggle competition for the course INF8953CE, during fall of 2020 at
Polytechnic Montreal. The goal was to design a classification algorithm that can
automatically identify hand-drawn images. The dataset used is a variant of the google quick draw dataset with 31 classes.

### Code Requirements
You can create a new Conda environment to avoid having dependencies issues:
```
conda create -n yourenvironment
source activate yourenvironment
```
After that you can install all the needed packages by running pip on the requirements.txt file:

```pip install requirements.txt```

### Dataset
The dataset used is a variant of the google quick draw dataset with 31 classes.
The dataset is available [here](https://www.kaggle.com/c/f2020-INF8953CE/data).

##### Labels
1) Apple :apple:
2) Empty 	
3) Moustache 🕯️
4) Mouth 
5) Mug
6) Nail :fish:
6) Nose :guitar:
7) Octagon :icecream:
8) Paintbrush
9) Panda :panda:
10) Parrot :parrot:
11) Peanut :peanut:
12) Pear :pear:
13) Pencil :pen:
14) Penguin :Penguin:
15) Pillow :pillow:
16) Pineapple :pineapple:
17) Pool :pool:
18) Rabbit :rabbit:
19) Rhinoceros :rhinoceros:
20) Rifle :rifle:
21) Rollerskates :rollerskate:
22) Sailbot :sailbot:
22) Scorpion :scorpion:
23) Screwdriver :screwdriver:
24) Shovel : shovel:
25) Sink :sink:
26) Skateboard :skateboard:
27) Skull :skull:
28) Spoon :spoon:
29) Squiggle :squiggle:

### Python  Implementation

1) Network Used- Convolutional Neural Network

If you face any problem, kindly raise an issue

### Procedure

1) Get the dataset as mentioned above and place the `.npy` files in `/data` folder.
2) First, run `LoadData.py` which will load the data from the `/data` folder and store the features and labels in  pickel files.
3) Now you need to have the data, run `QD_trainer.py` which will load data from pickle and augment it. After this, the training process begins.
2) Now you need to have the data, run `QuickDrawApp.py` which will use use the webcam to get what you have drawn.
3) For altering the model, check `QD_trainer.py`.
4) For tensorboard visualization, go to the specific log directory and run this command ` tensorboard --logdir=.` You can go to `localhost:6006` for visualizing your loss function and accuracy.

### Mergerd to Google's git repo
See the pull request [here](https://github.com/googlecreativelab/quickdraw-dataset/pull/25)

<img src="https://github.com/akshaybahadur21/QuickDraw/blob/master/qd.gif">

### References:
 
 - [Google's Quick, Draw](https://quickdraw.withgoogle.com/) 
 - [The Quick, Draw! Dataset](https://github.com/googlecreativelab/quickdraw-dataset)
 - [Quick Draw: the world’s largest doodle dataset](https://towardsdatascience.com/quick-draw-the-worlds-largest-doodle-dataset-823c22ffce6b)




