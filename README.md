<p align="center">
  <a href="https://github.com/Grimmwolf-lab/Fashion-Recommendation" title="Fashion-Recommendation"></a>
</p>
<h1 align="center"> Fashion-Recommendation </h1>
<p align="center"> Fashion recommendation using deep learning and Streamlit </p>

<h2 align="center">🌐 Links 🌐</h2>
<p align="center">
    <a href="https://github.com/Grimmwolf-lab/Fashion-Recommendation" title="Fashion-Recommendation">📂 Repo </a>
   

## 🚀 Features
- The web app provides 5 similar clothing recommendations of the given image data.
- Feature extraction of the dataset is done using the famous ResNet50 model of tensorflow.
- For predicting the recommendations we used sklearns NearestNeighbor model.

## 🛠️ Installation Steps

1. Clone the repository.

```Bash
git clone https://github.com/Grimmwolf-lab/Fashion-Recommendation.git
```
  
2. Pull all the data from google drive.
  
```Bash
dvc pull 
```


## 👷 Built with
- Python: as Main Coding Language for executing commands
- Docker: For containerizing the project and deploy online
- Github : For Repo Storage and source code management
- Git: For version control system of code files
- DVC : for version control of the large data file

## 📂 Directory Structure
- app.py : main code for simple streamlit web app
- features.dvc: DVC tracked,  image to numpy array extracted data
- model.dvc: DVC tracked, model training and extracting features from image
- uploads.dvc: store the user uploaded image in a DVC tracked file
- image-data.dvc: image dataset got from kaggle
- Dockerfile: Dockerfile to create image of the project
- requirements.txt: All the libraries used in the project
  
  


*Dataset*
> https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset


## Challenges
  - The first challenge and the most important one is to extract or train the model to get data from image, which was solved using the most popular model RESNET. As it was tested on ImageNet dataset.
  - Now the second challenge was how will I upload the project on github and other deployable platforms, After a good google search I came across DVC (Data Version Control) tool. It helps in version controlling of large data. I used DVC with my google drive but you can use it with any other tools like AWS S3 etc.
  
  
## Things I Learned
  - What is ResNet and how it works. (Not entirely but just the gist of it)
  - DVC, it was the entirely new concept to me. One of the most useful tool for any large Data related project.
  - Docker, I have interest in MLOps so I was learning about it. It was my first time actually using it (Actually loved working with it, will use again).

## Future Aspects of the project
  - Learning to publish/deploy the project on AWS or any cloud based tools. (Hard, but will get around it)
  - Will try to optimize it for it to work fast, as NearestNeighbor takes time to calculate the distances.


## 🧑🏻 Author

**Kailash Bora**

- 🌌 [Profile](https://github.com/Grimmwolf-lab "Kailash Bora")

- 🏮 [Email](mailto:kailashbora007@gmail.com?subject=Hi%20from%20<repo-email> "Hi!")




**NOTE:** *This project is only for self learning purpose. It is not suitable for commercial use.*
<p align="center">💙 If you like this project, Give it a ⭐ and Share it with friends!</p>

