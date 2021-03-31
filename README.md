# Cypress_Cucumber_API_Selenium_Python_Automation
UI_Automation
Automation suite for UI , API  functional testing using Cucumber -Cypress BDD framework aproach .
                    Python , Selenium (POM model ) for UI.
                    Python , request Module for API Automation.
                    Along with Manual testing cases.
Three Main folders :

1. Test-Developer-task-master :
 which consists of Cypress related files , scripts etc.

 2. Python_API_Automation - API Automation suite using Python request Module, along with reports.

 3. Python Selenium UI Automation - UI Automation using Python selenium approach , along with reports.

Basically the project contains Automation scripts for Elinvar website.

```Pre-requisites```
In order to run the automation script Python3 and pip should be pre-installed and below libraries should be installed. 
```pip install pytest-html```
  ``` pip install selenium ```
  ``` pip install pytest ```
  ``` pip install requests ```

```API : Postman should be installed .```

``` NPM, Cypress should be installed.```

Web Browsers & Web Drivers: Web Browsers: Safari, Chrome, Firefox, IE, Opera, Download webdrivers for the above browsers & put them in the Path variables.

IDE: PyCharm, Visual Studio Terminal(MacOS) & Command Prompt(Windows)

Steps to run the Automation Script
Cloning the repo from GitHub
https://github.com/rajeevpatil24/UI_Automation.git
Go to the path where above repo has been cloned, open the repo in an IDE Open terminal in IDE and run below command
```pytest TestAsset_API.py -vss --html=API_detailed_report22.html```
 For Cypress UI :
  ```npx cypress open```
For Elinvar UI :
```npm run start```

For API Url :

```cd api && export FLASK_APP=app.py && flask run```

For DIfferent runs , we have created report file accordingly.
