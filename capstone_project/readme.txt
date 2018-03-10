Description:
This is Udacity capstone project of MLND course. It is about remote senseing image classification. The techniques used here is to test different CNN archetictures with and without fine tuning.

Files descriptions:
1) data_analysis_vs_transfer_learning.ipynb: it visualizes data and plots classes distributions. Also, it benchmarks different CNN features for classification. (No fine tuning)
2) inception_v3_fine_tuning.ipynb, resNet50_fine_tuning.ipynb, and xception_fine_tuning.ipynb files: fine tuned version.


Before getting started:
To run these notebooks:
1) download the data set NWPU-RESISC45.rar from http://www.escience.cn/people/JunweiHan/NWPU-RESISC45.html
2) extract all folders of NWPU-RESISC45.rar file to NWPU-RESISC45 folder in the project path. So, NWPU-RESISC45 folder will have classes folders and each class folder has images.
3) explore the ipynb file using jupyter.

Main libraries used:
1) keras 2.0.8
2) sklearn 0.19.0
3) numpy 1.13.3
4) pandas 0.20.3
5) matplotlib 2.1.0

---------------------


Sources:
Functions used for visualization:
visualize.py file

show_images(): it plots multiple images
src: https://gist.github.com/soply/f3eec2e79c165e39c9d540e916142ae1

plot_confusion_matrix() to plot the confusion matrix
src: #ref: http://scikit-learn.org/stable/auto_examples/model_selection/plot_confusion_matrix.html

