## **📍 Domain 1: SDLC Automation (22%)**

**Exam Tasks:** Design, implement, and manage CI/CD pipelines; automate testing and deployment; integrate security into pipelines.

| Project                                             | Mapped Exam Task(s)                                                                                                      | Skills Covered                                                                        |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------- |
| **1. Multi-Stage CI/CD Pipeline for Microservices** | *Design and implement CI/CD pipelines; integrate automated build, test, deploy; implement multi-environment deployments* | CodePipeline, CodeBuild, CodeDeploy, ECS blue/green, Lambda deployments, CodeArtifact |
| **2. Automated Test Orchestration in CI/CD**        | *Implement automated testing; integrate quality gates into pipelines*                                                    | Unit, integration, load testing; security scans; pipeline approvals                   |
| **3. GitOps Deployment to EKS**                     | *Implement continuous delivery using container orchestration services*                                                   | ArgoCD, EKS, Git-based deployment automation                                          |
| **4. Serverless CI/CD for Lambda Functions**        | *Automate serverless application deployments*                                                                            | AWS SAM, API Gateway stage variables, environment-based deploys                       |

---

## **📍 Domain 2: Configuration Management & Infrastructure as Code (17%)**

**Exam Tasks:** Manage infrastructure using IaC; manage configurations; implement repeatable deployments.

| Project                                                         | Mapped Exam Task(s)                                            | Skills Covered                                          |
| --------------------------------------------------------------- | -------------------------------------------------------------- | ------------------------------------------------------- |
| **5. AWS Control Tower + StackSets Multi-Account Baseline**     | *Implement and manage multi-account infrastructure automation* | Control Tower, CloudFormation StackSets, IAM guardrails |
| **6. Reusable CDK Constructs for Standardized App Deployments** | *Implement reusable and modular IaC patterns*                  | Go AWS CDK constructs, ECS + RDS + ALB                  |
| **7. Immutable Infrastructure with Golden AMIs**                | *Implement immutable infrastructure patterns*                  | EC2 Image Builder, AMI distribution, RAM                |
| **8. Parameter-Driven Environment Provisioning**                | *Use parameterized templates for multiple environments*        | CloudFormation, SSM Parameter Store                     |

---

## **📍 Domain 3: Resilient Cloud Solutions (15%)**

**Exam Tasks:** Design and implement highly available, fault-tolerant, and disaster recovery solutions.

| Project                                           | Mapped Exam Task(s)                                                             | Skills Covered                                           |
| ------------------------------------------------- | ------------------------------------------------------------------------------- | -------------------------------------------------------- |
| **9. Multi-Region Active-Active Web Application** | *Implement multi-Region architectures with data replication and global routing* | Route 53 latency routing, DynamoDB global tables, S3 CRR |
| **10. Active-Passive Disaster Recovery Drill**    | *Test and validate disaster recovery strategies*                                | Pilot Light, Warm Standby, Resilience Hub                |
| **11. Auto Scaling with Predictive Policies**     | *Implement scaling strategies to meet demand*                                   | EC2 Auto Scaling, predictive scaling, CloudWatch metrics |
| **12. EventBridge-Based Failover Trigger**        | *Automate failover in response to events*                                       | EventBridge, Lambda, ALB failover                        |

---

## **📍 Domain 4: Monitoring & Logging (15%)**

**Exam Tasks:** Implement monitoring, logging, and observability solutions; automate operational responses.

| Project                                                | Mapped Exam Task(s)                                            | Skills Covered                                     |
| ------------------------------------------------------ | -------------------------------------------------------------- | -------------------------------------------------- |
| **13. Centralized Logging Across Accounts**            | *Aggregate and analyze logs from multiple sources*             | CloudWatch Logs, S3 log storage, Athena queries    |
| **14. Distributed Tracing with AWS X-Ray**             | *Implement distributed tracing to identify performance issues* | X-Ray SDK integration                              |
| **15. Grafana + CloudWatch Metrics Dashboard**         | *Create dashboards for operational visibility*                 | Grafana ECS deploy, CloudWatch metrics integration |
| **16. CloudWatch Logs Insights for Incident Analysis** | *Analyze and query logs to diagnose incidents*                 | CloudWatch Logs Insights, scheduled exports        |

---

## **📍 Domain 5: Incident & Event Response (14%)**

**Exam Tasks:** Implement automated incident detection and response; remediate operational issues.

| Project                                        | Mapped Exam Task(s)                                          | Skills Covered                          |
| ---------------------------------------------- | ------------------------------------------------------------ | --------------------------------------- |
| **17. Auto-Remediation for Public S3 Buckets** | *Detect and remediate insecure configurations automatically* | EventBridge, Lambda, S3 ACL management  |
| **18. GuardDuty Threat Response Automation**   | *Automate response to security threats*                      | GuardDuty, Lambda isolation, SNS alerts |

---

## **📍 Domain 6: Security & Compliance (17%)**

**Exam Tasks:** Implement security controls, compliance automation, and identity management.

| Project                                                    | Mapped Exam Task(s)                              | Skills Covered                                   |
| ---------------------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| **19. Security Hub + Step Functions Remediation Workflow** | *Aggregate and remediate security findings*      | Security Hub, Step Functions, Lambda automation  |
| **20. IAM Zero-Trust Role Deployment**                     | *Enforce least privilege and conditional access* | IAM permission boundaries, SCPs, MFA enforcement |

---

