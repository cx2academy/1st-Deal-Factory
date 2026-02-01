# 1st Deal Factory - Complete Toolkit

Professional wholesaling tools for beginners. Free, powerful, and ready to deploy.

## 🚀 Live Demo
Upload to GitHub Pages and access at: `https://yourusername.github.io/repo-name/`

---

## 📦 What's Included

### **1. Landing Page** (`index.html`)
- Overview of all tools
- Stats showcase
- "Get Started" button → leads to onboarding
- Links to all tools

### **2. Onboarding Flow** (`onboarding.html`)
- 6-step guided onboarding
- Welcome video (with 30-second timer)
- Rules & commitment system
- Introduction to all resources
- Locked tools showcase (for upsell)

### **3. Deal Calculator** (`calculator.html`)
- Property information tracker
- Real-time deal calculations
- Auto-analyzing deal quality
- Buyer spread calculator
- Screenshot-ready summaries

### **4. Action Tracker** (`action-tracker.html`)
- Daily action logging
- Gamified point system
- Streak tracking
- Weekly stats dashboard
- Auto-save to browser

### **5. Script Library** (`scripts.html`)
- 4 certified scripts (in modals)
- Cold call script
- FB Marketplace DM flow
- Follow-up system
- Objection responses

---

## 🎯 User Flow

```
Landing Page (index.html)
    ↓
Click "Get Started"
    ↓
Onboarding (onboarding.html)
    ↓
Section 1: Welcome video
Section 2: How it works
Section 3: Rules & commitment
Section 4: Your command center
    - Links to free tools
    - Links to checkout for locked tools
Section 5: 30-day commitment
Section 6: Next steps
    - Begin Module 1 (your course)
    - Introduce yourself (your community)
```

---

## 📁 File Structure

```
your-github-repo/
├── index.html              (Landing page)
├── onboarding.html         (New user onboarding)
├── calculator.html         (Deal calculator tool)
├── action-tracker.html     (Daily action tracker)
├── scripts.html            (Script library)
├── images/                 (Create this folder)
│   └── icons/              (Your brand icons go here)
│       ├── learn.png
│       ├── action.png
│       ├── feedback.png
│       ├── success.png
│       ├── library.png
│       ├── community.png
│       ├── calculator.png
│       ├── tracker.png
│       ├── scripts.png
│       ├── announcements.png
│       ├── module.png
│       └── intro.png
└── README.md
```

---

## ⚙️ Setup Instructions

### 1. Replace All Placeholders

**In `onboarding.html`:**

Line 398 - Add your welcome video:
```html
<iframe 
    id="welcomeVideo"
    src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
```

Line 539 - Course library link:
```html
<a href="YOUR_COURSE_LIBRARY_LINK_HERE" class="location-card">
```

Line 547 - Discussion board link:
```html
<a href="YOUR_DISCUSSION_BOARD_LINK_HERE" class="location-card">
```

Line 556, 564, 572 - Locked tools checkout link:
```html
<div class="location-card locked" onclick="window.location.href='YOUR_CHECKOUT_LINK_HERE'">
```

Line 583 - Announcements link:
```html
<a href="YOUR_ANNOUNCEMENTS_LINK_HERE" class="location-card">
```

Line 672 - Module 1 link:
```html
<a href="YOUR_MODULE_1_LINK_HERE" class="btn">Begin Module 1 →</a>
```

Line 680 - Introduction post link:
```html
<a href="YOUR_INTRODUCTION_LINK_HERE" class="btn btn-secondary">Go to Community →</a>
```

### 2. Replace Emoji Icons

See `ICON_REPLACEMENT_GUIDE.md` for complete instructions.

All 12 emoji placeholders need to be replaced with your brand icons:
- 4 icons in Section 2 (How This Works)
- 6 icons in Section 4 (Command Center)
- 2 icons in Section 6 (Next Steps)

### 3. Adjust Video Timer (Optional)

Line 699 - Change wait time before button enables:
```javascript
}, 30000); // 30 seconds = 30000ms
```

---

## 🌐 GitHub Pages Deployment

### Quick Deploy:

1. **Create new GitHub repository**
   - Name it (e.g., `1st-deal-factory`)
   - Make it Public

2. **Upload all files:**
   - All 5 HTML files
   - `images` folder with your icons
   - This README

3. **Enable GitHub Pages:**
   - Settings → Pages
   - Source: Deploy from branch
   - Branch: main
   - Folder: / (root)
   - Save

4. **Access your site:**
   - `https://yourusername.github.io/repo-name/`

See `GITHUB_PAGES_SETUP.md` for detailed instructions.

---

## 🎨 Customization

### All pages share the same design system:
- **Background:** Pure black `#0A0A0A`
- **Cards:** Dark gray `#171717`
- **Borders:** `#262626`
- **Primary text:** `#FAFAFA`
- **Secondary text:** `#A3A3A3`
- **Accent:** Red `#DC2626`

### Fonts:
- **Display (headings):** Manrope 600-800
- **Body (text):** Inter 400-700

### To customize colors:
Edit the `:root` variables at the top of any HTML file.

---

## 🔒 Locked vs Free Tools

### Free (Access immediately):
- Course library
- Discussion board
- Announcements

### Locked (Require purchase):
- Deal Calculator
- Action Tracker
- Script Library

Locked tools show a 🔒 icon and redirect to your checkout page when clicked.

---

## 📱 Mobile Responsive

All pages are fully responsive:
- Single column layouts on mobile
- Touch-friendly buttons
- Optimized font sizes
- Smooth scrolling

---

## ✅ Pre-Launch Checklist

- [ ] All placeholder links updated
- [ ] Welcome video added
- [ ] All 12 icons replaced
- [ ] Checkout link added for locked tools
- [ ] Module 1 link added
- [ ] Introduction post link added
- [ ] Video timer set (30+ seconds)
- [ ] All files uploaded to GitHub
- [ ] GitHub Pages enabled
- [ ] Tested on mobile
- [ ] Tested all navigation links

---

## 🆘 Support Files

- `ONBOARDING_SETUP_GUIDE.md` - Complete onboarding customization guide
- `ICON_REPLACEMENT_GUIDE.md` - How to replace all emoji icons
- `GITHUB_PAGES_SETUP.md` - Detailed GitHub Pages instructions

---

## 🎯 Quick Start (1-2-3)

1. **Replace icons** → Use Icon Replacement Guide
2. **Add your links** → Update all `YOUR_LINK_HERE` placeholders
3. **Deploy** → Upload to GitHub, enable Pages

Your professional wholesaling toolkit is ready to go! 🚀

---

## 💡 Tips

- Test locally before deploying (open index.html in browser)
- Keep icon file sizes under 50KB each
- Use YouTube embed URLs, not regular video URLs
- Make videos Public or Unlisted (not Private)
- Test on mobile before sharing with users

---

## 📊 Tech Stack

- Pure HTML/CSS/JavaScript
- No dependencies (except Google Fonts)
- No backend required
- Works on any static hosting
- Fully client-side

Perfect for GitHub Pages, Netlify, Vercel, or any hosting platform!
