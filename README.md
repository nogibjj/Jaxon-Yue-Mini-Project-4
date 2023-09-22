# IDS 706 Mini Project 4 [![PythonCiCd](https://github.com/nogibjj/Jaxon-Yue-Mini-Project-4/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/Jaxon-Yue-Mini-Project-4/actions/workflows/cicd.yml)

### Overview
* This repository includes the components for Mini-Project 4 - GitHub Actions Matrix Build for Multiple Python Versions

### Goal
* It aims to set up a GitHub Actions workflow and test across 3 different Python versions
* By configuring GitHub Actions Matrix, the project will be tested using Python 3.7, 3.8 and 3.9

### Key elements in the repository are:
* Makefile
* requirements.txt
* Dockerfile
* devcontainer
* main.py (with a sanity check function)
* test_main.py
* GitHub Actions (with newly added matrix to test on multiple versions of Python)

### Results
#### Matrix Testing Result
Using Matrix, this project is tested using Python 3.7, 3.8 and 3.9
<img width="915" alt="Screenshot 2023-09-21 at 9 22 59 PM" src="https://github.com/nogibjj/Jaxon-Yue-Mini-Project-4/assets/70416390/b92db22f-859a-4d81-9bef-03f98502b5c9">

#### GitHub Actions Result
Using GitHub Actions, I have passed make format, make lint, and make test as shown below.
<img width="1006" alt="Screenshot 2023-09-21 at 9 24 36 PM" src="https://github.com/nogibjj/Jaxon-Yue-Mini-Project-4/assets/70416390/fcae35b2-abfa-4916-b4c3-abb05bff6aaf">
