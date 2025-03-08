# Image Alchemy Converter ✨

A modern web-based image converter with a beautiful glass morphism design, offering client-side image conversion between popular formats. Built with pure HTML, CSS, and JavaScript.

![Demo Preview]
![image](https://github.com/user-attachments/assets/c71e26bc-9e71-48e7-a41a-86b050dedd4d)


## Features 🌟
- **Format Conversion**: Convert between JPEG, PNG, and WebP
- **Client-Side Processing**: Files never leave your device
- **Drag & Drop Interface**: Intuitive file upload
- **Glass Morphism UI**: Modern design with blur effects
- **Auto-Download**: Converted files download automatically
- **Theme Support**: 
  - Auto-detects system dark/light mode
  - Manual theme toggle button
- **Responsive Design**: Works on desktop and mobile
- **Visual Feedback**:
  - Loading spinner during conversion
  - Toast notifications for errors/success
  - Ripple animations on click

## Installation 💻
No server required! Just clone and open:
```bash
git clone https://github.com/mahesh-space/Image-Alchemy.git
cd Image-Alchemy
# Open index.html in a modern browser
```

## Usage 🖼️➡️🔄
1. **Upload Image**:
   - Click "Choose Image" or drag-drop a file
   - Supported formats: JPEG, PNG, WebP

2. **Select Output Format**:
   - Click the dropdown (default: JPEG)
   - Choose from JPEG, PNG, or WebP

3. **Convert**:
   - Click "Convert Now"
   - File auto-downloads after conversion
   - Toast notification confirms success

## Technologies Used 🛠️
- **HTML5**: File API for image handling
- **CSS3**: Glass morphism effects, animations
- **JavaScript**: 
  - Canvas API for image conversion
  - LocalStorage for theme preferences
- **Browser APIs**: 
  - Drag & Drop API
  - Blob API for file generation

## Theme Support 🌓
- Automatically matches system theme
- Manual toggle via 🌓 button (top-right)
- Preserves user preference across sessions

## Browser Support 🌐
| Browser | Support |
|---------|---------|
| Chrome  | ✅ 88+   |
| Firefox | ✅ 78+   |
| Edge    | ✅ 88+   |
| Safari  | ✅ 14.1+ |

*Note: WebP conversion may not work in older browsers.*

## Design Elements 🎨
- **Glass Morphism**:  
  Frosted glass effect using `backdrop-filter`
- **Animations**:
  - Dropdown slide-down
  - Ripple click effects
  - Smooth theme transitions
- **Responsive Layout**:
  - Flexbox for converter/description sections
  - Mobile-friendly dropdown

## License 📄
MIT License - See [LICENSE](LICENSE) for details.

---

**Crafted with ♥ by MG Jiwana**  
[Report Issues](https://github.com/mahesh-space/Image-Alchemy/issues) | 
[Contribute](https://github.com/mahesh-space/Image-Alchemy/pulls)

*For educational purposes. Not recommended for production use.*
