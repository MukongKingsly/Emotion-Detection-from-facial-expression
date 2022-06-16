The project is **Real-time Emotion Prediction With Deep Learning** using facial expression

The Dataset (FER2013) was taken from kaggle

The original FER data set was prepared by Pierre Luc Carrier and Aaron Courville by web crawling face images with emotion related keywords



**Dependencies**
- Opencv
    - pip install opencv-python
- pip install setuptools
- python3 -m pip install --upgrade pip setuptools wheel
- pip install OpenNMT-py
- pip install opencv-python
- pip install keras
- pip3 install --user --upgrade tensorflow  # install in $HOME, or
- pip install --upgrade tensorflow # virtual environment
- pip install camera



The project was done in 3 steps;
- Defined convolution layers
- Train model by feeding batches of data to it, then save it as "model.json"
- Use trained model to interprete emotions from facial expressions

To view the actual code in action you will have to install Jupyter notebook