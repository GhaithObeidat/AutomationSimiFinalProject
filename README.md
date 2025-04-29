# AutomationSimiFinalProject

## 📋 Project Overview

This is a Selenium WebDriver automation testing project using **Java** and **TestNG**, built for practicing UI automation on the sample website:  
🔗 [https://codenboxautomationlab.com/practice/](https://codenboxautomationlab.com/practice/)

---

🧪 Test Cases
The project includes 15 automated test cases targeting various UI components of the practice site.

1. RadioButton

2. autoCompleteTest

3. SelectTag

4. CheckBoxTest

5. Window_Example

6. Switch_Tab_Example

7. AlertTest

8. ConfirmTest

9. TableTest

10. HideAndShow

11. EnableAndDisable

12. MouseHover

13. Calender

14. Iframe

15. DownloadApp

---

## ✅ Prerequisites

- Java JDK 8 or above
- Maven
- Chrome browser
- [ChromeDriver](https://chromedriver.chromium.org/downloads) (Ensure compatibility with your Chrome version)
- IntelliJ IDEA, Eclipse, or other Java IDE

---

## 🚀 Setup Instructions

 **Clone the repository:**

 
   git clone https://github.com/your-username/AutomationSimiFinalProject.git
   cd AutomationSimiFinalProject

Install dependencies:


mvn clean install

Enable the tests you want to run:

In AppTest.java, set @Test(enabled = true) on the desired test methods.

Run the tests via Maven:


mvn test

Or via a testng.xml file for better control (see below).

📄 TestNG Suite Example

<!-- testng.xml -->
<!DOCTYPE suite SYSTEM "https://testng.org/testng-1.0.dtd">
<suite name="Automation Suite">
  <test name="All Functional Tests">
    <classes>
      <class name="AutomationSimiFinalProject.AutomationSimiFinalProject.AppTest"/>
    </classes>
  </test>
</suite>



Run with:

mvn test -DsuiteXmlFile=testng.xml

🗂 Project Structure

AutomationSimiFinalProject/

├── src/

└── test/

└── java/

└── AutomationSimiFinalProject/

└── AppTest.java

├── pom.xml

└── README.md


👤 Author
Ghaith Obeidat.

