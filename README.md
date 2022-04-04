<h1 align = "center">CoV-19</h1>
This project is developed as an academic project for DBMS subject. It is Web Application based on management of Corona Vaccine which runs on localhost server.

### Prerequisites
Must haves:
- MYSQL(Using XAMPP)
- Browser(That supports HTML and CSS)
- Terminal that supports Nodejs and git commands.

### Installing
To install all the dependencies write the following command on your terminal:<br>
`npm install`
<br><br>

## Getting Started
Firstly we recommend to install Hyper terminal or any other prompt that supports Nodejs. After the installation clone the files in your pc, traverse to the cloned folder in your pc through your terminal and then use the command `npm start` to run it on localhost. Make sure before running the project, you create the database in your xampp server by pasting the commands in tables.sql file. On starting the execution, the project will run on port 3000.<br>
We have also used PL-SQL in our project. Make sure you also add the procedures, triggers and functions of pl sql (from tables.sql file) in your xampp server before running the project.<br>
Keep the database name as <b>corona</b> in your xampp server.


## The Concept Behind
<br>
Our web application "Covid-19 vaccination management system" helps to keep records, and manage all the students, hospitals and inventory data using mySql database.
Here Students can register for hospitals in their area and the hospital can view all the student requests for vaccination in their hospital on creating an account and logging in.
<br><br>
Here each hospital provides a particular brand of vaccine, like Covaxin or Covishield, from which the student can choose any desired vaccination of their choice. Hospitals can also handle information related to students and add the dates when the students received their first and second dose of the vaccine. All this data is instantly updated in the database.
<br>
All Inventory details are visible in the hospital profile page.Here Inventory supplies vaccine to any specific hospitals.Also hospitals can add data in the inventory page inside their profile that shows all inventory that are linked to that hospital and quantity of vaccines they have supplied to the respective hospitals.
<br>
We also provide a statistics page where site viewers can view statistics of percentage of male, female and other students who have registered in our website.
There are various other details that are shown through various mysql queries like percentage of students who have received different vaccines and the number of doses each student has received.We have also represented the total hospitals that have registered in our website, along with the count and percentage of those which are private and government. This helps the viewers to know their choices and helps in easy analysis of information.
<br><br>
## Built With
- HTML - Markup language
- CSS - Style Sheet language
- Javascript- Client Scripting language
- MySQL - Database Management
- node.js - Backend Development environment
- express.js - Fast, unopinionated, minimalist web framework for Node.js

## Contributors
- Tanusha Reddy Gurram
- Tanvi Chandan

