*Company Name: Jindal intelicom*
Can you give a brief introduction about yourself?
1 Specifically, have you ever worked on a 0-to-1 pipeline creation and setup?

2 How would you go about Kubernetes? How will your agent pods/pipelines be built? What is the mirror in Azure for ECS in AWS?

3 If we have two VPCs/VNets (our VPC and a client's VPC), how would you flow data between them?

4 What happens in VNet peering? How is it able to stream data, and what is the authentication behind it?

5 How do you make sure data is not exposed to the outside internet?

6 Can you explain the use case of a NAT Gateway Is it mostly connected for outbound traffic or taking requests/inputs as well?

7 Suppose we are in a multi-tenant architecture and costs suddenly increase significantly (e.g., a 50% spike compared to the previous month). What could be potential reasons, and how would you go about reducing or optimizing the cost?

7 What was your primary method of deployment (e.g., Virtual Machines vs. Container Services)

8 If your VM/server sits in a private subnet and GitHub Actions uses dynamic runner IPs (no fixed IP), how do you deploy your pipeline without exposing the private subnet?

9 What is your deployment strategy (e.g., Blue-Green, Canary)? How do you avoid downtime during hotfixes or redeployments on a VM?

10 What are Helm charts?

11 What is Service Discovery?

12 What is etcd?
Bosch Azure DevOps Interview Questions 
1)Self Introduction
2)Explain your Project / Use Case.
3)Application Gateway and Load Balancer.
4)What is Terraform?
5)What is Azure Bastion Service?
6)Explain the Terraform Workflow.
7)What are RTO and RPO?
8)What is VNet Peering?
9)What is Azure VPN Gateway?
10)What is VMSS (Virtual Machine Scale Set)?
11)What is a Terraform Backend File?
12)What are the different Azure Storage Account Types?
13)How does Terraform create/deploy all Azure resources? Explain the complete flow.
14)What is Branching?
15)What is Git, and how do you run code using Git?
16)What is RBAC (Role-Based Access Control)?
17)What Azure Services have you worked on?
18)What is Azure App Service?
19)How do you check from Terraform which resources are deployed in Azure Cloud?
20)What are Azure Security Services, and how do they work?
21)Explain the Azure Services you have worked on.
Top 30 Screening Questions & Answers – DevSecOps Technology CoE Architect (12–18 Years)
1. What is DevSecOps?
Answer: DevSecOps integrates security into every phase of the Software Development Lifecycle (SDLC), automating security checks within CI/CD pipelines to deliver secure software faster.

2. What is a DevSecOps Center of Excellence (CoE)?
Answer: A DevSecOps CoE establishes enterprise standards, governance, reusable CI/CD pipelines, security policies, best practices, automation frameworks, and drives DevSecOps adoption across multiple teams.

3. What are the key responsibilities of a DevSecOps Architect?
Answer:

Design enterprise DevSecOps architecture
Define governance and standards
Build secure CI/CD platforms
Implement DevSecOps security controls
Lead cloud transformation
Mentor engineering teams
4. Explain a secure CI/CD pipeline.
Answer:
SCM → Build → Unit Test → SAST → SCA → Secrets Scan → IaC Scan → Container Scan → DAST → Artifact Repository → Deployment → Monitoring.

5. What security scans should be part of every pipeline?
Answer:

SAST
DAST
SCA
Secrets Scanning
Container Scanning
IaC Scanning
Compliance-as-Code
6. Difference between SAST, DAST and SCA?
Answer:

SAST: Scans source code.
DAST: Scans running applications.
SCA: Detects vulnerable third-party libraries.
7. What is GitOps?
Answer: GitOps manages infrastructure and deployments using Git as the single source of truth with tools like Argo CD or Flux CD.

8. Difference between GitOps and CI/CD?
Answer:

CI/CD: Builds and deploys applications.
GitOps: Continuously synchronizes infrastructure and applications from Git repositories.
9. What is Platform Engineering?
Answer: Platform Engineering builds Internal Developer Platforms (IDPs) that provide reusable infrastructure, self-service capabilities, standardized pipelines, and developer productivity tools.

10. What is an Internal Developer Platform (IDP)?
Answer: An IDP is a self-service platform enabling developers to provision infrastructure, deploy applications, and access standardized tools with minimal manual intervention.

11. What are Golden Pipelines?
Answer: Standardized, reusable CI/CD templates with built-in security, testing, compliance, and deployment best practices.

12. Explain Agentic AI in DevSecOps.
Answer: Agentic AI enables autonomous systems to analyze issues, make decisions, remediate incidents, optimize pipelines, and automate repetitive DevOps tasks.

