# Story Harbor

A warm, playful author website where people can discover your books, read featured chapters, and follow your newest releases.

## Features

- Interactive book reader with chapter navigation
- Responsive design for desktop and mobile
- Dark mode toggle
- Newsletter signup
- Built with Node.js for local development

## Local Development

1. Make sure you have Node.js installed (version 20 or higher).
2. Clone the repository.
3. Run `npm install` (though no dependencies are needed for the basic server).
4. Run `npm start` to start the server.
5. Open `http://localhost:3000` in your browser.

## Deployment

This project is set up for deployment to GitHub Pages. The workflow uses Node.js 24 to avoid deprecation warnings.

To deploy:
1. Push your changes to the `main` branch.
2. Enable GitHub Pages in your repository settings, selecting "GitHub Actions" as the source.
3. The workflow will automatically build and deploy your site.

## Customization

- Edit `index.html` for the main content.
- Modify `script.js` for interactivity.
- Update styles in the `<style>` tag in `index.html`.

## License

MIT