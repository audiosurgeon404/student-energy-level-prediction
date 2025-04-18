
# Student Energy Prediction App

Hey! Here I want to share my personal project for my university it is an interactive machine learning web application that predicts student energy levels based on academic and lifestyle factors. I collected all the data on my own for 2 weeks by conducting a large online questionnaire among students. 

## Overview

This project was intended for students to estimate their daily energy based on inputs like sleep, academic workload, and stimulant usage. It combines data science and full-stack development to deliver a dynamic, real-time prediction tool.

- Model Accuracy: 85% (Linear Regression)
- Frontend: HTML, CSS (Custom UI)
- Backend: Flask, scikit-learn, pandas
- Deployment: AWS EC2, Nginx, Git Bash, WinSCP

## Features

- Predicts student energy level (1–10 scale) based on:
  - Year of study
  - Faculty and stimulant use
  - Hours of sleep, lectures, and tests
- Clean, responsive user interface
- Error-handling and form validation
- Live deployment on AWS with 99.9% uptime

## How It Works

1. User submits lifestyle and academic details through a web form.
2. Data is preprocessed to match trained feature schema.
3. Serialized model (pickle) predicts energy level.
4. Results and prediction history are displayed in real-time.

## Installation

```bash
git clone https://github.com/audiosurgeon404/student-energy-prediction-app.git
cd student-energy-prediction-app
pip install -r requirements.txt
python app.py
