# Preview

![App Screenshot](./assets/Clean%20search%20app.png)

## Clean Search

Minimalist search interface built with FastAPI and vanilla JavaScript.  
Focused on clean UI, fast response, and distraction-free experience.

## Demo

👉 <https://clean-search-app-production.up.railway.app/>

## Features

- Real-time search using SerpAPI
- Clean and minimal UI (Tailwind CSS)
- Loading, empty, and error states
- Race condition handling (prevents outdated results)
- Responsive layout

## Tech Stack

- FastAPI (Python backend)
- Vanilla JavaScript (Fetch API)
- Tailwind CSS (UI)
- Railway (deployment)

## Project Goal

This project was built to demonstrate full-stack development:

- API integration
- Backend + frontend interaction
- State handling in UI
- Clean and consistent design system
- Production deployment

## Run Locally

```bash
pip install -r requirements.txt
uvicorn main:app --reload
