# 🩺 Health Prediction Management System

A robust Java console application for predicting potential health issues and recommending appropriate doctors based on user input. This project leverages strong **Object-Oriented Programming (OOP)** principles to ensure clean architecture, maintainability, and scalability.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![OOP](https://img.shields.io/badge/OOP-Principles-blue?style=for-the-badge)

---

## Overview

This system provides an interactive, text-based interface for users to register, input symptoms, receive disease predictions, and obtain relevant doctor recommendations. The modular and extensible design enables easy feature expansion and integration with advanced technologies in the future.

---

## Features

- **User Registration**: Collects personal and health-related data.
- **Symptom Collection**: Records user symptoms and generates health records.
- **Disease Prediction**: Uses a rule-based model for preliminary health assessment.
- **Doctor Recommendation**: Suggests suitable doctors based on predicted conditions.
- **OOP Best Practices**: Ensures code is modular, reusable, and easy to maintain.

---

## Object-Oriented Design Highlights

- **Encapsulation**: User, health, and disease data are logically grouped into dedicated classes.
- **Abstraction**: Separate services manage user data, predictions, and recommendations.
- **Modularity**: Organized into clear package structures (`main`, `models`, `services`).
- **Reusability**: Components are designed for easy extension and reuse in future enhancements.

---

## Project Structure

```
project-root/
├── main/
│   └── Main.java                # Entry point and user interaction logic
├── models/
│   ├── Disease.java             # Disease entity
│   ├── Doctor.java              # Doctor entity
│   ├── HealthRecord.java        # Stores user health inputs
│   ├── PredictionModel.java     # Disease prediction logic
│   └── User.java                # User profile data
├── services/
│   ├── DoctorService.java       # Doctor recommendation logic
│   ├── PredictionService.java   # Coordinates prediction workflow
│   └── UserService.java         # User management
├── README.md                    # Documentation
└── requirements.txt             # Dependencies (for reference)
```

---

## Technologies Used

- Java (JDK 8+)
- Console-based Input/Output
- Core OOP Principles

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/health-prediction-system-java.git
cd health-prediction-system-java
```

### 2. Compile the Code

```bash
javac main/Main.java models/*.java services/*.java
```

### 3. Run the Application

```bash
java main.Main
```

---

## Sample Workflow

```
Enter your name: John
Enter your age: 22
Enter your BMI: 28.6
Enter your medical history (or 'None'): None

User Registered: John

Enter your symptoms (comma-separated): fever

Predicted Disease: Unknown | Risk Level: Low
Recommended Doctor: Dr. Smith (General Physician)
```

---

## Future Enhancements

- Integration of real-time disease prediction using machine learning
- GUI implementation using JavaFX or Swing
- Cloud database integration for dynamic doctor lookup
- PDF report generation for health records

---

## Contact

- GitHub: [@AdapaJohn](https://github.com/AdapaJohn)
- LinkedIn: [John Adapa](https://www.linkedin.com/in/john-adapa)

---

_Built with passion for healthcare innovation and strong OOP fundamentals._
