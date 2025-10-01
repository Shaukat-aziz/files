# Setup Instructions

Follow these steps to activate your multimedia file hosting website.

## 1. Enable GitHub Pages

1. Go to your repository: https://github.com/Shaukat-aziz/files
2. Click on **Settings** (top navigation bar)
3. Scroll down and click on **Pages** (left sidebar under "Code and automation")
4. Under **Source**, select:
   - Branch: `main` (or your default branch)
   - Folder: `/ (root)`
5. Click **Save**
6. Wait 1-2 minutes for deployment

Your site will be live at: **https://shaukat-aziz.github.io/files/**

## 2. Verify Deployment

After a few minutes, visit:
```
https://shaukat-aziz.github.io/files/
```

You should see the multimedia hosting homepage.

## 3. Test File Access

Try accessing the example placeholder image:
```
https://shaukat-aziz.github.io/files/images/example-placeholder.svg
```

## 4. Upload Your Files

### Via GitHub Web Interface:
1. Navigate to the appropriate folder (`images/`, `videos/`, or `gifs/`)
2. Click **Add file** → **Upload files**
3. Drag and drop or select your files
4. Click **Commit changes**
5. Wait a minute for GitHub Pages to update

### Via Git Command Line:
```bash
# Clone the repository
git clone https://github.com/Shaukat-aziz/files.git
cd files

# Add your files
cp /path/to/your/image.jpg images/
cp /path/to/your/video.mp4 videos/

# Commit and push
git add .
git commit -m "Add multimedia files"
git push
```

## 5. Get Direct URLs

After uploading, your files will be accessible at:
```
https://shaukat-aziz.github.io/files/images/[filename]
https://shaukat-aziz.github.io/files/videos/[filename]
https://shaukat-aziz.github.io/files/gifs/[filename]
```

## 6. Link in PDF

### In Adobe Acrobat:
1. Select text or object
2. Right-click → Add/Edit Link
3. Enter the direct URL
4. Save PDF

### In Word (before converting to PDF):
1. Select text
2. Insert → Link
3. Enter the direct URL
4. Export to PDF

## Troubleshooting

### Site not loading?
- Wait 2-3 minutes after enabling GitHub Pages
- Check GitHub Pages settings are correct
- Ensure the branch is correct

### Files not accessible?
- Verify files are committed and pushed
- Check file path matches URL exactly (case-sensitive)
- Wait 1-2 minutes after pushing for cache to update

### Need custom domain?
- Go to Pages settings
- Enter custom domain under "Custom domain"
- Follow DNS configuration instructions

## File Size Limits

- Maximum file size: 100 MB (GitHub recommendation)
- Maximum repository size: 1 GB
- For larger files, consider Git LFS or external hosting

## Support

For issues or questions, open an issue in the repository:
https://github.com/Shaukat-aziz/files/issues
