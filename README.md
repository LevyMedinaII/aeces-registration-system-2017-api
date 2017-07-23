# AECES Registration System 2017 Server
Backend server for the AECES Registration System

## How to use:
1. Install postgresql on your system
2. Configure the database (db, username, password)
3. Create a .env file with the ff:
	DATABASE=<db>
	USER=<username>
	PASSWORD=<password>
4. Install node.js and npm (bundle with node.js)
5. Run npm install to install the required modules
6. Run npm start to start the server!

## Packages List:
1. nodemon
	* Used for speeding up development
	* Restarts server after saving changes
2. localtunnel
	* Allows the local application to be accesible via the internet
3. express
	* Base of the application
	* Used for running the server and routing
4. dotenv
	* Used for managing the environment of the application
5. sequelize
	* Database ORM
6. bodyParser
	* for parsing request bodies with express

## Some Files Details
1. .gitignore
	* Contains the list of files to be ignored by git
	* Currently contains .env and node_modules
2. .env
	* Contains all environment variables such as database access creds
3. package.json
	* Contains the configuration, dependencies, and scripts of the node application
4. server.js
	* Main file to be executed when starting the node app

## Notes:
* A brief explanation on the application files can be found in the corresponding files
* Start by checking out server.js for the explanation if you are not familiar with node and express!