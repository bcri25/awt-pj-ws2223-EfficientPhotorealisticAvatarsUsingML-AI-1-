Artificial Intelligence completely revolutionized our lives and allowed immense technological progress in various fields. We are approaching the next level of internet in terms of speed and interaction where Metaverse demands high fidelity and lifelike online experience. Therefore for authentic human interaction in Metaverse user avatar fidelity is paramount. Avatars do not only need to represent a person with high visual accuracy but also require expressing similar gestures, facial expressions and head poses. The purpose of this project is to research, implement and if possible, further improve existing Machine Learning methods that allow us create an avatar from a single video input as well as detect and transfer facial expressions from the person to the avatar.

Tasks:

    Research the existing state of photorealistic avatar creation from videos or images
        Familiarizing with state-of-the art papers and understanding if they are solving the problem and how
        Researching existing code bases and understanding how they can be used for the solution
    Develop a prototype that constructs 3D avatars of a person and applies gestures to it

        Implementing a prototype to create an avatar from a single video input as well as detect and transfer facial expressions from the person to the avatar

### Installation

* Clone this repository. (https://github.com/BelindaMyteberi/awt-pj-ws2223-EfficientPhotorealisticAvatarsUsingML-AI-1-.git)

* Switch to correct branch 
```
    git checkout video-input-first-attempt
```
* Initialise and update submodules

```
    git submodule init (necessary)
    git submodule update --init
```

* Open subm
```
    cd nonrigid_nerf
```
* Setup the conda environment `nrnerf` (or install the requirements using `pip`):
```
conda env create -f environment.yml
```

* Install COLMAP. (https://colmap.github.io/install.html) for video input data preprocessing (spatial points + view direction)

* An installation of FFMPEG enables *automatic* video generation from images and frame extraction from video input.
```
conda install -c conda-forge ffmpeg
```



