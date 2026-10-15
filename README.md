# FitTrack – Fitness Tracking Application

##  Project Description

FitTrack is a Java-based desktop application developed using Java Swing. It helps users track their daily fitness activities, manage workout plans, and monitor their fitness progress through a simple and user-friendly interface.

##  Features

* **Login Screen:** Enter your name to access the application.
* **Dashboard:** View daily steps, calories burned, and completed workouts.
* **Workout Plans:** View workout plans and mark workouts as completed.
* **Fitness Tracking:** Enter and save daily fitness data.
* **Progress Tracking:** Monitor daily steps, calories burned, and completed workouts.
* **Dark Mode:** Switch between light and dark themes.
* **Input Validation:** Prevents empty names, invalid numbers, and negative fitness values.
* **Logout:** Return to the login screen.

##  Technologies Used

* **Programming Language:** Java
* **GUI Framework:** Java Swing
* **Layout Management:** BorderLayout, GridLayout, BoxLayout, GridBagLayout
* **Collections Framework:** ArrayList
* **Event Handling:** ActionListener and Lambda Expressions
* **IDE:** Visual Studio Code / IntelliJ IDEA / Eclipse

##  Project Structure

```text
FitTrack/
│
├── FitTrack.java
└── README.md
```

##  Requirements

Before running the project, make sure you have:

* Java Development Kit (JDK) installed.
* A code editor or Java IDE.
* Java configured in your system PATH.

##  How to Run the Project

### Step 1: Download or Clone the Repository

Clone the repository using:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```
Alternatively, download the project files.

### Step 2: Open the Project Folder

Open the project folder in your preferred Java IDE or terminal.

### Step 3: Compile the Java File

Open the terminal and execute:

```bash
javac FitTrack.java
```
### Step 4: Run the Application
Execute the following command:
```bash
java FitTrack
```
The FitTrack application will open with the login screen.
##  How to Use
1. Launch the application.
2. Enter your name on the login screen.
3. Click **Get Started** to open the dashboard.
4. Navigate through Dashboard, Workout Plans, Fitness Tracking, and Progress.
5. Enter your fitness information and save it.
6. Use the **Toggle Dark Mode** button to change the theme.
7. Click **Logout** to return to the login screen.

##  Java Concepts Used

This project demonstrates the following Java concepts:

* Object-Oriented Programming (OOP)
* Classes and Objects
* Inheritance using `JFrame`
* Encapsulation through class fields and methods
* Exception Handling using `try-catch`
* Collections using `ArrayList`
* GUI development using Java Swing
* Event-driven programming
* Lambda expressions
* Conditional statements and loops

##  Limitations
* Fitness data is stored in application memory and is not permanently saved.
* The login screen only asks for a name; it does not provide password-based authentication.
* The application does not connect to a database.
* The dashboard does not automatically collect data from fitness devices.

## Future Enhancements

* Add user registration and secure login.
* Integrate a database using JDBC.
* Store fitness records permanently.
* Add charts and weekly or monthly progress reports.
* Introduce personalized workout recommendations.
* Add user profiles and fitness goals.

##  Author
**Student Project – FitTrack Fitness Tracking Application**


##  License
This project is developed for educational purposes.

