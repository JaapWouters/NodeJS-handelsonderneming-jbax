
# NodeJS passion project

I started this passion project because i cancelled my passion project with Gatsby. In this project i used NodeJS and the CMS system Turbo360. On this website you can see a showcase of some cars and other information.

This project was built with Turbo 360. To learn more, click here: https://www.turbo360.co
## Instructions

After cloning into repo, cd to project root directory and create a .env file. This file requires a TURBO_APP_ID and SESSION_SECRET keys:
```bash
TURBO_ENV=dev
SESSION_SECRET=YOUR_SESSION_SECRET
TURBO_APP_ID=123abc
```
To login to your Turbo360 account, run:
```bash
turbo login
```
To connect to your Turbo360 site, fill in the Site ID and API key:
```bash
turbo connect
```
Then run npm install from the root directory:
```bash
npm install
```
To run dev server, install Turbo CLI globally:
```bash
npm install turbo-cli -g
```
Then run devserver from project root directory:
```bash
turbo devserver
```
To deploy your code to the Turbo360 platform, run:
```bash
turbo deploy
```
To build for production, run build:
```bash
npm run build
```
## Check the website on localhost
http://localhost:3000/

## Demo video
https://youtu.be/7ZjK31Ncva0


