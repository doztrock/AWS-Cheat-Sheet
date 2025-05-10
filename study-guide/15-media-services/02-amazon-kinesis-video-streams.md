# 📹 Amazon Kinesis Video Streams

---

## 📌 Description  
**Amazon Kinesis Video Streams (KVS)** is a **fully managed service** that enables you to **securely stream, store, and process video and time-encoded data** (like audio, RADAR, LIDAR) from millions of devices to AWS for analytics, machine learning (ML), and playback. It supports **live and on-demand streaming**, and integrates with services like **Amazon Rekognition** and **AWS ML frameworks**.

---

## 🚀 Key Features  
- 📡 **Real-time ingestion** from devices (cameras, smartphones, drones, etc.)  
- 🔐 **Secure storage** with encryption and time-indexing  
- 🧠 **ML integration** with Amazon Rekognition, TensorFlow, OpenCV  
- 🔁 **Playback** via HTTP Live Streaming (HLS)  
- 🧩 **WebRTC support** for ultra-low latency, two-way communication  
- 🗂️ **Edge Agent** for local recording and scheduled cloud uploads  
- 📈 **Scalable infrastructure** without manual provisioning  

---

## 🛠️ Use Cases  
- 🏠 **Smart home**: Doorbell cameras, baby monitors, surveillance  
- 🏙️ **Smart cities**: Traffic monitoring, public safety  
- 🏭 **Industrial automation**: Equipment monitoring, quality control  
- 🧪 **ML applications**: Object detection, facial recognition  
- 🎮 **Interactive apps**: Real-time video chat, AR/VR streaming  

---

## 🔁 Comparison with Similar Services  

| Service                      | Difference from Kinesis Video Streams |
|------------------------------|---------------------------------------|
| **AWS Elemental MediaLive**  | Broadcast-grade live video processing; higher complexity and cost |
| **Amazon IVS**               | Simplified live streaming for interactive video; optimized for low-latency playback |
| **Amazon S3**                | General-purpose storage; lacks real-time ingestion and playback capabilities |

---

## 💰 Pricing  
- 💵 **Ingestion**: $0.0085 per GB  
- 💾 **Storage**: $0.023 per GB-month  
- 📤 **Data consumption**: $0.0085 per GB (ingested), $0.0119 per GB (HLS)  
- 📡 **WebRTC**:  
  - $0.03 per active signaling channel/month  
  - $2.25 per million signaling messages  
  - $0.12 per 1,000 TURN streaming minutes  
- 📌 **Note**: No AWS Free Tier available for KVS

---

## 🧠 Exam Keywords  
- "Real-time video ingestion"  
- "Time-indexed video storage"  
- "Integration with Rekognition and ML frameworks"  
- "WebRTC for low-latency streaming"  
- "Edge Agent for local video recording"  
- "Secure, scalable video processing"
