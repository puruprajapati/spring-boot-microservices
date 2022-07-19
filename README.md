# spring-boot-microservices-new
This repository contains the latest source code of the spring-boot-microservices tutorial


Architecture of the applicaion


![architecture](https://user-images.githubusercontent.com/4188383/179445386-81f65789-e3d7-4582-b2b2-891cf79d17a6.png)


Communication


![2 interprocess communication](https://user-images.githubusercontent.com/4188383/179445393-88d63f5a-3ced-4550-88f0-55f232c4d6ac.png)


We might have multiple instances of an application and resulting multiple dynamic uri s


![image](https://user-images.githubusercontent.com/4188383/179446173-f3f9ec15-0f2d-45cb-a29c-53d3c18159ad.png)


This pattern in service discovery


![image](https://user-images.githubusercontent.com/4188383/179446284-79d70f85-c354-4b37-93a6-ef6d5732ab89.png)

Discovery server will save the info of the server


![image](https://user-images.githubusercontent.com/4188383/179446428-96936f15-303e-4621-a97f-ed5c3f66ba0b.png)


without api gateway


![image](https://user-images.githubusercontent.com/4188383/179662698-451cc343-2509-4de6-a365-65fd6b6f9a59.png)


it will not work in production as app can have multiple instance


![image](https://user-images.githubusercontent.com/4188383/179662798-3b897e2b-6a85-4f35-ac9f-e633c0ecc70d.png)


api gateway also helps in 
- routing based on request headers
- authentication
- security
- load balancing
- ssl termination







URL :https://www.youtube.com/watch?v=0TQliqoX6Kc&list=PLSVW22jAG8pBnhAdq9S8BpLnZ0_jVBj0c&index=4

