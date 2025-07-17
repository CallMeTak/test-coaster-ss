# Resin Coaster Color Tester

A React/Next.js application for testing and visualizing different resin coaster color combinations with metallic accents.

## Features

- Interactive color selection for base coaster colors
- Metallic accent options (Gold, Silver, Copper)
- Real-time preview of color combinations
- Responsive design
- Static export ready for GitHub Pages

## Development

\`\`\`bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build
\`\`\`

## Deployment

This project is configured for static export and can be deployed to GitHub Pages automatically via GitHub Actions.

### Setup Instructions:

1. Fork or clone this repository
2. Go to your repository settings on GitHub
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select "GitHub Actions"
5. Push to the main branch to trigger deployment

The site will be available at: `https://[your-username].github.io/resin-coaster-tester/`

## Project Structure

- `/app` - Next.js app router pages
- `/components` - Reusable React components
- `/images` - Static image assets
- `/.github/workflows` - GitHub Actions deployment configuration

## Technologies Used

- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- shadcn/ui components
