### To run the project :

1. Go to root folder and install dependencies using :
```sh
npm i
```
2. Create env file using the .env with (PORT=3000
DB_USER=root
DB_PASSWORD=AVcardz
DB_DATABASE=avcardz)

3. Run the Project
If you encounter an error similar to `MySQL client does not support authentication protocol requested by server; consider upgrading MySQL client` refer [this](https://jsfiddle.net/sindresorhus/6406v3pf/) stack overflow post. 

4. create "avcardz" name database and create table user with  
     CREATE TABLE User (
       UserID VARCHAR(255) NOT NULL,
       Name VARCHAR(255) NOT NULL,
       Username VARCHAR(255) NOT NULL,
       Email VARCHAR(255) NOT NULL,
       Phone VARCHAR(255) DEFAULT NULL,
       Password VARCHAR(255) NOT NULL,
       PRIMARY KEY (UserID)
      );
    

