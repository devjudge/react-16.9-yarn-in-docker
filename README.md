# cj-app
React SPA


IMPORTANT NOTES (In case Backend Service API Integration is required):

    1. The backend endpoint host url can be accessed using "process.env.REACT_APP_API_URL" property. An example is shown in index.js.
    2. PLEASE USE THIS PROPERTY ("process.env.REACT_APP_API_URL") WHEN YOU ARE TRYING TO CALL A BACKEND API. ALSO DON'T CHANGE THIS PROPERTY ELSE THE APP WILL NOT BUILD PROPERLY AND YOUR SUBMISSION WILL NOT BE SCORED. 
    3. In order to run in your local system, please put one of the below commands only in the "start" scripts in package.json to start the server:
        - Windows (cmd.exe): set "REACT_APP_API_URL=<endpoint URL>" && react-scripts start
        - Windows (Powershell): ($env:REACT_APP_API_URL = "<endpoint URL>") -and (react-scripts start)
        - Linux, macOS (bash): REACT_APP_API_URL=<endpoint URL> react-scripts start
    4. Don't change the command in the "build" scripts in package.json else the app won't build properly and your submission will not be scored. 
        
PROJECT START STEPS:

    Pre-requisites:
    1. Install http-server module (https://www.npmjs.com/package/http-server).
    2. Install node 10, npm and yarn

    Steps:
    1. To run this application, do the following:
        1.a. Go to the project root directory.
        1.b. Run the following commands in the terminal/command line to build the app:
            - yarn
            - yarn run build (NOTE: make sure there in no webpack present before running this command in any directory above this directory.)
        1.c. Run the following command(s) in the terminal/command line to run the app:    
            - http-server ./build -p 4200 -a 0.0.0.0
    
    2. Go to http://localhost:4200 in your browser to view it.
