# Storytelling Agent (YouTube Auto Uploader)

यह प्रोजेक्ट रोज़ाना 4 बार अपने आप YouTube पर AI Generated हिंदी Stories Upload करता है।  
This project automatically generates 4 YouTube videos daily with AI stories, TTS, and uploads.

## Setup Guide (Steps)

1. इस ZIP को GitHub पर upload करें।
2. Repo settings → Secrets → Actions में ये जोड़ें:
   - `OPENAI_API_KEY` = आपकी OpenAI key
   - `GOOGLE_CLIENT_SECRET` = Google OAuth JSON का पूरा content
3. Repo में `.github/workflows/daily-4-videos.yml` पहले से दिया है।

### Auto Schedule (IST)
- सुबह 9 बजे
- दोपहर 1 बजे
- शाम 5 बजे
- रात 9 बजे

GitHub Actions अपने आप run करेगा और आपकी videos generate + upload होंगी।
