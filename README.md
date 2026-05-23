# 🍿 Mivio for Virtual Reality

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Platform Compatibility](https://img.shields.io/badge/Platforms-Meta%20Quest%20%7C%20Pico-brightgreen.svg?style=flat-square)](#platform-specific-goals)
[![Unity](https://img.shields.io/badge/Engine-Unity_3D-black.svg?style=flat-square&logo=unity)](https://unity.com/)

**Mivio VR** is a premium, high-performance immersive media management and playback application tailored for standalone Virtual Reality headsets like Meta Quest and Pico. 

Designed to replicate the ultimate home theater experience, Mivio VR allows users to sit in a virtual cinema and stream media directly from their local network (SMB/WebDAV), without needing a transcoding server.

---

## 🎨 Platform-Specific Experience Goals

Mivio VR breaks out of the 2D plane to deliver spatial computing and cinematic immersion:

- **Immersive Environments**: Virtual cinema rooms, void theaters, and pass-through AR modes for watching movies while seeing the real world.
- **Spatial UI**: Diegetic interfaces, hand-tracking support, and laser-pointer navigation for browsing your network media catalog.
- **Advanced Playback**: Hardware-accelerated decoding of 2D, 3D (SBS/OU), 180°, and 360° video files natively on the headset.
- **Local Network Streaming**: Direct SMB and WebDAV implementations built into the Unity environment to pull large video files seamlessly.

---

## 🚀 Getting Started

### Prerequisites
- **Unity 2022.3 LTS** (or newer) with Android Build Support.
- Meta Quest Developer Hub (for Quest deployment).
- Oculus XR / OpenXR Plugin configured in Unity.

### Setup and Running the Project
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/albertolicea00/mivio-vr.git
   cd mivio-vr
   ```

2. **Open in Unity:**
   Launch Unity Hub, click **Add**, and select the cloned `mivio-vr` folder.

3. **Deploy to Headset:**
   - Connect your Meta Quest via USB (ensure Developer Mode is enabled).
   - In Unity, go to `File > Build Settings`.
   - Select Android, choose your Quest device in the Run Device list.
   - Click **Build and Run**.

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
