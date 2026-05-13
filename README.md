# SkyStudio Website - Railway Deploy

## Deploy to Railway

### Option 1: Using Railway CLI
```bash
# Install Railway CLI
npm install -g @railway/cli

# Login
railway login

# Initialize project
railway init

# Deploy
railway up
```

### Option 2: Using GitHub
1. Push this folder to a GitHub repo
2. Go to railway.app
3. Click "New Project" → "Deploy from GitHub repo"
4. Select your repo
5. Railway will auto-detect Flask and deploy!

### Option 3: Using Railway Button
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/yourusername/skystudio-website)

## Files Structure
```
.
├── app.py              # Flask server
├── Procfile            # Railway process file
├── requirements.txt    # Python dependencies
├── runtime.txt         # Python version
├── .gitignore
└── static/
    ├── index.html      # Main website
    └── skystudio_icon.png  # Server icon
```

## Environment Variables
None required! The app runs on PORT env var automatically set by Railway.

## Local Testing
```bash
pip install -r requirements.txt
python app.py
```
Then open http://localhost:5000
# You
# You
# You
