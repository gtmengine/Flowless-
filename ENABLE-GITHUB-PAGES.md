# Enable GitHub Pages - Quick Guide

## 🚀 Steps to Enable (Takes 2 minutes)

### 1. Go to Repository Settings
1. Open: https://github.com/gtmengine/Flowless-/settings
2. Or: Go to your repository → Click **Settings** tab (top right)

### 2. Enable GitHub Pages
1. In the left sidebar, click **Pages** (under "Code and automation")
2. Under **Build and deployment**:
   - **Source:** Select **"Deploy from a branch"**
   - **Branch:** Select **"main"** 
   - **Folder:** Select **"/ (root)"**
3. Click **Save**

### 3. Wait for Deployment
- GitHub will show a message: "Your site is ready to be published"
- Wait **1-2 minutes** for the site to build
- Refresh the Pages settings page
- You'll see: "Your site is live at https://gtmengine.github.io/Flowless-/"

### 4. Test Your Site
After 1-2 minutes, visit:
- Landing page: https://gtmengine.github.io/Flowless-/
- Privacy policy: https://gtmengine.github.io/Flowless-/privacy.html

---

## 📸 Visual Guide

### What to look for in Settings → Pages:

```
Build and deployment
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Source
┌─────────────────────────────────────┐
│ Deploy from a branch           [▼] │  ← Select this
└─────────────────────────────────────┘

Branch
┌──────┐  ┌────────┐  
│ main │  │ /(root)│  [Save]  ← Select "main" and "/(root)", then click Save
└──────┘  └────────┘
```

---

## ✅ Verification

After enabling, you should see:

```
✅ Your site is live at https://gtmengine.github.io/Flowless-/

Visit site
```

---

## 🆘 Troubleshooting

**Still getting 404 after 5 minutes?**
1. Check that `index.html` and `privacy.html` are in the root directory (they are ✅)
2. Make sure the branch is set to "main" not "master"
3. Try clicking "Save" again in Settings → Pages
4. Check for any error messages in Settings → Pages

**Repository is private?**
- GitHub Pages requires a **public repository** for free accounts
- Go to Settings → General → Danger Zone → Change visibility → Make public

---

## 📞 Next Steps

Once GitHub Pages is enabled and working:
1. Verify privacy policy loads: https://gtmengine.github.io/Flowless-/privacy.html
2. Copy that URL for Chrome Web Store submission
3. Continue with `READY-TO-PUBLISH.md` instructions

---

**This is a one-time setup. Once enabled, any future changes to `index.html` or `privacy.html` will automatically update within 1-2 minutes.**
