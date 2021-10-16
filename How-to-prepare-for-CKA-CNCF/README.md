
You can find the full session video from here: https://www.youtube.com/watch?v=1oQlkO-QS70&ab_channel=DevOpsMalayalam 

## Introduction

## Module 1: Prerequisites

- Learn K8s not just CKA
- If you are absolute begineer: 
  * Start with official Kubernetes-basics docs: https://kubernetes.io/docs/tutorials/kubernetes-basics/
  * [Kubernetes Course For Absolute Begineer](https://kodekloud.com/courses/kubernetes-for-the-absolute-beginners-hands-on/) - Course from Mumshad/KodeKloud
  * Courses from Katakoda including: https://www.katacoda.com/courses/kubernetes
- Make sure you have good hands-on experience and this is very important in clearing CKA Exam.
- Make sure you are comfortable with Kubernetes theoretically as well.
  
## Module 2: How to prepare (Theoretical and Hands-on is must have)

- CKA exam is especially for SREs or Devops Engineers, who want to build,run and operate the Kubernetes infrastructure and platforms but not limited to anyone in IT. 
- Start with official [curriculam](https://github.com/cncf/curriculum/blob/master/CKA_Curriculum_v1.21.pdf)
- Read [Offical Candidate Requirements](https://docs.linuxfoundation.org/tc-docs/certification/lf-candidate-handbook/candidate-requirements)
- Deploy Kubernetes from scratch - Use [Kelsey Hightower doc](https://github.com/kelseyhightower/kubernetes-the-hard-way)- (Kubeadm on GCP) or using [VirtualBox/Vagrant method from KodeKloud](https://github.com/mmumshad/kubernetes-the-hard-way)
- Read [Kubernetes Up and Running](https://www.oreilly.com/library/view/kubernetes-up-and/9781491935668/) - (Higly Recommended if you are not having hands-on.
- Higly recommended [CKA course from KodeKloud](https://kodekloud.com/courses/certified-kubernetes-administrator-cka/) or in [Udemy](https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/)
- Practice, Practice and Practice.
  * High Recommended practice environment https://killer.sh/ 
- If you want Linux foundation itself is providing https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/

## Module 3: Tips And Tricks (Conclusion)

- Bookmarks every topics with respective documents relative link when you learn Kubernetes.
- Be familiar with [Kubernetes documentation](https://kubernetes.io/docs/home/) portal and make sure you know what to check and where.
- Use `kubectl` conventions heavily(run, dry-run, generators), refer: https://kubernetes.io/docs/reference/kubectl/conventions/ 
- Configure `vim` editor for yaml - for editing yaml files easily with proper indentation, spacing etc. (Read [How to Setup Vim Editor for YAML](https://www.techbeatly.com/2018/06/setup-your-vim-editor-for-ansible-playbook.html))


```shell
# add inside ~/.vimrc file
autocmd FileType yaml setlocal et ts=2 ai sw=2 nu sts=0
```

- Familiarize with k8s official Cheatsheets: https://kubernetes.io/docs/reference/kubectl/cheatsheet/
- Search for learning resources **NOT** for Exam Dumps !
- Practice with your personal lab as much as possible.

## References

- [10 Tips for your Kubernetes Exam – CKA & CKAD](https://www.techbeatly.com/2020/08/10-tips-for-your-kubernetes-exam-cka-and-ckad.html) (techbeatly)
- [How to Prepare for CKAD and CKA Certification?](https://www.infracloud.io/blogs/prepare-cka-ckad-certification/) (InfraCloud)
- [Certified Kubernetes Administrator (CKA)](https://www.cncf.io/certification/cka/) (Official Doc)
- [kubernetes-the-hard-way (using GCP)](https://github.com/kelseyhightower/kubernetes-the-hard-way) 
- [kubernetes-the-hard-way (using VirtualBox/Vagrant)](https://github.com/mmumshad/kubernetes-the-hard-way)
- Workshop Laps: https://training.play-with-kubernetes.com/kubernetes-workshop/
- How to register and portal details including exam details. 
  https://docs.linuxfoundation.org/tc-docs/certification/tips-cka-and-ckad


# Support For CKA Exam Prepration or Learning Kubernetes

-  If someone wants support for learning Kubernetes from us please follow the steps

1. Create a Github repository.
2. Add `jeswinjkn@gmail.com` or `net.gini@gmail.com` as collaborators.
3. Raise an issue with details of topic which you want to explore.
4. We will try to support and create POC for you to explore further.
5. After completing the POC, pleae raise the review request so as we can support you to complete the project. 
  
**More details**

- [DevOps Malayalam](https://devopsmalayalam.io)
- [CNCF Community Trivandrum](https://community.cncf.io/trivandrum/)
