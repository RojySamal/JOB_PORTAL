# JOB_PORTAL
This is a Full stack job App made with MERN Stack, MUI, Datagrid, cookie, etc.
## Table of contents

- [Installation ](#installation)
- [Usage](#usage)
- [Features](#features)
- [Author](#author)
  
## Installation 

To run this website locally, follow these steps:

1. Clone the repository: git clone 
    ```terminal
    https://github.com/RojySamal/JOB_PORTAL
    ```
2. Navigate to the project directories.
3. In Backend:
   Create a .env file with variables:
   ```
   PORT=9000
   DATABASE=YOUR_MONGO_URL
   JWT_SECRET=fidbfbFCDSm1558
   NODE_ENV=development if in development mode
     or NODE_ENV=production if you're deploying your App
   ```
   Then run
   ```
   npm install
   ```
    Then Start the development server: 
    ```terminal
    npm run start
    ```
5. In Frontend:

    Install dependencies: 
    ```terminal
    npm install
    ```
    Run: 
    ```teminal
    npm run start
    ```
6. Open your web browser and visit and view the website.

## Usage:
### For Recruiters :
Recruiters can post Jobs in the platform, they can have CRUD ( CREATE READ,
UPDATE DELETE ) functionality on their Job Posting which will also include JDs ( Job
Description ) as well as they can see all the candidates applied and their contact
details ( email & phone numbers ).

### For Applications :
Applicants can signup and enter their basic details including their contact details
& skillset and then on the feed / job board section they can apply to the jobs
posted by the recruiters.

## Features:
##### - Software Architecture: MVC pattern;
##### - HOC (High Order Component);
##### - Dark & Light theme mode with MUI (Material UI);
##### - Admin & user dashboard, pagination, Datagrid, Download in CSV, etc;
##### - Open & close dashboard sidebar;
##### - Admin can create jobs, create category, etc.
##### - Dashboard Analytic;
##### - Responsive App / MUI: Material UI;
##### - User can see his jobs history in user dashboard;
##### - Log In & Register Form with Formik and Yup for validation;
##### - Modern authentication system with JWT and cookie;
##### - Search job, filter jobs by category and location;
##### - Apply for a job in the single page job, if the user is already log In;

## Author:
- [Rojy Samal](https://github.com/RojySamal)
