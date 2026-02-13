# Image Upload Setup Instructions

## Current Status
The page is not loading because the server needs to be started properly.

## Quick Fix - Get the Page Loading

1. **Open Command Prompt or PowerShell**
2. **Navigate to project directory:**
   ```bash
   cd "c:\Users\Dell\Desktop\workshop\campus-confessions"
   ```

3. **Start the server:**
   ```bash
   node server.js
   ```

4. **Open your browser and go to:**
   ```
   http://localhost:3000
   ```

## Image Upload Feature Status

✅ **Frontend:** Complete - Image upload UI is ready
✅ **Database:** Complete - image_url column added
✅ **Backend:** Complete - Image handling code ready
❌ **Dependency:** Missing - Need to install multer

## To Enable Image Uploads

Once the page is loading, install multer:

```bash
npm install multer
```

Then restart the server and the image upload feature will work.

## What's Been Added

- **Add Image Button** in compose area
- **Image Preview** with remove option
- **Image Display** in posts
- **Click-to-Open** full-size images
- **File Validation** (JPG, PNG, GIF, WebP, max 5MB)

## Current Theme
Neutral F1 Racing theme with professional gray/blue color scheme.
