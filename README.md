### Hi, I'm Lucas

I'm the platform engineer at Automated Assembly Corporation, a flexible circuit manufacturer for the automotive and medical technology industries, in Minnesota. I'm the technical owner of the company's cloud, identity, and production software: the AWS organization, the data platform that collects from the production lines, and the internal apps built on it.

Right now I'm building toward AI platform engineering: Kubernetes, GitOps, and retrieval systems that are measured with evals instead of guessed at.

**What I work with**

| Area | What I've built or run |
|---|---|
| AWS | A multi-account organization in Terraform: Identity Center, service control policies, CloudTrail, ECS Fargate, RDS, SQS, S3, Secrets Manager, CloudWatch, Route 53, load balancers |
| Infrastructure and CI/CD | Terraform modules with tests, Docker, Azure DevOps pipelines, GitHub Actions with OIDC, Argo CD |
| Kubernetes | An EKS lab cluster I rebuild from my own Terraform, deployed by GitOps |
| Identity and security | Entra ID single sign-on and SCIM into AWS, SAML and OIDC, least privilege, access reviews, and the identity audit of the company's Microsoft 365 tenant |
| AI | Retrieval-based chat over company data in two production apps, eval sets, vector stores (Qdrant, pgvector), local models |
| Software and data | C# and ASP.NET Core, TypeScript and Next.js, Python, MySQL and PostgreSQL, queue-based ingest from line PCs |
| Vision and robotics | Machine vision (Cognex) and robot cell software on production lines; earlier, ROS2 and LiDAR rovers and an ML defect-detection prototype (paper at ICECET 2025) |
| Manufacturing | Ran a medical-device line and cut its scrap 61%; Epicor ERP; ISO 13485 workflows |

**What's here**

- [local-ai](https://github.com/LucasLinnemann/local-ai): a retrieval pipeline that runs on one machine (LM Studio, Qdrant, plain Python), with a 20-question eval set and what the numbers showed.

**How I work**

- No stored cloud keys: pipelines and workloads use short-lived credentials.
- Infrastructure in Terraform, deployed from git.
- If it isn't measured, it isn't done.

Reach me on [LinkedIn](https://www.linkedin.com/in/lucas-linnemann/).
