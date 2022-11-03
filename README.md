## What is REST API?
REST (Representational State Transfer) stands for Representational State Transfer.

When a client requests information about resources from a server, the server relays the current state of the resource back to the client machine.

representational-state-transfer-diagram

The client is your PC from which you can request data from a database server and all communication is via REST APIs.

There are several different methods for this:

GET - Used by the client to select or retrieve data from the server.

POST - Used by the client to send or write data to the server.

PUT - Used by the client to update existing data on the server.

DELETE - Used by the client to delete existing data on the server.

## Installation

` $ pip3 install flask ` </br></br>
` $ pip3 install flask_restful ` </br></br>
` $ pip3 install pandas ` </br></br>

## Tests

` GET http://127.0.0.1:5000/users `</br></br>
<p align="center">
  <img src="https://github.com/byosmandogan/RestApiAKYG/blob/main/RestApiAKYG/İmages/1.jpg">
</p>

` POST http://127.0.0.1:5000/users?name=Huseyin&age=22&city=Muğla `</br></br>
<p align="center">
  <img src="https://github.com/byosmandogan/RestApiAKYG/blob/main/RestApiAKYG/İmages/2.jpg">
</p>

` GET http://127.0.0.1:5000/users `</br></br>
<p align="center">
  <img  src="https://github.com/byosmandogan/RestApiAKYG/blob/main/RestApiAKYG/İmages/3.jpg">
</p>

` GET http://127.0.0.1:5000/Mustafa `</br></br>
<p align="center">
  <img  src="https://github.com/byosmandogan/RestApiAKYG/blob/main/RestApiAKYG/İmages/4.jpg">
</p>

` DELETE http://127.0.0.1:5000/users?name=Mehmet&age=21&city=Ankara `</br></br>
<p align="center">
  <img  src="https://github.com/byosmandogan/RestApiAKYG/blob/main/RestApiAKYG/İmages/5.jpg">
</p>

` GET http://127.0.0.1:5000/users `</br></br>
<p align="center">
  <img  src="https://github.com/byosmandogan/RestApiAKYG/blob/main/RestApiAKYG/İmages/6.jpg">
</p>


