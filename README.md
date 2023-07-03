# 📂 SQL: Employee Tracker 📂
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

## 📚 Description
The Employee Tracker is a Node.js command-line application for managing a company's employee database. You can view departments, roles, and employees, as well as add departments, roles, and employees. You can also update an employee's role. The application uses Inquirer for the interactive command line interface and MySQL to manage the database.

## 📖 Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Tests](#tests)
* [Questions](#questions)

## 💽 Installation
To get this application up and running on your own system, follow these steps:
```bash
git clone https://github.com/Dominick-D/EmployeeTracker
cd EmployeeTracker
npm install
```
After the dependencies are installed, log into your MySQL server and enter the following command to set up the database:
```sql
source db/schema.sql
exit
```
Once the database is set up, seed it with some initial data (If needed) by running:
```bash
npm run seed
```
## 🎯 Usage
[Walkthrough Video 🎥](your video link here)

Once you've successfully installed all the required dependencies, the application is ready for use. Invoke it by running the following command:

```bash
node index.js
```
You'll be presented with a series of prompts to interact with your employee database. Select your desired operation and follow the prompts.

## 📜 License
This project is licensed under the **MIT** license.

## ❓ Questions
If you have any questions about the repo, open an issue or contact me directly at [Here](dominickdonn.me/contact). You can find more of my work on [my portfolio](domdonn.me).