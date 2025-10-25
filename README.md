# DockGen AI - Demo

## Prereqs
- Node 18+
- Docker
- MongoDB
- OpenAI API Key (set as OPENAI_API_KEY)
- (Optional) GitHub PAT for repo access

## Run backend
cd backend
npm install
export OPENAI_API_KEY="..."
export MONGO_URI="mongodb://localhost:27017/dockgen"
node app.js

## Run frontend
cd frontend
npm install
npm run dev

## Demo
Open http://localhost:3000, paste repo URL and PAT, click Generate & Build.
