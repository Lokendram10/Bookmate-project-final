# 📚 BookMate – DevSecOps Project

BookMate is a  **HTML & CSS-based website** built as a learning project.  
In this project, I containerized the application, set up CI/CD pipelines, and integrated **DevSecOps tools** like **SonarQube, Trivy, and OWASP Dependency Check** using **Jenkins**.

---

## 🚀 Project Features
- Static **HTML & CSS website** (all in a single file).
- **Dockerized application** using Dockerfile.
- **Docker Compose** for multi-service management.
- **Jenkins CI/CD pipeline** for build, test, and deploy.
- **SonarQube** integration for code quality analysis.
- **Trivy** for container image vulnerability scanning.
- **OWASP Dependency Check** for dependency vulnerabilities.
- Automated deployment with **`docker-compose up -d --build`**.

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS  
- **DevOps Tools:** Jenkins, Docker, Docker Compose  
- **DevSecOps Tools:** SonarQube, Trivy, OWASP Dependency Check  
- **Cloud Platform:** AWS EC2 (for hosting Jenkins, SonarQube, etc.)  
- **Version Control:** Git, GitHub  

---

## 📂 Project Structure
```
BookMate/
│── index.html          # HTML & CSS website
│── Dockerfile          # Containerizing BookMate
│── docker-compose.yml  # Managing multi-service deployment
│── Jenkinsfile         # CI/CD pipeline
```

---

## ⚙️ CI/CD Pipeline Flow
1. **Clone the repository** from GitHub.  
2. **Build Docker image** from `Dockerfile`.  
3. **Run SonarQube analysis** for code quality.  
4. **Scan Docker image with Trivy** for vulnerabilities.  
5. **Run OWASP Dependency Check** on project dependencies.  
6. **Deploy application** using Docker Compose.  

---

## 📸 Screenshots
 <img width="1920" height="1031" alt="Screenshot (133)" src="https://github.com/user-attachments/assets/32cf8749-3d79-44bf-a286-fb5c0f42d37c" />
 <br/>
 <br/>
 <img width="1920" height="1038" alt="Screenshot (135)" src="https://github.com/user-attachments/assets/c97c7da4-0089-4a76-924a-cbeca797bc46" />
 <br/>
 <br/>
 <img width="1920" height="1031" alt="Screenshot (136)" src="https://github.com/user-attachments/assets/f12d7777-34d8-49d6-9535-e71bf7b7cb8f" />
 <br/>
 <br/>
 <img width="1920" height="1035" alt="Screenshot (137)" src="https://github.com/user-attachments/assets/67c67af8-8a29-4e90-b878-47339c4bd06b" /> 
 <br/>
 <br/>
 <img width="1920" height="1042" alt="Screenshot (132)" src="https://github.com/user-attachments/assets/14511f33-7d7f-4fe0-bcae-bdf2ea6dc9ac" />
 <br/>
 <br/>





---

## 📽️ Demo Video
 YouTube: https://youtu.be/_GGMj5SidwI?si=q0ogRj72-A0eXceL

---

## 📌 How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/Lokendram10/Bookmate-project-final
   cd BookMate
   ```
2. Build and run with Docker Compose:
   ```bash
   docker-compose up -d --build
   ```
3. Open in browser:  
   ```
   http://localhost:80
   ```

---

## ✨ Future Improvements
- Add backend integration.  
- Enhance website UI with JavaScript.  
- Deploy on Kubernetes (EKS).  

---

## 👨‍💻 Author
**Lokendra Dhote**  
- 🌐 [LinkedIn](https://www.linkedin.com/in/lokendra-dhote-b47152257)  
- 🐙 [GitHub](https://github.com/Lokendram10/Bookmate-project-final)  

---

## 📜 License
This project is for **educational purposes only**.
