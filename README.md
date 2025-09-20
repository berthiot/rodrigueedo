# Rodrigue Edo - Professional Portfolio

A professional portfolio website built with Jekyll, featuring a modern design and responsive layout. Perfect for showcasing projects, skills, and experience.

## 🚀 Live Demo

Visit the live portfolio: [https://berthiot.github.io/rodrigueedo](https://berthiot.github.io/rodrigueedo)

## ✨ Features

- **Modern Design**: Clean, professional layout with attractive gradients and animations
- **Responsive**: Fully responsive design that works on desktop, tablet, and mobile
- **Fast Loading**: Optimized Jekyll site with efficient CSS and minimal JavaScript
- **SEO Optimized**: Built-in SEO optimization with meta tags and structured data
- **Portfolio Sections**:
  - Home page with featured projects
  - About page with skills and experience
  - Projects showcase with detailed descriptions
  - Contact page with multiple communication channels

## 🛠 Technology Stack

- **Jekyll 4.4+**: Static site generator
- **Sass/SCSS**: CSS preprocessing
- **HTML5 & CSS3**: Modern web standards
- **JavaScript**: Interactive features and animations
- **GitHub Pages**: Hosting and deployment

## 🚀 Quick Start with GitHub Codespaces

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/berthiot/rodrigueedo)

1. Click the "Open in GitHub Codespaces" badge above
2. Wait for the codespace to build (this may take a few minutes)
3. Once ready, run: `bundle exec jekyll serve --host=0.0.0.0 --port=4000`
4. Your portfolio will be available at the forwarded port (usually opens automatically)

## 💻 Local Development

### Prerequisites

- Ruby 3.0+
- Bundler gem

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/berthiot/rodrigueedo.git
   cd rodrigueedo
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Start the development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000`

### Development Commands

- **Build the site**: `bundle exec jekyll build`
- **Serve locally**: `bundle exec jekyll serve`
- **Serve with live reload**: `bundle exec jekyll serve --livereload`
- **Build for production**: `JEKYLL_ENV=production bundle exec jekyll build`

## 📝 Customization

### Personal Information

Edit `_config.yml` to update:
- Site title and description
- Contact information
- Social media links
- Navigation menu

### Content

- **Home page**: Edit `index.md`
- **About page**: Edit `about.md`
- **Projects page**: Edit `projects.md`
- **Contact page**: Edit `contact.md`

### Styling

- Main styles are in `_sass/main.scss`
- Colors and fonts can be customized in the CSS variables
- The layout uses CSS Grid and Flexbox for responsive design

### Adding Projects

To add new projects, edit the `projects.md` file and add new project cards following the existing structure:

```markdown
<div class="project-card">
    <h3 class="project-title">Your Project Name</h3>
    <p class="project-description">Project description...</p>
    <div class="project-tech">
        <span class="tech-tag">Technology 1</span>
        <span class="tech-tag">Technology 2</span>
    </div>
    <div class="project-links">
        <a href="#" class="project-link">Live Demo</a>
        <a href="#" class="project-link">GitHub</a>
    </div>
</div>
```

## 🚀 Deployment

This portfolio is designed to work seamlessly with GitHub Pages:

1. Push your changes to the `main` branch
2. Enable GitHub Pages in your repository settings
3. Select "Deploy from a branch" and choose `main`
4. Your site will be available at `https://yourusername.github.io/repositoryname`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)  
- Safari (latest)
- Edge (latest)
- iOS Safari
- Android Chrome

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes and commit: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

- **Email**: rodrigue.edo@example.com
- **GitHub**: [berthiot](https://github.com/berthiot)
- **Portfolio**: [https://berthiot.github.io/rodrigueedo](https://berthiot.github.io/rodrigueedo)

---

⭐ If you found this portfolio template helpful, please give it a star!