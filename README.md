# louismicroservices
pgAdmin 5050
customer db 9001
fraud db 9001
eureka 8761

customer 8080
fraud 8082
notification 8083

#Start up database
- cd into louismicroservices
- docker-compose up 
- check if pgAdmin and db is boot up on localhost:5050

#Start up services
- eureka
- customer
- fraud
- notification
