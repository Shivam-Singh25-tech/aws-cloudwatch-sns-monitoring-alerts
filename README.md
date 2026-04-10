# 🚨 AWS CloudWatch + SNS Monitoring & Alerting System

This project demonstrates a real-time cloud monitoring and alerting system built using AWS CloudWatch and Amazon SNS. It continuously monitors EC2 instance performance and automatically sends alerts when predefined thresholds are exceeded.

---

## 📌 Project Overview

* Monitor EC2 instance metrics in real-time
* Trigger alerts based on thresholds
* Send notifications via Amazon SNS (Email alerts)
* Improve system reliability and uptime

---

## 🏗️ Architecture

EC2 Instance → CloudWatch Metrics → CloudWatch Alarm → SNS → Email Notification

---

## ⚙️ AWS Services Used

* Amazon EC2
* Amazon CloudWatch
* Amazon SNS
* AWS IAM
* CloudWatch Agent

---

## 📊 Monitoring Metrics

* CPU Utilization
* Memory Usage
* Disk Usage
* EC2 Instance Health

---

## 🚨 Alerting Mechanism

1. CloudWatch collects EC2 metrics
2. Alarm is configured (e.g., CPU > 70%)
3. When threshold is crossed → Alarm triggers
4. SNS sends email notification

---

## 📸 Project Screenshots

### 🖥️ EC2 Instance Running

<p align="center">
  <img src="Instance.png" width="600"/>
</p>

### 📊 CloudWatch Alarm Trigger

<p align="center">
  <img src="Message.png" width="600"/>
</p>

### 📩 SNS Topic / Email Notification

<p align="center">
  <img src="Topic.png" width="600"/>
</p>

---

## 🔐 Security Features

* IAM roles for secure access
* No hardcoded credentials
* Controlled alerting permissions

---

## 🚀 How It Works

1. EC2 instance runs application
2. CloudWatch monitors performance
3. Alarm detects abnormal behavior
4. SNS sends alert to user

---

## 📌 Future Improvements

* Add Slack / SMS alerts
* Use Auto Scaling with alarms
* Integrate with AWS Lambda

---

## 👨‍💻 Author

Shivam Kumar
Cloud & DevOps Learner ☁️
