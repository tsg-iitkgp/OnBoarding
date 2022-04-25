# Applications of Technology Students' Gymkhana


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  
  1. [Gymkhana Website](#gymkhana-website)
     1. [Objective](#gw-objective)
     2. [Maintenance](#gw-maintenance)
     3. [Features](#gw-features)
  2. [Students' Non-Academic ERP](#students-erp)
     1. [Objective](#se-objective)
     2. [Maintenance](#se-maintenance)
  3. [Inventory System](#inventory-system)
     1. [Objective](#is-objective)
     2. [Maintenance](#is-maintenance)
     3. [Existence](#is-existence)
  4. [Gymkhana Backend](#gymkhana-backend)
     1. [Objective](#gb-objective)
     2. [Maintenance](#gb-maintenance)
     3. [Existence](#gb-existence)
  5. [Calling Back Portal](#cb-portal)
     1. [Objective](#cbp-objective)
     2. [Maintenance](#cbp-maintenance)
     3. [Existence](#cbp-existence)

</details>

<a id="gymkhana-website"></a>

## Gymkhana Website

<a id="gw-objective"></a>

### Objective 

This site contains all the public information of gymkhana and targets the general audience in and out of IIT Kharagpur. This is to provide the target audience with the facilities that gymkhana have, the events it conduct, the way it ensures the mission and vision, etc.

<a id="gw-maintenance"></a>

### Maintenance 

This is site is built with React.js. The data of contacts, events, results, etc needs to be regularly updated. Based on the requirement, new pages and sections need to be developed. The data is static for now. It has to be fetched from the [backend](#gymkhana-backend) api after developing the dashboard and populating the database. For more details, visit: [tsg-iitkgp/web-frontend](https://github.com/tsg-iitkgp/web-frontend).

<a id="gw-features"></a>

### Features

The following are a few features of the website which are very essential and needs to be worked upon every year:
- Live Scoreboard: General Championship
- Events Page
- Gymkhana Noticeboard
- Committees Pages
- Contacts of Current and Past Office Bearers
- Information Pages: General Championship, Inter IIT, TSG Awards, Illumination, etc

#### Live Scoreboard

Live scoreboard was initiated during the academic session 2021 - 2022 and was a huge success. This feature on gymkhana website has a proper value addition to the student community. This needs to be updated year-on-year and to be kept alive.

#### Information Pages

These are a few separate set of pages which are wholely meant to provide basic knowledge to the students regarding the events such as Inter IIT, General Championship, TSG Awards, Illumination, etc.
Instead of having pages only for the results of the events, these pages would exhaustively give the info to the users.

#### Events Page

This page contains the current and past events of gymkhana. An events calendar can also be added here in the future.

#### Gymkhana Noticeboard

This feature has all the recent and active notices of Gymkhana.

#### Committees Pages

These are custom pages for each committee which would contain all the information regarding the events, results, competitions, etc conducted by the committee. This is a one-stop page to know about the committee.

#### Office Bearers Contacts

Data of the current and past office bearers of gymkhana will be displayed here. This can be improvised more to show images and contacts of past office bearers as well.


<a id="students-erp"></a>

## Students' Non-Academic ERP

<a id="se-objective"></a>

### Objective

The purpose of this project is to bring all the non-academic happenings of the institute under a single umbrella instead of keeping them scattered here and there. 

<a id="se-maintenance"></a>

### Maintenance

This project is currently under development and has two frontends i.e. a website and a mobile application. Both of them would work in sync and interact with the [Gymkhana Backend](#gymkhana-backend). For more details about the features of the application, visit: [Problem Statement - Website Hackathon](Files/Website-Hackathon-Problem-Statement.pdf)

<a id="inventory-system"></a>

## Digital Inventory System

<a id="is-objective"></a>

### Objective

The purpose of this application is to manage all the sports inventory of gymkhana, digitalise the records, simplify the issue and return processes.

<a id="is-maintenance"></a>

### Maintenance

This is desktop application built using electronjs and reactjs. Keep this application updated with new features and improvising the existing features based on the feedback recieved from the users. To know more, visit: [tsg-iitkgp/tsg-inventory-system](https://github.com/tsg-iitkgp/tsg-inventory-system)

<a id="is-existence"></a>

### Existence

The Digital Inventory System of Gymkhana was first developed by Praneeth Reddy Kolanu (@praneeth-rdy) (then Technology Coordinator) in the academic year 2021 - 2022 as a part of Akshay Kumar Singh's (then General Secretary Sports & Games) proposal.

<a id="gymkhana-backend"></a>

## Gymkhana Backend

<a id="gb-objective"></a>

### Objective

The idea is to develop a single modular backend which can cater for all the frontend applications developed by the TechTeam. 

<a id="gb-maintenance"></a>

### Maintenance

This project is based on Expressjs and SQLite database. There's a seperate module developed for each of the application. Do not disturb any module if you are not working on its application. Create a new module similar to the previous ones, if you are developing a new frontend and needs a backend.
To know more, visit: [tsg-iitkgp/tsg-backend](https://github.com/tsg-iitkgp/tsg-backend)

<a id="gb-existence"></a>

### Existence

This backend application of Gymkhana was first developed by Praneeth Reddy Kolanu (@praneeth-rdy) (then Technology Coordinator) in the academic year 2021 - 2022. This is currently being maintained by the TechTeam of Gymkhana.


<a id="cb-portal"></a>

## Calling Back Portal

<a id="cbp-objective"></a>

### Objective

This site has been made to keep track of students returning to campus in batches and those who've currently residing on campus after the covid pandemic.

<a id="cbp-maintenance"></a>

### Maintenance

This project is based on Django, Bootstrap and SQLite. This was a onetime use application made during campus re-opening after covid pandemic. Currently, this application is not being maintained.
To know more, visit: [tsg-iitkgp/calling-back-portal](https://github.com/tsg-iitkgp/calling-back-portal) <br/>
Link to the deployed site: [https://calling-back.iitkgp.ac.in](https://calling-back.iitkgp.ac.in)

<a id="cbp-existence"></a>

### Existence

This application of Gymkhana was developed by Praneeth Reddy Kolanu (@praneeth-rdy) (then Technology Coordinator) in the academic year 2021 - 2022.
