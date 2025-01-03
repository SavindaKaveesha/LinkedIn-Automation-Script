
# LinkedIn-Automation-Script

## Description  
This project contains a Java Selenium script to automate the LinkedIn login process. It uses the ChromeDriver to interact with the LinkedIn website and performs actions like entering credentials and clicking the login button.

## Features  
- Automates the LinkedIn login process.  
- Validates the presence and usability of input fields and buttons.  
- Navigates between web pages and handles browser interactions.

## Prerequisites  
Before running the script, ensure the following are installed on your system:  
- **Java Development Kit (JDK)**  
- **Selenium WebDriver**  
- **Chrome Browser**  
- **ChromeDriver** (compatible with your Chrome version)  
- **Git** (if you're cloning this repository)

## Setup and Usage  
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/SavindaKaveesha/LinkedIn-Automation-Script.git
   cd LinkedIn-Automation-Script
   ```

2. **Configure ChromeDriver**  
   Download ChromeDriver from [here](https://chromedriver.chromium.org/downloads) and update the path in the script:  
   ```java
   System.setProperty("webdriver.chrome.driver", "path/to/chromedriver");
   ```

3. **Run the Script**  
   Compile and run the script using your preferred Java IDE or the command line:  
   ```bash
   javac LoginAutomation.java
   java AutomationScript.LoginAutomation
   ```

4. **Credentials**  
   Update the username and password fields in the script with your LinkedIn login details:  
   ```java
   username.sendKeys("your_email@example.com");
   password.sendKeys("your_password");
   ```

## Project Structure  
```
LinkedIn-Automation-Script/
├── src/
│   └── AutomationScript/
│       └── LoginAutomation.java
├── .gitignore
└── README.md
```

## Important Notes  
- **Security:** Avoid hardcoding sensitive information like usernames and passwords. Use environment variables or secure credential storage solutions.  
- **Browser Compatibility:** Ensure ChromeDriver matches the version of your installed Chrome browser.  
- **Disclaimer:** This script is for educational purposes only. Ensure compliance with LinkedIn's terms of service when automating tasks.

## Contributing  
Feel free to open an issue or submit a pull request for improvements or additional features.  
