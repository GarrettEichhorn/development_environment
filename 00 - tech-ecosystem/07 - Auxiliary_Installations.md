# Installing / Launching Auxiliary Tools

## Jupyter Notebook

1. Open the Anaconda Navigator application that we downloaded together. It's recommended that you save a shortcut to your taskbar or desktop.

2. In the "Home" panel within the application, `Launch` the Jupyter Notebook window. You can select which environment you'd like to use.

3. Navigate to a folder you'd like to save the files. It's recommended that you create a folder on your Desktop to store all Jupyter Notebooks.

4. Click "New" in the top right-hand portion of the Jupyter window to create a new Notebook! Make sure to select Python 3.

5. Start coding! Here's a [reference guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/) for more information.

**Optional Step**  
You can also launch the Notebook directly from a `git bash` terminal window. Simply type `jupyter notebook` to initialize.

If the command throws an error, refer to this [guide](https://jupyter-notebook.readthedocs.io/en/stable/troubleshooting.html) to troubleshoot. It's most likely an issue with your PATH referencing another terminal window.

----------------

## Postman

1. Download [Postman](https://www.postman.com/downloads/) for windows with the 'Windows 64-bit' installer.

2. This guide assumes familiarity with API development. If you're new to programming, please reference these guides for more information on the power of API / Postman for development:

  * [Getting Started with Postman](https://learning.postman.com/getting-started/)
  * [Postman Tutorial](https://www.guru99.com/postman-tutorial.html)

----------------

## MongoDB

1. Download [MongoDB Compass](https://www.mongodb.com/download-center/compass) for Windows 64-bit

2. Open the Application and enter the correct connection string:

  * Hostname: `cantelcluster-shard-00-00-onuna.mongodb.net`
  * Port: `27017`
  * Authentication: Username/Password
  * Username: `your_name`
  * Password: `your_password`
  * Authentication Database: `admin`
  * Replica Set Name: `CantelCluster`
  * Read Preference: `Primary Preferred`
  * SSL: `System CA / Atlas Deployment`
  * SSH Tunnel: `None`
  * Favorite Name: `CantelCluster` (make sure you "Save Favorite" before connecting)  


3. To request a username / password, submit a ticket to the Service Desk via ServiceNow

----------------

## Studio3T

1. Download [Studio3T](https://studio3t.com/download/) for Windows

2. Open the Application and navigate to the "Connect" button near the top left

3. In the 'Connection Manager', create a "New Collection":  

  * Connection Name: `CantelCluster-shard-0`
  * Server - Connection Type: `DNS Seedlist`
  * Server - Server: `cantelcluster-onuna.mongodb.net`
  * Server - Replica Set Name: `CantelCluster-shard-0`
  * Server - Read Preference: `Primary`
  * Authentication - Authentication Mode: `Legacy (SCRAM-SHA-1)`
  * Authentication - User name: `your_name`
  * Authentication - Password: `your_password`
  * Authentication - Authentication DB: `admin`
  * Click "Test Connection" then "Save"  


4. Connect to `CantelCluster-shard-0`

5. This guide assumes familiarity with SQL and NoSQL languages. If you're new to query languages and or MongoDB syntax, please reference these guides for some important features and documentation:

   * [Visual Studio Builder](https://studio3t.com/knowledge-base/articles/visual-query-builder/)
   * [MongoDB 101](https://studio3t.com/academy/?utm_source=website&utm_medium=banner&utm_campaign=academy-3t)

----------------

## Tableau

----------------

## Atom

1. Download [Atom](https://atom.io/) for Windows

2. Launch the Application and take a look around!

3. Atom is a hackable text editor, which can streamline your programming functions as you traverse the full spectrum of full stack data science deployment. If you are new to programming or configuring custom text editors, please take a look through the "Welcome" documentation and other resources:

  * [Atom Basic](https://flight-manual.atom.io/getting-started/sections/atom-basics/)
  * [Top Atom Packages](https://medium.com/issuehunt/top-10-atom-recommended-packages-in-2018-71035b295d3b)
