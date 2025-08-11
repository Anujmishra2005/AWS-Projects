# 🎬 Podcast to Viral Clips SaaS

## Overview
This is a SaaS application that automatically converts full-length podcasts into short, engaging clips optimized for platforms like **YouTube Shorts** and **TikTok**. The platform uses AI-powered transcription, speaker detection, and video cropping to highlight the most interesting parts of a podcast and deliver ready-to-post vertical clips. It is built to handle multiple users, includes a credit-based payment system, and runs on scalable serverless infrastructure.

---

## ✨ Features
- 🎯 **Automatic Viral Moment Detection** – Finds the most engaging parts of a podcast (stories, questions, reactions).  
- 📝 **Accurate Transcription** – Powered by `whisperX`.  
- 🎤 **Active Speaker Detection** – Crops video to the person speaking using `LR-ASD`.  
- 📱 **Vertical Video Optimization** – Perfect for TikTok, Instagram Reels, and YouTube Shorts.  
- 🔊 **Automatic Subtitles** – Enhances engagement and accessibility.  
- ⚡ **GPU-Accelerated Rendering** – Fast processing with `FFMPEGCV`.  
- 💳 **Credit-Based System** – Users can purchase credits for processing.  
- 🛒 **Stripe Integration** – Secure payments for credit packs.  
- 👤 **User Authentication** – Powered by `Auth.js`.  
- 📊 **Dashboard** – Upload podcasts, view generated clips, and track credits.  
- ⏱ **Queue Processing with Inngest** – Handles long-running tasks efficiently.  
- 🌐 **Serverless Backend** – Podcast processing via **FastAPI** + **Modal**.  
- ☁ **AWS S3 Storage** – Secure file uploads and downloads.

---

## 🛠 Tech Stack
**Frontend:** Next.js 15, React, TypeScript, Tailwind CSS, ShadCN, Auth.js  
**Backend:** Python, FastAPI, whisperX (Transcription), LR-ASD (Active Speaker Detection), Gemini 2.5 Pro (Viral Moment Identification), FFMPEGCV (GPU Rendering), Modal (Serverless Processing), Inngest (Queue Management)  
**Cloud & Payments:** AWS S3, Stripe

---

## 📦 Quick Start

### Clone the Repository
```bash
git clone https://github.com/Anujmishra2005/AWS-Projects.git
