# Zewpol Store - App Repository

This repository hosts all HTML apps for the **Zewpol Ecosystem**.

## 📦 How to Publish an App

Apps become visible in the [Zewpol Store](https://zewpol.neocities.org) **immediately** after pushing to this repo.

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

