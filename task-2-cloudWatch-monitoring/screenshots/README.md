Task 2: Cloud Monitoring with AWS CloudWatch

✅ Objective:
Monitor a cloud-based application (EC2 instance) using AWS CloudWatch.

---

🖥️ Monitored Instance:
- Type: t2.micro
- AMI: Amazon Linux 2
- Installed App: Apache HTTP Server

---

📊 Metrics Monitored:
- CPUUtilization

---

🚨 Alarm Setup:
- Metric: CPUUtilization
- Condition: Greater than 30% for 5 minutes
- Action: Alarm created (no notification topic)

---

📋 Dashboard:
- Dashboard Name: EC2-Monitoring-Dashboard
- Widgets: CPUUtilization graph

---

📸 Screenshots:
See `/screenshots/` folder for all images.

---

✅ Conclusion:
Task 2 is successfully completed using AWS CloudWatch and EC2.

