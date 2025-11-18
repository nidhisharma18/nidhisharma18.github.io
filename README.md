# Portfolio Website

A modern, responsive portfolio website showcasing projects, experience, skills, and contact information.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🎯 Interactive typing animation in hero section
- 📋 Sections for Projects, Experience, Skills, Contact, and About
- 🎨 Beautiful gradient hero section
- 🔍 Smooth scrolling navigation

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (Vanilla JS)
- Font Awesome Icons
- Google Fonts (Inter)

## Getting Started

### Prerequisites

- A web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/nidhisharma18/nidhisharma18.github.io.git
cd nidhisharma18.github.io
```

2. Open `index.html` in your web browser or use a local server:

Using Python:
```bash
python -m http.server 8000
```

Using Node.js (http-server):
```bash
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Customization

### Personal Information

1. **Name and Title**: Edit the hero section in `index.html`
   - Update the `hero-title` with your name
   - Modify the typing texts in `script.js` (typingTexts array)

2. **Contact Information**: Update the "Reach Out" section
   - Location
   - Email
   - Phone number

3. **About Section**: Update your bio and personal details

4. **Projects**: Add or modify projects in the projects section
   - Update project titles, descriptions, features
   - Add or remove project tags
   - Update project links

5. **Experience**: Update work experience details
   - Company names
   - Job titles
   - Dates
   - Responsibilities and achievements

6. **Skills**: Update skills and technologies
   - Add or remove skill tags
   - Modify categories as needed

### Styling

- **Colors**: Edit CSS variables in `styles.css` at the `:root` selector
- **Fonts**: Change the Google Fonts import in `index.html`
- **Spacing**: Modify padding and margins in the CSS file

### Typing Animation

Edit the `typingTexts` array in `script.js` to change the animated text in the hero section:

```javascript
const typingTexts = [
    'Your Title 1',
    'Your Title 2',
    'Your Title 3',
];
```

## Deployment

### GitHub Pages

1. Push your code to the repository:
```bash
git add .
git commit -m "Initial portfolio commit"
git push origin main
```

2. Go to your repository settings on GitHub
3. Navigate to "Pages" in the left sidebar
4. Select the branch (usually `main` or `master`)
5. Select the folder (`/ (root)`)
6. Click "Save"

Your site will be available at `https://nidhisharma18.github.io`

### Other Hosting Options

- **Netlify**: Drag and drop the folder or connect your GitHub repository
- **Vercel**: Connect your GitHub repository
- **AWS S3**: Upload files to an S3 bucket and enable static website hosting

## File Structure

```
nidhisharma18.github.io/
├── index.html          # Main HTML file
├── styles.css          # CSS stylesheet
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal use.

## Credits

- Design inspired by modern portfolio websites
- Icons from [Font Awesome](https://fontawesome.com/)
- Fonts from [Google Fonts](https://fonts.google.com/)

## Support

For issues or questions, please open an issue on the GitHub repository.

---

Made with ❤️ by Nidhi Sharma

