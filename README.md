# Hi, I'm Juancho 👋

**Juan Andrés González · DevOps & Platform Engineer · Paraguay 🇵🇾**

I work with Kubernetes platforms, Linux systems, and delivery automation. I also build backend services, which helps me connect how applications are developed with how they run.

I like getting beyond “it works”: understanding why it works, finding what breaks, and documenting enough for someone else to reproduce it.

**Build it. Understand it. Make it repeatable.**

[LinkedIn](https://www.linkedin.com/in/juan-andres-gonzalez-arevalos-75808a1b2/) · [Email](mailto:juanandresgonza98@gmail.com) · [Terraform portfolio](https://github.com/JuanchoGonza98/terraform-s3-portfolio)

## What I work on

| Area | My focus |
| --- | --- |
| **Platforms** | Kubernetes, VMware Tanzu, and vSphere operations; troubleshooting and platform lifecycle work |
| **Delivery** | GitHub Actions pipelines, Argo CD, GitOps, and consistent application deployments |
| **Infrastructure** | Terraform, OpenTofu, Ansible, and reproducible Linux lab environments |
| **Applications** | Python services, FastAPI, Django, Nginx, and the infrastructure around them |

## Projects to explore

These repositories turn the tools above into something you can inspect, run, and learn from.

### ☁️ [Terraform S3 Portfolio](https://github.com/JuanchoGonza98/terraform-s3-portfolio)

A static website on AWS, served through CloudFront with a private S3 origin and deployed through a manual GitHub Actions workflow.

- **Infrastructure:** reusable Terraform module, separate DEV/HML state keys, object versioning, and environment-specific metadata.
- **Delivery:** temporary AWS credentials through OIDC, saved plans, and an explicit manual apply option.
- **Decisions:** documented security exceptions, usage-based cost estimates, verification evidence, and cleanup instructions.

**Explore:** [Architecture and setup](https://github.com/JuanchoGonza98/terraform-s3-portfolio#architecture) · [Security decisions](https://github.com/JuanchoGonza98/terraform-s3-portfolio/blob/main/SECURITY.md) · [Workflow runs](https://github.com/JuanchoGonza98/terraform-s3-portfolio/actions)

*Scope note: CloudFront is deployed in DEV. HML demonstrates separate S3 resources and state; it is not an identical copy of the complete DEV stack.*

### 🧩 [DevOps Python Microservices Platform](https://github.com/JuanchoGonza98/devops-python-microservices-platform)

A FastAPI microservices project connecting application development with container delivery and Kubernetes deployment.

**What to explore:** an Nginx gateway, Docker workflows, Kubernetes manifests, Kustomize overlays, GitHub Actions CI, GHCR publishing, and Argo CD delivery.

### 🛠️ [OpenTofu / KVM Lab Automation](https://github.com/JuanchoGonza98/kvm-k8s-opentofu-ansible)

A lab for reproducible infrastructure provisioning with OpenTofu, libvirt/KVM, and cloud-init.

**What to explore:** the steps between a declared infrastructure configuration and a repeatable environment for platform testing.

### 🤝 [Django CMS — Contribution](https://github.com/Elias-Gill/django_cms)

Contributed to a content management system built with Django and PostgreSQL, working on CI/CD, Docker, DevOps practices, and application development.

## How I approach engineering

- **Start with the problem.** Understand the application, the environment, and the operational constraints before choosing tools.
- **Troubleshoot with evidence.** Use logs, configuration, and reproducible checks to narrow down a failure.
- **Automate what needs to be repeatable.** Keep infrastructure and deployment steps reviewable in code.
- **Explain the tradeoffs.** Document what a solution covers, what it leaves out, and why.
- **Leave a useful trail.** Write READMEs and runbooks that help the next person operate the system.

## Tools I work with

**Platforms & containers:** Kubernetes · VMware Tanzu · vSphere · Docker · libvirt/KVM  
**Infrastructure & delivery:** Terraform · OpenTofu · Ansible · GitHub Actions · Argo CD · GitOps  
**Systems & applications:** Linux · Python · FastAPI · Django · Nginx · PostgreSQL

The projects above show how I use these tools together.

## Learning with a purpose

**Earned:** VMware Certified Tanzu Kubernetes Operator.

**Current priorities:** preparing for Terraform Associate and CKA through structured study and hands-on projects.

**Also on my learning path:** VMware Cloud Foundation / VKS administration and RHCSA.

My goal is to connect the exam concepts to real decisions: state ownership, access boundaries, deployment behavior, troubleshooting, and cost.

## Let's connect

I'm interested in conversations about platform engineering, Kubernetes operations, infrastructure automation, and making technical knowledge easier to share.

- [LinkedIn — Juan Andrés González](https://www.linkedin.com/in/juan-andres-gonzalez-arevalos-75808a1b2/)
- [juanandresgonza98@gmail.com](mailto:juanandresgonza98@gmail.com)

---

*Learning by building. Sharing what I understand along the way.*
