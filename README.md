Final Project Submission </br>
Zachary Seitz </br>
CS505 – Introduction to Data Mining | Fall 2022 | Dr. Yuan </br>
Southeast Missouri State University </br>

This project seeks to create a convolutional neural network capable of identifying diseases in chest x-rays. The project experiment is broken up into three notebooks, `seitz_data_processing.ipynb`, `seitz_model_testing.ipynb`, and `seitz_final_submission.ipynb`.

1.	`seitz_data_processing.ipynb`: contains all the processing required to create the experimental subset from the original dataset.*

2.	`seitz_model_testing.ipynb`: contains the training data and results for all the hyperparameter experiments that were carried out to find the most favorable values to accomplish the task.

3.	`seitz_final_submission.ipynb`: contains the training data and results for only the final model with the most favored hyperparameter values.

All four of the models and their histories are available in the models and model_history directories, respectively. The datasets directory contains CSVs for all the used and created datasets.

Only the 1,500 images used for training are included in the images.zip file, but the full dataset is available here: https://nihcc.app.box.com/v/ChestXray-NIHCC


*Special thanks to the NIH and following team for the data. </br>
Wang X, Peng Y, Lu L, Lu Z, Bagheri M, Summers RM. ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases. IEEE CVPR 2017, http://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf
