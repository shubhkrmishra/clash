# clash
Clash is an application, where user can vote for their preference of content, like and comment in a streamline process. The idea of this project came into picture to learn frontend using Next js and backend using Express js &amp;Typescript.

Inside Server Folder:
- Used the command inside server folder - "npm init -y" - To create package.json file inside server
- Adding express inside server using - "npm i express dotenv cors" {cors connect backend to frontend}
- Installing TypeScript as a dev dependency - "npm i -D typescript @types/express @types/cors nodemon"
- Now preparing Source directory structure inside server folder
- Prepared index.ts file and created basic template to run the application
- As we are working in the typescript, and node js usually work with java script. So we need to change the 'ts' to 'js' and for that, need to add tsconfig.json inside server directory, taken the configuration from - https://github.com/TusharVashishth/express_ts_kit/blob/main/tsconfig.json
- While adding some configuration in package.json and running the command - "npm run watch", dist folder is created
- In the other terminal, run this command to up the server - "npm run server" - Server is running and able to get response


Inside Frontend Folder:
- creating frontend directory using next js by command -  "npx create-next-app@latest"
- frontend application can be up and running using this command - "npm run dev"


If taking Pull of this application-
- First make sure to add some configuration to up the server
- git init - "npm i"
- create .env file inside server directory and add this code "PORT = ____" 