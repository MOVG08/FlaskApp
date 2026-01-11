# FlaskApp

A simple **Flask web application** built with Python.  
It can be run **locally** or **inside Docker** and includes **tests** and **CI with GitHub Actions**.

## Features

- Lightweight Flask application  
- Easy local setup with Python  
- Docker support  
- Automated tests  
- CI pipeline using GitHub Actions  

## Prerequisites

- Python 3.7 or higher  
- `pip`  
- Docker *(optional)*  

---


## CI / CD

This project uses GitHub Actions to automatically run tests on every push.

Workflow files are located in:

```bash
.github/workflows/
```
### Project structure
```bash
FlaskApp/
├── .github/workflows/   # CI configuration
├── Dockerfile           # Docker setup
├── app.py               # Flask application
├── get-pip.py           # Pip installer script
├── requirements.txt     # Python dependencies
├── test_app.py          # Tests
└── README.md            # Documentation
```
