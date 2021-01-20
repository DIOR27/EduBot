# Simple Web-based Tensorflow Chatbot

### Installing

* Requires Python 3.6.8

### First steps:

* Create a Python virtual enviroment with the following command:

```
python -m venv venv
```

* Go inside your venv folder and clone the GitHub repository. Then activate it running the following command:

```
Scripts/activate.
```

* Install pip libraries:

```
pip install -r requirements.txt
```

Go to the Bot folder, put the questions and answers that you want inside "contents.json" file. Then, train your model with the following command in the current Bot folder:

```
python train.py
```

## Running on a Web Interface

* Follow the steps to excecute your chatbot on the web.

* Replace 96 line according to the path of the "static" folder of your project under *STATICFILES_DIRS * variable. Then execute following command inside the root directory.

```
python manage.py runserver
```

* Open your browser and put the following web address: http://localhost:8000/

* Enjoy! (Stop the server with Ctrl + C in the command promt and train again the model for apply any changes on the contents.json file).

## Technologies:

* [Tensorflow] - Neural Network
* [Django] - Web Application

## Authors

* **Diego Orellana, Sebastián Medina** - *Universidad del Azuay, Ingeniería de Sistemas y Telemática*


