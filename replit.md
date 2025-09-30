# Hayahay | Blog

## Overview
This is a Hugo static site blog using the Ananke theme. Hugo is a fast and modern static site generator written in Go.

## Project Setup
- **Build System**: Hugo v0.147.3
- **Theme**: Ananke (cloned from https://github.com/theNewDynamic/gohugo-theme-ananke.git)
- **Configuration**: hugo.toml
- **Content**: Markdown files in content/posts/

## Development
The Hugo development server runs on 0.0.0.0:5000 with the following command:
```
hugo server --bind 0.0.0.0 --port 5000 --baseURL /
```

## Deployment
Configured for autoscale deployment:
- Build: `hugo --minify`
- Run: Hugo server on port 5000

## Recent Changes
- 2025-09-30: Initial Replit setup
  - Installed Hugo via Nix package manager
  - Cloned Ananke theme into themes directory
  - Configured development workflow for port 5000
  - Set up deployment configuration for autoscale

## Project Structure
- `/content/posts/`: Blog post content in Markdown
- `/themes/ananke/`: Ananke theme files
- `/public/`: Generated static site (built automatically)
- `/hugo.toml`: Hugo configuration file
