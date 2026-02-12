# Aryan Hemani - Data Science Portfolio

Modern, professional portfolio website optimized for cold LinkedIn outreach and job applications.

## 🚀 Live Demo
Once deployed: `https://aryanhemani1771.github.io/Portfolio/`

## ✨ Features

- **Impact-First Design**: Quantified achievements visible immediately
- **Modern Color Scheme**: Slate gray + cyan (professional data analytics aesthetic)
- **Sidebar Layout**: Experience and education timeline always visible
- **Mobile-Friendly**: Desktop layout that's zoomable on mobile
- **Optimized for Recruiters**: Designed for 10-30 second scans
- **Clean & Professional**: Perfect for data scientist/analyst roles

## 📂 File Structure

```
Portfolio-Final/
├── index.html          # Main portfolio page
├── resume.pdf          # Your resume (ADD THIS FILE)
├── images/             # Project screenshots and images
├── LICENSE             # License file
└── README.md           # This file
```

## 🛠️ Setup Instructions

### Option 1: Upload to Existing GitHub Repo

1. **Go to your GitHub repo**: https://github.com/aryanhemani1771/Portfolio

2. **Delete old files** (or move to a backup folder):
   - Delete `index.md`, `_config.yml`, `_layouts/`, etc.

3. **Upload new files**:
   - Click "Add file" → "Upload files"
   - Drag and drop ALL files from `Portfolio-Final/`
   - **IMPORTANT**: Add your `resume.pdf` to the root folder
   - Commit changes

4. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Source: `main` branch, `/ (root)` folder
   - Save

5. **Wait 2-3 minutes** - Your site will be live at:
   `https://aryanhemani1771.github.io/Portfolio/`

### Option 2: Using Git (Command Line)

```bash
# Navigate to your local folder
cd path/to/Portfolio-Final

# Initialize git (if new folder)
git init

# Add all files
git add .

# Commit
git commit -m "Updated portfolio with modern design"

# Add remote (replace with your repo URL)
git remote add origin https://github.com/aryanhemani1771/Portfolio.git

# Push (this will overwrite existing files)
git push -f origin main
```

## 📄 Adding Your Resume

**CRITICAL**: You MUST add your resume for the "View Resume" button to work!

1. Save your resume as `resume.pdf`
2. Place it in the **root folder** (same level as `index.html`)
3. Push to GitHub

```
Portfolio/
├── index.html
├── resume.pdf    ← ADD THIS
└── images/
```

## ✏️ Making Changes After Upload

### Update Email
Find line ~483 in `index.html`:
```html
<a href="mailto:aryanhemani1771@gmail.com" class="btn btn-primary">aryanhemani1771@gmail.com</a>
```

### Update LinkedIn
Find all instances of:
```html
https://www.linkedin.com/in/aryan-hemani/
```

### Update GitHub
Find all instances of:
```html
https://github.com/aryanhemani1771
```

### Add/Remove Projects
Find the "Featured Work" section (around line 520) and copy/paste project cards.

### Update Skills
Find the skills section (around line 500) and add/remove skill badges.

## 🎨 Color Scheme

- **Slate Gray**: `#334155` (headers, text)
- **Cyan**: `#0ea5e9` (accents, highlights)
- **Light Blue**: Backgrounds for impact cards
- **White/Gray**: Clean backgrounds

To change colors, find and replace hex codes in `index.html`.

## 📱 How It Looks

- **Desktop**: Sidebar (left) + Main content (right)
- **Mobile**: Same layout, users can zoom and pan
- **Optimized for**: LinkedIn cold outreach, recruiter scans

## 🔧 Troubleshooting

### Resume button not working?
- Make sure `resume.pdf` is in the root folder
- Check the filename is exactly `resume.pdf` (lowercase)

### Images not showing?
- Verify images are in the `images/` folder
- Check image filenames match exactly (including spaces and %20)

### Site not updating?
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Wait 5-10 minutes for GitHub Pages to rebuild
- Check Actions tab in GitHub for build status

### Layout looks broken?
- Make sure you uploaded ALL files including `index.html`
- Don't modify the HTML structure without testing

## 📧 Using for Cold Outreach

**LinkedIn Message Template**:
```
Hi [Name],

I noticed [Company] is hiring for [Role]. I'm a Data Scientist with 2+ years 
driving measurable impact through ML systems at Analysis Group.

Recent wins:
• Built production ML pipeline → Saved 80+ hours/month
• Deployed anomaly detection → 25% accuracy boost
• Processed 1.2M+ posts via NLP for customer insights

Portfolio: https://aryanhemani1771.github.io/Portfolio/

Would love to discuss how I can contribute to [Company's] data team.

Best,
Aryan
```

## 📊 What Recruiters See

**First 5 seconds**:
- Your name + title
- Education credentials (UCLA Master's, LSE)
- Email button

**First 30 seconds**:
- 6 quantified impact stats
- Experience timeline
- Technical skills

**If interested (60+ seconds)**:
- 4 detailed projects
- Full skill breakdown
- Contact options

## 🎯 Best Practices

1. **Keep resume updated** - Replace `resume.pdf` monthly
2. **Test on mobile** - Open on your phone to verify
3. **Update impact stats** - Add new achievements as they happen
4. **Track analytics** - Consider adding Google Analytics
5. **A/B test** - Try different project orders based on role type

## 📝 License

Unlicense - Free to use, modify, and distribute

---

**Questions?** Email: aryanhemani1771@gmail.com

**Built with**: HTML, CSS, modern design principles for data professionals

⭐ **Good luck with your job search!**
