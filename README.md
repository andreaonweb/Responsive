/* Мобильные телефоны (480px и меньше) */
@media screen and (max-width: 480px) {
    header {
        padding: 8px 3px;
    }
    
    .header {
        gap: 5px;
        flex-wrap: nowrap;
    }
    
    .navbar {
        flex-direction: row;
        gap: 5px;
        margin-top: 0;
        flex-shrink: 1;
    }
    
    .headerNav {
        margin: 0 3px;
        font-size: 10px;
        padding: 3px 6px;
        border-radius: 3px;
        background-color: rgba(255, 255, 255, 0.3);
        white-space: nowrap;
    }
    
    .duckLogo {
        width: 45px;
        height: 45px;
        margin-left: 5px;
        flex-shrink: 0;
    }
    
    .navRight {
        gap: 5px;
        flex-shrink: 0;
    }
    
    .carrito, .usuario {
        width: 32px;
        height: 32px;
        margin-right: 5px;
    }
    
    .footer {
        padding: 20px 10px;
        gap: 20px;
    }
    
    .duckLogoFooter {
        width: 50px;
        height: 50px;
    }
    
    .companyData p {
        font-size: 12px;
    }
    
    .footerCenter p {
        font-size: 14px;
    }
    
    .socialIcono {
        width: 40px;
        height: 40px;
        margin-left: 10px;
    }
    
    main {
        padding: 15px;
        min-height: 500px;
    }
}

/* Очень маленькие экраны (320px и меньше) */
@media screen and (max-width: 320px) {
    .headerNav {
        font-size: 9px;
        padding: 2px 4px;
        margin: 0 2px;
    }
    
    .duckLogo {
        width: 35px;
        height: 35px;
        margin-left: 3px;
    }
    
    .carrito, .usuario {
        width: 28px;
        height: 28px;
        margin-right: 3px;
    }
    
    .socialIcono {
        width: 35px;
        height: 35px;
        margin-left: 8px;
    }
    
    .companyData p {
        font-size: 11px;
    }
    
    .footerCenter p {
        font-size: 12px;
    }
}

/* Ландшафтная ориентация на мобильных */
@media screen and (max-height: 500px) and (orientation: landscape) {
    header {
        height: auto;
        padding: 8px 5px;
    }
    
    .header {
        flex-direction: row;
        gap: 8px;
        flex-wrap: nowrap;
    }
    
    .navbar {
        order: 2;
        margin-top: 0;
        flex-shrink: 1;
    }
    
    .headerNav {
        font-size: 11px;
        margin: 0 5px;
    }
    
    .duckLogo {
        width: 40px;
        height: 40px;
        flex-shrink: 0;
    }
    
    .carrito, .usuario {
        width: 30px;
        height: 30px;
        flex-shrink: 0;
    }
    
    main {
        min-height: 300px;
    }
    
    footer {
        min-height: 120px;











# Responsive
Responsive de Patito Store :3.
# Duck Store - Responsive Website

A rubber duck store with fully responsive design for all devices.

The project is fully responsive and optimized for the following devices:

### 🖥️ Desktop (1200px+)
- Full version of the site
- Horizontal navigation
- All elements displayed in a row

### 📱 Tablets (768px - 1199px)
- **Header always in one line**
- Reduced element sizes
- Compact navigation
- Adapted footer

### 📱 Mobile phones (480px - 767px)
- **Header always in one line**
- Very compact navigation
- Minimal element sizes
- Optimized font sizes

### 📱 Small screens (320px - 479px)
- **Header always in one line**
- Minimal element sizes
- Simplified navigation
- Compact footer

### 📱 Landscape orientation
- **Header always in one line**
- Special adaptation for horizontal mode
- Optimized sizes for limited height

## 🎯 Header Features

**Important**: Header always remains in one line on all devices thanks to:
- `flex-direction: row` - horizontal arrangement
- `flex-wrap: nowrap` - prevents line wrapping
- `flex-shrink` - controls element compression
- `white-space: nowrap` - prevents text wrapping

## 🧪 Testing responsiveness

### In browser:
1. Open Developer Tools (F12)
2. Click the device icon (📱) or Ctrl+Shift+M
3. Select various devices from the dropdown list
4. Test all pages:
   - `index.html` - main page
   - `contacto.html` - contact page
   - `patodetalle.html` - product details page

### Popular sizes for testing:
- iPhone SE: 375x667
- iPhone 12 Pro: 390x844
- Samsung Galaxy S20: 360x800
- iPad: 768x1024
- iPad Pro: 1024x1366

## 🎨 Design features

- **Color scheme**: Yellow (#ffd95f) and beige
- **Font**: Poppins (Google Fonts)
- **Custom cursor**: Duck icon
- **Smooth animations**: Hover effects and transitions
- **Flexbox**: Modern layout
- **Single-line header**: On all devices

## 📁 Project structure

```
Duck Store/
├── index.html              # Main page
├── contacto.html           # Contact page
├── patodetalle.html        # Product details page
├── README.md              # This file
└── assets/
    ├── css/
    │   ├── styles.css              # Main styles
    │   ├── contactoStyle.css       # Contact page styles
    │   └── patodetalleStyle.css    # Product details styles
    └── img/
        ├── logo.png                # Logo
        ├── icons/                  # Icons
        └── duckImages/             # Duck images
```


## 🌐 Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 📞 Contacts

- **Phone**: +34 918 528 954
- **Address**: Barcelona, Spain
- **Social networks**: TikTok, Twitter, Instagram

---

© 2025 Duck Store - The world of rubber ducks! 🦆 
