In Phonebook Microservice Web Application, there is a frontend service and a backend service to
interact with database service. Each service is managed by a Kubernetes deployment. The backend
service is a gateway for the application and it serves the necessary web pages for create, delete and
update operations while the frontend service serves a search page in order to conduct read operations.
To preserve the data in the database, persistent volume and persistent volume claim concepts are
adopted.