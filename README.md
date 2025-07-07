# Cross-modal multitask learning for automated quantitative characterization of infrastructure airhole defects

<p align="center">
  <img src="images/network.png" alt="Sample Image" width="600"/>
</p>

<p align="center">
  The cross-modal multitask learning framework.
</p>


This framework addresses the quantitative characterization of apparent quality defects in infrastructure by proposing a novel cross-modal multitask learning network. It effectively integrates the strengths of image-based defect detection and point cloud-based measurement. Defect pixels identified in images are precisely mapped to their corresponding 3D coordinates in the point cloud through dense feature matching. Leveraging prior knowledge of defect properties, a tailored measurement strategy is developed to accurately quantify the area and volume of defects. Extensive experiments demonstrate the framework’s effectiveness in detection, matching, and measurement tasks, providing strong technical support for the quantitative assessment of infrastructure defects.

**Updates**
- Jul 7, 2025: Release image datasets
- Jul 7, 2025: Initial commit


## Requirements
* Torch 1.13.1+cu117
* Python 3.9
```
conda create -n cmml python=3.9
conda activate cmml

pip install -r requirements.txt
```


## Dataset
### Download datasets
* Images[Google Drive link](https://drive.google.com/drive/folders/1CGEEdfYlp6kuNGK7z8iFe5hFoC2pSAdG?usp=sharing)
* Point clouds


### Dataset structure

The dataset includes a main folder:

- `data/`
  
  This folder contains 3 subfolders:
  
  - `images/`: Contains images of airhole defects.
  - `labels/`: Contains segmentation labels of airhole defects.
  - `depths/`: Contains depth maps of airhole defects.


## Training and Testing

TBU


## License

It is provided by the Intelligent Construction Research Team, School of Civil Engineering, Chongqing University.  
You are free to share and adapt the data, as long as appropriate credit is given.
Please cite this repository if you use the dataset in your work.


## Contact

For questions or collaboration: [ysy_wang@stu.cqu.edu.cn]
