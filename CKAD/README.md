# CKAD (Certified Kubernetes Application Developer) Study Resources 🎯

## 📊 Exam Information

- **Exam Code**: CKAD
- **Duration**: 2 hours
- **Format**: Performance-based (hands-on)
- **Passing Score**: 66%
- **Cost**: $395 USD
- **Validity**: 3 years

### 🔗 Exam Registration & Discounts
- [Official Exam Registration](https://training.linuxfoundation.org/certification/certified-kubernetes-application-developer-ckad/)
- [DevOpsCube Discount Codes](https://devopscube.com/kubernetes-certification-coupon/) - Regular updates on certification discounts
- [Linux Foundation Training Deals](https://training.linuxfoundation.org/certification/certified-kubernetes-application-developer-ckad/#discounts)

## 📚 FREE Resources

### Official Documentation
- [Kubernetes Documentation](https://kubernetes.io/docs/)
  - **Type**: FREE
  - **Format**: Documentation
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Essential reference for CKAD concepts, especially workloads and pod specifications.

- [Kubernetes API Reference](https://kubernetes.io/docs/reference/kubernetes-api/)
  - **Type**: FREE
  - **Format**: API Documentation
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Critical for understanding Pod, Deployment, Service, and other resource specs.

### Interactive Learning
- [Katacoda CKAD Scenarios](https://www.katacoda.com/courses/kubernetes)
  - **Type**: FREE
  - **Format**: Interactive Labs
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Practice CKAD-specific scenarios in browser-based environments.

- [Play with Kubernetes](https://labs.play-with-k8s.com/)
  - **Type**: FREE
  - **Format**: Online Lab Environment
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Free Kubernetes playground perfect for practicing CKAD tasks.

### Practice Resources
- [CKAD Exercises by dgkanatsios](https://github.com/dgkanatsios/CKAD-exercises)
  - **Type**: FREE
  - **Format**: GitHub Repository
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: The most comprehensive set of CKAD practice exercises available for free.

- [CKAD Practice Questions by bbachi](https://github.com/bbachi/CKAD-Practice-Questions)
  - **Type**: FREE
  - **Format**: GitHub Repository
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Additional practice scenarios with solutions and explanations.

### Video Content
- [TechWorld with Nana - Kubernetes Tutorial](https://www.youtube.com/watch?v=X48VuDVv0do)
  - **Type**: FREE
  - **Format**: YouTube Video (4+ hours)
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Excellent foundation for Kubernetes concepts needed in CKAD.

- [Kubernetes CKAD Tutorial by KodeKloud](https://www.youtube.com/watch?v=j-nTfnWs8dU)
  - **Type**: FREE
  - **Format**: YouTube Video
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: CKAD-focused tutorial covering exam-specific topics.

### Blogs & Study Guides
- [CKAD Exam Study Guide - DevOpsCube](https://devopscube.com/ckad-exam-study-guide/)
  - **Type**: FREE
  - **Format**: Blog Post
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Comprehensive CKAD study guide with exam tips and resources.

- [CKAD Tips and Tricks](https://medium.com/@harioverhere/ckad-certified-kubernetes-application-developer-tips-ab651e5a7a5)
  - **Type**: FREE
  - **Format**: Medium Article
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Practical exam tips and time-saving techniques.

## 💰 PAID Resources

### Video Courses
- [Udemy - CKAD with Practice Tests by Mumshad](https://www.udemy.com/course/certified-kubernetes-application-developer/)
  - **Type**: PAID (~$50-200, often on sale)
  - **Format**: Video Course + Practice Tests
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Most popular CKAD course with excellent hands-on labs and practice tests.

- [A Cloud Guru CKAD Course](https://acloudguru.com/course/certified-kubernetes-application-developer-ckad)
  - **Type**: PAID (~$39/month)
  - **Format**: Video Course + Labs
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Well-structured course with good lab exercises.

### Practice Platforms
- [KodeKloud CKAD Course & Labs](https://kodekloud.com/courses/certified-kubernetes-application-developer-ckad/)
  - **Type**: PAID (~$39/month)
  - **Format**: Interactive Labs + Mock Exams
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Browser-based labs that simulate the real exam environment perfectly.

- [Killer.sh CKAD Simulator](https://killer.sh/ckad)
  - **Type**: PAID (~$39)
  - **Format**: Exam Simulator
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Most realistic CKAD exam simulation. Slightly harder than the actual exam.

### Books
- [Kubernetes for Developers by William Denniss](https://www.manning.com/books/kubernetes-for-developers)
  - **Type**: PAID (~$40)
  - **Format**: Book
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Developer-focused Kubernetes guide perfect for CKAD preparation.

## 🎯 Exam Tips & Strategy

### Time Management
- 2 hours for 15-20 questions
- Average 6-8 minutes per question
- Start with easier questions to build confidence
- Flag complex questions and return later

### Essential kubectl Commands for CKAD
```bash
# Speed aliases
alias k=kubectl
export do="--dry-run=client -o yaml"
export now="--force --grace-period 0"

# Key commands for CKAD
kubectl create deployment nginx --image=nginx $do
kubectl create service clusterip my-svc --tcp=80:8080 $do
kubectl create job hello --image=busybox $do -- echo "Hello World"
kubectl create cronjob hello --image=busybox --schedule="*/1 * * * *" $do
kubectl expose deployment nginx --port=80 --target-port=8080
kubectl scale deployment nginx --replicas=3
kubectl rollout undo deployment nginx
```

### CKAD Exam Domains
1. **Application Design and Build** (20%)
   - Container images, Jobs, CronJobs
   - Multi-container pods, Init containers
   
2. **Application Deployment** (20%)
   - Deployments, rolling updates
   - Helm charts, Kustomize
   
3. **Application Observability and Maintenance** (15%)
   - Probes (liveness, readiness, startup)
   - Monitoring, logging, debugging
   
4. **Application Environment, Configuration and Security** (25%)
   - ConfigMaps, Secrets
   - SecurityContexts, ServiceAccounts
   - Resource limits and requests
   
5. **Services and Networking** (20%)
   - Services, NetworkPolicies
   - Ingress controllers

### Key Concepts to Master
- **Pod Design**: Labels, selectors, annotations
- **Multi-container Pods**: Sidecar, adapter, ambassador patterns
- **Configuration**: ConfigMaps, Secrets, environment variables
- **Observability**: Probes, logging, monitoring
- **Pod Security**: SecurityContext, ServiceAccounts
- **Jobs & CronJobs**: Batch workloads and scheduled tasks

### Before the Exam
- Practice creating resources from scratch using `kubectl create`
- Master the `--dry-run=client -o yaml` flag for generating manifests
- Practice editing YAML quickly in vim/nano
- Memorize common resource specifications
- Practice troubleshooting failing pods

---

*Good luck with your CKAD certification! 🚀*