13. What is Retrieval-Augmented Generation (RAG)?
Answer: RAG combines Large Language Models (LLMs) with external knowledge sources (Vector Databases) to generate accurate and context-aware responses.

14. What are Vector Databases?
Answer: Databases optimized for storing and searching embeddings, such as Pinecone, Milvus, Weaviate, ChromaDB, and FAISS.

15. What are AI Copilots?
Answer: AI-powered assistants that help developers with code generation, documentation, troubleshooting, and security recommendations.

16. Explain Infrastructure as Code (IaC).
Answer: IaC automates infrastructure provisioning using code with tools like Terraform, CloudFormation, Ansible, Helm, and Puppet.

17. Difference between Terraform and CloudFormation?
Answer:

Terraform: Multi-cloud, vendor-neutral.
CloudFormation: AWS-native infrastructure provisioning.
18. Why use Kubernetes?
Answer: Kubernetes automates deployment, scaling, load balancing, self-healing, rolling updates, and orchestration of containerized applications.

19. Difference between AKS, EKS, GKE, and OpenShift?
Answer:

AKS: Azure Kubernetes Service
EKS: AWS Kubernetes Service
GKE: Google Kubernetes Engine
OpenShift: Enterprise Kubernetes platform by Red Hat
20. What is Argo CD?
Answer: A GitOps continuous delivery tool that automatically synchronizes Kubernetes clusters with Git repositories.

21. What is Zero Trust Security?
Answer: A security model based on "Never Trust, Always Verify," enforcing identity verification, least-privilege access, and continuous validation.

22. What is Compliance-as-Code?
Answer: Automating compliance policies and security standards within infrastructure and deployment pipelines.

23. Which tools are commonly used for secrets management?
Answer:

HashiCorp Vault
Azure Key Vault
AWS Secrets Manager
GCP Secret Manager
24. Which tools are used for observability?
Answer:

Prometheus
Grafana
OpenTelemetry
Elastic Stack
Splunk
Dynatrace
25. What is OpenTelemetry?
Answer: An open-source observability framework used for collecting traces, logs, and metrics from distributed applications.

26. How would you implement DevSecOps in an enterprise?
Answer:

Build CoE
Standardize CI/CD
Integrate security scanning
Adopt GitOps
Implement IaC
Establish governance
Monitor KPIs
Train engineering teams
27. What KPIs would you define for a DevSecOps CoE?
Answer:

Deployment Frequency
Lead Time
MTTR
Change Failure Rate
Vulnerability Remediation Time
Pipeline Success Rate
Security Compliance Score
28. Describe a DevSecOps transformation project you have led.
Answer: A strong response should include:

Current state assessment
Roadmap creation
CI/CD modernization
Security automation
Kubernetes adoption
IaC implementation
Governance
Team enablement
Business outcomes (e.g., faster releases, improved security)
29. How do you secure Kubernetes?
Answer:

RBAC
Network Policies
Pod Security Standards
Image Scanning
Secrets Management
Admission Controllers
Runtime Security
Regular Patching
30. Why are you a good fit for this DevSecOps CoE Architect role?
Answer: Highlight experience in:

Enterprise DevSecOps architecture
CoE establishment
Platform Engineering
Secure CI/CD
Kubernetes
Multi-cloud (AWS, Azure, GCP)
IaC
AI/GenAI integration
Security automation
Leadership, governance, and mentoring teams.

 *TCS me screening ke time question answer Sir...*
 Hello sir, aaj interview m TCS se ye sab questions pucha tha mujhse 

What is Terraform Lifecycle.
What is Terraform State File, how you will manage it ?
What is Terraform Drift, how you can fix it.
What is Terraform locking.
What is Terraform Taint and Terraform Destroy
Can you write a code for Virtual Machine for main.tf file.

Do you know about Ansible? - - I said no for this Sir
Do you know about Kubernetes and Docker ? - I said no for this Sir


Terraform m jo pucha woh sab confidently answer kr diya tha mene and code bhi likh ke de diya tha VM ka usko paper pe

KPMG

1. How do you ensure compliance with data privacy regulations when working with AI systems in a DevSecOps environment?

2. Describe a time when you identified a security vulnerability in an AI system. How did you handle it?

3. Can you walk me through how you would write a unit test for a method that calculates a user's discount based on their subscription tier?

4. Describe your experience with container orchestration tools like kubernetes in the context of deploying AI models securely?

5. What strategies would you use to monitor AI models in production for security threats or performance degradation?

6. Explain the concept of adversarial attacks on AI models and how you would defend against them in a DevSecOps pipeline?

7. How would you balance the need for rapid AI model deployment with maintaining strong security controls?

8. Describe your experience with infrastructure as code tools and how you ensure their security in AI deployments infrastructure?

