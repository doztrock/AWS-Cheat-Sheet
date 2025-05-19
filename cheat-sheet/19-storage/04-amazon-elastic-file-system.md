# 📂 Amazon Elastic File System (Amazon EFS)

---

## 📌 Description  
**Amazon EFS** is a **fully managed, serverless, elastic file storage** system that can be mounted across multiple Amazon EC2 instances and containers. It provides a **shared file system** that automatically scales and is accessible via the standard **NFS protocol**.

---

## 🚀 Key Features  
- 🔁 **Shared storage** across multiple EC2, ECS, and EKS instances  
- ⚖️ **Elastic**: Automatically scales up/down based on usage  
- 📂 **Standard NFSv4 interface**  
- 🔒 **Secure**: Encryption at rest and in transit using AWS KMS  
- 🌍 **Multi-AZ availability** (Highly Available and Durable)  
- 🛠️ **Lifecycle management**: Automatically move infrequently accessed files to cost-optimized storage  
- 🚀 **Performance modes**: General Purpose or Max I/O  
- 💾 **Throughput modes**: Bursting or Provisioned  

---

## 🛠️ Use Cases  
- 📁 **Web server file storage**  
- 🧬 **Data science and machine learning** — shared access for large datasets  
- 🧑‍🏫 **Shared storage for development environments**  
- 🏢 **Enterprise apps** like CMS, ERP, CRM systems  
- 🎮 **Media processing pipelines**  

---

## 🔁 Comparison with Similar Services  

| Service         | Difference from Amazon EFS |
|------------------|-----------------------------|
| **Amazon EBS**   | Block storage for a single EC2 instance; EFS is shared file storage across instances |
| **Amazon FSx**   | Fully managed third-party file systems (e.g., Windows File Server, Lustre) for specialized workloads |
| **Amazon S3**    | Object storage; EFS is file storage with file system semantics |

---

## 💰 Pricing  
- 💵 **Standard Storage**: ~$0.30/GB-month  
- 🧊 **Infrequent Access (IA)**: ~$0.025/GB-month  
- 🔄 **Lifecycle policies**: Automatically move data to IA to save cost  
- 🚚 **Data transfer**: Free within same AZ; cross-AZ or inter-region has charges  

---

## 🧠 Exam Keywords  
- "Elastic NFS file system for EC2"  
- "Shared POSIX-compliant file storage"  
- "Supports multiple AZs and instances"  
- "Lifecycle management for IA tier"  
- "Mount targets, NFS, encryption, performance modes"
