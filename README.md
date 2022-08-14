## E-COMMERCE BACKEND

https://github.com/Tarynmoore/ROUTES

## Description 
This is an e-commerce backend application. This one in particular works for a clothing/music store. There are multiple different products, and each product has a tag. To see all the details of each product you must view in Insomnia. 

## Instructions 
First place your mysql password into the .envExample, then change the name of it to '.env' so it can connect correctly.

Next, open the db file in the terminal and open mysql 
```bash
mysql -u root -p 
``` 
Get the source of the schema
```bash
source schema.sql
```
Open the server.js in the terminal and install all the programs that are needed to run this application. Then get the seeds. 
```bash
npm i 
npm run seed
```
Lastly, start the application 
```bash
npm start
```
Once the application has started you must do the route requests in Insomnia.

[Untitled_ Aug 14, 2022 4_04 PM.webm](https://user-images.githubusercontent.com/101439331/184556532-c3a59301-5889-4e1e-be42-2e7d357d2a3c.webm)
