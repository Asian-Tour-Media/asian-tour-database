# 📤 GitHub Upload Instructions

## Files You Have Ready:

### 1. `index.html` ✅
- Your complete app with all 694 tournaments
- Loads data from GitHub automatically
- Admin features included

### 2. `data.json` ✅
- All 694 tournaments + 30 OOM entries
- In JSON format
- Ready to upload

---

## Step 1: Upload to GitHub

### Go to your GitHub repo:
https://github.com/Asian-Tour-Media/asian-tour-database

### Upload TWO files:

#### File 1: `index.html`
1. Click **"Add file"** → **"Upload files"**
2. Drag & drop `index.html`
3. Commit with message: "Update: Load data from GitHub"
4. Click **"Commit changes"**

#### File 2: `data.json`
1. Click **"Add file"** → **"Upload files"**
2. Drag & drop `data.json`
3. Commit with message: "Add: Tournament data"
4. Click **"Commit changes"**

---

## Your Repo Will Look Like:

```
asian-tour-database/
├── index.html        ← Updated to load from GitHub
├── data.json         ← All tournament data
├── other files...
```

---

## How It Works:

### Users Visit:
```
https://asian-tour-media.github.io/asian-tour-database/
    ↓
App loads from index.html
    ↓
App fetches data from data.json (in GitHub)
    ↓
Everyone sees the same data! ✅
```

---

## When You Add New Tournaments:

### Admin Adds Tournament:
1. Open your site
2. Login as admin
3. Click **"➕ Add Tournament"**
4. Fill form and save ✅

### Update GitHub:
1. Click **"💾 Export Data"** (when logged in as admin)
2. Download the file → rename to `data.json`
3. Go to GitHub
4. Click on existing `data.json` file
5. Click **pencil icon** (Edit)
6. Click **"Delete"** (remove old file)
7. Upload the new `data.json`
8. Commit: "Update: New tournament added"

---

## Result:
```
User A opens site → Sees new tournament ✅
User B opens site → Sees new tournament ✅
User C opens site → Sees new tournament ✅
Everyone synced! 🎉
```

---

## Summary of Files to Upload:

| File | Where | What |
|------|-------|------|
| `index.html` | Root of repo | Your app |
| `data.json` | Root of repo | All tournaments |

**That's it!** 👍

---

## Troubleshooting:

**Q: Data not showing?**
- Wait 5 minutes for GitHub to update
- Hard refresh your browser (Ctrl+Shift+R)

**Q: Export button not showing?**
- Make sure you're logged in as admin
- Password: `asiantour2024`

**Q: New tournaments not appearing?**
- You need to export and upload the updated `data.json` to GitHub
