# 1st Deal Factory - Web Apps

Professional web applications for real estate wholesaling, featuring the **Wholesale Calculator** and **Action Tracker**.

## 🎯 Features

### Wholesale Calculator (`calculator.html`)
- **Property Information**: Track address, beds/baths, square footage
- **Deal Calculator**: Calculate ARV, repair costs, offers, and ROI
- **Deal Analyzer**: Auto-analyze deal quality with confidence scores
- **Deal Summary**: Screenshot-ready summary for presentations
- **Real-time Calculations**: All formulas update instantly as you type

### Action Tracker (`action-tracker.html`)
- **Weekly Action Tracking**: Log daily wholesaling activities
- **Gamified Scoring System**: Points for every action taken
- **Streak Counter**: Track consecutive high-performance days
- **Motivation Dashboard**: Dynamic feedback based on performance
- **Auto-Save**: Data persists in browser localStorage

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right
3. Select **New repository**
4. Name it: `1st-deal-factory` (or any name you prefer)
5. Make it **Public**
6. Click **Create repository**

### Step 2: Upload Files

**Option A: Via GitHub Website (Easiest)**

1. In your new repository, click **uploading an existing file**
2. Drag and drop both HTML files:
   - `calculator.html`
   - `action-tracker.html`
3. Click **Commit changes**

**Option B: Via Git Command Line**

```bash
# Clone your repository
git clone https://github.com/YOUR-USERNAME/1st-deal-factory.git
cd 1st-deal-factory

# Copy your HTML files here
# Then commit and push
git add .
git commit -m "Add wholesale calculator and action tracker"
git push
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under **Source**, select **main** branch
5. Click **Save**
6. Wait 1-2 minutes for deployment

### Step 4: Access Your Apps

Your apps will be live at:
- **Calculator**: `https://YOUR-USERNAME.github.io/1st-deal-factory/calculator.html`
- **Action Tracker**: `https://YOUR-USERNAME.github.io/1st-deal-factory/action-tracker.html`

## 📱 Usage

### Wholesale Calculator

1. **Enter Property Details**: Address, beds/baths, square footage
2. **Input Deal Numbers**: 
   - ARV (After Repair Value)
   - Repair cost per square foot
   - Investor discount % (typically 70%)
   - Your assignment fee
3. **Get Instant Results**:
   - Your offer amount
   - Deal quality rating (🔥 Great / ⚠️ Marginal / ❌ Dead)
   - Buyer's return on cost
   - Complete deal summary

### Action Tracker

1. **Set Your Week**: Choose the Sunday start date
2. **Log Daily Actions**:
   - Facebook Marketplace messages
   - Cold calls made
   - Conversations started
   - Offers made
   - Follow-ups sent
3. **Track Progress**:
   - Total action points
   - Current streak
   - Daily status (🔥 Killer / 💪 Solid / 😴 Slow)
   - Weekly motivation

**Scoring System:**
- FB Messages: 1 point each
- Cold Calls: 2 points each
- Conversations: 3 points each
- Offers: 5 points each
- Follow-ups: 2 points each

**Goals:**
- 25+ points = Solid Day (starts streak)
- 50+ points = Killer Day
- Build streaks for consistency

## 🎨 Branding

Both apps feature the **1st Deal Factory** brand identity:
- **Colors**: Dark charcoal background, maroon accents, cream text
- **Typography**: Playfair Display (headings) + Inter (body)
- **Style**: Professional yet motivating, clean and modern

## 💾 Data Storage

- **Calculator**: No data stored (all calculations are live)
- **Action Tracker**: Data saves to browser localStorage
  - Data persists when you close/reopen
  - Data is device-specific
  - Clear browser data to reset

## 🔧 Customization

Both files are self-contained HTML with embedded CSS and JavaScript. To customize:

1. Download the HTML file
2. Open in any text editor
3. Modify colors in the `:root` CSS variables section
4. Adjust calculations in the JavaScript section
5. Re-upload to GitHub

## 📊 Recommended Workflow

### For Beginners:
1. Use **Action Tracker** daily to build consistency
2. Use **Calculator** when evaluating deals
3. Aim for 3-4 "Solid Days" per week minimum
4. Track your first 90 days to establish patterns

### For Teams:
1. Share the GitHub Pages links
2. Each person tracks their own actions
3. Screenshot weekly summaries to share progress
4. Compete on action volume (not just deals closed)

## 🆘 Support

Having issues? Check these common solutions:

**Calculator not calculating?**
- Ensure all fields have numbers (not blank)
- Check that percentages are entered as whole numbers (70 not 0.70)

**Action Tracker data disappeared?**
- Check if you cleared browser cache/cookies
- Try using the same browser each time
- Consider bookmarking the page for quick access

**GitHub Pages not loading?**
- Wait 2-3 minutes after enabling Pages
- Check that files are named exactly `calculator.html` and `action-tracker.html`
- Ensure repository is Public

## 📄 License

© 2026 The 1st Deal Factory. For educational and business use.

## 🎓 Resources

Want to learn more about wholesaling?
- Visit [1st Deal Factory Website] (add your link)
- Join the community (add your Discord/Facebook group)
- Subscribe for weekly tips (add your email list)

---

**Your First Deal Starts Here** 🏆
