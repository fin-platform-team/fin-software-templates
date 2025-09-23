# Fin Web stack

Web application stack to provision AWS resources.

**Resources**
- EKS
- S3
- k8s Namespace

```(mermaid)
graph TD
    A[AWS Cloud] --> B[EKS Cluster]
    A --> C[S3 Bucket]
    B --> D[Kubernetes Namespace]
    D --> E[Pods/Deployments]
    C --> F[Objects/Files]
    style A fill:#FF9900,stroke:#232F3E
    style B fill:#FF9900,stroke:#232F3E  
    style C fill:#FF9900,stroke:#232F3E
    style D fill:#326CE5,stroke:#232F3E
    style E fill:#326CE5,stroke:#232F3E
    style F fill:#FF9900,stroke:#232F3E
```