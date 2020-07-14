# Run the project
1. Run project environment
    ````
    $ docker-compose -f ./docker/environment.yml up -d
    ````
2. Run Gateway Service
    ````
    $ cd JGateway
    $ ./mvnw
    ````
    And run Getawey UI
    ````
    $ npm start
    ````
3. Run JCategory service
    ````
    $ cd JCategory
    $ ./mvnw
    ````
4. Run JProduct Service
     ````
    $ cd JProduct
    $ ./mvnw
    ````