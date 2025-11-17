# Fairy-Wren-Marketing-Website

Web app presence for FairyWren.dev

## Development

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- [PNPM](https://pnpm.io/) (v10 or higher)

### Installation

Install dependencies using PNPM:

```bash
pnpm install
```

### Running Locally

Start the development server:

```bash
pnpm start
```

This will start a local web server at `http://localhost:8000` and automatically open it in your browser.

Alternatively, you can use:

- `pnpm dev` - Same as start (opens browser automatically)
- `pnpm serve` - Start server without opening browser

### Project Structure

```
.
├── index.html                          # Root page (/)
├── splendid-app/
│   ├── index.html                      # Splendid App page
│   └── privacy-policy.html             # Privacy Policy page
└── package.json                        # PNPM configuration
```

## Deployment

This site is configured to deploy automatically to GitHub Pages when changes are pushed to the `main` branch.

### GitHub Pages Configuration

The site uses GitHub Actions for deployment. To enable:

1. Go to your repository settings
2. Navigate to **Pages** under **Code and automation**
3. Set **Source** to "GitHub Actions"
4. The workflow will automatically deploy on every push to `main`

The site will be available at: `https://superb-fairywren.github.io/Fairy-Wren-Marketing-Website/`

## Technologies

- HTML5
- CSS (Tailwind CSS via CDN)
- JavaScript
- GitHub Pages for hosting
- PNPM for package management
