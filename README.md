# DynamicMediaPro – Video Editing Portfolio

Custom-built portfolio website for **Adejumo Oluwatobi Emmanuel** (`DynamicMediaPro`).

## ✨ Features

- **Modern Cinematic Dark Theme**: Tailored specifically for video editors and motion designers.
- **WhatsApp Integration Everywhere**:
  - Main Hero CTA with pre-filled message: *"Hi Oluwatobi, I saw your portfolio and want to work together!"*
  - Floating WhatsApp action button (bottom-right) with unread notification badge.
  - Final conversion CTA section: *"Chat Directly on WhatsApp"*.
  - Header & Footer direct chat links.
- **Interactive Video Showcases**:
  - **Short-Form (9:16 Vertical)**: Reels / Shorts / TikTok format with hover preview, audio unmuting, view counts, and fullscreen modal.
  - **Long-Form (16:9 YouTube)**: Embedded HD player with custom badges, YouTube auto-thumbnails, and playback modal.
- **Built-in Video & WhatsApp Manager**:
  - Click **"+ Add New Video"** directly on the site to paste new YouTube links or MP4s.
  - Click **"WhatsApp #"** / **"Settings"** to update your phone number and greeting message anytime.
- **Zero Dependencies Needed**:
  - Runs directly in any web browser without needing Node.js, Python, or terminal build tools.
  - Double-click `index.html` to view it immediately!

---

## 🚀 How to Run & View Locally

1. Open File Explorer to:
   ```
   C:\Users\tobil\.gemini\antigravity\scratch\dynamicmediapro-portfolio
   ```
2. Double-click `index.html` to open it in Chrome, Edge, Brave, or your preferred browser.

---

## 🌐 How to Publish Online for Free

### Option 1: Netlify Drop (Easiest - 30 seconds)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop the `dynamicmediapro-portfolio` folder into the browser window.
3. Your site is instantly live with a free SSL certificate! You can connect your custom domain (e.g. `dynamicmediapro.com`) for free.

### Option 2: Vercel
1. Go to [https://vercel.com](https://vercel.com).
2. Upload this folder or connect via GitHub.
3. Deploy in 1 click.

---

## 📞 How to Permanently Hardcode Your WhatsApp Number

In [index.html](file:///C:/Users/tobil/.gemini/antigravity/scratch/dynamicmediapro-portfolio/index.html), search for line ~600:
```javascript
config: {
  whatsappNumber: "2348077140068", // Replace with your phone number (e.g. 2348123456789)
  defaultMessage: "Hi Oluwatobi, I saw your portfolio and would like to discuss a video project!"
}
```
Replace `2348077140068` with your actual phone number (country code first, no `+` or spaces).
