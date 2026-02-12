# 🚀 Automated Static Website Deployment on AWS using CI/CD

This project demonstrates how to deploy and manage a static website on **Amazon S3** using a fully automated **CI/CD pipeline with GitHub Actions**. Every change pushed to the main branch is automatically deployed to AWS, ensuring fast, secure, and error-free updates.

This project was completed as part of the **Cloud Computing AWS training by CipherSchools** and submitted to **Lovely Professional University**.

---

## 📌 Project Overview

Manual deployment of static websites is time-consuming and prone to errors. This project solves that by implementing:

- Automated deployment using GitHub Actions  
- Static website hosting on Amazon S3  
- Secure access using AWS IAM and GitHub Secrets  
- Best practices for cloud security and automation  

---

## 🎯 Objectives

- Host a static website on Amazon S3  
- Automate deployment using CI/CD  
- Apply AWS security best practices  
- Eliminate manual file uploads  
- Create a scalable foundation for future upgrades  

---

## 🛠️ Technologies & Tools Used

- **Amazon S3** – Static website hosting  
- **AWS IAM** – Access control & security  
- **GitHub Actions** – CI/CD automation  
- **AWS CLI** – File synchronization  
- **GitHub Secrets** – Secure credential storage  
- **GitHub** – Version control  

---

## ⚙️ Architecture & Workflow

1. Static website files are stored in a GitHub repository  
2. On every push to the `main` branch:  
   - GitHub Actions workflow is triggered  
   - AWS credentials are loaded securely from GitHub Secrets  
   - AWS CLI syncs files to the S3 bucket  
3. The updated website is instantly live on S3  

---

## 🔐 Security Best Practices

- No hardcoded AWS credentials  
- Credentials stored in GitHub Secrets  
- IAM user follows Principle of Least Privilege  
- Public access limited to read-only for website files  

---

## 🧪 Testing & Validation

- Website accessibility verified in browser  
- Automated deployment verified on every commit  
- File updates confirmed in S3  
- Public access tested from multiple devices  

---

## 📊 Key Results

- Deployment time reduced by over 80%  
- Fully automated & repeatable process  
- Improved security and reduced human error  
- Faster and more reliable updates  

---

## ⚠️ Current Limitations

- HTTP only (No HTTPS yet)  
- No CDN (CloudFront not configured)  
- Static websites only (No backend/server-side logic)  
- No automated monitoring or alerts  

---

## 🔮 Future Enhancements

- Enable HTTPS using AWS Certificate Manager  
- Add CloudFront CDN for global performance  
- Configure custom domain using Route 53  
- Add automated testing in CI/CD  
- Add monitoring & alerts using CloudWatch  
- Manage infrastructure using Terraform/CloudFormation  

---

## 📂 Project Link

- GitHub Repository:  
  https://github.com/AnmolAhir/CI-CD-using-AWS  

---

## 👨‍💻 Author

**Anmol Ahir**  
B.Tech – Computer Science & Engineering  
Lovely Professional University  
Cloud Computing AWS Training – CipherSchools  
