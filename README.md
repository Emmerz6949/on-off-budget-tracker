# Online/Offline Budget Tracker

## Description

This repository was created so I could add code to the budget tracker application to make it accessible even while a user is offline.

You can use the commits to follow my journey.



### How did I do it?

I used JavaScript, JSON, and the following Node.js package: the built in "path" package to write my code. My code includes the web manifest, the service worker, the db.js file to use IndexedDB, and a variety of lines of code to make it all come together.

If you wish to visit this website you can do so via this link: https://infinite-crag-33693.herokuapp.com/ .



### Installation

If you wish to fork this code for your own use, then make sure you have Node.js (https://nodejs.org/en/download/), and MongoDB Community Server (https://www.mongodb.com/try/download/community?tck=docs_server) installed. And after you've cloned or downloaded your forked repository use the command "npm install" in the terminal to install the necessary "compression", "express", "lite-server", "mongoose", and "morgan" packages (make sure your terminal is in the same directory as the package.json file). After that, if you have everything installed, you simply have to have your terminal in the same direcetory as server.js and use the command "node server.js" to run it. Once it runs you will need to type "localhost:3000" in the address bar of your browser to access the application.



### Usage

To use this budget tracker application click on the link in the "How did I do it?" section of this README.md. Once the website loads use the "Name of transaction" text box to type the name of your transaction & the "Transaction amount" number box to type the numeric value of the transaction, then press the "Add Funds" if it's a deposit or the "Subtract Funds" if it's a withdrawl. After you do, the table and graph that represent the transaction history will be updated.



### Credits

I used Node.js (https://nodejs.org/en/).

The majority of the code was provided by Trilogy Education Services (https://www.trilogyed.com/).
