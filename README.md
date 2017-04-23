# TrafficSignClassifier

## Dependencies:
- Python 3.6
- Jupyter Notebook
- Numpy
- scikit-learn
- TensorFlow
- Matplotlib



## Updates:
- 2017.4.22 16:00  
  - With the dateset changed, the program can run with a very low accuracy. I don't know if the question caused by the preprocess I've done. It reminds to solve.
- 2017.4.22 17:35  
  - The low-accuracy problem has been solved. It was caused by the wrong parameters in the LeNet2 model(the output value should be 62 but not 43).
- 2017.4.23 20:52
  - Using augmented data to train the model, and it performed well. The test set accuracy has been up to 94.9%.
