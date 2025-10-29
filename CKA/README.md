# CKA (Certified Kubernetes Administrator) Study Resources 🎯

## 📊 Exam Information

- **Exam Code**: CKA
- **Duration**: 2 hours
- **Format**: Performance-based (hands-on)
- **Passing Score**: 66%
- **Cost**: $395 USD
- **Validity**: 3 years

### 🔗 Exam Registration & Discounts
- [Official Exam Registration](https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/)
- [DevOpsCube Discount Codes](https://devopscube.com/kubernetes-certification-coupon/) - Regular updates on certification discounts
- [Linux Foundation Training Deals](https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/#discounts)

## 📚 FREE Resources

### Official Documentation
- [Kubernetes Documentation](https://kubernetes.io/docs/)
  - **Type**: FREE
  - **Format**: Documentation
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: The most authoritative source. Essential for understanding concepts and kubectl commands.

- [Kubernetes API Reference](https://kubernetes.io/docs/reference/kubernetes-api/)
  - **Type**: FREE
  - **Format**: API Documentation
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Critical for understanding resource specifications during the exam.

### Interactive Learning
- [Katacoda Kubernetes Scenarios](https://www.katacoda.com/courses/kubernetes)
  - **Type**: FREE
  - **Format**: Interactive Labs
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Hands-on practice in a real Kubernetes environment.

- [Play with Kubernetes](https://labs.play-with-k8s.com/)
  - **Type**: FREE
  - **Format**: Online Lab Environment
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Free 4-hour Kubernetes playground for hands-on practice.

### Video Content
- [TechWorld with Nana - Kubernetes Tutorial](https://www.youtube.com/watch?v=X48VuDVv0do)
  - **Type**: FREE
  - **Format**: YouTube Video (4+ hours)
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Comprehensive Kubernetes tutorial covering all major concepts needed for CKA.

- [Kubernetes Crash Course by Fireship](https://www.youtube.com/watch?v=s_o8dwzRlu4)
  - **Type**: FREE
  - **Format**: YouTube Video (100 seconds)
  - **Rating**: ⭐⭐⭐
  - **Description**: Quick overview to reinforce concepts you've learned.

### Practice Resources
- [CKA Exercises by dgkanatsios](https://github.com/dgkanatsios/CKAD-exercises)
  - **Type**: FREE
  - **Format**: GitHub Repository
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Excellent hands-on exercises that mirror exam scenarios.

- [Kubernetes the Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)
  - **Type**: FREE
  - **Format**: Tutorial/Guide
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Learn Kubernetes from scratch by setting up everything manually.

### Blogs & Articles
- [DevOpsCube CKA Guide](https://devopscube.com/cka-exam-study-guide/)
  - **Type**: FREE
  - **Format**: Blog Post
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Comprehensive study guide with exam tips and resource recommendations.

## 💰 PAID Resources

### Video Courses
- [Linux Academy CKA Course](https://acloudguru.com/course/certified-kubernetes-administrator-cka)
  - **Type**: PAID (~$39/month)
  - **Format**: Video Course + Labs
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Comprehensive course with hands-on labs and practice exams.

- [Udemy - CKA with Practice Tests](https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/)
  - **Type**: PAID (~$50-200, often on sale)
  - **Format**: Video Course + Practice Tests
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Mumshad Mannambeth's excellent course with Kodekloud integration.

### Practice Platforms
- [KodeKloud CKA Labs](https://kodekloud.com/courses/certified-kubernetes-administrator-cka/)
  - **Type**: PAID (~$39/month)
  - **Format**: Interactive Labs + Mock Exams
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Browser-based labs that closely simulate the exam environment.

- [Killer.sh CKA Simulator](https://killer.sh/cka)
  - **Type**: PAID (~$39)
  - **Format**: Exam Simulator
  - **Rating**: ⭐⭐⭐⭐⭐
  - **Description**: Most realistic exam simulation available. Harder than the actual exam.

### Books
- [Kubernetes in Action by Marko Lukša](https://www.manning.com/books/kubernetes-in-action)
  - **Type**: PAID (~$45)
  - **Format**: Book
  - **Rating**: ⭐⭐⭐⭐
  - **Description**: Comprehensive guide to Kubernetes concepts and practical implementation.

## 🎯 Exam Tips & Strategy

### Time Management
- The exam is 2 hours with 15-20 questions
- Spend no more than 6-8 minutes per question initially
- Flag difficult questions and return to them later
- Use `kubectl` shortcuts and aliases extensively

### Essential kubectl Commands
```bash
# Create aliases for speed
alias k=kubectl
alias kd='kubectl describe'
alias kg='kubectl get'

# Essential commands to master
kubectl explain <resource>
kubectl create --dry-run=client -o yaml
kubectl apply -f -
kubectl patch
kubectl scale
kubectl rollout
```

### Key Topics to Master
1. **Cluster Architecture & Installation** (25%)
2. **Workloads & Scheduling** (15%)
3. **Services & Networking** (20%)
4. **Storage** (10%)
5. **Troubleshooting** (30%)

### Before the Exam
- Practice with the exact same browser setup you'll use
- Familiarize yourself with the Kubernetes documentation structure
- Practice typing kubectl commands quickly
- Set up your environment with useful aliases and shortcuts

---

*Good luck with your CKA certification! 🚀*