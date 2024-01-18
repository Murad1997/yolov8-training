# A Step-by-Step Guide to Train Yolov8 on the OpenImageV7 Dataset for the Segmentation Task
* This notebook guides you to download OpenImageV7 dataset available [here](https://storage.googleapis.com/openimages/web/visualizer/index.html?type=segmentation&set=train&c=%2Fm%2F0cnyhnx&r=false).
* We need to install some libraries in order to start, the first is `fiftyone` and the second one is `ultralytics`.
  - `fiftyone` allows to automatically download the dataset for the specified class and specified task (e.g., `Segmentation` or `Detection`, etc.). We can also specify the `max_samples`, which we want to download just for experimentation purposes.
  -  `ultralytics` is the application programming interface (API) provided by the created of the creator of the Yolov8. [Here](https://docs.ultralytics.com/) is the link to the GitHub repo.
* In this notebook, we select `Barrel` class from the OpenImageV7 and perform the `Segmentation`.


## Notebook
[Run my Colab Notebook here](https://colab.research.google.com/drive/1qJIowO0O3EqLnBCXbGlpBdPiM9_Z8b-0#scrollTo=idABBQhYyjYQ)
