# Skills Intelligence Platform - GitHub Pages Deployment

This is your complete Skills Intelligence Platform ready to deploy to GitHub Pages!

## 🚀 Quick Deploy to GitHub Pages (5 minutes)

### Option A: Via GitHub Website (Easiest)

1. **Create a GitHub account** (if you don't have one): https://github.com/join

2. **Create a new repository**:
   - Go to https://github.com/new
   - Name it: `skills-marketplace` (or any name you like)
   - Make it **Public**
   - ✅ Check "Add a README file"
   - Click "Create repository"

3. **Upload the index.html file**:
   - In your new repository, click "Add file" → "Upload files"
   - Drag and drop the `index.html` file (the one you downloaded)
   - Click "Commit changes"

4. **Enable GitHub Pages**:
   - Go to Settings (top of your repo)
   - Scroll to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"

5. **Access your site**:
   - Wait 1-2 minutes
   - Your site will be live at: `https://YOUR-USERNAME.github.io/skills-marketplace/`
   - Share this URL with your team!

### Option B: Using GitHub Desktop (If you prefer a GUI)

1. Download GitHub Desktop: https://desktop.github.com/
2. Create new repository
3. Add the index.html file to the repository folder
4. Commit and push
5. Enable GitHub Pages in Settings

### Option C: Command Line (For developers)

```bash
# 1. Create a new repo on GitHub first, then:
git clone https://github.com/YOUR-USERNAME/skills-marketplace.git
cd skills-marketplace

# 2. Add your index.html file to this folder

# 3. Commit and push
git add index.html
git commit -m "Initial commit: Skills Intelligence Platform"
git push origin main

# 4. Enable GitHub Pages in repo Settings → Pages
```

## 📱 Features

- ✅ **Employee Portal** - Staff submit their own skills
- ✅ **Browse Projects** - Filter by skills and departments  
- ✅ **Analytics Dashboard** - Enterprise, department, and team-level insights
- ✅ **Skills Directory** - Search and browse all employees
- ✅ **Project Management** - Post projects and see automatic matching
- ✅ **Admin Panel** - Manage employees and data

## 💾 Data Storage

- All data is stored in **browser localStorage**
- Each user's browser has their own copy
- To share data across all employees, you'll need to add a backend (ask Claude for help!)

## 🔒 Important Notes

### Current Limitations:
- **Data is not shared** between users (everyone has their own copy)
- **No authentication** - anyone with the link can access it
- **Data is browser-specific** - if someone clears their browser data, it's lost

### For Production Use:
Consider adding:
1. **Backend database** (Firebase, AWS, or your company's infrastructure)
2. **Authentication** (company SSO)
3. **Email notifications** when employees express interest in projects

Claude can help you add these features - just ask!

## 🆘 Troubleshooting

**Site not loading?**
- Wait 2-3 minutes after enabling GitHub Pages
- Make sure file is named exactly `index.html` (lowercase)
- Check that the repository is Public

**Buttons not working?**
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Try a different browser
- Check browser console (F12) for errors

**Need to update?**
- Upload a new index.html file to replace the old one
- Changes appear in 1-2 minutes

## 📧 Support

Need help? Go back to Claude and ask for assistance with:
- Adding backend database
- SharePoint integration
- Custom features
- Deployment issues

## 🎉 You're Done!

Share your GitHub Pages URL with your team and start collecting skills data!

Example URL format: `https://your-username.github.io/skills-marketplace/`
