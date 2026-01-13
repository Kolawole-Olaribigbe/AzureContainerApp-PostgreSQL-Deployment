Project: AzureContainerApp-PostgreSQL-Deployment

Name: Kolawole Olaribigbe

Step one: Create Resource Group

- Select a subscription
- Name resource group
- Choose region
- Create

<img width="1361" height="638" alt="Screenshot 2026-01-13 171256" src="https://github.com/user-attachments/assets/4a0170a1-133d-42ed-98db-2548b5a19c9a" />



Step two(Basic): Create Container App

- Open Container App service
- Select a Resource Group
- Name Container App
- Choose Deployment source
- Select Same region as the resource group
- Select container app environment

<img width="1365" height="641" alt="Screenshot 2026-01-13 173123" src="https://github.com/user-attachments/assets/45996932-8080-4325-83bb-4f912306e521" />
<img width="1365" height="257" alt="Screenshot 2026-01-13 174149" src="https://github.com/user-attachments/assets/def21613-39ba-494e-a1ac-561660a34e80" />


Step two(Container): Create Container App

- Choose Image source (DockerHub)
- Choose Image type(Public)
- Enter Image
<img width="1365" height="578" alt="Screenshot 2026-01-13 174913" src="https://github.com/user-attachments/assets/52684d85-304b-47fa-9f82-de7885239627" />


Step two(Ingress): Create Container App

- Enable Ingress
- Ingress Traffic: Accept from anywhere
- Target Port: 3000
<img width="1365" height="566" alt="Screenshot 2026-01-13 175711" src="https://github.com/user-attachments/assets/21e44f6d-2fed-4f09-84aa-61f2741020c4" />

Step two(Reveiw configuration, then create): Create Container App

<img width="1365" height="498" alt="Screenshot 2026-01-13 182335" src="https://github.com/user-attachments/assets/16405e21-8162-4f51-a6b3-66d3aee91f3f" />
<img width="1365" height="421" alt="Screenshot 2026-01-13 182534" src="https://github.com/user-attachments/assets/1938fcb7-0515-41ba-bfa5-985943f860f5" />

