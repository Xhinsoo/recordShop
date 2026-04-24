# About this project
The Record Shop is a simple backend Spring Boot API service. 
It allows Northcoders Record shop to perform CRUD operations.

## 1. Getting Started:
    git clone httsp://github.com:Xhinsoo/recordShop.git

## 2. Navigate to the project directory:
   cd recordShop

## 3. Configuration
   i. Connect to postgresql:
   ii. Navigate to resource folder and edit the credentials
    spring.datasource.username= <your username>
    spring.datasource.password= <your password>

## 4. run main
    Run the main RecordShopApplication java file
    
## 5. API Documentation
To check API Documentation visit url at: http://localhost:8080/swagger-ui/index.html#/
   
## 6. Visit url: http://localhost:8080/api/album 
 Few demo queries:
        list all albums in stock
        get album by id
        list all albums by a given artist
        list all albums by a given release year
        list all albums by a given genre
        get album information by album name
        add new albums into the database
        update album details
        delete albums from the database

## 7. Built with
   Spring Boot
   Maven
   H2 database for testing, postgresql for record data
   Lombok to reduce boilerplate code by automatically generating getters, setters      and constructores
   Swagger



## 8. ![img.png](img.png)

Future consideration
    Add more models to simulate complex relationship.
    Integrate Efficient exception to provide feedback for developer or user.

    
## 9. Acknowledgements
    This was a project taught during Northcoder bootcamp program
