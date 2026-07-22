# 🛡️ AlertGuard — Driver Drowsiness Detection and Safety Monitoring System

AlertGuard is a real-time, AI-powered safety application that monitors driver alertness using computer vision and immediately warns the driver — and, in critical situations, a guardian — when signs of drowsiness are detected.

Built with **Python, Flask, OpenCV, and MediaPipe**, the system analyzes facial landmarks to compute the **Eye Aspect Ratio (EAR)**, detect yawning, and track head pose, classifying the driver's state as **Active, Drowsy, or Sleeping**. It combines this with secure facial-recognition login, a live monitoring dashboard, sound alerts, and automatic emergency SMS with live location — all in one platform.

---

## ✨ Features

- 🔐 **Biometric Login** — Facial recognition with liveness detection for secure, spoof-resistant access
- 👁️ **Real-Time Drowsiness Detection** — Eye Aspect Ratio (EAR) based eye-closure tracking
- 😮 **Yawn Detection** — Mouth-opening analysis to flag fatigue
- 🧭 **Head Pose Estimation** — Detects distraction and abnormal head positions
- 📊 **Live Dashboard** — Real-time camera feed, EAR graph, driver status, and alert panel
- 🔊 **Sound Alerts** — Instant audio warnings when drowsiness is detected
- 📍 **Emergency SMS Alerts** — Auto-sends live location to a registered guardian via **Twilio** when critical drowsiness (prolonged sleep) is detected
- 🗺️ **Live Location Tracking** — Integrated with **Google Maps API**
- 📁 **Document Management** — Upload and manage documents (e.g., driving license)
- 📝 **Activity Logs** — Timestamped logs of driver status, downloadable for review

---

## 🏗️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Python, Flask |
| Computer Vision / ML | OpenCV, MediaPipe |
| Frontend | HTML, CSS, JavaScript |
| Alerts | Twilio API (SMS) |
| Location | Google Maps API |
| Database | User / Logs / Documents tables |

---

## ⚙️ System Architecture

The system follows a **modular, layered, client-server architecture**:

1. **Authentication Module** — Registration & login via facial recognition + liveness detection
2. **Detection Module** — Real-time facial landmark analysis (EAR, yawn, head pose) using MediaPipe/OpenCV
3. **Dashboard Module** — Live visualization of camera feed, EAR graph, status, and logs
4. **Alert Module** — Sound warnings + SMS alerts via Twilio
5. **Map & Location Module** — Live tracking via Google Maps API
6. **Log Management Module** — Records and stores timestamped activity logs

### Flow
`System Init → Login/Register → Face Verification & Liveness Check → Dashboard → Camera Activation → Frame Capture → Landmark Detection → EAR/Yawn/Head Pose Calculation → State Classification → Alerts/Logs Update`

---

## 🧪 Testing

The system was validated through unit, integration, functional, performance, and scenario-based testing — simulating normal driving, drowsy, and sleeping conditions to confirm detection accuracy and alert reliability.

---

## 🔮 Future Scope

- Dedicated in-vehicle hardware integration (sensors/embedded systems)
- Deep-learning-based detection for better accuracy across lighting/occlusion conditions
- Voice & vibration alerts, automatic vehicle control triggers
- Cloud storage and analytics for driving behavior
- Mobile app version
- Predictive analytics for early fatigue warnings

---

## 👥 Team

| Name | Roll No. | Division |
|---|---|---|
| Anusha Patil | 2425000174 | B-44 |
| Pratik Patil | 2425000705 | B-46 |
| Shrutika Patil | 2425001031 | B-50 |
| Adarsh Gurav | 2425000776 | B-73 |
| Sanket Magdum | 2425000540 | B-77 |

**Guide:** Mr. Chaitanya Pednekar
**Institution:** Kolhapur Institute of Technology's College of Engineering, Kolhapur (Empowered Autonomous)

---

## 📚 References

- [OpenCV Documentation](https://opencv.org)
- [MediaPipe Documentation](https://developers.google.com/mediapipe)
- [Flask Documentation](https://flask.palletsprojects.com)
- [Twilio Documentation](https://www.twilio.com/docs)
- [Google Maps Platform Documentation](https://developers.google.com/maps)
- Soukupová & Čech (2016), *Real-Time Eye Blink Detection using Facial Landmarks*
- Abtahi et al. (2014), *Yawning Detection Using Embedded Smart Cameras*, IEEE

---

## 📄 License

This project was developed as part of an academic Mini Project II submission.
