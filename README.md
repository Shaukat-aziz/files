# 📁 Public File Hosting

A simple, elegant website for hosting and sharing files publicly.

## 🌐 Live Website

Visit the website at: `https://shaukat-aziz.github.io/files/`

## 📋 Features

- **Clean Interface**: Modern, responsive design that works on all devices
- **Easy Downloads**: Direct download links for all hosted files
- **Public Access**: All files are publicly accessible and free to download
- **Simple Management**: Easy to add new files and update the listing

## 🚀 How to Use

### For Downloaders

1. Visit the website
2. Browse the available files
3. Click the "Download" button next to any file

### For File Hosts

To add new files to this hosting service:

1. **Add your file**: Place your file in the `files/` directory
2. **Update the listing**: Edit `index.html` and add a new file item to the list:
   ```html
   <div class="file-item">
       <div class="file-info">
           <span class="file-icon">📄</span>
           <div class="file-details">
               <h3>your-file-name.ext</h3>
               <p class="file-meta">File description</p>
           </div>
       </div>
       <a href="files/your-file-name.ext" class="download-btn" download>Download</a>
   </div>
   ```
3. **Commit and push**: Commit your changes and push to GitHub
4. **Done!**: Your file will be available on the website

## 📂 Repository Structure

```
files/
├── index.html              # Main website page
├── styles.css              # Website styling
├── files/                  # Directory containing all hosted files
│   ├── example-document.txt
│   ├── example-data.json
│   └── example-image.png
└── README.md               # This file
```

## 🛠️ Setup GitHub Pages

To enable hosting on GitHub Pages:

1. Go to your repository settings
2. Navigate to "Pages" section
3. Under "Source", select the branch (usually `main` or `master`)
4. Click "Save"
5. Your site will be published at `https://shaukat-aziz.github.io/files/`

## 📝 File Types Supported

This hosting service supports all file types:
- Documents (PDF, DOCX, TXT, etc.)
- Images (PNG, JPG, GIF, etc.)
- Data files (JSON, CSV, XML, etc.)
- Archives (ZIP, TAR, etc.)
- Code files (JS, PY, etc.)
- And more!

## 🤝 Contributing

Feel free to add your files or suggest improvements to the website!
