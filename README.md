# Personal Portfolio Website

A modern, responsive personal portfolio website template built with HTML, CSS, and JavaScript.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth scrolling navigation
- 🎯 Interactive animations
- 📧 Contact form
- 🌈 Beautiful gradient hero section
- 💼 Project showcase section

## How to Run Locally

### Option 1: Simple HTTP Server (Recommended)

Since this is a static website, you can use any simple HTTP server. Here are a few options:

#### Using Python (if installed):

```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then open your browser and navigate to: `http://localhost:8000`

#### Using Node.js (if installed):

```bash
# Install http-server globally (one-time setup)
npm install -g http-server

# Run the server
http-server -p 8000
```

Then open your browser and navigate to: `http://localhost:8000`

#### Using PHP (if installed):

```bash
php -S localhost:8000
```

Then open your browser and navigate to: `http://localhost:8000`

### Option 2: Open Directly in Browser

You can also simply open `index.html` directly in your browser:
- Double-click `index.html`, or
- Right-click → Open with → Your preferred browser

**Note:** Some features (like smooth scrolling) may work better when served through an HTTP server rather than opening the file directly.

### Option 3: Using VS Code Live Server Extension

If you're using Visual Studio Code:
1. Install the "Live Server" extension
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Customization

### Update Personal Information

1. **Name and Title**: Edit `index.html` and replace:
   - "Your Name" with your actual name
   - "Full Stack Developer & Creative Problem Solver" with your title
   - Update the hero description

2. **About Section**: Modify the text in the `#about` section

3. **Skills**: Update the skill tags in the skills grid

4. **Projects**: Replace the project cards with your actual projects:
   - Update project titles and descriptions
   - Add your project links (GitHub, live demos)
   - Update technology tags

5. **Contact Information**: Update:
   - Email address
   - GitHub username
   - LinkedIn profile URL

6. **Profile Image**: Replace the SVG placeholder in the hero section with your actual profile image

### Styling

- **Colors**: Edit the CSS variables in `styles.css` (lines 7-14) to change the color scheme
- **Fonts**: The template uses Google Fonts (Inter). You can change this in `index.html`

### Contact Form

The contact form currently shows an alert when submitted. To make it functional:
- Connect it to a backend service (e.g., Formspree, EmailJS, or your own server)
- Update the form submission handler in `script.js`

## File Structure

```
.
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Deployment

### GitHub Pages

Since this is a `.github.io` repository, you can easily deploy it to GitHub Pages:

1. Push your code to the `main` branch
2. Go to your repository settings on GitHub
3. Navigate to "Pages" in the sidebar
4. Select the `main` branch as the source
5. Your site will be live at `https://yourusername.github.io`

### Other Hosting Options

- **Netlify**: Drag and drop your folder or connect your Git repository
- **Vercel**: Connect your Git repository for automatic deployments
- **Cloudflare Pages**: Similar to Netlify, free and easy to use

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your personal portfolio!