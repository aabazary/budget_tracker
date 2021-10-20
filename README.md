# <ins>Budget Tracker</ins>
![](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)![](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)![](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)![](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)![](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)![](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)![](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)
## <ins>Description</ins>
This is a budget tracker that utilizes MongoDB and IndexedDB, to allow the user to store data about their income and expenses. The data shows up as a list and graph so one can track there current balance. It also allows the user to input data while offline into the IndexedDB, so when the user returns online, the database takes in the information and updates the page.
## <ins>Table of Contents</ins>
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Features](#features)
- [Questions](#questions)

## <ins>Installation</ins>

Type `npm i` or `npm install` in the integrated terminal(if all the files do not install, attempt it again)

Run the application with `npm start`

## <ins>Usage</ins>

Link to deployed site:

https://arcane-reaches-12174.herokuapp.com/


The site works normally online, allowing you to input a transaction name and amount to either add or subtract. Doing so will create a graph showing the status of your budget.

<p align="center" >
<img src ="./public/READMEImages/sample1.png" height=300>
</p>

We can also use the site offline, by navigating(in the devtools) to Application>Service Worker tab. We can mimic an offline connection by checking the box labeled offline and refreshing the page

<p align="center" >
<img src ="./public/READMEImages/offline.png" height=300>
</p>

We can then input a transaction and ensure that that the data was stored by navigating to the IndexedDB>BudgetDB>BudgetStore section of the storage section to ensure that the data has been stored to the indexedDB

<p align="center" >
<img src ="./public/READMEImages/indexedDB.png" height=300>
</p>

We can then update the database by unselecting the offline checkbox, and reloading the page to see the IndexedDB data store the data into the database.

<p align="center" >
<img src ="./public/READMEImages/backOnline.png" height=300>
</p>

## <ins>License</ins>
![](https://img.shields.io/badge/License-MIT%20-blue?style=flat-square)

This project is covered under MIT
## <ins>Features</ins>
Allows users to store offline data inside IndexedDB and populates the database once back online

## <ins>Questions</ins>
Contact Budget Tracker at aabazary@gmail.com. Github link: https://github.com/aabazary
