# <div align="center">**BUDGET TRACKER**</div>

## **TABLE OF CONTENTS**    
[1. TABLE OF CONTENTS](#TABLE-OF-CONTENTS)  
[2. LICENSE](#LICENSE)  
[3. PROJECT DESCRIPTION](#PROJECT-DESCRIPTION)  
[4. APPLICATION LINKS](#APPLICATION-LINKS)  
[5. CONTRIBUTIONS](#CONTRIBUTIONS)  
[6. DEVELOPMENT](#DEVELOPMENT)  
[7. INSTALLATION](#INSTALLATION)   
[8. USAGE](#USAGE)   
[9. TESTING](#TESTING)  
[10. USER STORY](#USER-STORY)  
[11. ACCEPTANCE CRITERIA](#ACCEPTANCE-CRITERIA)   
[12. GRADING REQUIREMENTS](#GRADING-REQUIREMENTS)    
[13. FUNCTIONALITY](#FUNCTIONALITY)  

---

## **LICENSE**  
![MIT](https://img.shields.io/badge/License-MIT-blue.svg)
> This application is covered under the [MIT License](https://opensource.org/licenses/MIT)    

---

## **PROJECT DESCRIPTION**
> The purpose of this challenge was to update an existing budget track application to allow for offline access and functionality. The user should be able to add expenses and deposits to their budget with or without a connection. Additionally, this project was to be deployed via [Heroku](https://dashboard.heroku.com/).   

---

## **APPLICATION LINKS**
> [Live Heroku Application](https://ancient-dawn-71078.herokuapp.com/)   
> [GitHub Repository](https://github.com/mhans19/budget-tracker)  

---

## **CONTRIBUTIONS**   
Please contact **MORGAN HANSEN** for all application inqueries.
| Email | GitHub | LinkedIn |  
| :------: | :------: |  :------: |  
| <mdhansen19@gmail.com> | [GitHub](https://github.com/mhans19?tab=repositories) |  [LinkedIn](https://www.linkedin.com/in/morgan-hansen-47235872/?challengeId=AQF6MR471a-pZgAAAXMTL5e4xLqg_LNW5yawcXgk_uUmLrzsXk5ehOnzlQuK2dOVeX4ARtJwxmcHQrQhtgL_jM96wbBzhLvmAA&submisksionId=813167e8-8027-1e16-5911-1c143c23561f) |  
  
---

## **DEVELOPMENT**  
This application was developed with the following application structures:  
1. [Node.js](https://nodejs.org/en/)  
2. [Node Package Manager (NPM)](https://www.npmjs.com/)
    + [NPM Compression](https://www.npmjs.com/package/compression)  
    + [NPM dotenv](https://www.npmjs.com/package/dotenv)  
    + [NPM Mongoose](https://www.npmjs.com/package/mongoose)
    + [NPM Express](https://www.npmjs.com/package/express)
    + [NPM Morgan](https://www.npmjs.com/package/morgan)
    + [IndexedDB](https://www.npmjs.com/search?q=IndexedDB)
3. [JavaScript (js)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)   
4. [jQuery](https://jquery.com/)   
5. [JSON](https://www.json.org/json-en.html)
6. [Heroku](https://dashboard.heroku.com/)

---

## **INSTALLATION**
> This online application does not require any installation prior to running.   
However, if interested in contributing to the application, a user *must* complete the following:  
> 1. Download the [GitHub repository](https://github.com/mhans19/budget-tracker) to a local repository. 
> 2. [Install dependencies](#DEVELOPMENT) such as Node.js and NPM packages.   

---

## **USAGE**
> The application is deployed with Heroku and available for immediate use. Simply navigate to the application by following the [application link](https://ancient-dawn-71078.herokuapp.com/).

---

## **TESTING**
> During development, no testing was conducted.   

---

## **USER STORY**  
> AS AN avid traveler  
> I WANT to be able to track my withdrawals and deposits with or without a data/internet connection  
> SO THAT my account balance is accurate when I am traveling    
---

## **ACCEPTANCE CRITERIA**
> GIVEN a budget tracker without an internet connection  
> WHEN the user inputs an expense or deposit   
> THEN they will receive a notification that they have added an expense or deposit   
> WHEN the user reestablishes an internet connection   
> THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated  

---

## **GRADING REQUIREMENTS**
#### <div align="center">This Challenge is graded based on the following criteria:</div>
### **<div align="center">Acceptance Criteria: 40%</div>**
- [x] Satisfies all of the preceding acceptance criteria plus the following
- [x] Application must include a service worker.  
- [x] Application must include a web manifest.  
- [x] Application must use IndexedDB for offline functionality.  
- [x] Application must be deployed to Heroku.  

### **<div align="center">Deployment: 32%</div>**
- [x] Application deployed at live URL.
- [x] Application loads with no errors.
- [x] Application GitHub URL submitted.
- [x] GitHub repository contains application code.

### **<div align="center">Application Quality: 15%</div>**
- [x] User experience is intuitive and easy to navigate.  

### **<div align="center">Repository Quality: 13%</div>**
- [x] Repository has a unique name.
- [x] Repository follows best practices for file structure and naming conventions.
- [x] Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
- [x] Repository contains multiple descriptive commit messages.
- [x] Repository contains quality README file with description, screenshot, and link to deployed application.

---

## **FUNCTIONALITY**  
> In an internet browser, navigate to the [deployed application](https://ancient-dawn-71078.herokuapp.com/) and begin tracking expenses and deposits, online or offline.  
![](/assets/images/deployedApp.PNG)  
