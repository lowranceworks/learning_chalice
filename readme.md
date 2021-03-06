# Create a Cloud Hosted Python API Server - Using Python Chalice and AWS Lambda
AWS Chalice allows you to quickly create and deploy applications that use Amazon API Gateway and AWS Lambda. It provides:

- A command line tool for creating, deploying, and managing your app
- A familiar and easy to use API for declaring views in python code
- Automatic IAM policy generation

## Documentation
[Chalice Github](https://github.com/aws/chalice)
[Chalice Quickstart and Tutorial](https://chalice.readthedocs.io/en/stable/quickstart.html) \
[Chalice Homepage](https://chalice.readthedocs.io/en/stable/)\
[Create a Cloud Hosted Python API Server - Using Python Chalice and AWS Lambda
](https://www.youtube.com/watch?v=r60-90Stb2o) \
[httpie](https://github.com/httpie/httpie#windows-etc)

## Requirements
python \
python -m pip \
python -m venv \
python -m pip install chalice \
~/.aws/config (to store aws credentials and region) \
httpie (to send the get request)

## Set up for Windows

(Install Python)[https://www.python.org/]

Install pip 
```
py get-pip.py
```

Make and change directory for project 
```
mkdir project ; cd project 
```

Start up a virtual environment
```
python -m venv . 
```

```
python -m pip install --upgrade pip setuptools
```


```
python -m pip install --upgrade httpie
```
