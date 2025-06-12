# Explanation of Notebooks and Code
All of our code was ran on kaggle, which offers a jupyter notebook interface! In order to gain access to the data we had to join the BYU locating flagellar motors challenge (https://www.kaggle.com/competitions/byu-locating-bacterial-flagellar-motors-2025/overview). 

To be able to run YOLO and DETR models, we took inspiration from a series of notebooks created by @andrewjdarley. Our main focus was to train different YOLO architectures, and to compare the results!
We focus on the parse-data.ipynb notebook which parses and prepares the data for YOLO-style training, and worked on individual training notebooks (YOLOv8n, YOLOv8m, YOLOv11, and RT-DETR). 
Once registered the competition, rather than downloading the data locally (a file of around 68GB), kaggle offers an option to use the competition data, as well as previous notebooks (and the notebooks' outputs), as inputs for a current notebook. For example, once we parsed the data, we can reuse it in another notebook, witohut having to "re-parse" it, in the "current" notebook".
If one would like to replicate our code, we would reccomend attempting to join the BYU kaggle competition, and then running our notebooks there. 

Our work can be found in the /scripts folder in our project repository, where each model has it's own folder, containing the notebook we used to run the code, as well as some of the outputs produced for each model, as well as the data-parsing and EDA notebooks!


