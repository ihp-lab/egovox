# EgoVox
This is a dataset created for data augmentation for egocentric social role understanding, in the following paper.

* Minh Tran, Yelin Kim, Che-Chun Su, Min Sun, Cheng-Hao Kuo, Mohammad Soleymani. Exo2Ego: A Framework for Adaptation of Exocentric Video Masked Autoencoder for Egocentric Social Role Understanding, ECCV 2024

The dataset was created by [IHP-lab](https://ihp-lab.org). 

You can download the data [here](https://drive.google.com/file/d/1PAv41zt1LxgAoaM_5v51qfOWyO7FeFYd/view?usp=sharing).


Our data synthesis code is adapted from [TriPlaneNet](https://github.com/anantarb/triplanenet/tree/main). We organize our EgoVox zipped data as follow:
```
├── EgoVox
│   ├── EgoVox_original_frames
│   │   ├── id01187_Jcfm89ldSr8_00045
│   │   │   ├── 0.jpg
│   │   │   ├── ...
│   │   ├── ...
│   ├── EgoVox_synthesized
│   │   ├── id01187_Jcfm89ldSr8_00045
│   │   │   ├── synthesized_0
│   │   │   │   ├── 0.jpg
│   │   │   │   ├── ...
│   │   │   ├── ...
│   │   ├── ...
│   ├── EgoVox_parse
│   │   ├── id01187_Jcfm89ldSr8_00045
│   │   │   ├── 0.npy
│   │   │   ├── ...
│   │   ├── ...
│   ├── EgoVox_train.pkl
│   ├── EgoVox_train.pkl
```

The data is released under USC Research License.