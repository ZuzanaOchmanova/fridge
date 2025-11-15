## Structure

- `backend/` – Python API (FastAPI or Azure Functions)
- `mobile/` – React Native Android app
- `docs/` – notes, diagrams, roadmap

## Smart Fridge Tracker Describtion🍳🥦
AI-assisted fridge inventory & expiry tracker

Smart Fridge Tracker is a learning and portfolio project focused on building an end-to-end system for reducing food waste. The app helps users track what’s in their fridge, monitor expiration dates, and avoid buying duplicates while shopping.

Core Idea
  Quickly add items to your fridge inventory
  See what you have left (e.g. “3 eggs left”)
  Get notified before items expire

Features (planned & in progress)
📱 Mobile app (Android, React Native / Expo)
  Manual item entry (product name, quantity, expiry date)
  Sort and filter items by expiration date (e.g. “expiring soon”)
  Configurable reminders (e.g. 7 days and 1 day before expiry)
  Local notifications on Android

🧠 AI / ML (Python backend)
  Image-based product input: add items by taking a photo
  Computer vision / OCR to:
  Recognize products
  Extract expiration dates from packaging (long-term goal)

☁️ Backend & Infrastructure
  Backend/API in Python (e.g. FastAPI or Azure Functions)
  Deployed on Microsoft Azure
  Database for fridge items and quantities
  Blob storage for product images
  Future: push notifications via backend service

Purpose

This is not a commercial product. It is a personal learning project designed to showcase:
  Python, machine learning, and computer vision
  API design and cloud deployment on Azure
  Integration between a mobile app, backend, database, and AI components
