Got it — your exam guide lays out **4 domains**, each with specific tasks.
I’ll turn *every task* into a **realistic AWS hands-on project use case** so you can practice the full SAP-C02 skill set in the lab.

---

## **Hands-On AWS Projects for SAP-C02 Preparation**

### **Domain 1 – Design Solutions for Organizational Complexity** (26%)

1. **Multi-VPC Hybrid Networking**

   * Build 3 VPCs across 2 Regions with **VPC peering**, **Transit Gateway**, and hybrid connectivity using **AWS Site-to-Site VPN** + **Direct Connect**.
   * Integrate with **on-prem DNS** using **Route 53 Resolver**.
   * Add **VPC Flow Logs** + **CloudWatch Logs Insights** for traffic analysis.

2. **Centralized Security Hub + GuardDuty**

   * Deploy a multi-account setup with **AWS Organizations**.
   * Enable **AWS Security Hub**, **GuardDuty**, **CloudTrail**, and **IAM Access Analyzer** organization-wide.
   * Create a **central security account** for aggregated findings.

3. **Resilient Multi-Site DR Architecture**

   * Deploy a **warm standby** workload in a secondary region using **Elastic Disaster Recovery**.
   * Implement **RTO/RPO-based failover** with **Route 53 health checks**.
   * Test failover/failback.

4. **Multi-Account Governance with Control Tower**

   * Use **AWS Control Tower** to set up a landing zone.
   * Enable **Service Control Policies (SCPs)** and **centralized logging** to S3.
   * Implement **Resource Access Manager (RAM)** for shared services.

5. **Cost Visibility Dashboard**

   * Create an **AWS Cost Explorer** + **Budgets** setup per OU.
   * Implement **tagging strategy** for cost allocation.
   * Simulate RI & Savings Plan recommendations with **Compute Optimizer**.

---

### **Domain 2 – Design for New Solutions** (29%)

6. **Blue/Green Deployment with CodePipeline**

   * Create **CloudFormation** IaC for an app.
   * Implement **CodePipeline** + **CodeDeploy** blue/green deployment to **ECS Fargate**.
   * Test rollback.

7. **Active-Active Multi-Region Web App**

   * Deploy a web app in **2 Regions** using **Global Accelerator** or **Route 53 latency-based routing**.
   * Backend database: **Aurora Global Database** with write forwarding.
   * Implement **automated DR testing**.

8. **Web Security at Scale**

   * Deploy an API on **API Gateway** + **Lambda**.
   * Protect with **AWS WAF**, **Shield Advanced**, **Cognito** auth.
   * Use **VPC endpoints** for secure service calls.

9. **Highly Available Event-Driven System**

   * Build **SQS → Lambda → DynamoDB** pipeline.
   * Add **DLQ** and **Step Functions** for retries.
   * Implement **multi-AZ failover** for DynamoDB global tables.

10. **High-Performance Caching Layer**

    * Deploy **ElastiCache Redis** for session storage.
    * Benchmark EC2 app with/without cache.
    * Implement **CloudFront** for static content.

---

### **Domain 3 – Continuous Improvement for Existing Solutions** (25%)

11. **Self-Healing Architecture**

    * Set **CloudWatch alarms** that trigger **SSM Automation Documents** to restart EC2 or failover RDS.
    * Add **EventBridge rules** for proactive remediation.

12. **Secrets Rotation + Compliance**

    * Store DB creds in **Secrets Manager**.
    * Enable automatic rotation with Lambda.
    * Audit access using **CloudTrail** + **Config rules**.

13. **Global App Acceleration**

    * Deploy an app in one Region, use **AWS Global Accelerator** to improve latency.
    * Compare performance metrics pre/post acceleration.

14. **Resilience Testing**

    * Simulate failures (kill EC2, stop RDS instance).
    * Measure MTTR and apply architecture changes (ASG scaling, Multi-AZ RDS).

15. **Ongoing Cost Optimization**

    * Enable **AWS Compute Optimizer** + **S3 Storage Lens**.
    * Identify underutilized EC2/EBS/S3 resources and remediate.

---

### **Domain 4 – Accelerate Workload Migration & Modernization** (20%)

16. **Application Migration Assessment**

    * Use **Migration Hub** to assess on-prem workloads.
    * Categorize with the **7Rs migration strategy**.
    * Produce TCO estimates.

17. **Database Migration**

    * Migrate an on-prem MySQL to **Amazon Aurora** using **AWS DMS** + **SCT**.
    * Test data validation and cutover.

18. **Container Modernization**

    * Migrate a monolithic app from EC2 to **ECS Fargate** or **EKS**.
    * Use **ECR** for image storage.

19. **Serverless Refactor**

    * Refactor a scheduled batch job to **Lambda + Step Functions**.
    * Use **S3 events** to trigger processing.

20. **Event-Driven Microservices**

    * Break down a monolith into services communicating via **EventBridge**.
    * Use **DynamoDB** for persistence and **SNS/SQS** for async processing.

---
