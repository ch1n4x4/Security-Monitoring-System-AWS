# SECURITY MONITORING SYSTEM

## Objective

The implementation focuses on comparing two unique monitoring systems to
know the best fit, considering our goals.
The goal of this system is to monitor the Secrets Manager service on the AWS
cloud infrastructure where database credentials are stored, notify the security
team when a breach occurs and potentially block attacker from performing
further actions after accessing the “Secret”

### Skills Learned

- Cloud Security Infrastructure & Monitoring
- Automated Incident Response ("The Kill-Switch")
- Security Analysis & Technical Auditing
- Governance, Risk, and Compliance (GRC)
- Technical Communication

### Tools Used

- AWS
- AWS Secrets Manager
- Amazon EventBridge
- AWS CloudTrail
- Amazon CloudWatch (including Alarms and Metric Filters)
- AWS Lambda Amazon SNS (Simple Notification Service)
- AWS Identity and Access Management (IAM)
- AWS Command Line Interface (CLI)
- AWS Systems Manager (SSM)
- AWS CloudShell

### Process

- Preparation and Goal SettingDefine Objective: The primary goal was to monitor the AWS Secrets Manager service, notify the security team of breaches, and block attackers from further actions.Identify Target: The system specifically targeted the protection of "Production Database Credentials".
- Implementation of Detection Flows
- Notification and Response Setup
- Simulation and TestingExecution
- Results and Proof of Remediation
- Analysis and Evaluation
  
### Outcome 

The outcome of the project was a successful implementation of an automated security system that both detected and neutralized a credential breach in real-time.

## Steps
<a href = "https://github.com/ch1n4x4/Security-Monitoring-System-AWS/blob/main/Cloud_security_monitoring.pdf">Secure Architecture</a>
