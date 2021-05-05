Name : Online Examination System

Technologies : React js, Node js, Express js, Mongo Db, Ant Design, Redux js

Key features:
    1. User Management
    2. Modular code
    3. Permission management
    4. Persistent answers on page refresh in the Test Portal
    5. Examination results using graphs
    6. Results can directly be downloaded as excel sheet
    7. Feedback system
    8.Negative Marking Scheme

For Installation of Pre-requisite:
	Run "npm install" in the main directory.

Steps to Use:
1. Open the default.json file located inside the config folder.
2. Add Your Own Email ID and Password.
3. Change Connection String according to your database 
4. Uncomment tool.createadmin() line. 
   (Admin details can be tool.js file in services folder) 
    Default Admin Values:
		Email : admin@email.com
		Password : admin
5. Run The Server. To run the server, use "nodemon" in main directory.
6. Again Comment The tool.createadmin() line after successfull execution of server.