9. Tell me about a time when you had to explain a complex security concept related to AI to a non technical stakeholder. How did you approach it?

10. What logging and auditing practices would you implement to support security and compliance in AI model operations?
11. **Devops Questions from Orange **

1. Suppose there is a memory leak inside one of the Kubernetes pods. How would you identify and troubleshoot it if you do not have any observability or monitoring tools available

2. Can you write Terraform code to create an Azure Virtual Machine from scratch?

3. What is the difference between kubectl apply and kubectl create? When would you use each command?
4. In your project, how are Persistent Volume Claims (PVCs) used? Which applications use PVCs, and how do you ensure that the storage is secure and compliant with organizational policies?

5. Can you write a Dockerfile for a sample application? 
6. ⁠Please explain each instruction used in the Dockerfile.
7. What are the security best practices you follow in a CI/CD pipeline?
8. Can you explain the team structure in your DevOps project? How is the work distributed among team members, and what are your responsibilities?
9. @+91∙∙∙∙∙∙∙∙84 


Interview questions TCS Walkin

First Round 

What is the state file in terraform?
Why is statefile required to be locked?
Write one resource creation code in terraform.
What is the module file structure?
How Jrfrog artifactory downloads the artifact in server through pipeline write code for it.
Tell me about kubernetes architecture 
If pod failed how u debug
Difference between deployment and Replic set
What is the name space in Kubernetes 

Second Round

What is powershell scripting how it is helping you.
Write a Resource creation code for SQL database.
Write code for CI with three different stages
What is the image pull backoff error.
Is image pull backoff errors come for node or pod .
What is the liveness in kubernetes.
What is ingress in Kubernetes?
QUESTIONS ASKED IN Bupa

1. First asked everything about me and the work I have done in my project
2. Best Practices What I have followed in my work
3. How Applications connect with the resources and applications access the resources
4. What is the file structure I have used in my project
5. What is Statelocking and how have you enforces statelocking?
6. How will resolve the issue if 2 pods are unable to talk to each other?
7. What is AKS Cluster?. Have you worked on Kubernetes?
8. How did you manage the secrets in your project?
9.Can you tell your azure hierarchy in your project?
10. What resources you have deployed in the cloud . 
11. What are terraform modules . What are reusable modules?
12. What is MTTR in observality?
13.How have you implemented the AI in your project?
Interview Questions (31st July) Tru Technologies

1) Can we store SSL certificates in Azure Key Vault?

2) If you have created 8 VMs using Terraform and 2 VMs manually through the Azure Portal, how would you manage them?

3) If a VM goes down, how would you know?

4) How can you create a backup of Virtual Machines (VMs)?

5) What will you do after a frontend developer pushes code to the Git repository?

6) What happens when two developers update the Terraform state file simultaneously?

7) Explain your CI/CD pipeline.

8) Explain all the stages and jobs you have written in your CI/CD pipeline.

9) Questions on Kubernetes

10) How would you manage your databse i.e PostgreSQL?
11) 🚀 Hiring | Senior Cloud Transformation Architect ☁️
📍 Location: Bangalore (Hybrid)
Contraxct -6 months 

We're looking for an experienced Senior Cloud Transformation Architect to lead large-scale enterprise cloud transformation and modernization initiatives. This is an excellent opportunity for professionals with strong technical leadership and client-facing architecture experience.
🔹 Key Skills
✅ AWS / Azure / GCP
✅ Kubernetes
✅ Terraform / CloudFormation / Bicep
✅ CI/CD, GitOps & DevSecOps
✅ Oracle, PostgreSQL, MySQL & MongoDB
✅ FinOps & Cloud Cost Optimization
✅ Observability & Site Reliability Engineering (SRE)
✅ Cloud Security, IAM, Zero Trust & CSPM
✅ Enterprise Program & Stakeholder Management

🔹 Experience
✔️ 12–18 years of overall IT experience
✔️ 8+ years leading enterprise cloud transformation programs
✔️ Hands-on experience in large-scale cloud migration & modernization projects
✔️ Experience managing enterprise programs and globally distributed teams

📩 Interested candidates, please share your updated resume to:
Swetha.u@onasit.com

🔔 𝐈𝐦𝐩𝐨𝐫𝐭𝐚𝐧𝐭:
Please 𝐝𝐨 𝐧𝐨𝐭 𝐜𝐨𝐦𝐦𝐞𝐧𝐭 “𝐈𝐧𝐭𝐞𝐫𝐞𝐬𝐭𝐞𝐝.”
Kindly reach out to the respective recruiters 𝐝𝐢𝐫𝐞𝐜𝐭𝐥𝐲 𝐯𝐢𝐚 𝐞𝐦𝐚𝐢𝐥 to apply or inquire.
