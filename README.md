# DQ_project
Project developed for the *Data Quality* course @ Politecnico di Milano\
Acadamic year 2022 - 2023\
<br />
The goal of this project is to evaluate how different imputation techniques influence the performance of different classification algorithms on a given dataset.\
The dataset is composed of 2001 samples and 17 labels: 'x-box', 'y-box', 'width', 'high’,  'onpix', 'x-bar', 'y-bar', 'x2bar', 'y2bar', 'xybar', 'x2ybr', 'xy2br', 'x-ege', 'xegvy', 'y-ege', 'yegvx' and 'letter' , that is the target  to predict. The values of the different labels are almost all around 0 and 15, while the target are 26 different letters: 'L', 'F', 'Z', 'T', 'U', 'H', 'Y', 'B', 'R', 'O', 'X', 'S', 'M', 'P', 'K', 'Q', 'V', 'C', ‘W’,  'N', 'G', 'J', 'E', 'A', 'I', 'D' .\
The dataset is then manipulated in order to obtain various datasets with different amounts of missing (NaN) values. These values are then injected with two different imputation techniques since ML algorithms cannot be executed on incomplete datasets . 
The obtained results are then compared in order to evaluate how different imputation techniques influence the ML algorithms' performances.
