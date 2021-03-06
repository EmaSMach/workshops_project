## General view

Workshops is a project implemented in Python (version 3.8.x) using Django (version 2.2.x) (based on a previous implementation in PHP) that consists of a project composed of applications that respectively: Allow the management of lists of students in courses that are classified by departments, Allow logging in as a student, teacher or administrator, and one that shows a control panel or home page according to the role that each user has. Other functionalities can be added in the future (that's why it has been implemented in Django, ensuring a coherent structure of the project and its applications).

### The basic functions are:

- Perform creation/reading/updating/deleting (CRUD) operations on students and courses sorted or unsorted by different filters (individually or in batches).

- To be able to import and export batch student lists in files with the following formats: Excel (.xslx, .xls), LibreOfficeCalc (.ods), comma separated flat text files (.csv) or in database sqlite files.

- Create an interactive tutorial for each application.

### List of apps used

- A portal page (the portal to login and which will be the home page)
- A login/register app.
- UsersData (app to create the models used in whole the project)      
- AdminDashboard (the administrator's main panel)                     
- Dashboard (the main panel of the normal user and the 'teachers')    
- UserBrowser (application used to perform searches for any
user to search for other users)                                       

### List of esential models used

- CourseType  
- Course      
- UserProfile

### Documentation and License

The project documentation and the license used are in the 'docs' folder inside the main directory, this project uses the open source GNU GPLv3 license.
