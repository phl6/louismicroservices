# louismicroservices
##Used ports
|Config Service|Port|
|-------|----|
|pgAdmin|5050| 
|eureka|8761| 
|zipkin|9411| 

|Service|Port|
|-------|----|
|customer db|9001|
|fraud db|9001|
|customer|8080| 
|fraud|8082| 
|notification|8083|
|API Gateway| 8084|
***

##Start up database
- cd into louismicroservices
- docker-compose up 
- check if pgAdmin and db is boot up on localhost:5050 (with password: password)
***

##Start up services
- eureka
- customer
- fraud
- notification
