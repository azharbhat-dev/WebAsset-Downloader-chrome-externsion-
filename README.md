# WebAsset Downloader

A Chrome extension that helps web developers and designers download and organize website assets efficiently.

## Features

- **Download All Asset Types**
  - Images (JPG, PNG, GIF, WebP, SVG, ICO)
  - Stylesheets (CSS)
  - JavaScript files
  - Fonts (WOFF, WOFF2, TTF, OTF, EOT)
  - Videos (MP4, WebM)
  - Audio (MP3, WAV)
  - Data files (JSON, XML, CSV)
  - Documents (PDF, DOC, XLS)
  - Archives (ZIP, RAR, TAR, GZ)

- **Smart Organization**
  - Automatically categorized into folders by type
  - Organized by domain name
  - Numbered folders for easy sorting

- **Easy to Use**
  - One-click scan
  - Individual or bulk download
  - Real-time asset counter
  - Clean, minimal interface

## Installation

### From Chrome Web Store
1. Visit [Chrome Web Store](https://chrome.google.com/webstore)
2. Search "WebAsset Downloader"
3. Click "Add to Chrome"

### Manual Installation (Development)
1. Download this repository
2. Open Chrome and go to `chrome://extensions/`
3. Enable "Developer mode" (top right)
4. Click "Load unpacked"
5. Select the extension folder

## How to Use

1. Navigate to any website
2. Click the extension icon in your browser toolbar
3. Click **"Scan Page"** button
4. Review discovered assets
5. Download files:
   - Click individual "Download" buttons
   - Or click "Download All" for bulk download

## File Organization

Downloaded files are automatically organized:

```
webasset-downloads/
└── example.com/
    ├── 1-html/          # HTML source
    ├── 2-images/        # All images
    ├── 3-stylesheets/   # CSS files
    ├── 4-scripts/       # JavaScript
    ├── 5-fonts/         # Font files
    ├── 6-data-files/    # JSON, XML, CSV
    ├── 7-videos/        # Video files
    ├── 8-audio/         # Audio files
    ├── 9-documents/     # PDF, DOC, XLS
    └── 10-archives/     # ZIP, RAR, etc.
```

## Use Cases

### Web Development
- Study competitor implementations
- Download assets for analysis
- Extract design resources
- Backup website resources

### Design Work
- Collect visual inspiration
- Download image assets
- Extract fonts and colors
- Archive design references

### Learning
- Study website structure
- Analyze CSS techniques
- Examine JavaScript patterns
- Understand asset optimization

## Privacy

- **Zero data collection** - No analytics, no tracking
- **Local processing** - All scanning happens in your browser
- **No external servers** - Nothing is sent anywhere
- **Open source** - Transparent code you can verify

## Technical Details

- **Manifest Version**: 3
- **Permissions**:
  - `activeTab` - Scan current page
  - `scripting` - Extract assets from DOM
  - `downloads` - Save files locally
  - `host_permissions` - Work on any website

## Legal & Ethical Use

### Permitted Uses
- Websites you own or have permission to access
- Educational purposes and learning
- Fair use analysis and research
- Publicly accessible content

### Prohibited Uses
- Downloading copyrighted content without permission
- Violating website terms of service
- Commercial use without proper licensing
- Unauthorized redistribution

**Always respect intellectual property rights and website terms of service.**

## Known Limitations

- Cannot download dynamically loaded content that hasn't been rendered
- Some sites with strict CORS policies may block downloads
- Very large files may take time to download
- Protected content behind authentication requires manual login

## Changelog

### Version 1.0.0 (Initial Release)
- Complete asset discovery system
- Organized folder structure
- Individual and bulk downloads
- Clean, minimal interface
- Chrome Web Store compliant

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Developer

Created by azharbhat-dev

## Support

- **Issues**: [GitHub Issues](https://github.com/azharbhat-dev/WebAsset-Downloader-chrome-externsion-/issues)
- **Email**: bazhar691@gmail.com

---

**Disclaimer**: This tool is provided for educational and legitimate purposes only. Users are responsible for ensuring their use complies with applicable laws and website terms of service.
