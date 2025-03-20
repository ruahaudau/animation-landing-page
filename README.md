# Design Tool Agent Landing Page

A modern, animated landing page showcasing design tool capabilities using Anime.js.

## Live Demo

Visit the live site: [Design Tool Agent](https://landingpage-ruahaudau.vercel.app/)

## Project Structure

```
anime/
├── public/              # Static files for deployment
│   ├── index.html      # Main landing page
│   └── lib/            # JavaScript libraries
│       └── anime.min.js
├── documentation/       # Anime.js documentation and examples
├── lib/                # Source library files
├── src/                # Source code
├── vercel.json         # Vercel deployment configuration
└── package.json        # Project dependencies
```

## Features

- Animated heart logo with continuous pulse effect
- Gradient text animations
- Interactive UI components
- Responsive design
- Statistics display with counting animations
- Smooth hover effects

## Technologies Used

- [Anime.js](https://animejs.com/) - JavaScript animation library
- HTML5/CSS3
- Vercel for deployment

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/ruahaudau/animation-landing-page.git
   cd animation-landing-page
   ```

2. Start a local server:
   ```bash
   python3 -m http.server 8000
   ```

3. Visit `http://localhost:8000` in your browser

## Deployment

The project is configured for deployment on Vercel. The `vercel.json` file handles:
- Static file serving from the `public` directory
- Proper routing configuration
- Build settings

To deploy:
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel --prod`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Credits

- Animation library: [Anime.js](https://animejs.com/)
- Fonts: Roobert, System fonts
- Icons: Custom SVG implementations
