**DevSecOps Project - Netflix Clone on cloud using Jenkins**
![arch](https://github.com/user-attachments/assets/4b10cd85-7914-4c6a-89a3-0e801a129210)


**Project Overview:**

Developed and deployed a Netflix-like streaming application on AWS using DevSecOps best practices. 
Implemented a CI/CD pipeline with Jenkins, 
integrated security tools (SonarQube, Trivy, OWASP Dependency-Check),
and set up monitoring with Prometheus and Grafana. Automated containerized deployments using Docker and Kubernetes.

**Key Responsibilities & Technologies Used**

**1. Cloud Infrastructure Setup & Deployment (AWS & Docker)**
Provisioned AWS EC2 instance (Ubuntu 22.04) for hosting the application.
Installed and configured Docker for containerized deployment.
Built and deployed the application as a Docker container:
Pulled the application source code from GitHub.
Built Docker images and ran the application using Docker Compose.
Integrated TMDB API Key for fetching movie details.

**2. Security Implementation (DevSecOps)**
Installed and configured SonarQube to perform static code analysis for security vulnerabilities.
Scanned application dependencies using OWASP Dependency-Check.
Used Trivy for container image scanning to identify vulnerabilities.
Implemented SonarQube Quality Gate in Jenkins pipeline to enforce security standards.

**3. CI/CD Pipeline Automation (Jenkins)**
Installed Jenkins on the AWS EC2 instance.
Configured a Jenkins declarative pipeline for automating build, security scans, and deployment.
Integrated Docker plugins, Node.js, and Java (JDK 17) in Jenkins for seamless execution.
Implemented DockerHub authentication in Jenkins to push Docker images securely.
Configured Jenkins to trigger builds automatically on code commits.

**4. Monitoring & Logging (Prometheus & Grafana)**
Installed and configured Prometheus to monitor application performance.
Deployed Node Exporter for collecting system metrics.
Integrated Grafana to visualize logs and metrics from Prometheus.
Configured Prometheus monitoring for Jenkins CI/CD pipeline performance tracking.

**5. Kubernetes Deployment & Scaling**
Created a Kubernetes cluster with node groups for auto-scaling.
Deployed application containers in Kubernetes Pods for high availability.
Configured Helm to install Prometheus and monitor Kubernetes nodes.

**6. Notification & Alerts**
Set up email notifications in Jenkins for build failures.
Configured Prometheus AlertManager to notify on system anomalies.

**Key Achievements**
✅ Successfully deployed a Netflix Clone on AWS with an automated CI/CD pipeline.

✅ Implemented shift-left security by integrating SonarQube, Trivy, and OWASP Dependency-Check.

✅ Achieved 100% automation for build, security, and deployment using Jenkins.

✅ Improved system observability with real-time monitoring dashboards using Grafana.

✅ Ensured secure Docker image storage by integrating DockerHub authentication.

✅ Scaled application seamlessly using Kubernetes with Node Groups.


**Technical Stack & Tools**
**Cloud Platforms:** AWS (EC2, S3, IAM)
**CI/CD:** Jenkins, Git, GitHub Webhooks
**Containerization:** Docker, DockerHub, Kubernetes, Helm
**Security Tools:** SonarQube, OWASP Dependency-Check, Trivy
**Monitoring & Logging:** Prometheus, Grafana, Node Exporter
**Programming & Scripting:** Shell Scripting, JavaScript, Node.js
**Database & APIs:** TMDB API

**Jenkins passed :-**

![Screenshot 2025-02-27 213928](https://github.com/user-attachments/assets/16fdd1af-06b5-400f-b8bc-2dae615aadbf)
![Screenshot 2025-02-27 214128](https://github.com/user-attachments/assets/daa6fed4-94aa-4205-903f-4cba77c6eba7)


**SonarQube passed :-**

![Screenshot 2025-02-27 214858](https://github.com/user-attachments/assets/7a863405-0bf4-4f4b-a9bd-60d318a368c9)



**ARGOCD SYNCED :-**

![Screenshot 2025-02-27 214731](https://github.com/user-attachments/assets/eb5b6293-d324-4b79-837c-51f120261bbf)



**PROMETHEUS :-**

![Screenshot 2025-02-27 215224](https://github.com/user-attachments/assets/cb17cb69-436e-46c5-a76b-f6cb27f1f14a)

**NETFLIX PAGE :-**

![Screenshot 2025-02-27 215057](https://github.com/user-attachments/assets/864b3221-22b8-407a-a333-35aebcbecd4b)

