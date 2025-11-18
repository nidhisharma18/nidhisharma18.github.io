# My Portfolio Website

Hey! This is my personal portfolio site where I showcase my work, experience, and projects. Built it with a dark theme (black & purple) because I'm a fan of how it looks - plus it's easier on the eyes when browsing late at night.

## What's Here

Pretty straightforward setup:
- Dark theme with purple accents (my favorite color combo)
- Responsive design that works on phones, tablets, laptops - basically everything
- Some smooth animations and hover effects to make it feel less static
- A typing animation in the hero section that cycles through different roles
- Sections for all the usual stuff: projects, work experience, skills, education, and contact info

## Tech Stack

Nothing fancy, just vanilla web technologies:
- HTML5
- CSS3 (using CSS variables because they're super handy)
- Plain JavaScript (no frameworks, kept it simple)
- Font Awesome for icons
- Inter font from Google Fonts

## Running It Locally

You'll need a web browser (any modern one works) and a way to serve it locally since opening HTML files directly can be limiting.

**Option 1: Python** (if you have it installed)
```bash
python3 -m http.server 8000
```
Then go to `http://localhost:8000`

**Option 2: Node.js**
```bash
npx http-server
```

**Option 3: VS Code**
If you're using VS Code, just install the "Live Server" extension and right-click on `index.html` → "Open with Live Server"

## Making It Yours

If you want to use this as a template, here's where to update stuff:

**Personal info**: Everything's in `index.html` - just search and replace
- Hero section has name and description
- "Reach Out" section has contact details
- About section has your bio

**Projects**: Each project is in its own card in the projects section. Pretty easy to add/remove/modify.

**Skills**: The skills section is organized by categories. Just add or remove tags as needed.

**Styling**: Most colors are CSS variables at the top of `styles.css` in the `:root` section. Change those and the whole site updates. I went with purple (#8b5cf6) as the primary color, but feel free to switch it up.

**Typing animation**: The rotating text is controlled by the `typingTexts` array in `script.js`. Update that to change what roles/titles cycle through.

## Deploying to GitHub Pages

Since this is already set up as a GitHub Pages repo, it should deploy automatically once you push to the `main` branch. If it doesn't:

1. Go to your repo settings on GitHub
2. Click "Pages" in the sidebar
3. Select `main` branch and `/ (root)` folder
4. Hit save

Should be live at `https://nidhisharma18.github.io` within a few minutes.

## Project Structure

```
.
├── index.html     # Main page
├── styles.css     # All the styling
├── script.js      # JavaScript for interactions & animations
└── README.md      # This file
```

Add your resume PDF as `resume.pdf` in the root folder if you want the "View Resume" button to work.

## Credits & Thanks

- Icons from [Font Awesome](https://fontawesome.com/)
- Fonts from [Google Fonts](https://fonts.google.com/)
- Inspiration from various portfolio sites I've seen over the years

## Notes

This is my personal portfolio, so I'm not planning on maintaining it as a template for others. But feel free to fork it, use it, modify it however you want - just remember to update it with your own info!

---

Built by Nidhi Sharma

