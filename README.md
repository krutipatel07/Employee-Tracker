# Employee Tracker
[![Issues](https://img.shields.io/github/issues/krutipatel07/Employee-Tracker)](https://github.com/krutipatel07/Employee-Tracker/issues) [![Issues](https://img.shields.io/github/contributors/krutipatel07/Employee-Tracker)](https://github.com/krutipatel07/Employee-Tracker/graphs/contributors) 

## Description
An application that allows business owners to view and manage employees, roles, and departments within their company.

## Contents
* [Usage](#Usage)
    * [Video Demo](#Video-Demo)
* [Tools & Resources](#Tools & Resources)
* [Questions](#Questions)
* [Credits](#Credits)

## Usage
1. To use this application, first clone this repository.
2. In the command line, navigate to the root of the application and run `npm install`.
4. In the command line, to view database from MySQL `run mysql -u root -p`.
5. Run `source db/schema.sql` in the MySQL shell.
5. Run `source db/seeds.sql` in the MySQL shell to populate test data if desired.
5. Run `quit` to exit out of the MySQL shell.
7. Start the application by running `node server` in the command line.
8. Follow prompts to use the application to view and/or add employees, roles, and departments, as well as update employees.

### Video Demo
View a video demonstration of the application via [Screencastify](https://drive.google.com/file/d/12R_0ZYFZE3XRjxy0hQekKbXxGp6WlosN/view?usp=sharing).
    
## Tools & Resources
* [Node.js](https://nodejs.org/en/blog/vulnerability/july-2021-security-releases/) - JavaScript runtime environment
* [MySQLWorkbench](https://www.mysql.com/products/workbench/) - Visual database design tool

### Dependencies
* [inquirer](https://www.npmjs.com/package/inquirer) - For the CLI user interface. This will prompt user within the CLI for employee information.
* [console.table](https://www.npmjs.com/package/console.table) - Used to print MySQL into tables to the console.
* [mysql](https://www.npmjs.com/package/mysql) - Used to connect to the MySQL database and perform queries
* [promise-mysql](https://www.npmjs.com/package/promise-mysql) - Used to create promises from MySQL queries

## Questions
If you have any questions about the repo, please [open an issue](https://github.com/krutipatel07/Employee-Tracker/issues) or contact me via email at kruti.patel0709@gmail.com. You can find more of my work on my GitHub, [krutipatel](https://github.com/krutipatel07/).
    
## Credits
* Coded by Kruti Patel.