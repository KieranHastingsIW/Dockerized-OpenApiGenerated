# Dockerized-OpenApiGenerated
A guide and the resources to generate and run an API from an OpenApi spec yaml file 

1. clone repository into directory of choice
2. In DOS CMD run the `docker-compose build` command
3. the build will take around 3 - 4 minutes so go make yourself a coffee, you deserve it.
4. once the build is complete run `docker-compose up` 
5. to test the depolyment of the application in your search engine of choice search `localhost:80` this should direct you to teh swagger ui of the mimacom Banking API.


NOTE: lightweight simple bank app was used to reduce build time.
//TODO:

    create test cases for the light weight bank app 
    write up testing
    TESTING 