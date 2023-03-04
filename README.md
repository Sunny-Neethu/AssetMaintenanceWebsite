# AssetMaintenanceWebsite
<h2>Description</h2>
<p>
A website dedicated to asset maintenance provides employees with a platform to submit requests for maintenance of their assets. The employee is required to input their name, email address, a picture of the issue, and a description of the problem. When the admin logs in using their unique username and password, they are presented with a dashboard displaying all the issues that need to be resolved. The admin has the ability to view, edit, and delete maintenance work logs as required.
The website is designed to emphasize the backend of the web page.
</p>
<br />


<h2>Languages</h2>
- <b>EJS</b> 
- <b>Javascript</b>
- <b>BodyParser</b> 
- <b>NodeJS</b>
- <b>HTML5</b> 
- <b>CSS#</b>

<h2>Database</h2>
- <b>MongoDB</b>

<h2>Environments Used </h2>
- <b>Windows 10</b> 

<h2>IDE used</h2>

- <b>Visual Studio Code (V 1.76)</b> 

<h2>Program walk-through:</h2>



<p align="center">
<h3> Main Page</h3>
On the main page, there is a navigation bar that offers two options: "New Request" for employees to submit maintenance requests and "Login" for the maintenance team's admin user. When an employee submits a maintenance request, they must input all the necessary fields. The details they provide are then stored in the MongoDb database under the name "Maintenance." The employee is notified that their request has been accepted.
<br>
<br>
<img src="https://github.com/Sunny-Neethu/Sunny-Neethu/blob/main/images/AssetMaintenanceWebsite.PNG" height="80%" width="80%" alt="mainpage"/>

<h3> Admin dashboard Page</h3>
To log in, the admin clicks on the "Login" option in the navigation and is asked to enter their name and password. As this is a prototype, the username and password are both "admin." Once logged in, the admin is presented with a dashboard that displays details retrieved from the database. The admin has the ability to view, edit, and delete the maintenance log.
<br>
<br>
<img src="https://github.com/Sunny-Neethu/Sunny-Neethu/blob/main/images/AssetMaintenance-dashboard.PNG" height="80%" width="80%" alt="dashboard"/>

<h3>How to make the code run ?</h3>
First, download and extract the code, and then open it in Visual Studio Code. I have already installed all the necessary modules, but based on past experience, you may need to install npm and node modules in order to replicate this. Once you have the code open, navigate to index.html. Then, in the terminal, type "node index.js." This will take you to the link where the results will be displayed.

</p>
