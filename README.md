# Digit-Recognition-RandomForest
__________________________________

Handwritten/Digital digit recognition is the process to provide the ability to machines to recognize human handwritten digits. It is not an easy task for the machine because handwritten digits are not perfect, vary from person-to-person, and can be made with many different flavors.

Procedure :
=> Analyse the problem that is need to be found.                                                                     
=> Collect dataset using Scikit-learn Digit Dataset that has 10 classes with total number of samples as 1797. Single image of dimension 64 as 8 x 8 matrices. Our dataset is not an image but values of image. We define them as pixel values.                                                                      
=> Load dataset and summarize detials such as Data = (42000, 784), Target = [0 1 2....8 9].                          
=> Segregate Dataset into x and y using iloc function, where x = dataset.iloc[:. 1:] and y = dataset.iloc[:, o].                         
=> Use Random forest classifier with tuning parameters n_estimator, max_depth,criterion).                       
=> Train the model.
=> Evaluation and Validation.
=> Observe how our model classify our new data.
