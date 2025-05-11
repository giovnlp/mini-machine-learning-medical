# 🤖 Predicting Hospital No-Shows with Neural Networks

This project uses a neural network to predict whether a patient will show up to a medical appointment. It is based on a real dataset from a Brazilian public hospital.

## 🩺 Problem Statement

Hospitals face a frequent issue with patients not attending scheduled appointments, causing inefficiencies and wasted resources. The goal of this project is to predict no-shows using patient data such as age, gender, medical conditions, and appointment scheduling information.

## 🧠 Technologies Used

- Python  
- pandas & numpy (data handling)  
- scikit-learn (ML model & data splitting)  
- matplotlib (visualization)

## 📊 Dataset

The dataset comes from a public hospital in Brazil and includes features like:

- `ScheduledDay` and `AppointmentDay`
- `Age`, `Gender`, and medical conditions (e.g., hypertension, diabetes)
- Whether the patient received an SMS reminder
- Neighborhood (transformed into dummy variables)

The target variable is `No-show`, which indicates if the patient missed the appointment.

## 🧹 Data Preprocessing

Key steps include:

- Converting categorical data (e.g., gender, no-show) to numeric
- Creating a `WaitingTime` feature from the difference between scheduled and appointment dates
- Removing unnecessary ID columns
- One-hot encoding the `Neighbourhood` column

## 🤖 Model

A simple **Multi-Layer Perceptron (MLP)** classifier from `scikit-learn` is used.








--> This mini project was made based on an online artifical inteligence medical course.

