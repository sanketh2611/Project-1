# Project-1
Build and Deployment activities via command line interface

# Overview  
This project demonstrates a complete Build & Deployment workflow using CLI with core DevOps tools:  
- **GitHub** → Source code  
- **Maven** → Build & packaging  
- **SonarQube** → Code quality analysis  
- **JFrog Artifactory** → Artifact repository  
- **Apache Tomcat** → Application server  

---

# Tech Stack  
- **Java version**: 21  
- **Maven version**: 3.9.11  
- **SonarQube**: 25.4.0  
- **JFrog Artifactory**: 7.17.7  
- **Apache Tomcat**: 11.0.0  
- **Git**: 2.43  

---

# Core Command  
Single Maven command for build, quality check, artifact upload and deployment:  

**mvn clean install sonar:sonar deploy tomcat7:deploy**
