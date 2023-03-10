# GraphQL
GraphQL learning

![GraphQL](GraphQL.png)

# What is GraphQL

GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data. 
GraphQL provides a complete and understandable description of the data in your API, which gives you the power to ask for exactly what you need and nothing more. 

##### Description

* Simple lay out of the GraphQL we are learning in school
    - School
    - Student
    - Teacher

.env file not included:

- HOST = "localhost"
- ADMIN_USERNAME = "Admin"
- ADMIN_PASSWORD = "Pasword"
- DATABASE_NAME = "School"
- DIALECT = "mysql"
- DIALECTMODEL = "mysql2"
- PORT = "3000"

In MySQL you need to first create a database:

- CREATE DATABASE School;

## dependencies

dependencies that needs to be installed:

-   dotenv: ^16.0.3,
-   express: ^4.18.2,
-   express-graphql: ^0.12.0,
-   graphql: ^16.6.0,
-   mysql: ^2.18.1,
-   mysql2: ^3.2.0,
-   sequelize: ^6.28.0

## Postman

In school we used postman to test the API:

POST HTTP method 
__mutation (changes the data)__

To create a student: (also posible to do the same with teacher and school) 
-    mutation {
-        createStudent(FirstName:"John", LastName: "Doe", SchoolId:1) {
-           FirstName,
-           LastName
-      }
-   }

To delete a student: (also posible to do the same with teacher and school) 
-   mutation {
-       deleteStudent(id:1) {
-           FirstName,
-       }
-   }

__(not mutation)__
To show all students: (also posible to do the same with teacher and school) 
-    {
-        getStudents {
-            FirstName,
-            LastName
-        }
-    }



## Contributing
ME :) Yes me :)
**Signed: Janne Marie Tvetene**
