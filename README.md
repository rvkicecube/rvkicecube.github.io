# IceCube Reykjavík Website

Welcome to the official website repository for IceCube Reykjavík - Iceland's premier Magic: The Gathering cube draft community.

## About

This website is built with [Quarto](https://quarto.org/), a scientific and technical publishing system that creates beautiful, responsive websites from markdown files.

## Structure

- `index.qmd` - Homepage with introduction and overview
- `about.qmd` - Detailed information about cube draft and our community
- `events.qmd` - Upcoming and past tournament information
- `decklists.qmd` - Featured decklists and strategy guides  
- `contact.qmd` - Contact information and FAQ
- `_quarto.yml` - Site configuration and navigation
- `styles.css` - Custom styling with ice/winter theme

## Building the Site

### Prerequisites

1. Install [Quarto](https://quarto.org/docs/get-started/)
2. Ensure you have a recent version of R or Python (optional but recommended)

### Local Development

1. Clone this repository
2. Navigate to the project directory
3. Run the development server:
   ```bash
   quarto preview
   ```
4. Open your browser to view the site (typically `http://localhost:3000`)

### Building for Production

To build the static site for deployment:

```bash
quarto render
```

This creates a `docs/` directory with the complete static website.

## Deployment

### GitHub Pages (Recommended)

1. Push your changes to the `main` branch
2. Go to your repository settings on GitHub
3. Under "Pages", set source to "Deploy from a branch"
4. Select `main` branch and `/docs` folder
5. Your site will be available at `https://rvkicecube.github.io`

### Alternative Deployment Options

- **Netlify**: Connect your GitHub repo for automatic deployments
- **Vercel**: Import the project for serverless deployment
- **Any Static Host**: Upload the contents of the `docs/` folder

## Customization

### Styling
- Edit `styles.css` to modify the visual design
- The current theme uses an ice/winter color palette with blues and whites
- CSS variables at the top of the file make color changes easy

### Content
- All content is in `.qmd` files using Markdown syntax
- Add new pages by creating new `.qmd` files and updating `_quarto.yml`
- Event information, contact details, and other content can be easily updated

### Configuration
- Site-wide settings are in `_quarto.yml`
- Update navigation, site title, and other metadata there

## Contributing

We welcome contributions to improve the website! Please:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `quarto preview`
5. Submit a pull request

## License

This website is open source and available under the MIT License.

## Contact

For questions about the website or IceCube Reykjavík events, please see our [Contact page](contact.qmd) or open an issue on GitHub.

---

*Built with ❄️ for the Icelandic Magic: The Gathering community*
