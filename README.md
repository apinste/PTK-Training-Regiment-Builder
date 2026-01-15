# PTK-Training-Regiment-Builder
The PTK Training Regiment Builder is an interactive web application designed for Pekiti Tirsia Kali practitioners to create personalized training protocols. This innovative tool allows students to build custom daily training regimens by selecting techniques, setting repetitions, and organizing their practice sessions.

# PTK Training Regiment Builder

![PTK Logo](https://img.shields.io/badge/Pekiti_Tirsia_Kali-Training_Tools-d4af37?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

## 🥋 About

The **PTK Training Regiment Builder** is an interactive web application designed for Pekiti Tirsia Kali practitioners to create personalized training protocols. This innovative tool allows students to build custom daily training regimens by selecting techniques, setting repetitions, and organizing their practice sessions.

**Nunquam Non Paratus** - *Never Unprepared*

---

## ✨ Features

- 📚 **Technique Library** - Browse comprehensive video training materials
- 🎯 **Custom Regiment Builder** - Create personalized training sequences
- ⏱️ **Training Timer** - Set repetitions and duration for each technique
- 🔄 **Reorder Exercises** - Drag and arrange techniques in your preferred order
- 🎬 **Training Mode** - Guided playback through your custom regiment
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile devices
- 🎨 **PTK-Branded Interface** - Matches trainpekiti.com aesthetic

---

## 🚀 Live Demo

Visit the live application: [PTK Regiment Builder](https://yourusername.github.io/ptk-regiment-builder/ptk-regiment-builder.html)

*(Replace with your actual GitHub Pages URL)*

---

## 📋 Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Embedding in Wix](#embedding-in-wix)
- [Technology Stack](#technology-stack)
- [Security](#security)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 💻 Installation

### Option 1: Use GitHub Pages (Recommended)

1. **Fork or Clone this repository**
   ```bash
   git clone https://github.com/yourusername/ptk-regiment-builder.git
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Select main branch as source
   - Save changes

3. **Access your live site**
   - GitHub will provide a URL like: `https://yourusername.github.io/ptk-regiment-builder/`

### Option 2: Run Locally

1. **Download the repository**
   ```bash
   git clone https://github.com/yourusername/ptk-regiment-builder.git
   cd ptk-regiment-builder
   ```

2. **Open in browser**
   - Simply open `ptk-regiment-builder.html` in any modern web browser
   - No build process or server required!

---

## 📖 Usage

### Building Your Regiment

1. **Browse Techniques** - Use category filters to find specific techniques
2. **Add to Regiment** - Click "Add to Regiment" on any video
3. **Customize Settings** - Set repetitions and duration for each exercise
4. **Reorder** - Use up/down arrows to arrange your training sequence
5. **Begin Training** - Click "Begin Training" to start guided practice

### Training Mode

- Navigate through exercises with Previous/Next buttons
- View current exercise details and settings
- Complete your entire regiment in sequence
- Exit anytime to modify your regiment

---

## 🎨 Customization

### Adding Your Own Videos

Edit the `VIDEO_LIBRARY` array in `ptk-regiment-builder.html` (around line 24):

```javascript
const VIDEO_LIBRARY = [
  {
    id: 1,
    title: "Your Technique Name",
    category: "Solo Baston", // or Doble Baston, Espada y Daga, etc.
    level: "Fundamental",    // or Intermediate, Advanced
    duration: "8:30",
    thumbnail: "https://path-to-your-thumbnail.jpg",
    wixVideoId: "your-wix-video-id"
  },
  // Add more videos here...
];
```

### Customizing Categories

Categories are automatically generated from your video library. To add new categories, simply include them in your video objects.

### Changing Colors/Branding

The application uses Tailwind CSS classes. Search for color classes like `yellow-600`, `neutral-900`, etc., and replace with your preferred colors.

---

## 🌐 Embedding in Wix

### Step 1: Get Your GitHub Pages URL

After enabling GitHub Pages, copy your URL:
```
https://yourusername.github.io/ptk-regiment-builder/ptk-regiment-builder.html
```

### Step 2: Add to Wix

1. In Wix Editor, click **Add** (+) button
2. Go to **Embed Code** → **HTML iframe**
3. Click "Enter Code"
4. Paste this code:

```html
<iframe 
  src="https://yourusername.github.io/ptk-regiment-builder/ptk-regiment-builder.html"
  width="100%" 
  height="1000px"
  frameborder="0"
  sandbox="allow-scripts allow-same-origin"
  style="border: none;">
</iframe>
```

5. Adjust height as needed for your page layout

---

## 🛠️ Technology Stack

- **React 18** - UI component library
- **Tailwind CSS** - Utility-first CSS framework
- **Babel Standalone** - JSX transformation
- **Lucide React** - Icon library
- **Vanilla JavaScript** - No build process required

### Why These Technologies?

- ✅ **No server required** - Pure client-side application
- ✅ **No build process** - Works immediately in any browser
- ✅ **Secure** - Sandboxed iframe deployment
- ✅ **Fast** - Minimal dependencies, quick load times
- ✅ **Modern** - Latest React features and best practices

---

## 🔒 Security

### Safe Deployment Practices

- **Sandboxed iframe** - Restricts code execution to safe operations
- **HTTPS only** - GitHub Pages enforces secure connections
- **No external dependencies** - All libraries from trusted CDNs
- **No data collection** - All data stays in user's browser
- **No localStorage** - Data resets on page refresh for privacy

### Content Security

- All video content requires Wix member authentication
- Videos are not publicly accessible
- Repository code is open source but videos are protected

---

## 🤝 Contributing

We welcome contributions from the PTK community! Here's how you can help:

### Reporting Issues

1. Check existing issues to avoid duplicates
2. Create a new issue with detailed description
3. Include screenshots if applicable
4. Tag with appropriate labels

### Submitting Changes

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Code Style

- Use clear, descriptive variable names
- Comment complex logic
- Follow existing code formatting
- Test changes before submitting

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### What This Means

- ✅ Commercial use allowed
- ✅ Modification allowed
- ✅ Distribution allowed
- ✅ Private use allowed
- ⚠️ Must include license and copyright notice

---

## 📞 Contact

**Pekiti Tirsia Kali - Kaluyugan de Palares**

- 🌐 Website: [trainpekiti.com](https://trainpekiti.com)
- 📧 Email: contact@trainpekiti.com *(replace with actual email)*
- 💬 GitHub Issues: [Submit an issue](https://github.com/yourusername/ptk-regiment-builder/issues)

### Social Media

- Facebook: [Your Facebook Page]
- Instagram: [@yourinstagram]
- YouTube: [Your YouTube Channel]

---

## 🙏 Acknowledgments

- **Grandtuhon Leopoldo T. Gaje, Jr.** - Keeper of the Pekiti-Tirsia Kali System
- **Tuhon Arlene Pinpin Stevens** - First woman Tuhon in PTK
- **Tuhon Malcolm Stevens** - U.S. Marine veteran and FMA instructor
- **The PTK-KDP Community** - For continuous support and feedback

---

## 🗺️ Roadmap

### Current Features (v1.0)
- ✅ Video library browser
- ✅ Regiment builder
- ✅ Training mode
- ✅ Responsive design

### Planned Features (v2.0)
- 🔜 Save regiments to browser storage
- 🔜 Share regiments with training partners
- 🔜 Built-in interval timer with audio cues
- 🔜 Progress tracking and statistics
- 🔜 Printable training cards
- 🔜 Mobile app version

---

## 📊 Project Status

![Development Status](https://img.shields.io/badge/Development-Active-success)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![Last Updated](https://img.shields.io/badge/Last_Updated-January_2025-orange)

---

## ⭐ Show Your Support

If this project helps your training, please consider:

- ⭐ Starring this repository
- 🐛 Reporting bugs
- 💡 Suggesting new features
- 🤝 Contributing code
- 📢 Sharing with other PTK practitioners

---

**Veteran-Owned Business | Serving DC/MD/VA | Supporting Mentor-Based Training Circles**

*© 2025 Pekiti Tirsia Kali - Kaluyugan de Palares. All rights reserved.*
