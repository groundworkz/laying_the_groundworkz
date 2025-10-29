# CKS (Certified Kubernetes Security Specialist) Study Resources 🔐

> **⚠️ Note**: This file has not been manually verified and may contain errors. Please verify all information independently before relying on it for your certification preparation.

## 📊 Exam Information

- **Exam Code**: CKS
- **Duration**: 2 hours
- **Format**: Performance-based (hands-on)
- **Passing Score**: 67%
- **Cost**: $395 USD
- **Validity**: 3 years
- **Prerequisites**: Valid CKA certification required

### 🔗 Exam Registration & Discounts
- [Official Exam Registration](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/)
- [DevOpsCube Discount Codes](https://devopscube.com/kubernetes-certification-coupon/) - Regular updates on certification discounts
- [Linux Foundation Training Deals](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/#discounts)

## 📚 FREE Resources

### Official Documentation
- [Kubernetes Security Documentation](https://kubernetes.io/docs/concepts/security/)
  - **Type**: FREE
  - **Format**: Documentation
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Essential reading for all Kubernetes security concepts and best practices.

- [Pod Security Standards](https://kubernetes.io/docs/concepts/security/pod-security-standards/)
  - **Type**: FREE
  - **Format**: Documentation
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Critical for understanding pod security contexts and policies.

- [Network Policies](https://kubernetes.io/docs/concepts/services-networking/network-policies/)
  - **Type**: FREE
  - **Format**: Documentation
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Essential for understanding network segmentation and security.

### Security Tools Documentation
- [Falco Documentation](https://falco.org/docs/)
  - **Type**: FREE
  - **Format**: Official Docs
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Runtime security monitoring tool frequently covered in CKS.

- [OPA Gatekeeper](https://open-policy-agent.github.io/gatekeeper/website/docs/)
  - **Type**: FREE
  - **Format**: Documentation
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Policy engine for Kubernetes admission control.

- [Trivy Documentation](https://aquasecurity.github.io/trivy/)
  - **Type**: FREE
  - **Format**: Documentation
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Container image vulnerability scanning tool.

### Practice Resources
- [CKS Exam Exercises by killer-sh](https://github.com/killer-sh/cks-course-environment)
  - **Type**: FREE
  - **Format**: GitHub Repository
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Practice exercises from the creators of killer.sh simulator.

- [CKS Practice by walidshaari](https://github.com/walidshaari/Certified-Kubernetes-Security-Specialist)
  - **Type**: FREE
  - **Format**: GitHub Repository
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Comprehensive collection of CKS study materials and practice scenarios.

### Video Content
- [TechWorld with Nana - Kubernetes Security](https://www.youtube.com/watch?v=VjlvS-qiz_U)
  - **Type**: FREE
  - **Format**: YouTube Video
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Great overview of Kubernetes security concepts.

- [CNCF Security Webinars](https://www.cncf.io/webinars/)
  - **Type**: FREE
  - **Format**: Webinar Series
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Regular security-focused webinars from cloud native experts.

### Security Guides & Blogs
- [CIS Kubernetes Benchmark](https://www.cisecurity.org/benchmark/kubernetes)
  - **Type**: FREE
  - **Format**: Security Benchmark
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Industry standard security benchmarks for Kubernetes.

- [NSA Kubernetes Hardening Guide](https://media.defense.gov/2022/Aug/29/2003066362/-1/-1/0/CTR_KUBERNETES_HARDENING_GUIDANCE_1.2_20220829.PDF)
  - **Type**: FREE
  - **Format**: PDF Guide
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Comprehensive security hardening guidance from the NSA.

## 💰 PAID Resources

### Video Courses
- [Udemy - CKS Course by Kim Wuestkamp](https://www.udemy.com/course/certified-kubernetes-security-specialist/)
  - **Type**: PAID (~$50-200, often on sale)
  - **Format**: Video Course
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Most comprehensive CKS course available, created by a Kubernetes expert.

- [A Cloud Guru CKS Course](https://acloudguru.com/course/certified-kubernetes-security-specialist-cks)
  - **Type**: PAID (~$39/month)
  - **Format**: Video Course + Labs
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Well-structured course with practical security scenarios.

### Practice Platforms
- [Killer.sh CKS Simulator](https://killer.sh/cks)
  - **Type**: PAID (~$39)
  - **Format**: Exam Simulator
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Most realistic CKS exam simulation available. Essential for exam preparation.

- [KodeKloud CKS Course](https://kodekloud.com/courses/certified-kubernetes-security-specialist-cks/)
  - **Type**: PAID (~$39/month)
  - **Format**: Interactive Labs
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Hands-on labs covering all CKS exam topics.

### Books
- [Kubernetes Security by Liz Rice & Michael Hausenblas](https://kubernetes-security.info/)
  - **Type**: FREE (PDF) / PAID (Print)
  - **Format**: Book
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Comprehensive guide to Kubernetes security by industry experts.

## 🎯 Exam Tips & Strategy

### CKS Exam Domains
1. **Cluster Setup** (10%)
   - CIS benchmarks, Ingress TLS, Node metadata protection
   
2. **Cluster Hardening** (15%)
   - RBAC, Service accounts, Upgrading clusters securely
   
3. **System Hardening** (15%)
   - AppArmor, seccomp, Kernel hardening
   
4. **Minimize Microservice Vulnerabilities** (20%)
   - Security contexts, Pod Security Standards, mTLS
   
5. **Supply Chain Security** (20%)
   - Image scanning, Admission controllers, Static analysis
   
6. **Monitoring, Logging and Runtime Security** (20%)
   - Behavioral analytics, Immutability, Auditing

### Essential Security Tools to Master
```bash
# Image scanning with Trivy
trivy image nginx:latest

# Falco for runtime security
falco --list-rules
falco -r /path/to/rules/file.yaml

# OPA policy testing
opa fmt policy.rego
opa test policy.rego

# AppArmor profiles
aa-status
aa-enforce /path/to/profile
```

### Key Security Concepts
- **RBAC**: Roles, RoleBindings, ClusterRoles, ClusterRoleBindings
- **Network Policies**: Ingress/egress rules, default deny policies
- **Pod Security**: SecurityContext, Pod Security Standards
- **Admission Control**: ValidatingAdmissionWebhooks, OPA Gatekeeper
- **Supply Chain**: Image scanning, signed images, admission controllers
- **Runtime Security**: Falco rules, behavioral monitoring

### Security Best Practices
- Always enable RBAC and follow principle of least privilege
- Implement network segmentation with NetworkPolicies
- Scan container images for vulnerabilities
- Use non-root containers and read-only filesystems
- Implement proper secrets management
- Enable audit logging and monitoring
- Keep Kubernetes and node OS updated

### Before the Exam
- Practice with security tools (Falco, Trivy, OPA)
- Master RBAC configuration and troubleshooting
- Understand AppArmor and seccomp profiles
- Practice writing and debugging NetworkPolicies
- Familiarize yourself with CIS benchmarks
- Practice security incident response scenarios

---

*Good luck with your CKS certification! 🔐*