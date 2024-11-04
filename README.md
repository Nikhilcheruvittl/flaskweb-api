
# Registration Portal with Authentication

This project is a user registration portal built with the Flask framework, featuring authentication functionality. Users can register, log in, and access protected routes within the application. The project uses Flask-SQLAlchemy for database management and Flask-Login for user session handling and authentication.

# Technologies Used

 - Flask: Lightweight web framework for routing and server management.
 - Flask-SQLAlchemy: ORM (Object Relational Mapping) library for database integration.
 - Flask-Login: User session management and authentication.




# Installation and Usage Instructions

## Prerequisites





#### Clone the repository:

```http
  git clone <repository-url>
   cd <repository-directory>

```



#### Get Set up the virtual environment:

```http
  python -m venv venv
  source venv/bin/activate  

```

#### Install the required packages:

```http
 pip install -r requirements.txt

```
#### Set up the database

```http
 from app import db
db.create_all()

```

#### Run the application:

```http
 flask run
The application should now be running at http://127.0.0.1:5000.
 
```
## Usage

- Navigate to the homepage to register a new user.
- Use the login page to access the portal.
- Upon login, access restricted routes, demonstrating user authentication and session handling.


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

