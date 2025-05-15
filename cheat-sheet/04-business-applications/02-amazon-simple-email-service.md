# 📧 Amazon Simple Email Service (Amazon SES)

---

## 📌 Description  
**Amazon SES** is a **scalable, cloud-based email service** that enables businesses to **send and receive email securely** for use cases like **marketing**, **transactional messaging**, and **notifications**. It supports high deliverability and integrates easily with other AWS services and applications.

---

## 🚀 Key Features  
- 📤 **Send Emails**: Transactional, marketing, or bulk email  
- 📥 **Receive Emails**: Use rules to filter, process, or store incoming messages  
- 📈 **High Deliverability**: Email authentication (DKIM, SPF, DMARC) to improve trust and reduce spam  
- 🔐 **Secure**: Supports TLS encryption, IAM policies, and VPC endpoints  
- 🔄 **Flexible Integration**: SMTP interface, SDKs, or Amazon SES API  
- 📊 **Monitoring & Analytics**: Track open/click rates, bounce rates, complaints  
- 🔔 **Notifications**: Integrate with SNS for delivery/bounce notifications  

---

## 🛠️ Use Cases  
- 🧾 **Transactional Email**: Order confirmations, password resets  
- 💼 **Marketing Campaigns**: Newsletters and promotional content  
- 📣 **Automated Alerts**: System or application notifications  
- 📩 **Custom Inbound Processing**: Parse or store incoming email in S3/Lambda  

---

## 🔁 Comparison with Similar Services  

| Service         | Difference from Amazon SES |
|------------------|----------------------------|
| **Amazon SNS**   | SNS is for push notifications; SES is for email-based messaging |
| **Pinpoint**     | SES focuses on email; Pinpoint is for multichannel marketing (SMS, push, voice, email) |
| **Third-party SMTP (e.g., SendGrid)** | SES offers tighter AWS integration, lower cost, and better control for AWS-hosted apps |

---

## 💰 Pricing  
- **Email Sending**:  
  - $0.10 per 1,000 emails sent  
  - $0.12 per GB of attachments  
- **Email Receiving**:  
  - $0.10 per 1,000 emails received  
- **Free Tier**:  
  - 62,000 emails/month when sent from an EC2 instance  
- **Dedicated IPs**:  
  - $24.95/month per IP (optional)  

---

## 🧠 Exam Keywords  
- "Transactional email service"  
- "High deliverability (SPF, DKIM, DMARC)"  
- "Send and receive emails"  
- "SNS for delivery/bounce notifications"  
- "Integrated with Lambda, S3, and CloudWatch"
