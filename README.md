# gatling-test
This projects shows performace test using gatling

Gatling structure can be defined in 4 different parts:

- HTTP protocol configuration

  This will define your base URL that you will be running your tests against. Also, you can define some other configurations such as 
  useragent, language header, connection and so on.
  
- Headers definition 

  This provides the headers for each request that will be sent to the server. This is relevant because the headers also add a bit of 
  load to the server you are testing.
  
- Scenario definition 

  The core of your test! A Scenario is a group of actions (GET, POST, etc.) that will be executed in order to simulate a user 
  interaction with your application.
  
- Simulation definition 

  This defines the load (amount of users) that will concurrently execute your scenario for a period of time.



















References
===========
- https://gatling.io/
- https://gatling.io/docs/current/cheat-sheet/
- https://dzone.com/articles/create-a-checkout-load-test-scenario-with-gatling
