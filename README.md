<p align="center">
  <img src="assets/profile-header.gif" width="100%" alt="Juan Andrés González, DevOps and Cloud Engineer in Paraguay. Infrastructure with purpose. To God be the glory.">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/juan-andres-gonzalez-arevalos-75808a1b2/">LinkedIn</a>
  &nbsp; / &nbsp;
  <a href="mailto:juanandresgonza98@gmail.com">Email</a>
  &nbsp; / &nbsp;
  <a href="#selected-work">Selected work</a>
  &nbsp; / &nbsp;
  <a href="STATIC.md">View without animation</a>
</p>

<br>

### DevOps & Cloud Engineer

I'm **Juancho**, based in Paraguay. My current role is DevOps Engineer, working on AWS infrastructure, serverless applications, deployment workflows, and Linux operations.

My work connects **cloud architecture, infrastructure as code, security configuration, and troubleshooting**. My platform background includes Kubernetes, VMware Tanzu, and vSphere; my backend experience helps me understand the applications that run on that infrastructure.

I enjoy understanding a system deeply enough to explain it: following the request path, investigating a failure, making a deployment repeatable, and leaving useful documentation for the next person.

**My faith in Jesus Christ is part of who I am.** I seek to honor God through diligence, integrity, humility, and care in the work I do and the knowledge I share.

<p>
  <a href="https://www.biblegateway.com/passage/?search=Colossians%203%3A23&amp;version=KJV">
    <img src="assets/colossians-3-23.png" width="100%" alt="To God be the glory. Colossians 3:23, King James Version.">
  </a>
</p>

<details>
<summary>Read Colossians 3:23 as text</summary>

> And whatsoever ye do, do it heartily, as to the Lord, and not unto men;
>
> **Colossians 3:23 — King James Version (KJV)**

</details>

<br>

## What I work on professionally

My current work involves AWS infrastructure and application delivery across separate environments, alongside operational troubleshooting and technical documentation.

| Area | Work I do |
| --- | --- |
| **AWS & serverless** | Build and maintain Terraform configuration for ZIP and container-based Lambda functions, API Gateway, Step Functions, SQS, DynamoDB, S3, and ECR integrations. |
| **Security & connectivity** | Configure IAM permissions, KMS and SSM integrations, private connectivity, and environment-specific settings within established security requirements. |
| **Infrastructure & delivery** | Adapt infrastructure changes to shared modules and corporate pipelines; diagnose Terraform and deployment failures; coordinate changes across development and homologation environments. |
| **Observability & Linux operations** | Operate and troubleshoot Elasticsearch, Kibana, and Filebeat on EC2, including log ingestion, memory pressure, and storage issues. |
| **Operational clarity** | Prepare deployment procedures, runbooks, and technical documentation to support repeatable changes and production handovers. |

My platform experience also includes Kubernetes and VMware environments, GitOps workflows, and application deployment. The projects below provide public examples of how I build and learn.

<br>

## Selected work

**Personal projects and contributions.** These complement my professional experience with code, architecture notes, and reproducible exercises that can be shared publicly.

The animations are conceptual illustrations; project documentation provides implementation details and verification evidence.

<a href="https://github.com/JuanchoGonza98/terraform-s3-portfolio">
  <img src="assets/terraform-project.gif" width="100%" alt="Terraform S3 Portfolio: source, plan, CloudFront delivery, and a private S3 origin.">
</a>

### [Terraform S3 Portfolio](https://github.com/JuanchoGonza98/terraform-s3-portfolio)

An AWS cloud infrastructure project serving a static website through CloudFront while keeping its S3 origin private.

**Cloud engineering:** OAC and distribution-scoped bucket access, HTTPS delivery, SSE-S3 encryption, object versioning and retention, and usage-based cost estimates.

**Infrastructure & delivery:** reusable Terraform modules, `for_each`, templates, separate DEV/HML state keys, native S3 locking, and a manual GitHub Actions workflow using temporary OIDC credentials and saved plans.

**Evidence:** documented security tradeoffs, tested access boundaries, a deployed content update, and cleanup procedures.

