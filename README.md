# ID Card Print Tool

A professional web-based tool for creating printable ID card layouts with advanced image optimization and flexible printing options.

## 📋 Table of Contents
- [Features](#-features)
- [Getting Started](-#getting-started)
- [How to Use](#-how-to-use)
- [Advanced Settings](#-advanced-settings)
- [Browser Compatibility](#-browser-compatibility)
- [Version History](#-version-history)
- [Technical Specifications](#-technical-specifications)
- [Troubleshooting](#-troubleshooting)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Features

### Core Functionality
- **Dual Mode Operation**: Single person or multi-person ID card creation
- **Front & Back Support**: Upload both sides of ID cards
- **Flexible Copy Options**: 2, 4, 6, or 8 copies per person
- **A4 Print Layout**: Optimized for standard A4 paper printing
- **Professional Borders**: Clean rounded borders with proper spacing

### Advanced Features
- **Image Optimization**: Automatic compression and resizing
- **Duplicate Canvas**: Clone entire canvas layouts in sequence
- **Real-time Preview**: See your layout before printing
- **Drag & Drop**: Easy file upload interface
- **Print-Ready Output**: Optimized CSS for perfect printing

### Image Processing
- **Quality Control**: Adjustable compression (10%-100%)
- **Size Optimization**: Custom width/height limits
- **Format Support**: JPEG, PNG, and other common formats
- **Compression Stats**: Real-time file size reduction information

## 🚀 Getting Started

### Installation
1. Download the `index.html` file
2. Open in any modern web browser
3. Start creating your ID card layouts immediately

### Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No internet connection required (fully offline)
- No additional software installation needed

## 📖 How to Use

### Single Mode (Default)
1. **Upload Images**: Click on upload areas to select front and back images
2. **Set Copies**: Choose number of copies (2, 4, 6, or 8)
3. **Adjust Quality**: Modify image compression settings if needed
4. **Generate Layout**: Click "Generate Layout" to create printable pages
5. **Print**: Use the "Print" button for optimized printing

### Multi Mode
1. **Switch Mode**: Click "Toggle Mode" to switch to Multi mode
2. **Add People**: Use "Add Person" button (up to 4 people supported)
3. **Upload All Images**: Provide front and back images for each person
4. **Set Individual Copies**: Choose copies for each person separately
5. **Generate & Print**: Same as Single mode

### Duplicate Canvas Feature
- **Enable Duplication**: Check "Duplicate Canvas" before generating layout
- **Result**: Each canvas will be duplicated in A,A,B,B sequence
- **Use Case**: Perfect for backup copies or different distribution needs

## ⚙️ Advanced Settings

### Image Quality Settings
- **Image Quality Slider**: 10% (smallest file) to 100% (best quality)
- **Recommended**: 60% for good balance of quality and file size
- **Max Width**: 300-2000 pixels (default: 800px)
- **Max Height**: 300-2000 pixels (default: 500px)

### Print Optimization
- **A4 Layout**: 210mm × 297mm standard size
- **Card Dimensions**: 3.7" × 2.3" per ID card
- **Page Capacity**: Up to 4 ID rows per A4 page
- **Print Margins**: 10mm border for clean printing

## 🌐 Browser Compatibility

### Fully Supported
- ✅ Google Chrome (v80+)
- ✅ Mozilla Firefox (v75+)
- ✅ Safari (v13+)
- ✅ Microsoft Edge (v80+)

### Features Used
- HTML5 File API
- Canvas Image Processing
- CSS Print Media Queries
- JavaScript ES6+ Features

## 📝 Version History

### v1.2.0 - Duplicate Canvas Feature *(Current)*
- ✨ **NEW**: Added "Duplicate Canvas" functionality
- ✨ **NEW**: A,A,B,B sequence duplication pattern
- ✅ Compatible with both Single and Multi modes
- 🔧 Enhanced user interface with organized controls

### v1.1.0 - PDF Size Optimization
- ✨ **NEW**: Advanced image compression controls
- ✨ **NEW**: Adjustable quality slider (10%-100%)
- ✨ **NEW**: Custom dimension limits for optimization
- 📊 **NEW**: Real-time compression statistics
- ⚡ Improved print output quality
- 🔧 Better file size management

### v1.0.0 - Initial Release
- 🎉 Core ID card layout functionality
- 📱 Single and Multi person modes
- 🖼️ Front and back image support
- 🖨️ A4 print-optimized layout
- ⚙️ Basic copy number selection (2,4,6,8)
- 🎨 Professional styling with rounded borders

## 🔧 Technical Specifications

### File Structure
```
id-card-tool/
├── index.html          # Main application file
├── README.md          # This documentation
└── icon.png          # Optional: App icon (if available)
```

### Code Architecture
- **Frontend Only**: Pure HTML, CSS, JavaScript
- **No Dependencies**: No external libraries required
- **Offline Ready**: Works without internet connection
- **Responsive Design**: Adapts to different screen sizes

### Image Processing
- **Canvas API**: Used for image optimization
- **JPEG Compression**: Automatic format conversion
- **Memory Efficient**: Optimized image storage system
- **Unique ID System**: Prevents image conflicts

## 🛠️ Troubleshooting

### Common Issues

**Images not displaying**
- Ensure file formats are supported (JPEG, PNG, etc.)
- Check if images are corrupted
- Try reducing image file size

**Print layout issues**
- Use browser's print preview before printing
- Ensure A4 paper size is selected
- Check printer margins are set to minimum

**Performance issues**
- Reduce image quality setting
- Lower max width/height values
- Avoid extremely large source images (>5MB)

**Browser compatibility**
- Update to latest browser version
- Clear browser cache if issues persist
- Try different browser if problems continue

### Optimization Tips
- Use 60% quality for best size/quality balance
- Keep source images under 2MB for best performance
- Generate layout before making setting changes
- Use duplicate canvas feature judiciously for large layouts

## 🤝 Contributing

We welcome contributions to improve this tool! Here's how you can help:

### Areas for Contribution
- 🐛 Bug fixes and improvements
- ✨ New features and enhancements
- 📚 Documentation updates
- 🎨 UI/UX improvements
- 🔧 Performance optimizations

### Development Guidelines
- Maintain backward compatibility
- Follow existing code style
- Test across multiple browsers
- Update version numbers appropriately
- Document all changes in README

## 📄 License

This project is released under the MIT License. You are free to:
- ✅ Use commercially
- ✅ Modify and distribute
- ✅ Include in private projects
- ✅ Share with attribution

## 📞 Support

For questions, issues, or feature requests:
- Check the [Troubleshooting](#troubleshooting) section first
- Review [Version History](#version-history) for recent changes
- Ensure you're using the latest version

---

**Made with ❤️ for efficient ID card printing**

*Last updated: August 2025 | Version 1.2.0*
