# Node.js-Express.js-MogoDB-CRUD-Rest-API
Node.js Express.js MongoDB Insert Update Delete Rest API using postman

### Create data
- Send: URL: http://localhost:8080/endpoint/add-student 
- POST->body->raw->JSON
  {
    "first_name": "User1",
    "last_name": "Test1",
    "email": "user1@gmail.com",
    "password": "!user1_123456@"
  }
  
### Read data
- Send: URL: http://localhost:8080/endpoint/
  
### Update data
- Send: URL: http://localhost:8080/endpoint/update-student/(id)
- PUT->body->raw->JSON
  {
    "first_name": "User2",
    "last_name": "Test2",
    "email": "user2@gmail.com",
    "password": "!user2_123456@"
  }
  
### Delete data
- Send: URL: http://localhost:8080/endpoint/del-student/(id)

[Postman Download](https://www.postman.com/downloads/)
</br>
[MongoDB Community Download](https://www.mongodb.com/try/download/community)
