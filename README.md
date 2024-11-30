# 🚀 **Calculator Project** 

A robust and efficient **Java-based Calculator**, seamlessly integrated with **Jenkins CI/CD Pipelines** for continuous integration, testing, and deployment. This project is a great example of using automation to ensure code quality and reliability.

---

## 🌟 **Key Features**

✨ Perform basic arithmetic operations: **Addition, Subtraction, Multiplication, Division**  
✨ Automated **Unit Testing** with JUnit for reliability  
✨ Integrated **Static Code Analysis** for quality assurance  
✨ Comprehensive **Code Coverage** metrics with JaCoCo  
✨ End-to-end **CI/CD Pipeline** with Jenkins for automation  

---

## 🛠️ **Jenkins Pipeline Workflow**

The Jenkins pipeline consists of multiple automated stages to ensure a smooth CI/CD process:

| **Stage**           | **Description**                                                                 |
|----------------------|---------------------------------------------------------------------------------|
| **1. Setup**         | Cleans the workspace and prepares the environment                              |
| **2. Compile**       | Compiles the Java code to ensure it’s error-free                               |
| **3. Static Analysis**| Analyzes code quality using tools like **SonarQube** or **Checkstyle**         |
| **4. Unit Test**     | Runs JUnit test cases to validate functionality                                |
| **5. Code Coverage** | Measures code coverage with **JaCoCo**, ensuring a high-quality codebase       |
| **6. Build Artifact**| Generates a deployable JAR file                                                |
| **7. Deployment**    | Optionally deploys the artifact to staging/production (if configured)          |

---

## 🚀 **Technologies & Tools Used**

- **Language**: Java  
- **Build Tool**: Maven  
- **CI/CD Tool**: Jenkins  
- **Testing Framework**: JUnit  
- **Code Coverage**: JaCoCo  
- **Static Analysis**: SonarQube (Optional)  

---

## 📋 **Prerequisites**

Before you begin, ensure you have the following installed on your system:  

✔️ **Java JDK** (v8 or above)  
✔️ **Maven** (v3.6 or above)  
✔️ **Jenkins** (v2.0 or above)  
✔️ Optional: SonarQube for static analysis  

---

## 🚀 **Getting Started**

Follow these steps to set up the project on your local machine:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ezhilezhil/Calculator.git
```

### 2️⃣ Navigate to the Project Directory

```bash
cd Calculator
```

### 3️⃣ Build the Project

```bash
mvn clean install
```

### 4️⃣ Run the Application

```bash
java -jar target/calculator.jar
```

---

## 🔧 **Setting Up Jenkins**

To automate the project using Jenkins:

1. **Clone Repository in Jenkins**:
   - Configure Jenkins to clone the repository using the Git URL.

2. **Set Up Pipeline**:
   - Create a pipeline with the stages outlined in the **Pipeline Workflow** section.

3. **Configure Maven in Jenkins**:
   - Go to `Manage Jenkins > Global Tool Configuration` and set up Maven.

4. **Optional**: Add SonarQube and JaCoCo integration for better analysis and coverage.

---

## 📁 **Project Structure**

```plaintext
Calculator/
├── src/
│   ├── main/
│   │   └── java/
│   │       └── com.example.calculator/
│   │           └── Calculator.java  # Core logic
│   └── test/
│       └── java/
│           └── com.example.calculator/
│               └── CalculatorTest.java  # Unit tests
├── pom.xml  # Maven configuration
└── README.md
```

---

## 📊 **Screenshots**

### Jenkins Pipeline View
![WhatsApp Image 2024-10-19 at 12 09 25](https://github.com/user-attachments/assets/1996bf52-614b-4c70-a66a-1ec2a8280a36)


---

## 🌟 **Future Enhancements**

- ➕ Add support for **advanced mathematical operations** like square root, logarithms, etc.  
- 🖥️ Build a **GUI/Web-based interface** for better usability.  
- 📦 Integrate with **Docker** for containerized builds and deployments.  

---

## 📜 **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

**💡 Tip**: You can explore how CI/CD workflows can improve software development speed and quality. Happy coding! 🚀  



