# Zewpol Store - App Repository

This repository hosts all HTML apps for the **Zewpol Ecosystem**.

## 📦 How to Publish an App

Apps become visible in the [Zewpol Store](https://zewpol.neocities.org) **A bit after** after pushing to this repo.

### Step 1: Create Your HTML App

Create an HTML file in the `/apps` folder (e.g., `my-awesome-app.html`)

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Zewpol App</title>
    <style>
        body { background: #000; color: #0f0; font-family: monospace; }
    </style>
</head>
<body>
    <h1>My Awesome App</h1>
    <script>
        // Your app logic here
    </script>
</body>
</html>
```
Step 2: add your registry to the apps-registry.json file
```
{
  "id": "my-awesome-app",
  "name": "My Awesome App",
  "version": "1.0.0",
  "description": "What this app does",
  "author": "Your Name",
  "verified": false,
  "downloads": 0,
  "rating": 0,
  "htmlFile": "my-awesome-app.html",
  "reviews": []
}
```
Step 3: Done! 🎉

Your app will appear in the Zewpol Store within seconds.

📋 App Requirements

Requirement Details
Format HTML only (can include CSS/JS)
Size Limit 5MB max
Verified Producer Contact Zewpol team to get verified badge
Reviews Apps need 10+ downloads before reviews can be left

🔧 Registry Fields

Field Type Required Description
id string ✅ Unique identifier (no spaces)
name string ✅ Display name
version string ✅ Semantic version (e.g., 1.0.0)
description string ✅ Short description (max 200 chars)
author string ✅ Developer name
verified boolean ✅ Whether producer is verified
downloads number ✅ Download counter (starts at 0)
rating number ✅ Average rating (starts at 0)
htmlFile string ✅ Filename in /apps folder
reviews array ✅ Array of review objects

📊 Auto-Updating Fields

The Zewpol Store automatically tracks:

· Downloads - Incremented when users install
· Ratings - Calculated from user reviews
· Reviews - Stored locally (future: GitHub sync)

🏷️ Getting Verified

Verified producers get a ✓ badge in the store. Requirements:

· 5+ published apps OR
· 10+ total downloads OR
· Official Zewpol partnership
and your done! (NOTE: PUBLICATION TO THE APP STORE MAY TAKE 2-5 WEEKS TO HAPPEN)
