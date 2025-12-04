# Kallakuru Venkateswara Swamy Temple Website

A beautiful, responsive website for the Kallakuru Venkateswara Swamy Temple in West Godavari, Andhra Pradesh.

## Features

- **Multi-Language Support**: Available in English (EN), Telugu (తె), and Hindi (हि)
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and elegant design with smooth animations
- **Easy Navigation**: Fixed navigation bar with smooth scrolling
- **Complete Information**: 
  - Temple history and legends (prominently displayed)
  - Visitor information and directions
  - Gallery section
  - Contact details
- **Language Switcher**: Easy language toggle in the navigation bar

## Getting Started

1. Open `index.html` in a web browser
2. No build process required - it's a simple static website

## Adding Images

The website is ready to display images. To add real temple images:

1. **Download images** from the provided source:
   - https://ourtemples.info/temple/sri-venkateswaraswamy-temple-juvvalapalem-road-kallakuru-andhra-pradesh-534237/

2. **Add images to the `images` folder**:
   - `temple-main.jpg` - Main temple image (About section)
   - `history-temple.jpg` - History section image (optional)
   - `gallery-1.jpg` to `gallery-6.jpg` - Gallery images

3. **Image file names must match exactly** (case-sensitive):
   - The website will automatically load images from the `images` folder
   - If an image is missing, a placeholder will be shown

4. **See `images/README.md`** for detailed image requirements and guidelines

## Customization

### Colors
Edit the CSS variables in `styles.css` (lines 4-10) to change the color scheme:
- `--primary-color`: Main accent color (currently gold)
- `--secondary-color`: Secondary color (currently dark gold)
- `--text-color`: Main text color
- `--light-bg`: Background color for alternate sections

### Content
- Edit `index.html` to update any text content
- All temple information is based on the provided sources

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Language Support

The website supports three languages:
- **English (EN)** - Default language
- **Telugu (తె)** - తెలుగు
- **Hindi (हि)** - हिंदी

### How to Use:
- Click the language buttons (EN/తె/हि) in the navigation bar
- Your language preference is saved in browser localStorage
- All content including navigation, history, and information is translated

### Adding More Languages:
Edit `translations.js` to add more languages. Follow the existing structure.

## File Structure

```
dev_web/
├── index.html         # Main HTML file
├── styles.css         # All styling
├── script.js          # JavaScript functionality
├── translations.js    # Multi-language translations
├── images/            # Image folder (add temple images here)
│   ├── README.md      # Image guidelines
│   ├── temple-main.jpg
│   ├── gallery-1.jpg
│   └── ...
└── README.md          # This file
```

## Notes

- **Images**: The website is ready to use but you'll need to add actual temple photographs to the `images` folder
- **History Section**: The temple history is prominently displayed with enhanced styling
- **Content**: All content is based on the temple history from the provided sources
- **Design**: The design is inspired by simple, clean temple websites
- **Language**: Language preference is automatically saved and restored on page reload

## Future Enhancements

- Add a lightbox for gallery images
- Add a contact form
- Add temple timings and pooja schedules
- Add donation/payment integration
- Add event calendar

---

**May Lord Venkateswara bless you with peace, prosperity, and happiness.**
