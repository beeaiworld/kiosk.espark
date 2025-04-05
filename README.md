# ESpark Mall Interactive Wayfinding Kiosk

A modern digital kiosk solution for indoor navigation in shopping malls, built with Mapbox GL JS and Three.js.

## Features

- 🗺️ Interactive Map Navigation
  - Smooth zoom, pan, and rotate controls
  - Custom map style definitions
  - Performance-optimized rendering

- 🏢 Indoor Precise Wayfinding
  - Detailed store boundaries
  - Multi-layer visualization
  - Custom polygon layers

- 🎯 Visual Store Identification
  - Color-coded store polygons
  - Clear labeling system
  - Key point indicators

- 📱 Multi-platform Support
  - Portrait kiosk display optimization
  - Responsive mobile web version
  - LTR and RTL language support

## Technical Stack

- **Core Mapping**: Mapbox GL JS
- **3D Visualization**: Three.js
- **Data Structure**: Custom GeoJSON Layers
- **Styling**: Mapbox Studio
- **Responsive Design**: Modern CSS/JavaScript

## Project Structure

```
espark-mall-wayfinding/
├── src/
│   ├── components/         # React components
│   ├── map/               # Mapbox implementation
│   ├── styles/            # CSS and styling
│   ├── utils/             # Helper functions
│   └── assets/            # Static assets
├── public/                # Public assets
└── docs/                  # Documentation
```

## Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/beeaiworld/kiosk.espark.git
cd kiosk.espark
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
cp .env.example .env
# Add your Mapbox access token to .env
```

4. Start development server:
```bash
npm start
```

## Configuration

### Mapbox Setup
1. Create a Mapbox account and obtain an access token
2. Configure map style in Mapbox Studio
3. Set up custom layers and overlays

### Kiosk Mode
- Configure for portrait orientation
- Enable touch interface
- Set up accessibility features

## Development Guidelines

### Code Style
- Follow ESLint configuration
- Use Prettier for code formatting
- Maintain consistent component structure

### Performance Optimization
- Implement lazy loading for map layers
- Optimize GeoJSON data structure
- Use efficient rendering techniques

## Deployment

### Kiosk Deployment
1. Build production version:
```bash
npm run build
```

2. Deploy to kiosk server
3. Configure for touch interface
4. Set up automatic updates

### Mobile Web Deployment
1. Configure responsive design
2. Optimize for mobile browsers
3. Implement service worker for offline support

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Mapbox for the core mapping technology
- Three.js community for 3D visualization support
- Contributors and maintainers

## Contact

For questions and support, please contact the development team.
