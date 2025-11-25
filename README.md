# Lab 8 – Algonquin Pet Store (On Steroids)

## 1. Demo Video
YouTube Link: [Demo](https://youtu.be/a6QepO8eYzU)

---

## 2. Task 1 – Summary of Implementation
For Task 1, I deployed the initial version of the application using the provided all-in-one YAML file.  
I applied the manifest to the cluster, verified that all pods and services were created, and confirmed that the system components (MongoDB, RabbitMQ, and the core microservices) were running and reachable inside the cluster.

---

## 3. Task 2 – Summary of Implementation
For Task 2, I updated the all-in-one manifest with the required changes.  
This included switching to the Lab 8 container images, updating the service configurations, and exposing the frontend through a LoadBalancer.  
After applying the updated file, I validated that all services communicated correctly and confirmed the application was accessible externally.

---

**File used:** `aps-all-in-one-Task1.yaml` & `aps-all-in-one-Task2.yaml`  
(The full file is included in the repo)
