# 🚀 NumberBox Web & Safe Harbor Portal - GitHub Pages Deployment

This project is a standalone, ultra-modern static web application ready for instant deployment on **GitHub Pages**.

---

## 📌 2-Minute Quick Deploy to GitHub Pages:

### Step 1: Create a GitHub Repository
1. Log into your account on [GitHub](https://github.com/).
2. Click **New Repository**.
3. Name your repository (e.g., `numberbox-site` or `numberbox-safeharbor`).
4. Set visibility to **Public** and click **Create repository**.

---

### Step 2: Push Local Files to GitHub

Run these commands in PowerShell or terminal inside this folder:

```powershell
# Initialize git if needed
git init

# Stage all files
git add index.html assets/ terms/ GITHUB_DEPLOY_GUIDE.md

# Commit
git commit -m "Deploy NumberBox with International Safe Harbor & Pen-Test Authorization"

# Set branch to main
git branch -M main

# Link to your remote GitHub repo (replace with your repo URL)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git

# Push
git push -u origin main
```

---

### Step 3: Enable GitHub Pages
1. In your GitHub repository, open **Settings**.
2. Click on **Pages** in the left sidebar.
3. Under **Build and deployment** > **Source**:
   - Select **Deploy from a branch**.
   - Under Branch, select **`main`** and folder **`/(root)`**.
4. Click **Save**.

---

### 🌐 Live URL
Within 1-2 minutes, your website will be live at:
```
https://<YOUR_USERNAME>.github.io/<YOUR_REPOSITORY>/
```

---

## 🛡️ International Legal Policies Included:
- **Budapest Convention on Cybercrime (ETS No. 185, Article 2 - Lawful Authorized Access)**
- **CFAA (18 U.S.C. § 1030) & US DOJ Policy on Good-Faith Security Research**
- **ISO/IEC 29147 & Disclose.io Core Terms (Legal Safe Harbor)**
- **Explicit Authorization for API Auditing & Database Proof-of-Concept Extraction**
