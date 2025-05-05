# 🩺 Health Prediction Management System

A Java-based console application for predicting possible health issues and recommending doctors based on user input. The project is built using **Object-Oriented Programming (OOP)** concepts to ensure clean code architecture, maintainability, and scalability.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![OOP](https://img.shields.io/badge/OOP-Principles-blue?style=for-the-badge)
![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

---

## 📋 Features

- ✅ User registration with personal health data  
- ✅ Symptom collection and health record creation  
- ✅ Disease prediction using a rule-based model  
- ✅ Doctor recommendations based on predicted disease  
- ✅ Clean architecture based on OOP principles  

---

## 🧠 OOP Concepts Used

- **Encapsulation** – Logical grouping of user, health, and disease data into classes  
- **Abstraction** – Specific services for user management, prediction, and doctor recommendation  
- **Modularity** – Clean package structure (`main`, `models`, `services`)  
- **Reusability** – Services and models designed for extension and reuse  

---

## 📁 Project Structure

project-root/ ├── main/ │ └── Main.java # Main entry point and user interaction ├── models/ │ ├── Disease.java # Represents a disease entity │ ├── Doctor.java # Represents a doctor entity │ ├── HealthRecord.java # Stores user's health-related inputs │ ├── PredictionModel.java # Contains logic for predicting diseases │ └── User.java # Represents user data ├── services/ │ ├── DoctorService.java # Handles doctor recommendation │ ├── PredictionService.java # Coordinates prediction process │ └── UserService.java # Handles user creation and management ├── README.md # Project documentation └── requirements.txt # List of dependencies

---

## 🛠️ Technologies Used

- Java (JDK 8+)
- Console Input/Output
- Object-Oriented Programming (OOP)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/health-prediction-system-java.git
cd health-prediction-system-java
```

### 2. Compile the Code

javac main/Main.java models/*.java services/*.java

### 3. Run the Application

java main.Main

### 🧪 Sample Output:
Enter your name: John
Enter your age: 22
Enter your BMI: 28.6
Enter your medical history (or 'None'): None
User Registered: John
Enter your symptoms (comma-separated): fewer

Predicted Disease: Unknown | Risk Level: Low
Recommended Doctor: Dr. Smith (General Physician)



📌 Future Enhancements:
🔍 Real-time disease prediction using machine learning
🌐 GUI integration with JavaFX or Swing
☁️ Online database integration for dynamic doctor lookup
🧾 PDF report generation for health records

📄 License:
This project is licensed under the MIT License.

🙌 Contributing:
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

🔗 Connect:
GitHub: @AdapaJohn
LinkedIn: John Adapa

Built with ❤️ using Java and solid OOP fundamentals.
