<h1>Designing Multi-Container Pods in Kubernetes Using Init and Sidecar Containers</h1>

<h2>Description</h2>
This project demonstrates how to design and deploy multi-container pods in Kubernetes using Init and Sidecar containers. It covers shared volume communication, container lifecycle sequencing, and container collaboration within a single pod. The goal is to replicate real-world DevOps use cases and reinforce practical skills needed for CKA/CKAD certification and production-grade Kubernetes environments.

<h2>Tools & Technologies</h2>


- Kubernetes (Minikube)  
- Init & Sidecar Containers  
- Nginx, BusyBox  
- YAML, kubectl  
- Shared Volumes (emptyDir) 

<h2>Project Walk-through</h2>

<p align="center">
1. Define Multi-Container Pod in YAML <br />
<img src="https://i.postimg.cc/MZnWfZTm/1.jpg" />
<br />
<br />
2. Deploy the Pod <br/>
<img src="https://i.postimg.cc/6qtg00KZ/2.jpg" />
<br />
<br />
3. Verify Init Container  <br/>
<img src="https://i.postimg.cc/v8nNKDZB/3.jpg" />
<br />
<br />
4. Simulate Web Traffic <br/>
<img src="https://i.postimg.cc/W1Y8zP1C/4.jpg"/>
<br />
<br />
5. Check Sidecar Logs <br/>
<img src="https://i.postimg.cc/0NmSvgMp/5.jpg"/>
<br />
<br />
  
</p>

