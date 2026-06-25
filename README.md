# 🌐 AWS Monitoring System – CloudWatch + SNS + Dashboards

## 🚀 Project Overview
This project demonstrates the implementation of a cloud monitoring and alerting system using AWS services.

The system continuously monitors AWS resources such as EC2 instances and automatically sends notifications whenever a predefined threshold is crossed. Amazon CloudWatch collects metrics and creates alarms, Amazon SNS sends email notifications, and CloudWatch Dashboards provide a centralized view of system performance and health.

---

## 🧰 Tech Stack
- GitHub
- Amazon EC2
- Amazon CloudWatch
- Amazon SNS (Simple Notification Service)
- CloudWatch Dashboards
- AWS IAM
- Linux (Amazon Linux 2023)
- SSH

---

## 🏗️ Architecture

EC2 Instance → Amazon CloudWatch Metrics → CloudWatch Alarm → Amazon SNS → Email Notification

CloudWatch Dashboard ← Real-Time Metrics from EC2 Instance

The EC2 instance sends performance metrics to CloudWatch. When CPU utilization exceeds the configured threshold, CloudWatch triggers an alarm and sends an email notification through SNS. The dashboard provides real-time monitoring of all important metrics and alarm states.

---

## ✨ Features

- Real-time monitoring of AWS resources
- Automated CPU utilization alerts
- Email notifications using Amazon SNS
- Centralized monitoring dashboard
- Cloud resource health tracking
- Performance metrics visualization
- Alarm state monitoring (OK, IN ALARM)
- Scalable and serverless monitoring solution
- Secure access management using AWS IAM
- Proactive infrastructure monitoring

---

## 📸 Screenshots

<img width="1918" height="980" alt="Screenshot 2026-06-25 125322" src="https://github.com/user-attachments/assets/8a2a68c3-8a25-4507-8771-ce6a89c538e9" />
<img width="1918" height="977" alt="Screenshot 2026-06-25 125841" src="https://github.com/user-attachments/assets/d7e73211-6329-4c93-82f4-3d0c717e2927" />
<img width="1917" height="987" alt="Screenshot 2026-06-25 125831" src="https://github.com/user-attachments/assets/6b9ad3bf-4dc0-4813-9448-189eee78d770" />

---

## 🧠 What I Learned

- Monitoring AWS resources using Amazon CloudWatch
- Creating CloudWatch alarms based on performance metrics
- Configuring SNS for automated email notifications
- Building dashboards for real-time infrastructure monitoring
- Understanding observability and proactive monitoring practices
- Managing IAM permissions for AWS services
- Generating and testing alerts using EC2 workloads
- Implementing cloud monitoring best practices

---

## ⚙️ Deployment Steps

1. Launch an Amazon EC2 instance.
2. Create an SNS topic and subscribe an email address.
3. Confirm the email subscription.
4. Create a CloudWatch alarm for CPU utilization.
5. Configure the alarm to send notifications through SNS.
6. Create a CloudWatch Dashboard and add monitoring widgets.
7. Generate CPU load on the EC2 instance to test the alarm.
8. Verify email notifications and dashboard metrics.

---

## ⚠️ Note

- Confirm your SNS email subscription before testing alarms.
- Ensure CloudWatch alarm thresholds are configured correctly.
- Stop or terminate unused AWS resources to avoid unexpected charges.
- Use AWS Free Tier resources responsibly.

---

## 💼 Resume Highlight

Designed and implemented an AWS Monitoring System using Amazon CloudWatch, SNS, and Dashboards. Configured real-time monitoring, automated email alerts, and performance visualization for AWS resources, enabling proactive infrastructure management and improving system reliability through cloud-native monitoring solutions.
