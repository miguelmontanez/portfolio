# Miguel Montanez — Software Developer Portfolio

A personal portfolio site that showcases Miguel's projects, experience, and contact details.

## Live demo

Visit the deployed site (if available): https://portfolio-5oc0.onrender.com/

## What this project contains

- A React-based portfolio web app with sections for summary, skills, education, experience, projects, blogs, and contact.
- Client-side code lives in the `src/` folder.
- Static build output (production) is placed in the `build/` folder.

## Sections

- Summary / About
- Skills and technologies
- Education
- Work experience
- Projects (Open source + Big projects)
- Achievements and certifications
- Blogs and talks
- Contact and social links

## Requirements

- Node.js 14+ and npm 6+ (or Yarn)
- Git (for cloning)
- Docker (optional)

## Quick start (local development)

```bash
# Clone the repository
git clone https://github.com/miguelmontanez/portfolio.git

# Enter the project folder
cd portfolio

# Copy example environment variables
# Linux/macOS
cp env.example .env
# Windows (PowerShell)
copy env.example .env

# Install dependencies
npm install

# Start development server
npm start
```

The dev server opens at http://localhost:3000 by default.

## Docker (optional)

```bash
# Build the image
docker build -t portfolio:latest .

# Run the container
docker run -p 3000:3000 portfolio:latest
```

## Configuration

- Edit `src/portfolio.js` to personalize content: name, summary, social links, and which sections to show.
- Use `src/_globalColor.scss` to change global color variables and theme.
- Add a resume PDF to `src/containers/greeting/resume/resume.pdf` to enable the resume link.
- Environment variables (in `.env`) include `REACT_APP_GITHUB_TOKEN`, `GITHUB_USERNAME`, and `MEDIUM_USERNAME` for optional integrations.

## Deployment

Recommended hosting options:
- GitHub Pages (see Create React App docs)
- Netlify
- Render

The project uses a standard Create React App build process:

```bash
npm run build
# then deploy the contents of the build/ folder to your host
```

## Technologies

- React
- lottie-react for animations
- react-twitter-embed
- react-easy-emoji
- SASS for styling

## Contributing

This repo contains the source for Miguel's personal portfolio. If you want to suggest edits, open an issue or submit a pull request.

## License

This repository is provided as-is. For licensing details, see the project `LICENSE` file.

