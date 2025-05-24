Sportomic

Getting Started
Clone the Repository:

 https://github.com/KhushPatel2210/sportomic
 
Install dependencies:

Navigate to client directory and install frontend dependencies using yarn

yarn install

Similary navigate to api folder and install backend dependencies

yarn install

ENV variables:

create .env file in the client folder and add these variables

VITE_BASE_URL= http://localhost:4000

VITE_GOOGLE_CLIENT_ID= your google client id

create .env file in the api folder and add these variables

PORT= 4000

DB_URL= your db url

JWT_SECRET= your secret (string)

JWT_EXPIRY= 20d

COOKIE_TIME= 7

SESSION_SECRET= your secret session (string)

CLOUDINARY_NAME= your secret session

CLOUDINARY_API_KEY= your cloudinary key

CLOUDINARY_API_SECRET= your cloudinary api secret

CLIENT_URL= http://localhost:5173

Run project:

Open terminal, navigate to client directory and run below command to start frontend

    yarn run dev
    
Open another terminal, navigate to api directory and run this command to start backend server

    yarn start
