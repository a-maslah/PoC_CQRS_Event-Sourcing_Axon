# PoC_CQRS_Event-Sourcing_Axon
Développement d'un PoC (Froof Of Concept) de Séparation de la partie command et query d'un micro-service basé sur CQRS et Event Sourcing en utilisant Axon Server
## Architecture 
![architectimage](https://user-images.githubusercontent.com/62752474/148677851-9b324768-1462-4e2f-ab9d-fd32e0d5ca73.png)
## Axon Server
Events:
![axondash](https://user-images.githubusercontent.com/62752474/148677836-27df1fb7-06f0-457d-af23-5000f03da135.PNG)
![eventsAxons](https://user-images.githubusercontent.com/62752474/148677813-5e171725-93be-430a-a304-de3cc5856e94.PNG)
Microservices:
![axonOverwiew](https://user-images.githubusercontent.com/62752474/148677808-8053c040-ce23-4452-9967-ec5282fa4c4e.PNG)

## Customer-Command-Side
![commandsExemple](https://user-images.githubusercontent.com/62752474/148677837-aa42ecee-77ae-4978-869e-fff670bc7361.PNG)
Create Customer:
![createCustomer](https://user-images.githubusercontent.com/62752474/148677838-bfc5ff29-820b-4fad-9424-b33926a65073.PNG)

## Customer-Query-Side
![queries](https://user-images.githubusercontent.com/62752474/148677816-108b49f0-142a-4eb0-b690-83883e9a24d1.PNG)
