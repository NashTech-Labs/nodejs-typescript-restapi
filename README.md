# nodejs-typescript-restapi

This example presented a simple REST-API built with Nodejs & typescript.

# Technologies
Nodejs
Javascript
Typescript

# Build
Run npm install

Run tsc

# Run
nodemon app.js

# API call 
Get tasks

curl --location --request GET 'http://localhost:3000/'

Create a  task

curl --location --request POST 'http://localhost:3000/todo' \
--header 'Content-Type: application/json' \
--data-raw '{
"text": 2
}'

Update task

curl --location --request PUT 'http://localhost:3000/todo/2022-09-24T10:26:53.237Z' \
--header 'Content-Type: application/json' \
--data-raw '{
"text": "Cockpit Ui Work"
}'

Delete task

curl --location --request DELETE 'http://localhost:3000/todo/2022-09-24T10:26:53.237Z' \
--data-raw ''

