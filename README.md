![0_VarLEKR1Mbu8SGN7](https://github.com/user-attachments/assets/b890aa7d-b3fe-4445-bdfb-c30bd38e194a)

**🚀 GKE Microservices Demo with Helm & Argo CD**
- Automating the deployment of Google’s Hipster Shop microservices demo to Google Kubernetes Engine (GKE) using:
  - Helm Umbrella Chart
  - Argo CD GitOps Continuous Deployment
  - Google Kubernetes Engine (GKE)
  - AWS EC2

**⚒️ Requirements**
- GKE Cluster with 1 node
- kubectl, helm v3+, gcloud CLI installed
- Argo CD deployed
- Helm Umbrella Chart Creation

**📌 Notes**
- Redis and all microservices are deployed via the umbrella Helm chart
- Values.yaml under umbrella-chart defines image versions, ports, replicas, and env vars
- Argo CD keeps everything in sync with this Git repositor

**🖼️ Tiny Preview**

![Screenshot 2025-06-29 222435](https://github.com/user-attachments/assets/72019464-f7d0-42b7-8870-9c7c65413705)

![Screenshot 2025-06-29 232951](https://github.com/user-attachments/assets/2be1e1d3-d159-442a-bd44-43ce88c09bc4)

![Screenshot 2025-06-29 233610](https://github.com/user-attachments/assets/45341028-cea3-4df9-b942-cbb8a44f441b)

![Screenshot 2025-06-30 151926](https://github.com/user-attachments/assets/1355ae4f-9baf-4709-9afd-16859b6eb3f0)

![Screenshot 2025-06-30 154118](https://github.com/user-attachments/assets/1b8e3356-e991-41cf-835a-41c95016d432)

![Screenshot 2025-06-30 154623](https://github.com/user-attachments/assets/6d9957b0-0945-40c6-9e88-d3314b691e69)

![Screenshot 2025-06-30 154703](https://github.com/user-attachments/assets/a72406af-829a-4d1b-a7ce-78103ef39716)

![Screenshot 2025-06-30 160318](https://github.com/user-attachments/assets/63ea87ce-dade-40cb-be76-e91b15235938)

![Screenshot 2025-06-30 162426](https://github.com/user-attachments/assets/8f4e8582-4639-41ce-9cc8-b752f277ee1b)


