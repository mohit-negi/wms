## WMS Developed with springboot + Default tomcat server + hibernate 

- Template - RBAC

#### Pipeline features
- Reactive Version
    - Hibernate reactive
    - Netty server
-   Microservice
    - AMQP between services

## Project Todo
- DataBase design :

    - [ ] ER Diagram
    - Entities to be considered :
        1. User
        2. Godown
        3. Product
        4. Consumer
        5. Producer
        - Required for management
        1. Purchase order
        2. Delivery order
- Boiler plate setup :
    - [ ] Entites and their appropriate relation
    - [ ] Securing application with RBAC template
- IMS - API
    - [ ] Entities getter and setters
    - [ ] Features and usecases
        - [ ]  User order - order picked from the nearest godown 
        - [ ] User orders a product , how it handles products not available in the nearest godown , product transfer between godown , update purchase and sold list according to it - possible consideration Dijkstra & Knapsack (For shortest path)
        - [ ] Godown ticket management list 
        
        - [ ] Bill generation - Gst and sgst included
        

        
    


