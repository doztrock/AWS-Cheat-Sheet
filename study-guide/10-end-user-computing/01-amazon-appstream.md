# 💻 Amazon AppStream 2.0

---

## 📌 Description  
**Amazon AppStream 2.0** is a **fully managed application streaming service** that allows you to **deliver desktop applications securely** to any device via a web browser, without the need for rewriting applications or managing complex infrastructure. It enables users to access the applications they need from anywhere, while centralizing application management and scaling automatically based on demand.

---

## 🚀 Key Features  
- 🌐 **Access Anywhere**: Stream applications to users on Windows, Linux, macOS, or Chromebooks via HTML5 browser or AppStream client.
- 🛠️ **Image Builder**: Install and configure applications on a virtual machine to create custom images for streaming.
- 🧩 **Fleet Types**: Choose between Always-On, On-Demand, and Elastic fleets to balance cost and performance.
- 🔐 **Secure Access**: Integrate with SAML 2.0 for single sign-on (SSO) and use AWS Identity and Access Management (IAM) for fine-grained access control.
- 📁 **Persistent Storage**: Provide users with access to home folders backed by Amazon S3, Google Drive, or OneDrive.
- 🎨 **Graphics Support**: Utilize GPU-enabled instances for graphics-intensive applications like CAD or 3D modeling.
- 📊 **Monitoring**: Use Amazon CloudWatch to monitor fleet utilization and performance metrics.

---

## 🛠️ Use Cases  
- 🧪 **Software Trials and Demos**: Allow users to try applications without installation.
- 🏫 **Education**: Provide students with access to applications for learning environments.
- 🏢 **Remote Work**: Enable employees to access corporate applications securely from any location.
- 🎨 **Design and Engineering**: Stream graphics-intensive applications for design, engineering, and simulation tasks.
- 🛠️ **Application Modernization**: Convert traditional desktop applications to a Software-as-a-Service (SaaS) delivery model.

---

## 🔁 Comparison with Similar Services  

| Service                  | Difference from Amazon AppStream 2.0 |
|--------------------------|--------------------------------------|
| **Amazon WorkSpaces**    | Provides full virtual desktops, whereas AppStream 2.0 streams individual applications. |
| **AWS App Runner**       | Designed for deploying web applications and APIs, not for streaming desktop applications. |
| **Amazon EC2**           | Requires manual setup and management of virtual machines; AppStream 2.0 offers managed application streaming. |

---

## 💰 Pricing  
- **Fleet Instances**:
  - *Windows*: $0.10 per hour for stream.standard.medium instances.
  - *Linux*: $0.084 per hour for stream.standard.medium instances.
- **Stopped Instance Fee**: $0.025 per hour when instances are stopped but provisioned.
- **User Fee**: $4.19 per authorized user per month for Windows fleets (no user fee for Linux).
- **Image Builder**: Charged per hour based on instance type.
- **Public IPv4 Addresses**: $0.005 per hour per address.
- *Note*: Pricing varies by AWS Region and usage; refer to the [official pricing page](https://aws.amazon.com/appstream2/pricing/) for detailed information.

---

## 🧠 Exam Keywords  
- "Application streaming service"
- "Image builder and fleet"
- "SAML 2.0 integration"
- "Persistent user storage with Amazon S3"
- "Graphics-intensive application support"
- "Secure, scalable application delivery"
