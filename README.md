# AutomationSimiFinalProject

## 📋 Project Overview

This is a Selenium WebDriver automation testing project using **Java** and **TestNG**, built for practicing UI automation on the sample website:  
🔗 [https://codenboxautomationlab.com/practice/](https://codenboxautomationlab.com/practice/)

---

🧪 Test Cases
The project includes 15 automated test cases targeting various UI components of the practice site.

1. RadioButton
Selects a random radio button from the available options.

2. autoCompleteTest
Enters a short country code (e.g., "jo", "sy", etc.) into the autocomplete field.

Uses keyboard navigation to select a suggestion.

3. SelectTag
Interacts with a dropdown (<select> tag) and selects an option by value.

4. CheckBoxTest
Randomly selects two checkboxes from the available set.

5. Window_Example
Opens a new browser window.

Switches to it, clicks a link, and then switches back to the original window.

6. Switch_Tab_Example
Opens a new tab in the browser.

Switches to the new tab and back, printing page titles for both.

7. AlertTest
Enters a name into an input field.

Clicks an alert button and accepts the popup.

8. ConfirmTest
Enters a name into an input field.

Triggers a confirm dialog and dismisses it.

9. TableTest
Retrieves data from an HTML table.

Prints values from the instructor column.

10. HideAndShow
Tests hide/show functionality of a textbox using buttons.

11. EnableAndDisable
Toggles the enabled state of an input field.

Types into it after enabling.

12. MouseHover
Performs a mouse hover over a menu.

Clicks the "Reload" option that appears on hover.

13. Calender
Navigates to the calendar section.

Switches to the new tab and prints available date elements.

14. Iframe
Switches to an iframe.

Performs a menu action inside it and prints the title after switching windows.

15. DownloadApp
Clicks a link to initiate the download of an APK file.

---

## ✅ Prerequisites

- Java JDK 8 or above
- Maven
- Chrome browser
- [ChromeDriver](https://chromedriver.chromium.org/downloads) (Ensure compatibility with your Chrome version)
- IntelliJ IDEA, Eclipse, or other Java IDE

---

## 🚀 Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/AutomationSimiFinalProject.git
   cd AutomationSimiFinalProject
Install dependencies:

bash
Copy
Edit
mvn clean install
Enable the tests you want to run:

In AppTest.java, set @Test(enabled = true) on the desired test methods.

Run the tests via Maven:

bash
Copy
Edit
mvn test
Or via a testng.xml file for better control (see below).

📄 TestNG Suite Example
xml
Copy
Edit
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

bash
Copy
Edit
mvn test -DsuiteXmlFile=testng.xml
🗂 Project Structure
bash
Copy
Edit
AutomationSimiFinalProject/
├── src/
│   └── test/
│       └── java/
│           └── AutomationSimiFinalProject/
│               └── AppTest.java
├── pom.xml
└── README.md
👤 Author
Ghaith Obeidat.

