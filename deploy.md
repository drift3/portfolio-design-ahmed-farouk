# 🚀 Deployment Guide

## Quick GitHub Pages Deployment

### Step 1: Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and sign in
2. Click "New repository" (green button)
3. Name it: `portfolio` or `ahmed-farouk-portfolio`
4. Make it **Public**
5. Click "Create repository"

### Step 2: Upload Files
You can upload files in two ways:

#### Option A: Drag & Drop (Easiest)
1. In your new repository, click "uploading an existing file"
2. Drag and drop ALL these files:
   - `index.html`
   - `script.js`
   - `README.md`
   - `pics/` folder (entire folder with all subfolders)

#### Option B: Git Commands (Advanced)
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository **Settings** tab
2. Scroll down to **Pages** section
3. Under "Source", select **Deploy from a branch**
4. Choose **main** branch
5. Leave folder as **/ (root)**
6. Click **Save**

### Step 4: Access Your Website
- Your site will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`
- It may take 5-10 minutes to go live
- GitHub will show you the URL in the Pages settings

## 🔧 Troubleshooting

### Images Not Loading?
- Make sure the `pics` folder is uploaded with all subfolders
- Check that image paths match exactly (case-sensitive)

### Site Not Loading?
- Wait 10 minutes after enabling Pages
- Check that `index.html` is in the root directory
- Ensure repository is public

### Want a Custom Domain?
- Buy a domain (like `ahmedfarouk.com`)
- In Pages settings, add your custom domain
- Update DNS settings with your domain provider

## 📱 Testing Locally
Before deploying, test locally:
```bash
# If you have http-server installed
http-server . -p 3000

# Or just open index.html in your browser
```

## 🎯 Next Steps After Deployment
1. Share your portfolio URL on LinkedIn
2. Add it to your email signature
3. Include it in your resume/CV
4. Share on social media

Your portfolio will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

---
**Need help?** Contact Ahmed at a.faroukcx@gmail.com