# IDS 706 Mini Project 4 [![CI](https://github.com/nogibjj/Jaxon-Yue-IDS-706-Mini-Project-3/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/Jaxon-Yue-IDS-706-Mini-Project-3/actions/workflows/cicd.yml)
### Overview
* This repository includes the components for Mini-Project 4 - GitHub Actions Matrix Build for Multiple Python Versions
Requirements.

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

#### GitHub Actions Result
Using GitHub Actions, I have passed make format, make lint, and make test as shown below.
<img width="1154" alt="Screenshot 2023-09-12 at 5 59 55 PM" src="https://github.com/nogibjj/Jaxon-Yue-IDS-706-Mini-Project-3/assets/70416390/71c80522-d698-4d17-8e95-acdd7be03671">

### References
Link to Mini project 2, where this project was adapted from
https://github.com/nogibjj/Jaxon-Yue-IDS-706-Mini-Project-2
