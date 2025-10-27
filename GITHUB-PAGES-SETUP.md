# GitHub Pages Setup Guide for Flowless

## 📋 Overview
This guide will help you publish the Flowless privacy policy and landing page on GitHub Pages.

## 🚀 Quick Setup (5 minutes)

### Step 1: Push Files to GitHub

```bash
# Navigate to your repository
cd D:\PY_Projects\Flowless

# Add the new files
git add index.html privacy.html Chrome-Web-Store-Materials.md GITHUB-PAGES-SETUP.md

# Commit the changes
git commit -m "Add GitHub Pages landing page and privacy policy"

# Push to GitHub
git push origin main
```

### Step 2: Enable GitHub Pages

1. Go to your repository: https://github.com/gtmengine/Flowless-
2. Click **Settings** (top right)
3. Click **Pages** (left sidebar under "Code and automation")
4. Under **Build and deployment**:
   - Source: Select **Deploy from a branch**
   - Branch: Select **main** and **/ (root)**
   - Click **Save**
5. Wait 1-2 minutes for GitHub to build your site

### Step 3: Verify Your Site

Your site will be live at:
```
https://gtmengine.github.io/Flowless-/
```

Your privacy policy will be at:
```
https://gtmengine.github.io/Flowless-/privacy.html
```

### Step 4: Test the Privacy Policy URL

1. Open: https://gtmengine.github.io/Flowless-/privacy.html
2. Verify all content displays correctly
3. Check that all links work
4. Copy the URL for Chrome Web Store submission

## 📝 Files Included

- **index.html** - Flowless landing page with features and download link
- **privacy.html** - Privacy policy for Chrome Web Store compliance
- **Chrome-Web-Store-Materials.md** - Complete submission guide with all required text

## 🔗 URLs for Chrome Web Store Submission

Copy these URLs when filling out the Chrome Web Store form:

- **Privacy Policy URL:**
  ```
  https://gtmengine.github.io/Flowless-/privacy.html
  ```

- **Official URL (Homepage):**
  ```
  https://gtmengine.github.io/Flowless-/
  ```

- **Support URL:**
  ```
  https://github.com/gtmengine/Flowless-
  ```

## ✅ Checklist

- [ ] Push `index.html` and `privacy.html` to GitHub
- [ ] Enable GitHub Pages in repository settings
- [ ] Wait for site to build (1-2 minutes)
- [ ] Visit https://gtmengine.github.io/Flowless-/ to verify
- [ ] Visit https://gtmengine.github.io/Flowless-/privacy.html to verify
- [ ] Copy privacy policy URL for Chrome Web Store
- [ ] Update Chrome Web Store listing with privacy URL

## 🎯 Next Steps

1. ✅ Set up GitHub Pages (this guide)
2. Upload extension to Chrome Web Store
3. Fill in the privacy policy URL in the store listing
4. Submit for review
5. Update `index.html` with real Chrome Web Store link once approved

## 💡 Pro Tips

- GitHub Pages is case-sensitive - keep all filenames lowercase
- Changes to GitHub Pages can take 1-2 minutes to deploy
- Test all links before submitting to Chrome Web Store
- You can update the privacy policy anytime by pushing changes to GitHub

## 🔄 Updating the Privacy Policy

If you need to update the privacy policy later:

```bash
# Edit privacy.html
# Update the "Last updated" date

git add privacy.html
git commit -m "Update privacy policy"
git push origin main

# Wait 1-2 minutes for changes to deploy
```

## 🆘 Troubleshooting

**Site not loading?**
- Wait 2-5 minutes after enabling GitHub Pages
- Check Settings → Pages for any error messages
- Ensure `index.html` is in the root directory

**Privacy policy not found?**
- Verify `privacy.html` is in the root directory
- Check the filename is exactly `privacy.html` (lowercase)
- Wait a few minutes for GitHub Pages to rebuild

**Need to change the URL?**
- The URL format is: `https://<username>.github.io/<repo-name>/`
- For your repo: `https://gtmengine.github.io/Flowless-/`
- This cannot be changed without renaming the repository
