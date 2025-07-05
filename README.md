# Generative AI - GDG Winter Project

This repository holds all the notes and my notebooks for the winter project __Generative AI__ offered by __Google Developer's Group IIT Kanpur__.

### Recruitment tasks:
- [Recy_Task_1](https://github.com/om4099/GDG-Project-Winter-2024/blob/main/Recy_Task_1.ipynb) was the first recruitment task.  
  It required mentees to scrape poem details like `Titlee`, `Poem URL`, `Poet`, `Poet URL` and `Publishing Year` from [Poets.org](https://poets.org/poems).  
  Here I have used very basic library of `BeautifulSoup` as it was my introduction to Web Scraping.
- [Recy_Task_2](https://github.com/om4099/GDG-Project-Winter-2024/blob/main/Recy_Task_2.ipynb) was the first recruitment task.  
  It required mentees to build a `CNN` model using `Tensorflow` which can classify images of 15 different animals and make Confusion Matrix and report F1-accuracy of the built model. It was to be trained on [animal_data.zip](https://github.com/om4099/GDG-Project-Winter-2024/blob/main/animal_data.zip)  
  Firstly I rsized the images to make them of same sizes and stored them in arrays. Then I used a `Sequential` architecture to build the `CNN` model.
  Model used `Adam` optimizer and `categorical_crossentropy` as a loss funtion. Trained the model on 10 `epochs`.
  Model faired desscent for a simple architecturwe with `Train Accuracy = 0.9185` , `Test Accuracy = 0.7609254717826843` and `F1 Score 0.7560`.

The project was divided into 2 tracks namely, track 1 and track 2.

### Track 1:
- First week was about Dataset Preparation, it taught us web scraping, data pre-processing, tokenization and Exploratory Data Analysis(EDA).  
  [Track_1_Assignment_1_Part_1](https://github.com/om4099/GDG-Project-Winter-2024/blob/main/Track_1_Assignment_1_Part_1.ipynb) was based on week 1.
  - It required mentees to create a Creative Dataset by scraping, tokenize it and perform EDA on it.
- Second week was an introduction to Transformers , Attention , basic architecture of Transformer models and the underlying logic. It also covered the archituecture of RNN, LSTM and GRUs.  
- Third week was an extension of Second week where mentees were taught about self attention, positional encoding, encoder and decoder in detail.  
  [Track_1_Assignment_1_Part_2](https://github.com/om4099/GDG-Project-Winter-2024/blob/main/Track_1_Assignment_1_Part_2.ipynb) was based on week 2 and some content of week 3.
  - It required mentees to construct a coocurrence matrix and perform Principal Component Analysis (PCA) ont the dataset for dimentionality reduction to visualize the word embeddings.
- Fourth week taught mentees to fine tune a pre trained model from Hugging Face and deployment of model.
  [Track_1_Assignment_2](https://github.com/om4099/GDG-Project-Winter-2024/blob/main/Track_1_Assignment_2.ipynb) was based on week 4.
  - This was the final Assignment and goal of the project. It required mentees to fine tune a GPT-2 model on the previously prepared Creative Dataset such that the model is able to generate a creative piece of words based on the user's input.

### Track 2:  
- Though the track 2 was supposed to cover Image genration to a descent level. But due to time constrqaints, only Vanilla GAN, FCGAN, DCGAN and Generator and Discriminator were covered.  
  [Track_2_Assignment_1](https://github.com/om4099/GDG-Project-Winter-2024/blob/main/Track_2_Assignment_1.ipynb) was based on the basics of GANs.
   - It required mentees to build a GAN model trained on the [MNIST dataset](https://storage.googleapis.com/tensorflow/tf-keras-datasets/mnist.npz) using both the FCGAN and DCGAN architecture.
