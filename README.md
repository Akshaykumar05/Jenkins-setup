# Jenkins-setup
![image](https://github.com/user-attachments/assets/505d3f26-8c0e-4f74-8439-3a83ea5ff143)

* In this repo I'm summaring all about Jenkins and its plugins with different tools of DevOps. First we'll locally setup Jenkins using Docker container, later we'll see its different plugins integration.

-------------------------

* Jenkins is an open-source automation server widely used for Continuous Integration (CI) and Continuous Delivery (CD) in DevOps. It helps automate the building, testing, and deployment of applications, making software delivery faster and more reliable.

## Key Features of Jenkins
1. Free & Open-Source – No licensing cost, highly customizable.
2. Plugin Support – Over 1,800+ plugins to integrate with tools like Git, Docker, Kubernetes, Terraform, AWS, etc.
3. Supports CI/CD Pipelines – Automate code builds, testing, and deployments.
4. Works with Any Language – Supports Java, Python, Node.js, Go, etc.
5. Distributed Builds – Can run jobs on multiple nodes for faster execution.
6. Web-Based UI & CLI – Easy management and monitoring.
7. Extensive Community Support – Used by major companies worldwide.


---------------

* Localhost Jenkins using docker.
  
  <img width="922" alt="image" src="https://github.com/user-attachments/assets/4ec4befa-2710-48f4-bd61-f17045d6c20b">

## Hands-on to do:
1. Create first-job with "Hello world" build it and analyse the Console output.
2. Understand to install a plugin "Simple theme" and configure it to apply. Delete an installed plugin
3. Create a user and provide role based permissions.
4. Understand use of Git plugins and Clean workspace.
------------
1. Created a job named "demo-sec" and attempled the build failure due to wrong command.
  <img width="925" alt="jenkins-wrong-build" src="https://github.com/user-attachments/assets/3de8c540-5f92-4100-8ec7-877db6da37ac">

   In the above picture red border shows the job failure and there is cloudy wether due to this failure.

