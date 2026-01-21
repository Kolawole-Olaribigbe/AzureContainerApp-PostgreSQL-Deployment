Project: AzureContainerApp-PostgreSQL-Deployment

Name: Kolawole Olaribigbe

Step one: Create Resource Group

- Select a subscription
- Name resource group
- Choose region
- Create

<img width="1361" height="638" alt="Screenshot 2026-01-13 171256" src="https://github.com/user-attachments/assets/4a0170a1-133d-42ed-98db-2548b5a19c9a" />



Step two: Create Container App(Basic)

- Open Container App service
- Select a Resource Group
- Name Container App
- Choose Deployment source
- Select Same region as the resource group
- Select container app environment

<img width="1365" height="641" alt="Screenshot 2026-01-13 173123" src="https://github.com/user-attachments/assets/45996932-8080-4325-83bb-4f912306e521" />
<img width="1365" height="257" alt="Screenshot 2026-01-13 174149" src="https://github.com/user-attachments/assets/def21613-39ba-494e-a1ac-561660a34e80" />


Step two: Create Container App(Container)

- Choose Image source (DockerHub)
- Choose Image type(Public)
- Enter Image
<img width="1365" height="578" alt="Screenshot 2026-01-13 174913" src="https://github.com/user-attachments/assets/52684d85-304b-47fa-9f82-de7885239627" />


Step two: Create Container App(Ingress)

- Enable Ingress
- Ingress Traffic: Accept from anywhere
- Target Port: 3000
<img width="1365" height="566" alt="Screenshot 2026-01-13 175711" src="https://github.com/user-attachments/assets/21e44f6d-2fed-4f09-84aa-61f2741020c4" />

Step two: Create Container App(Review configuration, then create)

<img width="1365" height="498" alt="Screenshot 2026-01-13 182335" src="https://github.com/user-attachments/assets/16405e21-8162-4f51-a6b3-66d3aee91f3f" />
<img width="1365" height="421" alt="Screenshot 2026-01-13 182534" src="https://github.com/user-attachments/assets/1938fcb7-0515-41ba-bfa5-985943f860f5" />
<img width="1365" height="643" alt="Screenshot 2026-01-13 183106" src="https://github.com/user-attachments/assets/99747e6d-1a5c-4f6f-93bb-c7ea2e4f18b9" />

Step three: Go to the newly deployed resource
<img width="1360" height="424" alt="Screenshot 2026-01-13 183609" src="https://github.com/user-attachments/assets/d66af95e-acfd-4382-abd3-3635ce4b0af0" />

Step four: From the menu, navigate to the 'Application' menu. Then click "Revisions and replicas"
<img width="760" height="451" alt="Screenshot 2026-01-13 183934" src="https://github.com/user-attachments/assets/fdf5bebc-b65c-4316-8072-43d9044d2925" />

Step five: Click "Show Logs", then the "Basics" tab to Check if application is running
<img width="1126" height="635" alt="Screenshot 2026-01-13 184750" src="https://github.com/user-attachments/assets/ea394aed-713c-4f5f-8166-0a2357f0b7b4" />

- Click on "Logs" tab to check if image is receiving traffic
<img width="1125" height="642" alt="Screenshot 2026-01-13 195355" src="https://github.com/user-attachments/assets/a03c6f4e-bb67-4475-aa46-c8e6ba477d64" />

- Check if page displays, by using the revision url provided in azure
<img width="1365" height="725" alt="Screenshot 2026-01-13 195505" src="https://github.com/user-attachments/assets/3097f4af-ab65-4e22-8473-3a97f99e0654" />



Project: AzureContainerApp-PostgreSQL-Deployment(Contd.)

Step one: Configure PostgreSQL Database(Basics)

- Open Azure Database for PostgreSQL flexible Server

<img width="1365" height="542" alt="Screenshot 2026-01-21 163243" src="https://github.com/user-attachments/assets/6d2fc074-45ba-40e6-b6d3-f5569bc28b21" />
<img width="1365" height="437" alt="Screenshot 2026-01-21 163341" src="https://github.com/user-attachments/assets/db23ebe2-a5dc-4e12-ada3-17202881a72e" />
<img width="1365" height="576" alt="Screenshot 2026-01-21 164147" src="https://github.com/user-attachments/assets/3f1246f7-70c2-4e8b-b81d-4fb286258d4f" />

- Step one(Networking):
<img width="1361" height="575" alt="Screenshot 2026-01-21 164450" src="https://github.com/user-attachments/assets/d09e5742-92a1-4f04-9557-262aed133bab" />
<img width="1365" height="576" alt="Screenshot 2026-01-21 164512" src="https://github.com/user-attachments/assets/747e5eb2-bcf0-45b8-a4e1-2cc62ca13035" />

- Step one(Security):
<img width="1365" height="576" alt="Screenshot 2026-01-21 164744" src="https://github.com/user-attachments/assets/3407b453-8d4a-4f4d-8b5a-121c82b2ddce" />

- Step one(Tags):
<img width="1365" height="580" alt="Screenshot 2026-01-21 164813" src="https://github.com/user-attachments/assets/4f302dcf-fb24-41a9-b91c-fe0a9c943a04" />

- Step one(Review and create):
<img width="1365" height="576" alt="Screenshot 2026-01-21 164909" src="https://github.com/user-attachments/assets/52d25943-1eb8-4187-90af-d369910a00d6" />
<img width="1365" height="402" alt="Screenshot 2026-01-21 164938" src="https://github.com/user-attachments/assets/8356e204-4f4a-4250-aeeb-e767587a110e" />

Step two: Create Database
- Go to resource
- From Menu, navigate to "Databses" under the "Settings" submenu
<img width="1361" height="583" alt="Screenshot 2026-01-21 182943" src="https://github.com/user-attachments/assets/fb6e5dd6-cc33-467d-a9a8-f8518e546a2d" />

- Click on "Add" to create new database
<img width="1364" height="609" alt="Screenshot 2026-01-21 183300" src="https://github.com/user-attachments/assets/8e140033-f183-4599-bcd3-001de53ea314" />
<img width="583" height="643" alt="Screenshot 2026-01-21 183436" src="https://github.com/user-attachments/assets/cb58f279-735e-43d4-a4e2-5ce6d1920639" />

- Navigate to "Connect" under the "Settings" submenu
- Select newly cereated database
<img width="1365" height="581" alt="Screenshot 2026-01-21 183838" src="https://github.com/user-attachments/assets/627c2b32-22a8-4202-95dd-08c473fd96a2" />

Step three: Edit Environment variables
- Navigate to Container App
- Open container
- Go to Environment variables tab
<img width="1361" height="643" alt="Screenshot 2026-01-21 174456" src="https://github.com/user-attachments/assets/42ff00aa-f9d4-48c2-bb2c-51b4ec93d93e" />

Step four: Check App
<img width="1365" height="726" alt="Screenshot 2026-01-21 184719" src="https://github.com/user-attachments/assets/d5834458-3c03-4f9f-a9f3-13b9f626532e" />

