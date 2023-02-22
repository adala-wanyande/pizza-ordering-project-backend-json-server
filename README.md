# Roselyne's Gourmet Pizza JSON-Server API
### Introduction
This is a repository to store the api backend for the front end project [provided here](https://github.com/benard-dev/pizza-ordering-project.git). The frontend app sends network requests to the server using RESTful conventions. The API has 3 resources; contact us messages, orders, and pizzas.

Click this [link](https://pizza-ordering-project-backend.herokuapp.com/) to view the json-server which has been hosted using Heroku.
### Roselyne's Gourmet Pizza JSON-Server Api Features
* Users can send POST, GET, PATCH and DELETE requests to the 3 resources provided.created.
### Installation Guide
* Clone this repository [here](https://github.com/benard-dev/pizza-ordering-project-backend-json-server).
* Run `npm install` to install all dependencies
### Usage
* Run `npm start` to serve the db.json on your local machine using json-server.
* Connect to the API using Postman on port 8000.
### API Endpoints
| HTTP Verbs | Endpoints | Action |
| --- | --- | --- |
| POST, GET, PATCH, DELETE | /api/pizzas | To interact with the pizzas resource appropriately |
| POST, GET, PATCH, DELETE | /api/contact-us-messages | To interact with the contact us messages resource appropriately |
| POST, GET, PATCH, DELETE | /api/orders | To interact with the orders resource appropriately |
### Technologies Used
* [NodeJS](https://nodejs.org/) This is a cross-platform runtime environment built on Chrome's V8 JavaScript engine used in running JavaScript codes on the server. It allows for installation and managing of dependencies and communication with databases.
* [npm](https://www.npmjs.org/) npm is the package manager for the Node JavaScript platform. It puts modules in place so that node can find them, and manages dependency conflicts intelligently. It is extremely configurable to support a wide variety of use cases. Most commonly, it is used to publish, discover, install, and develop node programs.
### Authors
* [Benard Wanyande](https://github.com/benard-dev)
### License
This project is available for use under the MIT License.
