# Netflix Clone Deployment with Jenkins - DevSecOps Project

This project demonstrates the deployment of a Netflix clone application using Jenkins on AWS EC2, incorporating DevSecOps practices.

<img src="flow.png" width=850 height=500>
<img src="Screens1.png" width=850 height=500>
<img src="Screens2.png" width=850 height=500>



## Features

- **Phase 1: Initial Setup and Deployment**
  - Launch EC2 instance and clone the code repository
  - Install Docker and run the app using a container
  - Obtain TMDB API key for accessing movie data
 
<img src="aws.png" width=850 height=350>

- **Phase 2: Security**
  - Install SonarQube and Trivy for vulnerability scanning
  - Integrate SonarQube with CI/CD pipeline
  - Configure SonarQube to analyze code for quality and security
 
<img src="sonarqube.png" width=850 height=500>

- **Phase 3: CI/CD Setup**
  - Install Jenkins for automation and necessary plugins
  - Configure Java, Node.js, and SonarQube in Jenkins
  - Create CI/CD pipeline for automated deployment
 
<img src="Jenkins.png" width=850 height=500>
<img src="Docker.png" width=850 height=500>

- **Phase 4: Monitoring**
  - Install Prometheus and Grafana for monitoring
  - Configure Prometheus to scrape metrics from Node Exporter and Jenkins
  - Set up Grafana to visualize metrics
 
<img src="Prometheus.png" width=850 height=500>
<img src="Grafana.png" width=850 height=500>

- **Phase 5: Notification**
  - Implement email notifications in Jenkins or other notification mechanisms
 
<img src="Email.png" width=850 height=500>

- **Phase 6: Kubernetes**
  - Create Kubernetes cluster with node groups
  - Monitor Kubernetes with Prometheus
  - Install Node Exporter using Helm
  - Add a job to scrape metrics in Prometheus configuration
<img src="Argo.png" width=850 height=500>
