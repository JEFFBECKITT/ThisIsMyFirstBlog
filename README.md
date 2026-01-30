# ThisIsMyFirstBlog

A personal blog website built with MkDocs and Material for MkDocs theme, featuring responsive design, accessibility, light/dark mode, and a beautiful gradient color scheme.

## Features

- ✨ **Responsive Design**: Works seamlessly on all devices
- 🌓 **Light/Dark Mode**: Toggle between themes based on preference
- 🎨 **Gradient Color Theme**: Beautiful purple gradient design
- ♿ **Accessible**: Built with accessibility in mind
- 🖼️ **Hero Images**: Stunning hero sections on each page
- 📝 **Blog**: Easy-to-manage blog posts
- 📧 **Contact Page**: Get in touch section

## Pages

- **Home**: Welcome page with overview
- **Blog**: Blog posts and articles
- **Contact**: Contact information and connection methods

## Local Development

### Prerequisites

- Python 3.x
- pip

### Installation

1. Clone the repository:
```bash
git clone https://github.com/JEFFBECKITT/ThisIsMyFirstBlog.git
cd ThisIsMyFirstBlog
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the development server:
```bash
mkdocs serve
```

4. Open your browser and navigate to `http://127.0.0.1:8000`

## Building the Site

To build the static site:

```bash
mkdocs build
```

The built site will be in the `site/` directory.

## Deployment

This site is configured to automatically deploy to GitHub Pages when changes are pushed to the main branch.

### Azure Static Web Apps

To deploy to Azure Static Web Apps, follow these steps:

1. Build the site: `mkdocs build`
2. Deploy the `site/` directory to Azure Static Web Apps

## Adding Blog Posts

To add a new blog post:

1. Create a new `.md` file in `docs/blog/posts/`
2. Add the post to the navigation in `mkdocs.yml` under the Blog Posts section
3. Update `docs/blog/index.md` to include a link to your new post

## Technologies Used

- [MkDocs](https://www.mkdocs.org/) - Static site generator
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) - Theme
- [GitHub Pages](https://pages.github.com/) - Hosting
- [GitHub Actions](https://github.com/features/actions) - CI/CD

## License

See the [LICENSE](LICENSE) file for details.