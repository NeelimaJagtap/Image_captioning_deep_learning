Description

This project is about captioning an image, this is one of the most complicated tasks for a computer model to perform accurately. It requires a lot of supervision such as object annotation. In this project we will be presenting a different technique that uses deep learning models to caption any given image. This method only requires images and predefined generated captions.
In our work we have performed the caparison using 4 deep learning models namely Bi-LSTM model, Transformer model, Local Attention model and Global Attention model. These models are trained and tested by splitting the data obtained from the Flickr 8K dataset.
Requirements
Python 3
PyTorch 1.3+
TensorFlow 2.7
Flickr 8K dataset. {“Flickr8K_Dataset.Zip(1GB)” & “Flickr8K_text. Zip(2.2MB)”}
Download here (https://www.kaggle.com/code/mehmetlaudatekman/image-captioning-flickr8k/data)
Google Colab
Flask API (localhost:5000/predict)


How To Use

We are working using the Flickr 8K Dataset for Image Captioning, please make sure that it is available in your environment before running the code.
Make sure that the machine in which you are running the code has GPU enabled as several libraries that are used will require them.
Suggest you using Google colab Pro as the GPU limit will be exceeded while running the model. The GPU used is NVIDIA Tesla K80 GPU.
For the Epoch and the Batch Sizes initially start with the small number and increase the values based on the response time.
The code files of all the 4 models (Bi-LSTM model, Transformer model, Local Attention model and Global Attention model) are provided in the source code file.
To implement the required model please change the decoder type in the code as Rnn_Local_Decoder for local attention model and Rnn_Global_Decoder for global attention model.
To run the UI application first run the code that is present in the “flask.py” file in local environment and use the link provided in requirements (Flask API).

