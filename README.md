## **Full-Stack Application Deployment on AWS EC2**

This project demonstrates the deployment of a full-stack web application on AWS EC2 instances. The application includes a **React.js frontend**, a **Node.js backend**, and a **MySQL database**, hosted on separate instances for better performance and security.


## **Deployment Steps**

Step 1. ## **Database Setup (MySQL)**
1. Launched an EC2 instance to host the MySQL database.  
2. Installed and configure MySQL for secure access.  
3. Set a strong root password and allow connections from the backend server.  
4. Verified the database is running and ready for connections.  

step 2. ## **Backend Setup (Node.js)**  
1. Launched an EC2 instance for the backend application.  
2. Installed the required version of Node.js and prepared the server environment.  
3. Uploaded the backend application code and installed dependencies.  
4. Set up a connection to the MySQL database and loaded the required schema.  
5. Configured the backend to run as a continuous service.  

step 3. ## **Frontend Setup (React.js with Nginx)**  
1. Launched an EC2 instance for the frontend application.  
2. Installed Nginx as the web server for serving the React app.  
3. Uploaded the React build files to the web server directory.  
4. Configured Nginx to route API requests to the backend server.  
5. Restarted the server and verify it is accessible over the internet.  

step 4 ## **Testing**
- Accessed the frontend via the public IP of the frontend EC2 instance.  
- Verified that the backend APIs are functioning correctly through the frontend.  
- Confirmed the database connectivity and data flow between components.  


## **Conclusion**

By completing the outlined steps, I successfully deployed a full-stack application on AWS EC2 instances. The backend, frontend, and database were securely connected using private IPs and hostnames, enabling seamless communication. The application is fully operational and accessible through the public IP of the frontend server.
