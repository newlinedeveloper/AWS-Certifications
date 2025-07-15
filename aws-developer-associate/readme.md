## 🧭 AWS Developer Associate DVA-C02: Exam Domains & Syllabus

### 📌 **Domain 1: Development with AWS Services** (32%)

#### ✅ Key Topics:

* **Architectural patterns**: Event-driven, microservices, monolithic, orchestration, choreography, fanout
* **Stateful vs Stateless**, **tightly vs loosely coupled components**
* **Fault-tolerant design**: retries, exponential backoff, DLQs
* **Asynchronous vs synchronous**
* **Working with AWS SDKs, APIs**, unit testing with AWS SAM
* **Lambda Functions**: configuration, lifecycle, VPC access, event sources
* **Data stores**: DynamoDB, RDS, S3

  * Partition keys, indexing, query vs scan, TTL, lifecycle rules
* **Data streaming, caching** (ElastiCache)

#### 🎯 Skills to Practice:

* Build Lambda + API Gateway + DynamoDB app
* Use retries, error handling, and DLQs
* Integrate messaging: SQS, SNS
* Handle JSON, serialization, and DB storage

---

### 📌 **Domain 2: Security** (26%)

#### ✅ Key Topics:

* **Authentication & Authorization**

  * IAM roles, policies (inline, managed), RBAC
  * Cognito (user pools vs identity pools), JWT, OIDC
  * STS (assume role, temporary credentials)
* **Encryption**

  * KMS (CMK, key rotation, SSE, envelope encryption)
  * Encryption at rest/in transit, client vs server-side
  * ACM & cert management
* **Secrets Management**

  * AWS Secrets Manager, Parameter Store
  * Environment variables, securing credentials

#### 🎯 Skills to Practice:

* Secure Lambda using IAM roles & policies
* Use KMS with S3, Lambda
* Implement secrets in code using Secrets Manager

---

### 📌 **Domain 3: Deployment** (24%)

#### ✅ Key Topics:

* **Preparing deployment artifacts**

  * SAM, CloudFormation, container images, AppConfig
  * Lambda layers, dependencies, env variables
* **CI/CD & Automation**

  * CodePipeline, CodeBuild, CodeDeploy
  * Git-based workflows, canary/blue-green/rolling strategies
* **Testing**

  * Unit/mocking/integration tests
  * API Gateway stages, aliases, deployment environments

#### 🎯 Skills to Practice:

* Deploy a serverless app using SAM or CDK
* Use CodePipeline + CodeDeploy for Lambda
* Deploy API Gateway in stages using aliases

---

### 📌 **Domain 4: Troubleshooting & Optimization** (18%)

#### ✅ Key Topics:

* **Observability**

  * CloudWatch (logs, metrics, alarms, Insights)
  * X-Ray (traces, service maps)
  * Structured logging, custom metrics
* **Debugging & Root Cause**

  * Analyzing logs, exceptions, error codes (e.g., 403, 429)
* **Optimization**

  * Memory tuning in Lambda
  * Concurrency, caching, filtering (SQS/SNS)

#### 🎯 Skills to Practice:

* Use CloudWatch Logs Insights to find issues
* Implement custom metrics and alerts
* Trace and optimize Lambda cold starts and performance

---

## ✅ In-Scope AWS Services

Familiarize yourself with these **heavily tested services**:

| Category        | Examples                                                      |
| --------------- | ------------------------------------------------------------- |
| Compute         | Lambda, Elastic Beanstalk, EC2                                |
| Storage         | S3, EFS, EBS, Glacier                                         |
| Database        | DynamoDB, Aurora, RDS, ElastiCache                            |
| Security        | IAM, Cognito, KMS, STS, Secrets Manager                       |
| Dev Tools       | CodePipeline, CodeBuild, CodeDeploy, SAM, CloudFormation, CDK |
| Observability   | CloudWatch, X-Ray, CloudTrail                                 |
| API/Integration | API Gateway, SQS, SNS, EventBridge, Step Functions            |

---

## ❌ Out-of-Scope Topics

Avoid spending time on these:

* VPC design and routing
* Managing IAM users/groups (only roles/policies relevant)
* AWS Shield, Device Farm, GameLift, WorkSpaces
* Machine learning services like Lex, Polly, Rekognition

---

