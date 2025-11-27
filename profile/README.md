# 🎧 Audiome

<div align="center">

<img src="https://img.shields.io/badge/Audiome-Where%20Everyone%20Controls%20The%20Story-00d4ff?style=for-the-badge&logo=headphones&logoColor=white" alt="Audiome"/>

### **A Platform Where Everyone Controls The Story**

*AudioMe transforms books into immersive and interactive journeys that connects creators and booklovers worldwide.*

[![App Store](https://img.shields.io/badge/Download-App%20Store-000000?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com)
[![Play Store](https://img.shields.io/badge/Download-Play%20Store-3DDC84?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com)
[![Website](https://img.shields.io/badge/Visit-audiome.tech-00d4ff?style=for-the-badge&logo=safari&logoColor=white)](https://audiome.tech)

</div>

---

## 🌟 About Audiome

**Transforming Stories Into Living Experiences**

Audiome bridges the gap between traditional reading and immersive audio. Whether you're a listener or a creator, our AI-powered platform makes it simple to enjoy, share, and create stories.

<table>
<tr>
<td width="50%">

### 🎨 Designed for Effortless Creativity
A simple, intuitive structure that helps beginners start fast while offering the flexibility experts need to create freely.

</td>
<td width="50%">

### 🤖 AI That Brings Stories to Life
Regenerative AI brings emotion, clarity, and depth to every narration, making each moment more immersive.

</td>
</tr>
<tr>
<td width="50%">

### 🌍 Reach Audiences Everywhere
Share your work with a global community and connect with listeners from diverse cultures and backgrounds instantly.

</td>
<td width="50%">

### 💰 Create and Earn with Ease
Publish your stories, track your growth, and earn revenue through engagement-driven monetization tools.

</td>
</tr>
</table>

---

## ✨ Key Features

### 🎙️ Listen Live, Connect Instantly
Discover a new way to connect through stories and enjoy moments that bring people closer.

### 📚 Genre-Driven Community Hubs
Join a vibrant community of listeners who love what you love. Get personalized recommendations from people who share your taste.

### 🎤 Create. Connect. Cultivate.
Turn your passion for books into a movement. Host your club, share your voice, and watch your listening community thrive.

### 🔊 Personalize Your Voice Experience
Choose from diverse AI voices and tailor tone, style, and pace to match your story.

### 📖 Your Books, Brought to Life
Turn written stories into immersive audio and reach listeners everywhere.

---

## 💬 What Users Say

> *"AudioMe feels like it was built just for me. I choose the voice, set the pace, bookmark moments, and even upload my own."*
> — **James K.**

> *"I've never experienced books like this before. It feels like I'm living the story, not just hearing it."*
> — **Emma R.**

> *"I came for the books and stayed for the people. I didn't just find a community. I built one."*
> — **Ethan B.**

> *"The moment I realized I could upload my own voice for narration, I was hooked. AudioMe makes storytelling feel personal and powerful."*
> — **Emily V.**

---

## 🏗️ Platform Architecture

```
┌─────────────────────────────────────────────────────────────────────┐
│                         Audiome Platform                             │
├─────────────────────────────────────────────────────────────────────┤
│                                                                       │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐               │
│  │   Web App    │  │  Mobile App  │  │   Admin      │               │
│  │              │  │  iOS/Android │  │   Panel      │               │
│  └──────┬───────┘  └──────┬───────┘  └──────┬───────┘               │
│         │                 │                  │                        │
│         └────────────────┼──────────────────┘                        │
│                          ▼                                            │
│  ┌───────────────────────────────────────────────────────────────┐  │
│  │                    API Gateway (GKE)                           │  │
│  │                   api.dev.audiome.tech                         │  │
│  └───────────────────────────────────────────────────────────────┘  │
│                          │                                            │
│    ┌─────────┬──────────┼──────────┬─────────┬─────────┐            │
│    ▼         ▼          ▼          ▼         ▼         ▼            │
│ ┌──────┐ ┌──────┐ ┌──────────┐ ┌──────┐ ┌──────┐ ┌──────────┐      │
│ │ Auth │ │ TTS  │ │  Books   │ │ PDF  │ │ Live │ │Transcribe│      │
│ │  API │ │  API │ │   API    │ │ API  │ │  API │ │   API    │      │
│ └──────┘ └──────┘ └──────────┘ └──────┘ └──┬───┘ └──────────┘      │
│                                             │                         │
│  ┌──────────────────────────────────────────┴────────────────────┐  │
│  │                    LiveKit (WebRTC)                            │  │
│  │              Real-time Audio Streaming                         │  │
│  └────────────────────────────────────────────────────────────────┘  │
│                                                                       │
└─────────────────────────────────────────────────────────────────────┘
```

---

## 📦 Repositories

| Repository | Description | Stack |
|------------|-------------|-------|
| [**stage-k8s-deployment**](https://github.com/Audiome-25/stage-k8s-deployment) | Kubernetes manifests & infrastructure | `K8s` `GKE` `Helm` |
| [**audiome-live**](https://github.com/Audiome-25/audiome-live) | Live streaming & real-time features | `Python` `FastAPI` `LiveKit` |
| [**standalone-transcribe-service**](https://github.com/Audiome-25/standalone-transcribe-service) | Audio transcription service | `Python` `Speechmatics` |

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LiveKit](https://img.shields.io/badge/LiveKit-FF6B6B?style=flat-square&logo=webrtc&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

</div>

---

## 👥 Team

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/AudioMe25">
        <img src="https://github.com/AudioMe25.png" width="80px;" alt=""/>
        <br /><sub><b>AudioMe25</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/bhavika-ci">
        <img src="https://github.com/bhavika-ci.png" width="80px;" alt=""/>
        <br /><sub><b>bhavika-ci</b></sub>
      </a>
    </td>
  </tr>
</table>

---

<div align="center">

### 🚀 Experience Stories, Sound, and Connection

**Download for free and start your journey today!**

[![App Store](https://img.shields.io/badge/App%20Store-Download-000000?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com)
[![Play Store](https://img.shields.io/badge/Play%20Store-Download-3DDC84?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com)

---

**© 2025 AudioMe. All rights reserved.**

[Privacy Policy](https://audiome.tech/privacy) • [Terms of Use](https://audiome.tech/terms) • [Contact](mailto:contact@audiome.tech)

</div>
