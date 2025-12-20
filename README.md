# Free Website Template with Google Sheets CMS

Create your own website for **FREE** using GitHub Pages and Google Sheets.

## What You Need

- A GitHub account (free)
- A Google account (free)
- 15 minutes

## Setup

### 1. Create a GitHub Repository

1. Go to https://github.com/new
2. Name your repository: `YOUR_USERNAME.github.io` (replace `YOUR_USERNAME` with your actual GitHub username)
   - This naming convention gives you a clean URL without `/website` at the end
   - Example: If your username is `kanrog`, name it `kanrog.github.io` for the URL `https://kanrog.github.io`
3. Set it to **Public**
4. Click "Create repository"

### 2. Fork This Repository

1. Go to this repository and click "Fork" at the top right
2. In the fork settings, change the repository name to match your `YOUR_USERNAME.github.io` name
3. Click "Create fork"

### 3. Create a Google Sheet

1. Click this link to make a copy of the template sheet: [Copy Template Sheet](https://docs.google.com/spreadsheets/d/1cLMaglrhcWkKaleRF6-ZwZtvSn0eNT9xfonY_QfRP1s/copy)
2. A new sheet will be created in your Google Drive - this is your copy to edit
3. Copy your Sheet ID from the URL: `https://docs.google.com/spreadsheets/d/YOUR_SHEET_ID/edit`
4. Click "Share" → "Change to anyone with the link" → Select "Viewer"

### 4. Set Up Your Google Sheet

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

### 5. Update index.html

1. Open `index.html` in your forked repository
2. Click the edit pencil icon
3. Find: `const SHEET_ID = 'YOUR_SHEET_ID_HERE';`
4. Replace with your actual Sheet ID
5. Commit the change

### 6. Enable GitHub Pages

1. Go to Settings → Pages
2. Select "main" branch as source
3. Your site is now live at: `https://YOUR_USERNAME.github.io/`

## How to Update Your Website

Just edit your Google Sheet. Your website updates automatically!

## Tips

- Use hex color codes: `#FF5733`
- Include units for sizes: `24px`, `2em`
- For images, upload to GitHub and use the raw URL, or use any public image URL
- Keep text concise for better readability
