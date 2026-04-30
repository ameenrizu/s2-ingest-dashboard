# 🎬 S2 Ingest Dashboard

A lightweight dashboard prototype for monitoring VFX ingest pipeline status.

## 🚀 Overview
This tool provides a visual interface to track the status of shots across different pipeline stages.  
Currently built using a simple HTML, CSS, and JavaScript stack.

## ✨ Features
- 📥 Ingest status tracking
- 🎞️ Proxy / QT generation status
- 🔗 Symlink availability
- 🔐 Permission checks
- 💾 Storage / path validation
- ⚠️ Remarks / issue tracking
- 📊 Overall shot status with visual indicators
- 🔍 Search, filter, and sorting support
- 🔄 Auto refresh with timer
- 🧪 Dummy / mock data toggle

## 🧪 Current Mode
- Runs in **Mock Data Mode**
- Supports both:
  - Manual dummy shots
  - Random generated test data

## 🔌 API Integration (Future)
The dashboard is designed to plug into a real backend API.

Integration point:
```js
async function getData()
