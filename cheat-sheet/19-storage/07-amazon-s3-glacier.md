# 🧊 Amazon S3 Glacier

---

## 📌 Description  
**Amazon S3 Glacier** offers multiple **low-cost, secure, and durable storage classes** for **archiving infrequently accessed data**. It’s ideal for backups, compliance archives, long-term retention, and replacing physical tapes.

---

## 🚀 Key Features  
- 💾 **Archive storage classes** designed for different access speed and cost needs:  
  - ⚡ **S3 Glacier Instant Retrieval**  
  - 🔁 **S3 Glacier Flexible Retrieval** (formerly just "S3 Glacier")  
  - 💤 **S3 Glacier Deep Archive**

- 🧠 Supports lifecycle transitions from S3 Standard, Intelligent-Tiering, etc.  
- 🛡️ Encryption at rest and in transit (supports SSE-S3 & SSE-KMS)  
- 🧾 Designed for **regulatory compliance**, auditability, and long-term data retention  

---

## 🚀 Storage Classes Overview  

| Storage Class                | Description                                           | Retrieval Time                         |
|-----------------------------|-------------------------------------------------------|----------------------------------------|
| **S3 Glacier Instant Retrieval** | For archived data that still needs fast access        | ⚡ Milliseconds (instant)               |
| **S3 Glacier Flexible Retrieval**| For occasional access at low cost, with flexible speeds | 🕒 Expedited (1–5 min), Standard (3–5 h), Bulk (5–12 h) |
| **S3 Glacier Deep Archive**     | Lowest-cost storage for data rarely accessed          | 💤 Standard (12 h), Bulk (up to 48 h)   |

> Use **lifecycle policies** to transition data from other S3 classes to Glacier automatically.

---

## 🔁 Retrieval Modes (Glacier Flexible & Deep Archive only)

| Retrieval Mode | Retrieval Time           | Available In                  | Best For                           |
|----------------|--------------------------|--------------------------------|------------------------------------|
| **Instant**     | Milliseconds              | Instant Retrieval only         | Frequent, fast access              |
| **Expedited**   | 1–5 minutes               | Glacier Flexible               | Urgent access to small files       |
| **Standard**    | 3–5 hours / 12 hours      | Flexible / Deep Archive        | Default access for most use cases  |
| **Bulk**        | 5–12 hours / up to 48 hrs | Flexible / Deep Archive        | Massive restore at the lowest cost |

---

## 🛠️ Use Cases  
- 🧾 Long-term backup and archiving  
- 🔐 Regulatory compliance (HIPAA, FINRA, GDPR)  
- 🧬 Scientific or historical data preservation  
- 💽 Replacing physical tape libraries  
- 📦 Cold storage for audit and DR

---

## 🔁 Comparison with Similar Services

| Service           | Difference from S3 Glacier |
|-------------------|-----------------------------|
| **Amazon S3 Standard** | For frequent access; Glacier is for long-term storage |
| **Amazon EBS**     | Block-level storage; not optimized for archiving         |
| **AWS Backup**     | Can send snapshots to Glacier as part of backup plans    |
| **S3 Intelligent-Tiering** | Can automatically move objects to Glacier Instant Retrieval if configured |

---

## 💰 Pricing

| Storage Class              | Storage Cost        | Minimum Retention | Notes                                 |
|----------------------------|---------------------|--------------------|----------------------------------------|
| Glacier Instant Retrieval  | ~$0.004/GB-month    | 90 days             | Fast access + retrieval request cost   |
| Glacier Flexible Retrieval | ~$0.0036/GB-month   | 90 days             | Flexible retrieval options             |
| Glacier Deep Archive       | ~$0.00099/GB-month  | 180 days            | Lowest cost, slowest retrieval         |

- 📤 Retrieval fees vary depending on mode (Expedited > Standard > Bulk)  
- 🧾 Early deletion charges apply if removed before minimum retention  
- 🚚 Inbound to S3 is free, outbound is charged

---

## 🧠 Exam Keywords  
- "Long-term archival with infrequent access"  
- "Low-cost storage with retrieval delay"  
- "Compliance retention requirements (90/180 days)"  
- "Backup data not accessed frequently"  
- "Tape replacement for cold data"  
- "Use lifecycle policy to transition from S3 Standard"  
- "Not suitable for frequent or low-latency access"  
