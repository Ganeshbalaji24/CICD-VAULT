# 🔐 Vault + Jenkins (Local Secure CI/CD)

## 📌 Project Overview

This project demonstrates **secure secrets management** using **HashiCorp Vault running locally on a Windows PC**, integrated with **Jenkins running on Windows**.

The goal is to show how a CI/CD pipeline can **securely fetch secrets at runtime** without hardcoding credentials or storing secrets in source code.

This is a **fully local setup**, designed to be:
- Simple
- Interview-ready
- GitHub-friendly
- Easy to explain and reproduce

---

## 🎯 What This Project Solves

❌ Hardcoded secrets in pipelines  
❌ Secrets stored in Git repositories  
❌ Insecure CI/CD configurations  

✅ Centralized secrets in Vault  
✅ Least-privilege access using policies  
✅ Secure secret retrieval during pipeline execution  

---

## 🏗️ High-Level Architecture

