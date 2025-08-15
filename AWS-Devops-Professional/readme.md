## **Domain 1 – SDLC Automation (22%)**

**Goal:** Build, manage, and optimize CI/CD systems.

1. **Multi-Stage CI/CD Pipeline for Microservices**

   * CodePipeline with separate stages for build, test, and deploy.
   * Deploy to ECS (Blue/Green) and Lambda.
   * Use CodeArtifact for dependency management.

2. **Automated Test Orchestration in CI/CD**

   * Integrate unit, integration, and load testing in pipelines.
   * Add security scans (Inspector, Snyk) that fail the build on critical findings.

3. **GitOps Deployment to EKS**

   * Use ArgoCD + CodePipeline for continuous delivery to Kubernetes.
   * Store manifests in Git, auto-sync changes to cluster.

4. **Serverless CI/CD for Lambda Functions**

   * Build Lambda with SAM in CodeBuild.
   * Use API Gateway stage variables for multiple environments.

---

## **Domain 2 – Configuration Management & IaC (17%)**

**Goal:** Manage resources at scale with IaC and automation.

5. **AWS Control Tower + StackSets Multi-Account Baseline**

   * Deploy IAM guardrails, GuardDuty, and Config rules to all accounts.

6. **Reusable CDK Constructs for Standardized App Deployments**

   * Create a CDK module for ECS + RDS + ALB deployments.

7. **Immutable Infrastructure with Golden AMIs**

   * Build hardened AMIs with EC2 Image Builder.
   * Distribute to multiple accounts via Resource Access Manager.

8. **Parameter-Driven Environment Provisioning**

   * Use CloudFormation with SSM Parameter Store for environment configs.
   * Deploy identical stacks to dev, staging, and prod.

---

## **Domain 3 – Resilient Cloud Solutions (15%)**

**Goal:** Architect for fault tolerance and disaster recovery.

9. **Multi-Region Active-Active Web Application**

   * Route 53 latency routing to two Regions.
   * DynamoDB global tables, S3 cross-Region replication.

10. **Active-Passive Disaster Recovery Drill**

    * Automate failover from primary to standby Region.
    * Measure RTO and RPO with AWS Resilience Hub.

11. **Auto Scaling with Predictive Policies**

    * Deploy an app with EC2 Auto Scaling + predictive scaling policies.
    * Use CloudWatch metrics to trigger scale events.

12. **EventBridge-Based Failover Trigger**

    * Fail over ALB targets on specific health-check failures.
    * Trigger via EventBridge rules + Lambda.

---

## **Domain 4 – Monitoring & Logging (15%)**

**Goal:** Implement observability, traceability, and central logging.

13. **Centralized Logging Across Accounts**

    * Aggregate CloudWatch Logs into a single account S3 bucket.
    * Query logs with Athena.

14. **Distributed Tracing with AWS X-Ray**

    * Instrument microservices with X-Ray.
    * View traces in the X-Ray console and filter by latency.

15. **Grafana + CloudWatch Metrics Dashboard**

    * Deploy Grafana on ECS.
    * Integrate CloudWatch and create real-time dashboards.

16. **CloudWatch Logs Insights for Incident Analysis**

    * Build saved queries for specific error patterns.
    * Schedule daily exports to S3.

---

## **Domain 5 – Incident & Event Response (14%)**

**Goal:** Detect, respond, and recover from incidents quickly.

17. **Auto-Remediation for Public S3 Buckets**

    * EventBridge rule detects public bucket ACLs.
    * Lambda auto-removes public access.

18. **GuardDuty Threat Response Automation**

    * GuardDuty finding triggers Lambda that isolates EC2 instances.
    * Notify security team via SNS.

---

## **Domain 6 – Security & Compliance (17%)**

**Goal:** Automate security enforcement and auditing.

19. **Security Hub + Step Functions Remediation Workflow**

    * Security Hub sends findings to Step Functions.
    * Step Functions runs Lambda functions to remediate issues.

20. **IAM Zero-Trust Role Deployment**

    * Implement permission boundaries and service control policies.
    * Enforce MFA and session tagging.

---

---

Do you want me to prepare that full **multi-project AWS CDK Go repo** for you? That would make this roadmap directly executable.
