# 🚀 AutomationExerciseProject

## 🧠 Overview  
This is a **practice automation project** I built while learning **test automation frameworks** and **software design patterns**.  
It automates key workflows on the **[Automation Exercise](https://automationexercise.com)** website — including registration, login, product browsing, and checkout — using **Java**, **Selenium**, and **TestNG**.

The project follows **clean code principles** and uses well-known **design patterns** to make the framework maintainable, reusable, and easy to scale.

---

## ⚙️ Tools & Technologies  
- ☕ **Java**  
- 🧭 **Selenium WebDriver**  
- 🧪 **TestNG**  
- 📦 **Maven**  
- 💻 **GitHub**  
- 🔄 **CI/CD Ready** (GitHub Actions planned for automated testing)

---

## 🧩 Design Patterns Implemented  
| Pattern | Description |
|----------|-------------|
| 🧱 **Page Object Model (POM)** | Separates page elements from test logic for better readability and reusability. |
| ⚙️ **Factory Pattern** | Handles browser and driver instantiation dynamically. |
| 🪞 **Facade Pattern** | Simplifies complex workflows by exposing easy-to-use methods for tests. |
| 🔁 **Singleton Pattern** | Ensures only one WebDriver instance exists during a test session. |

---

## 📁 Project Structure  
```
AutomationExerciseProject/
 ├─ src/
 │   ├─ base/           → Base classes & configurations
 │   ├─ pages/          → Page Object classes (POM)
 │   ├─ tests/          → Test classes (TestNG)
 │   └─ utils/          → Helpers & Factory classes
 ├─ test-output/        → Generated test reports
 ├─ pom.xml             → Maven configuration file
 └─ .gitignore
```

---

## 🚀 How to Run  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/Muhammad-Hossam/AutomationExerciseProject.git
   cd AutomationExerciseProject
   ```
2. **Run the test suite**  
   ```bash
   mvn clean test
   ```
3. **View the reports** in the `test-output` folder after execution.

---

## 🌟 Features  
- Automated testing of main user flows  
- Modular and maintainable codebase  
- Easy to expand with new test cases  
- Ready for CI/CD pipeline integration  
- Generates test reports automatically  

---

## 💡 Future Improvements  
- Add **data-driven testing** (JSON/Excel)  
- Add **Allure** or **ExtentReports** for rich reporting  
- Integrate full **GitHub Actions CI/CD pipeline**  
- Include **cross-browser testing** support  

---

## 👨‍💻 Author  
**Muhammad Hossam**  
📍 [GitHub Profile](https://github.com/Muhammad-Hossam)

> 🧪 *This project was created as a hands-on practice while learning automation testing and applying real-world design patterns.*

---

⭐ 
