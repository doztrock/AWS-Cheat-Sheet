# 🪣 Amazon Simple Storage Service

---

## 📌 Description  
**Amazon S3** is a **scalable, durable, and secure object storage** service designed for storing and retrieving **any amount of data** from anywhere. It’s ideal for backup, archiving, big data, content distribution, static websites, and more.

---

## 🚀 Key Features  
- 📦 **Object storage**: Stores data as objects (key + value + metadata)  
- ♾️ **Virtually unlimited scale**  
- 🔐 **Built-in security**: Supports encryption (SSE-S3, SSE-KMS, SSE-C), IAM, bucket policies  
- 🗂️ **Storage classes**: Standard, Intelligent-Tiering, Glacier, Glacier Deep Archive, etc.  
- 📜 **Versioning & Lifecycle Policies**  
- 🔄 **Replication**: Same-Region or Cross-Region Replication (CRR/SRR)  
- 📡 **Event notifications**: Trigger Lambda, SNS, or SQS on object events  
- 🌍 **Static website hosting**  
- 📈 **99.999999999% (11 9’s) durability**

---

## 🛠️ Use Cases  
- 🧾 Backup and archiving  
- 🌐 Hosting static websites  
- 🎥 Media storage and streaming  
- 📊 Data lakes and analytics  
- 🧪 Machine learning datasets  
- 🛡️ Disaster recovery  

---

## 🔁 Comparison with Similar Services  

| Service        | Difference from Amazon S3 |
|----------------|----------------------------|
| **Amazon EBS** | Block storage for EC2; S3 is object storage for any use case |
| **Amazon EFS** | File system for Linux-based shared access; S3 is not a file system |
| **Amazon FSx** | Managed file systems; S3 is object-based, not POSIX compliant |

---

## 💰 Pricing  
- 💾 **Storage**: ~$0.023/GB-month (Standard class)  
- 📥 **PUT, GET, DELETE requests**: Charged per 1,000 requests  
- 🚚 **Data transfer**: Free into S3, outbound is charged  
- 💡 Use **Intelligent-Tiering** or **Lifecycle rules** to save on cost  

---

## 🧠 Exam Keywords  
- "Object storage for any scale"  
- "11 nines of durability"  
- "Multiple storage classes"  
- "S3 events to trigger Lambda"  
- "Cross-Region Replication (CRR)"  
- "Bucket policies and encryption"
