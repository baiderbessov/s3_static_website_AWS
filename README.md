# AWS S3 Static Website with Terraform

Provision a static website on AWS using **Terraform** and host it via **Amazon S3**.

This project demonstrates a simple, cost-effective, and reproducible approach to deploying static web content using Infrastructure as Code (IaC).

---

## 🚀 Overview

This repository contains Terraform configuration to:

- Create an S3 bucket for static website hosting
- Configure public access and permissions
- Upload website assets (HTML, image)
- Enable static website hosting
- Output the website endpoint

---

## 🧱 Architecture

User → S3 Static Website Hosting  
        ↓  
   Public Endpoint  

---

## 📦 Features

- Infrastructure as Code with Terraform
- Fully automated S3 bucket provisioning
- Static website hosting (index + error pages)
- Automatic upload of website files
- Public access configuration

---

## 📁 Project Structure
.
├── main.tf          # S3 bucket + objects + website config
├── provider.tf      # AWS provider configuration
├── variables.tf     # Input variables
├── outputs.tf       # Outputs (website URL)
├── index.html       # Main website page
├── error.html       # Error page
├── profile.png      # Static asset
└── .gitignore

---

## ⚙️ Requirements

- Terraform >= 1.0
- AWS Account
- AWS CLI configured

```bash
aws configure
