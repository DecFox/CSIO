## Localization of RoI using Image Fusion

In this project, we try to localize a desired region (RoI) by fusing given thermal and visual images, extracting the best features from both and employing segmentation to localize the desired region from the given dataset

We make use of color-based segmentation techniques to get a broader localization of the RoI, following which region and edge based techniques are used to get a more precise result.

The main code can be found in 
```
ROI.ipynb
```
 and the dataset can be found in 
 ```
 /Assets/fusion
 ```
 divided into thermal and visual directories and named with corresponding indexes.
 
 Code dependencies can be downloaded using pip:
 ```
 pip install -r requirements.txt
 ```
 following which a jupyter server can be initialised for execution.
