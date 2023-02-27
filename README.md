# Dockerized-OpenApiGenerated
A guide and the resources to generate and run an API from an OpenApi spec yaml file 

NOTE: A lightweight simple bank app was used to reduce build time. 

1. Clone repository into directory of choice.
2. In DOS CMD run the `docker-compose up` command.
3. The build will take around 3 - 4 minutes so go make yourself a coffee, you deserve it.
5. To test the deployment of the application in your search engine of choice search `localhost:80` this should direct you to the swagger ui of the mimacom Banking API.

TESTING 
- To test the creation of the API use POSTMAN.
1. Import the postman collection fond in this repository into your desktop version of POSTMAN.
2. Run the `Get Accounts` request.
3. The output should be a JSON object with an array called test within it, this array should contain 2 instances of the string iban. 
4. Along with the JSON output the response status should be 501 unimplemented. 

