# Portfolio Setup Guide

## Welcome to your GitHub-like portfolio!

Congratulations! You now have a professional portfolio that looks like a GitHub profile but is fully customizable with your resume information.

## What's Included

1. **README.md** - Your GitHub profile README with all your resume information
2. **portfolio.html** - A standalone HTML portfolio page with modern design
3. **SETUP_GUIDE.md** - This guide to help you customize and deploy your portfolio

## Customization Steps

### 1. Replace Placeholder URLs

In both `README.md` and `portfolio.html`, you need to replace these placeholders:

- `YOUR_GITHUB_USERNAME` - Your GitHub username
- `YOUR_LINKEDIN_URL` - Your LinkedIn profile URL
- `YOUR_PORTFOLIO_URL` - Your personal website URL (if you have one)
- `YOUR_GITHUB_URL` - Your GitHub profile URL

### 2. Add Your Profile Picture

- In `portfolio.html`, replace the profile picture URL in the `<img>` tag
- In `README.md`, you can add a profile picture using GitHub's profile picture feature

### 3. Customize the Snake Animation (Optional)

If you want the animated contribution graph:

1. Create a new repository with your GitHub username (e.g., `yourusername/yourusername`)
2. Add the workflow file from `.github/workflows/main.yml` to your new repository
3. The animation will automatically generate every 12 hours

## Deploying Your Portfolio

### Option 1: GitHub Pages (Recommended)

1. Create a new repository named `yourusername.github.io`
2. Upload `portfolio.html` to this repository
3. Go to Settings → Pages → Source → Deploy from a branch
4. Choose `main` branch and `/` (root) folder
5. Your portfolio will be live at `https://yourusername.github.io/`

### Option 2: Any Web Hosting

- Upload `portfolio.html` to any web hosting service (Netlify, Vercel, Firebase, etc.)
- The file is self-contained and doesn't require any build process

### Option 3: GitHub Profile README

- Use the `README.md` file as your GitHub profile README
- Simply create a repository with your username and add this README

## Features of Your Portfolio

### GitHub-style README
- Animated header with your name and title
- Typing animation with your professional slogans
- About me section with personal information
- Skills section with expandable categories
- Featured projects with technology tags
- Professional experience with detailed descriptions
- Education and certifications
- GitHub analytics and contribution graphs
- Contact links

### Modern Portfolio Website
- Dark theme with GitHub-like styling
- Responsive design for all devices
- Smooth animations and transitions
- Clean, organized sections
- Social media integration
- Timeline view for experience and education

## Additional Customization

### Changing Colors

In `portfolio.html`, you can customize the colors by modifying the CSS variables:
- Primary color: `#58a6ff` (blue)
- Background: `#0d1117` (dark)
- Text: `#c9d1d9` (light gray)

### Adding More Projects

To add more projects, simply duplicate the project card in the HTML:
```html
<div class="project-card">
    <h3 class="project-title">Your Project Title</h3>
    <p class="project-description">Project description here</p>
    <div class="project-tech">
        <span class="tech-tag">Technology 1</span>
        <span class="tech-tag">Technology 2</span>
    </div>
</div>
```

### Updating Skills

Add or remove skills in the skills section:
```html
<span class="skill-tag">Your Skill</span>
```

## Support

If you need help customizing your portfolio, feel free to reach out:
- Email: harshithachavan620@gmail.com
- LinkedIn: Your LinkedIn profile

## License

This portfolio is open source and free to use. Feel free to modify it as you see fit.

---

**Happy coding!** 🚀
