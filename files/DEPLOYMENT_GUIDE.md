# Extended Stay America Cincinnati Welcome Page
## Complete Deployment & Usage Guide

---

## 📋 Table of Contents
1. [Running Locally in VS Code](#running-locally-in-vs-code)
2. [Deploying to GitHub Pages (FREE!)](#deploying-to-github-pages)
3. [Creating QR Code](#creating-qr-code)
4. [Sending to Clients](#sending-to-clients)

---

## 🚀 RUNNING LOCALLY IN VS CODE

### **Step 1: Install VS Code (if not already installed)**
1. Go to https://code.visualstudio.com/
2. Download and install for your operating system
3. Open VS Code

### **Step 2: Open the Project Folder**
1. Create a new folder on your computer (e.g., `esa-welcome-page`)
2. In VS Code, click **File → Open Folder**
3. Select your new folder and click **Open**

### **Step 3: Add the Files**
1. Copy these files into your folder:
   - `index.html` (the main page)
   - `logo.jpeg`
   - `esa1.jpeg`
   - `esa2.jpeg`
   - `esa3.jpeg`
   - `New-Fire-TV-Home-Navigation-Icons-showing-Input-tab.webp`
   - `hPqDtwfxN4NOD4s6b6ecWwSRY__1_.avif`

**Folder structure should look like:**
```
esa-welcome-page/
├── index.html
├── logo.jpeg
├── esa1.jpeg
├── esa2.jpeg
├── esa3.jpeg
├── New-Fire-TV-Home-Navigation-Icons-showing-Input-tab.webp
├── hPqDtwfxN4NOD4s6b6ecWwSRY__1_.avif
└── DEPLOYMENT_GUIDE.md
```

### **Step 4: Install Live Server Extension (RECOMMENDED)**
1. In VS Code, click the **Extensions** icon (left sidebar, looks like 4 squares)
2. Search for **"Live Server"** by Ritwick Dey
3. Click **Install**
4. Restart VS Code

### **Step 5: Run the Page Locally**
**Option A: Using Live Server (Recommended)**
1. Right-click on `index.html`
2. Select **"Open with Live Server"**
3. Your page opens in your browser automatically!
4. Changes auto-refresh as you make edits

**Option B: Without Live Server**
1. In your folder, double-click `index.html`
2. It opens in your default browser

---

## 📤 DEPLOYING TO GITHUB PAGES (FREE!)

### **Why GitHub Pages?**
✅ Completely FREE  
✅ No credit card needed  
✅ 1GB storage (more than enough)  
✅ Lightning-fast loading  
✅ Professional URL  
✅ Auto-updates when you push code  

### **Step 1: Create a GitHub Account (if you don't have one)**
1. Go to https://github.com
2. Click **Sign up**
3. Create account with your email
4. Verify email
5. Complete setup

### **Step 2: Create a New Repository**
1. After logging in, click **+** (top right) → **New repository**
2. Name it: `esa-welcome-page` (or any name you want)
3. **Description**: "Extended Stay America Cincinnati Guest Welcome Guide"
4. Choose **Public** (important for GitHub Pages to work)
5. Check **"Add a README file"**
6. Click **Create repository**

### **Step 3: Upload Your Files to GitHub**

**Option A: Using GitHub Website (Easier for Beginners)**
1. In your new repository, click **Add file → Upload files**
2. Drag and drop these files OR click to browse:
   - `index.html`
   - `logo.jpeg`
   - `esa1.jpeg`
   - `esa2.jpeg`
   - `esa3.jpeg`
   - `New-Fire-TV-Home-Navigation-Icons-showing-Input-tab.webp`
   - `hPqDtwfxN4NOD4s6b6ecWwSRY__1_.avif`
3. Click **Commit changes** (green button at bottom)
4. Wait 2-3 minutes

**Option B: Using Git Command Line (More Professional)**
*Skip this if you did Option A*

1. Download **Git** from https://git-scm.com/
2. Open Command Prompt (Windows) or Terminal (Mac/Linux)
3. Navigate to your folder:
```bash
cd path/to/esa-welcome-page
```

4. Initialize git:
```bash
git init
git add .
git commit -m "Initial commit: Add ESA welcome page"
```

5. Copy the URL from your GitHub repo and run:
```bash
git remote add origin https://github.com/YOUR-USERNAME/esa-welcome-page.git
git branch -M main
git push -u origin main
```

### **Step 4: Enable GitHub Pages**
1. Go to your repository
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under "Source", select **main** branch
5. Click **Save**
6. Wait 2-5 minutes
7. You'll see: "Your site is published at: `https://YOUR-USERNAME.github.io/esa-welcome-page`"

### **Step 5: Test Your Live Site**
1. Click the link provided (or paste it in browser)
2. Your page is now LIVE on the internet! 🎉

---

## 🔗 CREATING A QR CODE (FREE!)

### **What's a QR Code?**
A small square barcode that guests can scan with their phone camera to instantly visit your page. No typing needed!

### **Method 1: QR Code Monkey (Easiest)**
1. Go to https://www.qrcode-monkey.com/
2. In the left panel, select **URL**
3. Paste your GitHub Pages URL:
   ```
   https://YOUR-USERNAME.github.io/esa-welcome-page
   ```
4. Click **Generate QR Code** (right side)
5. You can customize colors:
   - Change colors in left panel
   - Add your logo (optional)
6. Click **Download** → Save as PNG
7. Print and post in your hotel lobby, rooms, and welcome desk!

### **Method 2: Google Charts (Super Simple)**
Just visit this URL (replace with your actual URL):
```
https://chart.googleapis.com/chart?chs=300x300&chld=L|0&cht=qr&chl=https://YOUR-USERNAME.github.io/esa-welcome-page
```
It generates a QR code instantly!

### **Method 3: Free Online Generators**
- https://www.qr-code-generator.com/ (Easy, lots of options)
- https://qrfy.com/ (Simple and fast)
- https://create.qrcode.studio/ (Advanced customization)

---

## 💼 SENDING TO YOUR CLIENTS

### **Option 1: Share the Live Link (BEST)**
"Here's your guest welcome page:"
```
https://YOUR-USERNAME.github.io/esa-welcome-page
```
✅ They click the link - page loads instantly!  
✅ Works on any device (phone, tablet, computer)  
✅ No installation needed  

### **Option 2: Print the QR Code**
1. Generate QR code (see above)
2. Print and place in:
   - Welcome packets
   - Guest rooms
   - Lobby notice board
   - Check-in desk
   - Elevators
3. Guests scan with phone camera = instant access

### **Option 3: Text/Email the Link**
Send via:
- Text message: "Welcome! View guest info: [link]"
- Email: "Welcome to ESA Cincinnati. Here's your guide: [link]"
- WhatsApp: Share link directly
- Hotel app/website: Embed or link to it

### **Option 4: Display Code on TVs**
1. Upload QR code to your room TVs
2. Display on welcome channel
3. Guests scan instantly

---

## 🔄 UPDATING YOUR PAGE

### **To Make Changes:**

**If hosting on GitHub:**
1. Make changes to `index.html` locally in VS Code
2. Save the file
3. Open Command Prompt in your folder:
```bash
git add .
git commit -m "Update: [describe what changed]"
git push origin main
```
4. Wait 1-2 minutes
5. Changes appear on live site automatically!

**If just running locally:**
1. Edit `index.html` in VS Code
2. Save
3. Live Server auto-refreshes (if using it)

---

## 📱 TESTING ON MOBILE

### **Test on Your Phone:**
1. Open browser on your phone
2. Go to your GitHub Pages URL:
   ```
   https://YOUR-USERNAME.github.io/esa-welcome-page
   ```
3. Page should display perfectly (responsive design)

### **Test QR Code:**
1. Use phone camera
2. Point at QR code
3. Tap notification that appears
4. Should open your page

---

## 💡 TIPS FOR SUCCESS

✅ **Naming Your Repo:** Use lowercase with hyphens: `esa-welcome-page` (not `ESA-Welcome-Page`)

✅ **Your GitHub Pages URL:** 
```
https://YOUR-USERNAME.github.io/REPO-NAME
```

✅ **Make it Mobile-Friendly:** This page automatically adapts to any screen size!

✅ **Update Regularly:** Add news, special offers, event info

✅ **Track Visits:** (Optional) Use free tools like Google Analytics to see how many guests view the page

✅ **Print QR Codes:** Standard 2"x2" prints work best

---

## 🆘 TROUBLESHOOTING

### **Page not loading?**
- Wait 5 minutes after pushing to GitHub
- Check URL spelling (no extra spaces)
- Try refreshing browser (Ctrl+R or Cmd+R)
- Check that files are properly named (case-sensitive)

### **Images not showing?**
- Verify image filenames match exactly
- Check they're in the same folder as index.html
- Try refreshing browser

### **QR Code not working?**
- Make sure you copied full GitHub Pages URL
- Test the URL works in browser first
- Try generating QR code again
- Check QR code isn't printed too small (min 1"x1")

### **Can't access GitHub?**
- Check internet connection
- Try different browser
- Contact GitHub support: https://support.github.com

---

## 📧 FINAL CHECKLIST

- [ ] GitHub account created
- [ ] Repository created and set to public
- [ ] All files uploaded to GitHub
- [ ] GitHub Pages enabled
- [ ] Live URL tested and working
- [ ] QR code generated
- [ ] QR code printed
- [ ] Links sent to clients
- [ ] Page tested on mobile device
- [ ] Success! 🎉

---

## 🎓 STUDENT DISCOUNT NOTES

As a student, you can also use:
- **GitHub Student Pack**: Free premium features
  - Go to https://education.github.com/pack
  - Verify as student
  - Get free credits and tools

- **Other Free Hosting Options**:
  - **Netlify**: Drag and drop to deploy (Free)
  - **Vercel**: Built for students (Free)
  - **Replit**: Browser-based coding (Free)

But **GitHub Pages is still the best** for your use case! ✨

---

## 🎯 NEXT STEPS

1. **Today**: Set up GitHub and deploy
2. **Tomorrow**: Generate QR code and test
3. **Next Week**: Share with clients
4. **Ongoing**: Update content as needed

You're all set! 🚀 Your clients will love the professional welcome page!

---

## 📞 Need Help?

- GitHub Help: https://docs.github.com
- VS Code Docs: https://code.visualstudio.com/docs
- Web Development: https://developer.mozilla.org

Good luck! 💚
