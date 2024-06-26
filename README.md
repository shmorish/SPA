# SPA

## Description

This is a Single Page Application (SPA) that uses the [Django](https://www.djangoproject.com/) web framework and [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) to create a simple web application that allows users to create, read, update, and delete (CRUD) notes.

## Installation

### Clone the Repository
```bash
git clone https://github.com/shmorish/SPA.git
```

We recommend using [Conda](https://anaconda.com/) to create a virtual environment for this project. You can create a new virtual environment using the following command:
```bash
conda create -n spa python=3.11
```

### Activate the Virtual Environment
Activate the virtual environment:
```bash
conda activate spa
conda install -c conda-forge django
cd mysite
python3 manage.py runserver
```
<!--conda activate, install ->  django-admin startproject mysite -->
