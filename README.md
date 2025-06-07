# 🌌 Galaxy Style Website Template

An interactive digital universe-themed website template. Experience an exciting user journey with 3D planets and starfield created using Three.js.

## ✨ Features

* 🌍 **3D Planets**: Rotating and clickable planet objects  
* ⭐ **Starfield Background**: 5000+ colorful stars backdrop
* 🎮 **Interactive Navigation**: Camera controls with mouse and touch support
* 📱 **Responsive Design**: Perfect display on mobile and desktop devices
* 🔗 **Dynamic Links**: Ability to assign different URLs to each planet
* 📝 **Notification System**: Windows XP style notification windows
* 🎨 **Customizable**: Easily change planet colors, positions, and links
* 
### Home Page View
![Ana Səhifə](https://github.com/RuhidJavadoff/galaxy-style-website-template/blob/main/screenshold/01a.png)

### 
![Planet İnteraktivliği](https://github.com/RuhidJavadoff/galaxy-style-website-template/blob/main/screenshold/02a.png)

## 🚀 Installation

1. **Clone the repository:**
```bash
git clone https://github.com/RuhidJavadoff/galaxy-style-website-template.git
cd galaxy-style-website-template
```

2. **Upload files to web server** or open on local server
3. **Open index.html** file in your browser

## ⚙️ Configuration

### Modifying Planet Data
Edit the `planetsData` array in the `main.js` file:

```javascript
const planetsData = [
    {
        id: 'planet-id',
        name: 'Planet Name',
        link: 'https://your-link.com',
        position: { x: 0, y: 0, z: 0 },
        radius: 5,
        color: 0x00FF00,
        texture: 'path/to/texture.png'
    },
    // You can add more planets...
];
```

### Changing Colors and Appearance
* **Background color**: `scene.background = new THREE.Color(0x050510);`
* **Star count**: `const starCount = 5000;`
* **Planet rotation speed**: `planet.rotation.y += 0.001;`

## 🎯 Use Cases

* ✅ Personal portfolio websites
* ✅ Company presentation pages  
* ✅ Creative project showcase
* ✅ Interactive menu system
* ✅ Gaming and entertainment platforms

## 📋 Requirements

* Modern web browser (Chrome, Firefox, Safari, Edge)
* WebGL support
* JavaScript must be enabled

## 🛠️ Technologies

* **Three.js** - 3D graphics library
* **JavaScript (ES6+)** - Main programming language
* **HTML5 Canvas** - Rendering surface
* **CSS3** - Styling and animations

## 📝 License

This project is shared under the MIT License. See the LICENSE file for detailed information.

## 🤝 Contributing

1. Fork the project
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Contact

**Ruhid Javadoff**
* 🌐 Website: [ruhidjavadoff.site](https://ruhidjavadoff.site)
* 📧 Email: ruhidjavadoff@gmail.com
* 📱 Social Media: Follow Us

## 💖 Support

If this project has been helpful to you, you can show your support:

### 💰 Donate
* 💳 **PayPal**: ruhidjavadoff@gmail.com
* 🌐 **Donation Page**: [ruhidjavadoff.site/donate](https://ruhidjavadoff.site/donate)

### ⭐ GitHub Stars
Don't forget to star this repository!

---

<div align="center">

**Welcome to your journey in the digital universe! 🚀**

Made with ❤️ by Ruhid Javadoff

</div>


