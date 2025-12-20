# Free Website Template with Google Sheets CMS

Create your own website for **FREE** using GitHub Pages and Google Sheets.

## What You Need

- A GitHub account (free)
- A Google account (free)
- 15 minutes

## Setup

### 1. Fork This Repository

Click "Fork" at the top right of this page.

### 2. Create a Google Sheet

**Option A: Quick Start (Recommended)**
1. Click this link to make a copy of the template sheet: [Copy Template Sheet](https://docs.google.com/spreadsheets/d/1xanlmg5nOmLs5rTFBV3P9bCVNVabNFIdF9x_ilDIx0Q/copy)
2. A new sheet will be created in your Google Drive - this is your copy to edit
3. Copy your Sheet ID from the URL: `https://docs.google.com/spreadsheets/d/YOUR_SHEET_ID/edit`

**Option B: Manual Setup**
1. Go to https://sheets.google.com and create a new spreadsheet
2. Name it whatever you want
3. Follow the structure in Step 3 below
4. Copy your Sheet ID from the URL: `https://docs.google.com/spreadsheets/d/YOUR_SHEET_ID/edit`

**Make it Public**
1. Click "Share" → "Change to anyone with the link" → Select "Viewer"

### 3. Set Up Your Google Sheet

Create two tabs:

**Tab 1: "Sheet1"** (Your website content)
- Row 1: Labels (don't change)
- Row 2: Site title, hero image URL, slogan, intro text, footer text
- Row 5+: Each row is a new section with: title, link (optional), image URL, text

**Tab 2: "Styling"** (Colors and fonts)
- Row 1: Labels (don't change)
- Row 2+: Your color/font choices

**Example Styling tab:**

| Field Name | Color | Font Size |
|---|---|---|
| Main Header Background | #a5bf24 | |
| Site Header Text | #ffffff | 48px |
| Section Header Text | #333333 | 32px |
| Section Body Text | #555555 | 16px |
| Section Background | #707070 | |
| Footer Background | #333333 | |
| Footer Text | #ffffff | |
| Link Hover Color | #667eea | |

### 4. Update index.html

1. Open `index.html` in your forked repository
2. Click the edit pencil icon
3. Find: `const SHEET_ID = 'YOUR_SHEET_ID_HERE';`
4. Replace with your actual Sheet ID
5. Commit the change

### 5. Enable GitHub Pages

1. Go to Settings → Pages
2. Select "main" branch as source
3. Your site is now live at: `https://YOUR_USERNAME.github.io/REPOSITORY_NAME/`

## How to Update Your Website

Just edit your Google Sheet. Your website updates automatically!

## Tips

- Use hex color codes: `#FF5733`
- Include units for sizes: `24px`, `2em`
- For images, upload to GitHub and use the raw URL, or use any public image URL
- Keep text concise for better readability
