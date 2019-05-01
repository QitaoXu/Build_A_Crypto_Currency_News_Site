# Build_A_Crypto_Currency_News_Site

This repo is for learning course instructed by John Elder on udemy. 
Here is course webpage: [Build a Crypto Currency News Site With Python and Django](https://www.udemy.com/build-a-crypto-currency-news-site-with-python-and-django/learn/v4/overview)
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

if you are using macbook like me, first, please make sure have installed Python3.
If you have not, one way to install it is to use homebrew.
```
brew install python
```
If you are not comfortable with homebrew, you can also go to Python website to download it and install it by yourself.

Next, please make sure you also have installed pip3. Normally, it is with your installed Python3.
```
pip3 -V
```

Okay, please check that you have installed virtualenv,
```
pip3 freeze
```

If not, please install virtualenv,
```
pip3 install virtualenv 
```

Okay, you are good to start this app.

### Start News App

First, in the directory of , Build_A_Crypto_Currency_News_Site

```
source ./bin/activate
```
This command can help you start an virtual environment for this app.

Next, install Django in virtual environment

```
pip3 install django
```

It may take serval minutes.

Next, walk into directory Build_An_Todo_App/ and in terminal just type
```
python3 manage.py runserver
```
Okay, you are all set, just go to http://localhost:8000 and have fun!

If you want to stop server, just Ctrl + c in the terminal that you start it.
