# Deploying a Three-Tier DevSecOps Web Application
Deploy a secure and scalable three-tier web application on AWS EKS using Docker and DevSecOps best practices. This project automates CI/CD with Jenkins, ArgoCD, SonarQube, and Trivy for code quality and security, while Prometheus and Grafana provide real-time monitoring. It leverages AWS services like ECR, S3, EC2, and DynamoDB, with Terraform managing full Infrastructure as Code (IaC) for seamless provisioning and deployment.



![Screenshot 2025-07-02 211523](https://github.com/user-attachments/assets/f1438274-7c29-4297-ace1-2ba07291e350)


## 1) IAM User Setup:
   ### Creating an IAM user with the necessary permissions for EKS, S3, DynamoDB, ECR, and EC2.

  * #### On AWS Console, search I am, and click Users.
  

<img width="1914" height="909" alt="Screenshot 2025-07-13 100602" src="https://github.com/user-attachments/assets/f95c241e-49cc-4762-ab7a-37109bd2d86c" />


* #### Giving a username to my I am User.


<img width="1892" height="920" alt="Screenshot 2025-07-13 100833" src="https://github.com/user-attachments/assets/4eee0c37-3496-4b90-9cde-e59f1f4d9c0d" />


* #### Attaching the administrative access for testing and then click Create user.


<img width="1904" height="910" alt="Screenshot 2025-07-13 100931" src="https://github.com/user-attachments/assets/a316f02d-1b42-471e-88e6-6e5f43f4c360" />



* #### Creating an access and secret access keys.


<img width="1905" height="910" alt="Screenshot 2025-07-13 101204" src="https://github.com/user-attachments/assets/b0741591-9ada-4de3-bbc9-cdd810e99291" />


<img width="1902" height="911" alt="Screenshot 2025-07-13 101323" src="https://github.com/user-attachments/assets/eb5ba139-558e-4788-82d5-84679ce23b1f" />


* #### Download the file for later use of the secret key and access key.


<img width="1904" height="910" alt="Screenshot 2025-07-13 101342" src="https://github.com/user-attachments/assets/f20db528-a238-4c1e-a9dc-46f6997feab9" />



