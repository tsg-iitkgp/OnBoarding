# Applications of Technology Students' Gymkhana


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  
  1. [Gymkhana Website](#gymkhana-website)
     1. [Objective](#gw-objective)
     2. [Maintenance](#gw-maintenance)
     3. [Features](#gw-features)
  2. [Gymkhana Blogs Site](#tsgblogs)
     1. [Objective](#tsgblogs-objective)
     2. [Maintenance](#tsgblogs-maintenance)
     3. [Existence](#tsgblogs-existence)
  3. [ApnaInsti](#apnainsti)
     1. [Objective](#ai-objective)
     2. [Features](#ai-features)
     3. [Existence](#ai-existence)
     4. [Maintenance](#ai-maintenance)
  4. [Inventory System](#inventory-system)
     1. [Objective](#is-objective)
     2. [Maintenance](#is-maintenance)
     3. [Existence](#is-existence)
  5. [Gymkhana Backend](#gymkhana-backend)
     1. [Objective](#gb-objective)
     2. [Maintenance](#gb-maintenance)
     3. [Existence](#gb-existence)
  6. [Induction Website](induction)
     1. [Objective](#iw-objective)
     2. [Maintenance](#iw-maintenance)

</details>

<a id="gymkhana-website"></a>

## Gymkhana Website

<a id="gw-objective"></a>

### Objective 

This site contains all the public information of gymkhana and targets the general audience in and out of IIT Kharagpur. This is to provide the target audience with the facilities that gymkhana have, the events it conduct, the way it ensures the mission and vision, etc.

<a id="gw-maintenance"></a>

### Maintenance 

This is site is built with React.js. The data of contacts, events, results, etc needs to be regularly updated. Based on the requirement, new pages and sections need to be developed. The data is static for now. It has to be fetched from the [backend](#gymkhana-backend) api after developing the dashboard and populating the database. For more details, visit: [tsg-iitkgp/web-frontend](https://github.com/tsg-iitkgp/web-frontend). <br/>
Link to the deployed site: [https://gymkhana.iitkgp.ac.in](https://gymkhana.iitkgp.ac.in)

<a id="gw-features"></a>

### Features

The following are a few features of the website which are very essential and needs to be worked upon every year:
- Live Scoreboard: General Championship and Inter IIT
- Events Page
- Admin Dashboard
- Certificate Generator
- Committees Pages
- Contacts of Current and Past Office Bearers
- Information Pages: General Championship, Inter IIT, TSG Awards, Illumination, etc

#### Live Scoreboard

Live scoreboard was initiated during the academic session 2021 - 2022 and was a huge success. This feature on gymkhana website has a proper value addition to the student community. This needs to be updated year-on-year and to be kept alive.

#### Events Page

This page contains the current and past events of gymkhana. An **events calendar** can also be added here in the future. The events listed here can be edited through the Events Update feature of the Admin Dashboard.

### Admin Dashboard
It was created to access any feature which is restricted to TSG Office bearers or Secretaries, such as the Certificate Generator and Events Update. 
If any new such feature is developed, it should be added to the Admin Dashboard.

### Certificate Generator
This feature is a recent addition, placed in the Admin Dashboard, to digitalise the generation as well as distribution of the certificates to be issued to students by TSG.

#### Information Pages

These are a few separate set of pages which are wholely meant to provide basic knowledge to the students regarding the events such as Inter IIT, General Championship, TSG Awards, Illumination, etc.
Instead of having pages only for the results of the events, these pages would exhaustively give the info to the users.


#### Committees Pages

These are custom pages for each committee which would contain all the information regarding the events, results, competitions, etc conducted by the committee. This is a one-stop page to know about the committee. It can be made dynamic too so that it can be modified using Admin Dashboard.

#### Office Bearers Contacts

Data of the current and past office bearers of gymkhana will be displayed here. This can be improvised more to show images and contacts of past office bearers as well.

<a id="tsgblogs"></a>

## Gymkhana Blogs Site

<a id="tsgblogs-objective"></a>

### Objective 

This site is meant to display all the blogs published by Technology Students' Gymkhana. 

<a id="tsgblogs-maintenance"></a>

### Maintenance 

This is built with Ghost. Ghost is an open source headless Node.js CMS. Editors would be given access to the dashboard of the site, so that they can themselves post the blogs on the site. To know more about ghost, do visit: [https://ghost.org/docs/](https://ghost.org/docs/). <br/>
Link to the deployed site: [https://tsgblog.iitkgp.ac.in](https://tsgblog.iitkgp.ac.in)


<a id="tsgblogs-existence"></a>

### Existence 

The Blogs Site of Gymkhana was first developed by Mukul Mehta (then Technology Coordinator) in the academic year 2020 - 2021.


<a id="apnainsti"></a>

## ApnaInsti

<a id="ai-objective"></a>

### Objective
ApnaInsti application was developed to serve as a centralised platform that caters to the day-to-day needs of the student community, either it be the access of information pertaining to the student activities and also dynamic features which can improve the campus experience of every student in IIT Kharagpur.

<a id="ai-features"></a>
### Features
The ApnaInsti app has a lot of features common to the TSG Website, like Events, Results, Opportunities, Contacts sections, but it also has some unique new features like:
 - Buy & Sell: An Intra-Institute OLX-like service, for all the students, where they can buy or sell their products to the other students.
 - Slot Booking: A portal to register for the facilities offered by the TSG, such as Gymnasium and Badminton, with payments integrated in the app itself.
 - Mess Menu: A section where the students can check the menu of the mess of their respective Halls of Residence.
 - Grievance Form: A form where students can report any kind of problem that they are facing.
 - Live Buses: This feature is under development and once developed will help the students track the live location of the buses provided by the Institute.


<a id="ai-maintenance"></a>

### Maintenance 
The Heads of the Developers' Society (3rd year students) are responsible for the maintenance and upgradation of the ApnaInsti App, which has to be eventually taken care of by the Technology Coordinator. Dashboards for specific laterals, such as societies, events and announcements can be developed to ensure updation of data by relevant stakeholders.

<a id="ai-existence"></a>

### Existence
The ideation and foundation of the app was originally done by Mr Shivam Kumar Jha (Technology Coordinator 2019-20) which was later on revised by Ms Devaki Nandana Vardhineedi (Vice President 2021-22) and remarkable advancements were achieved by Mr Praneeth Reddy Kolanu ( Technology Coordinator 2021-22). Afterwards, the final planning and execution was led by Kunal Verma (Technology Coordinator 2022-23) and the Tech Team (2022-23), eventually leading to the formation of Developers’ Society which then developed ApnaInsti.

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

The idea is to develop a single modular backend which can cater for all the frontend applications developed by the TechTeam. It currently hosts the Gymkhana Website and Blogs Website. 

<a id="gb-maintenance"></a>

### Maintenance

This project is based on Expressjs and SQLite database. There's a seperate module developed for each of the application. Do not disturb any module if you are not working on its application. Create a new module similar to the previous ones, if you are developing a new frontend and needs a backend. The backend is currently hosted on an EC2 instance in AWS.
To know more, visit: [tsg-iitkgp/tsg-backend](https://github.com/tsg-iitkgp/tsg-backend)

<a id="gb-existence"></a>

### Existence

This backend application of Gymkhana was first developed by Praneeth Reddy Kolanu (@praneeth-rdy) (then Technology Coordinator) in the academic year 2021 - 2022. This is currently being maintained by the TechTeam of Gymkhana.

<a id="induction"> </a>

## Induction Website

<a id="iw-objective"></a>

### Objective
Although this is not a project made by the Tech Team, the induction website [http://www.inductionprogram.iitkgp.ac.in/](http://www.inductionprogram.iitkgp.ac.in/) is currently being maintained by the Tech Team to facilitate the onboarding of students through the induction program and ensure proper information display at the time of Freshers' Induction.

<a id="iw-maintenance"></a>

### Maintenance
The induction website needs corrections and relevant updates only during the induction week. Contact the respective stakeholders of the Induction Programme to ensure the credibility of the data provided. The source code is available with Computer and Informatics Centre only which can be accessed at the time of induction program.