[Architecture](https://github.com/JuanchoGonza98/terraform-s3-portfolio#architecture) · [Security decisions](https://github.com/JuanchoGonza98/terraform-s3-portfolio/blob/main/SECURITY.md) · [Workflow runs](https://github.com/JuanchoGonza98/terraform-s3-portfolio/actions)

<details>
<summary>Environment scope</summary>

DEV includes CloudFront and its private S3 origin. HML demonstrates separate S3 resources and state. Its deployment predates the CloudFront addition to the shared root configuration; a new HML plan can propose additional resources. The project README documents this boundary.

</details>

<br>

<a href="https://github.com/JuanchoGonza98/devops-python-microservices-platform">
  <img src="assets/microservices-project.gif" width="100%" alt="Python Microservices Platform: FastAPI, CI and GHCR, Argo CD, and Kubernetes.">
</a>

### [Python Microservices Platform](https://github.com/JuanchoGonza98/devops-python-microservices-platform)

A FastAPI-based project connecting application development with container delivery and Kubernetes deployments.

**Explore:** an Nginx gateway, Docker workflows, Kubernetes manifests, Kustomize overlays, GitHub Actions CI, GHCR image publishing, and Argo CD-based GitOps delivery.

**The connection that interests me:** how application code, container images, deployment configuration, and reconciliation fit together.

<br>

<a href="https://github.com/JuanchoGonza98/kvm-k8s-opentofu-ansible">
  <img src="assets/lab-project.gif" width="100%" alt="OpenTofu KVM lab: infrastructure declarations, libvirt, cloud-init, and Linux virtual machines.">
</a>

### [OpenTofu / KVM Lab Automation](https://github.com/JuanchoGonza98/kvm-k8s-opentofu-ansible)

Infrastructure provisioning with OpenTofu, libvirt/KVM, and cloud-init for repeatable lab environments and platform testing.

**Explore:** how a declared configuration becomes a reproducible environment for learning, experimentation, and troubleshooting.

<br>

<a href="https://github.com/Elias-Gill/django_cms">
  <img src="assets/django-project.gif" width="100%" alt="Django CMS contribution, involving Django, PostgreSQL, Docker, and CI/CD practices.">
</a>

### [Django CMS — Contribution](https://github.com/Elias-Gill/django_cms)

Contributed to a content management system built with Django and PostgreSQL, working on CI/CD, Docker, DevOps practices, and application development.

**The perspective it adds:** understanding the application alongside its infrastructure and delivery workflow.

<br>

## How I approach the work

| Principle | In practice |
| --- | --- |
| **Understand the system** | Follow dependencies, request paths, identities, and state before changing configuration. |
| **Troubleshoot with evidence** | Use logs, configuration, and reproducible checks to narrow down a failure. |
| **Make changes reviewable** | Keep infrastructure and delivery behavior in code, with clear plans and boundaries. |
| **Explain the decisions** | Document scope, operational limits, security tradeoffs, and cost assumptions. |
| **Share what I learn** | Write the README and runbook I would want to find when returning to a system. |

<br>

## Technical landscape

| Area | Technologies |
| --- | --- |
| **AWS compute & application services** | EC2 · Lambda · API Gateway · Step Functions · SQS |
| **AWS data, access & configuration** | S3 · DynamoDB · ECR · IAM · KMS · SSM |
| **Infrastructure & delivery** | Terraform · OpenTofu · Ansible · GitHub Actions · Argo CD · GitOps |
| **Platforms & virtualization** | Kubernetes · VMware Tanzu · vSphere · Docker · libvirt/KVM |
| **Operations & observability** | Linux · Elasticsearch · Kibana · Filebeat |
| **Backend & web** | Python · FastAPI · Django · Nginx · PostgreSQL |

<br>

## Learning with a direction

**Earned** — VMware Certified Tanzu Kubernetes Operator.

**Preparing** — Terraform Associate and Certified Kubernetes Administrator (CKA).

**Also on my learning path** — VMware Cloud Foundation / VKS administration and RHCSA.

I connect structured study, professional work, and hands-on projects through practical questions: who owns the state, how access is granted, what a deployment changes, and how to troubleshoot it.

<br>

---

<p align="center">
  <strong>To God be the glory.</strong><br>
  <sub>JUAN ANDRÉS GONZÁLEZ / PARAGUAY / COLOSSIANS 3:23</sub>
</p>
