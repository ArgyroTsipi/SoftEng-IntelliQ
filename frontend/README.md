# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

npx create-react-app my-app

## Getting started with frontend 

## STEP1: HTTPS 
Set Chrome as your default browser.

In the Chrome browser:
Navigate to ΄chrome://flags΄ 
In the chrome://flags page, type in the search bar: ΄invalid certificate΄
Εnable it and relaunch.

## STEP 2: Backend
Make sure you have the backend server running. You can find instructions on how to do this on the general readme file.

## STEP 3: Frontend
In terminal, navigate to the project's folder and type ΄cd frontend΄.

Install all the necessary packages by typing ΄npm install΄ in the terminal window and press ΄enter΄.

To run the frontend type one of these commands in the terminal and press ΄enter΄:

    Windows(cmd.exe)  
    ΄set HTTPS=true&&npm start΄

    Windows(Powershell)
    ΄($env:HTTPS = "true") -and (npm start)΄

    Linux, MacOS (Bash)
    ΄HTTPS=true npm start΄

    If you have followed the instructions correctly, the webpage should load.

## HTTP 
If you want to run it with HTTP instead of HTTPS, change in every url the ΄https΄ to ΄http΄.

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.
