# Ninjacart CV Classification

Problem Statement

Ninjacart is India's largest fresh produce supply chain company. They are pioneers in solving one of the toughest supply chain problems of the world by leveraging innovative technology. They source fresh produce from farmers and deliver them to businesses within 12 hours. An integral component of their automation process is the development of robust classifiers which can distinguish between images of different types of vegetables, while also correctly labeling images that do not contain any one type of vegetable as noise.

As a starting point, ninjacart has provided us with a dataset scraped from the web which contains train and test folders, each having 4 sub-folders with images of onions, potatoes, tomatoes and some market scenes. We have been tasked with preparing a multiclass classifier for identifying these vegetables. The dataset provided has all the required images to achieve the task.

Dataset Link

https://drive.google.com/file/d/1clZX-lV_MLxKHSyeyTheX5OCQtNCUcqT/view?usp=sharing

Context

This dataset contains images of the following food items: noise-Indian market and images of vegetables- onion, potato and tomato.

Data Collection

The images in this dataset were scraped from Google.

Content

This dataset contains a folder train, which has a total of 3135 images, split into four folders as follows:

Tomato : 789

Potato : 898

Onion : 849

Indian market : 599

This dataset contains another folder test which has a total of 351 images, split into four folders

Tomato : 106

potato : 83

onion : 81

Indian market : 81

Inspiration

The objective is to develop a program that can recognize the vegetable item(s) in a photo and identify them for the user.

Concepts Tested:

Dataset Preparation & Visualization

CNN models

Implementing Callbacks

Deal with Overfitting

Transfer Learning
