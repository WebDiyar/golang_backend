1. Book reservation
2. Web application designed for managing a collection of books and users.
   With this application, users can add, edit, and delete books, as well as create and manage user profiles.
4. Amangeldi Diyar, Egisbekov Erlan, Raisov Raiymbek.
5. Step 1 Create project folder,write go mod init github
   Step 2 write go get gorm.io
   Step 3 go get gofiber/fiber/v2 and joho/godotenv from github
   Step 4 we go to vs code and create folders models, storage and file.env
   where we write all database details,then we create main.go file. we can start with models folder and create our books model and user model here we have both models in one file
   but we can write them separately in the storage we have postgres.go to make connection
        
