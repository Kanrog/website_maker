# Free Website Template with Google Sheets CMS

Create and host your own website for **100% FREE** using GitHub Pages and Google Sheets - no coding knowledge required!

## 🌟 Features

- ✅ **Completely Free** - Uses GitHub Pages (free hosting) and Google Sheets (free CMS)
- ✅ **No Coding Required** - Edit your website by simply updating a Google Sheet
- ✅ **Easy to Customize** - Change colors, fonts, and content without touching code
- ✅ **Automatic Updates** - Website updates when you change the Google Sheet
- ✅ **Responsive Design** - Looks great on desktop, tablet, and mobile
- ✅ **Image Support** - Add images to any section

## 📋 What You'll Need

1. A GitHub account (free)
2. A Google account (free)
3. 15-30 minutes to set up

## 🚀 Quick Start Guide

### Step 1: Fork This Repository

1. Click the "Fork" button at the top right of this page
2. This creates your own copy of the template

### Step 2: Set Up Your Google Sheet

1. **Create a New Google Sheet**: Go to https://sheets.google.com and create a blank spreadsheet
2. **Set Up Content** (see GOOGLE_SHEET_TEMPLATE.md for detailed structure):
   - Row 1: Site header (title, hero image, slogan, intro, footer)
   - Row 2+: Content sections (header, link, image, text)
   - Create "Styling" tab for colors and fonts
3. **Make it Public**:
   - Click "Share" in the top right
   - Click "Change to anyone with the link"
   - Set permission to "Viewer"
   - Click "Done"
3. **Get Your Sheet ID**:
   - Look at your sheet URL: `https://docs.google.com/spreadsheets/d/YOUR_SHEET_ID/edit`
   - Copy the `YOUR_SHEET_ID` part

### Step 3: Configure Your Website

1. Open `index.html` in your forked repository
2. Click the pencil icon to edit
3. Find this line near the top:
   ```javascript
   const SHEET_ID = 'YOUR_SHEET_ID_HERE';
   ```
4. Replace `YOUR_SHEET_ID_HERE` with your actual Sheet ID
5. Commit the change

### Step 4: Enable GitHub Pages

1. Go to your repository Settings
2. Scroll down to "Pages" section
3. Under "Source", select "main" branch
4. Click "Save"
5. Your site will be live at: `https://YOUR_USERNAME.github.io/REPOSITORY_NAME/`

### Step 5: Customize Your Content

Edit your Google Sheet to update your website:

#### **Row 1 - Field Labels** (DO NOT DELETE - helps you understand each field)
- Labels for all fields

#### **Row 2 - Site Header** (Your main site content)
- **B2**: Main site title/header
- **C2**: Hero image URL (optional)
- **D2**: Site slogan/tagline
- **E2**: Introduction text
- **F2**: Footer text

#### **Row 3** - Empty row for spacing

#### **Row 4 - Section Labels** (DO NOT DELETE - helps you understand section fields)
- Labels for content sections

#### **Row 5 and Beyond - Content Sections**
Each row creates a new section on your site:
- **Column A**: Section header/title
- **Column B**: Link URL (optional - makes header clickable)
- **Column C**: Image URL (upload images to GitHub, use the raw URL)
- **Column D**: Section text content

#### **Styling Tab** (Second sheet tab)
Configure colors and fonts:
- **Row 1**: Field labels (DO NOT DELETE)
- **Row 2**: Main header color and size (e.g., #ffffff, 48px)
- **Row 3**: Section header color and size (e.g., #333333, 32px)
- **Row 4**: Text color and size (e.g., #555555, 16px)
- **Row 5**: Background color (e.g., #ffffff)
- **Row 6**: Link hover color (e.g., #667eea)

## 📸 Adding Images

1. Upload images to your GitHub repository (create an `images` folder)
2. Get the raw URL: `https://raw.githubusercontent.com/YOUR_USERNAME/REPOSITORY_NAME/main/images/your-image.jpg`
3. Paste this URL in Column B (Row 1) or Column C (Row 2+) of your Google Sheet

## 🎨 Customization Tips

- **Colors**: Use hex codes (e.g., #FF5733) or color names (e.g., blue)
- **Font Sizes**: Include units (e.g., 24px, 2em, 1.5rem)
- **Images**: Use high-quality images for best results
- **Text**: Keep paragraphs concise for better readability

## 🔧 Troubleshooting

**Website not updating?**
- Make sure your Google Sheet is set to "Anyone with the link can view"
- Check that you've entered the correct Sheet ID in index.html
- Wait a few minutes - changes may take time to propagate

**Images not showing?**
- Verify image URLs are correct and publicly accessible
- Use raw GitHub URLs for images hosted on GitHub
- Check image file extensions are correct

**Styling not applying?**
- Ensure you have a "Styling" tab in your Google Sheet
- Check hex codes are formatted correctly (#RRGGBB)
- Include units for font sizes (px, em, rem)

## 📺 Video Tutorial

[Link to YouTube tutorial will be added here]

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to open an issue or submit a pull request!

## 📄 License

This template is free to use for any purpose. No attribution required.

## ❤️ Support

If this template helped you, consider:
- ⭐ Starring this repository
- 📢 Sharing it with others
- 📺 Subscribing to the YouTube channel

---

**Made with ❤️ for everyone who wants a free website**
