# Physical AI & Humanoid Robotics Textbook

This project is an AI-Native technical textbook built with Docusaurus and a RAG (Retrieval-Augmented Generation) chatbot backend.

## Structure

- `/docs`: Textbook chapters in Markdown.
- `/src`: Custom React components (Chatbot, Auth, etc.).
- `/rag-backend`: Python FastAPI backend for the RAG chatbot.
- `/i18n`: Internationalization (English and Urdu support).

## Installation

### Frontend (Docusaurus)
```bash
npm install
```

### Backend (RAG Chatbot)
```bash
cd rag-backend
pip install -r requirements.txt
```

## Local Development

### Start Frontend
```bash
npm start
```

### Start Backend
```bash
cd rag-backend
python main.py
```

## Build & Deployment

### Build Frontend
```bash
npm run build
```

### Deployment to Vercel
1. Push this repository to your GitHub.
2. Connect the repository to Vercel.
3. Vercel will automatically detect Docusaurus and deploy it.

### Deployment to GitHub Pages
```bash
npm run deploy
```
