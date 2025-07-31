# OrangeHRM Automation Project

This project automates the workflow of the OrangeHRM demo application, focusing on admin functionalities such as job categories, locations, and skills management. The automation is built using **Java**, **Selenium WebDriver**, and **TestNG**, following the Page Object Model (POM) design pattern and Page factory.

## 🔗 Application URL

[OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login)

1. **Login** to the application using valid credentials.
2. Navigate to **Job → Job Categories**:
   - Add a category named **"Test Engineer"**.
   - Delete the created category.
3. Navigate to **Organisation → Locations**:
   - Add a new location with all mandatory fields.
   - Delete the created location.
4. Navigate to **Admin → Qualifications → Skills**:
   - Add a skill named **"Testing Demo"**.
   - Delete the skill.
   - Verify successful deletion.
5. **Logout** and close the browser.

## 🧪 Key Automation Scope

- Handling various web elements (text boxes, buttons, dropdowns).
- Element access.
- Navigation from login to dashboard.
- Cross-browser compatibility.

## 🛠 Technologies Used

- **Java**
- **Selenium WebDriver**
- **TestNG**
- **Maven**
- **Extent Reports**
- **Apache POI / JSON** (for test data)


   ```
