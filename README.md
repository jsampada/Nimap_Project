# Nimap-Project
'''Project Overview
This project demonstrates how to build a REST API in Django for managing users, clients, and projects.
It allows user registration using Django's admin system and provides functionality for managing clients and 
projects through the API. The system is designed with the following entities:

Users: Managed through Django’s admin template.
Clients: Registered using REST APIs and managed via CRUD operations.
Projects: Created for clients and assigned to users, with the ability to retrieve
project assignments for the currently logged-in user.
The database used for this project is  MYSQL.

Workflow Description

Client Management:
The system allows CRUD (Create, Read, Update, Delete) operations on clients.
Clients are registered by submitting a client_name and are associated with the user who created them.
Clients can be fetched, updated, or deleted based on their unique ID, and any changes to the client’s information are timestamped.

Project Management:
Projects are created and assigned to a specific client.
A project can be assigned to multiple users, and users can be involved in multiple projects.
Projects are associated with both clients and the users assigned to them, and the system tracks which user created a particular project.

User Management:
Users are registered using Django’s default authentication system via the admin panel.
Each project is assigned to existing users (already registered in the system).
Logged-in users can fetch all the projects they have been assigned to.
'''