# Cosmic Crew

## Overview

Cosmic Crew is a modern, interactive web application designed to connect local stargazing communities, provide real-time astronomy data, and offer an AI-powered learning experience. Built with vanilla JavaScript and deployed on Vercel, it offers a seamless, responsive experience for astronomy enthusiasts of all levels.

## Features

- **Tonight's Sky**: Real-time weather conditions, visible astronomical objects, and ISS pass times based on your location.
- **Local Events**: Discover and join stargazing events in your area.
- **Learning Path**: Structured lessons and achievements to guide your astronomy journey.
- **AI Astronomy Tutor**: Personalized learning assistance powered by advanced AI.
- **Community Hub**: Connect with local astronomy groups and mentors.

## API Integrations

- **OpenWeatherMap API**: Provides real-time weather data for stargazing conditions.
- **NASA APIs**:
  - Astronomy Picture of the Day (APOD)
  - Near-Earth Object Web Service (NEOWS)
  - ISS Pass Times
  - Planetary Positions

## AI Tutor

The AI tutor uses a personalized approach to answer astronomy questions. It considers your learning level, location, and sky conditions to provide tailored responses. Powered by the Perplexity Sonar API, it offers advanced natural language processing capabilities for an enhanced learning experience.

## Security

- **API Key Management**: All API keys are stored as environment variables and never exposed in the codebase.
- **Content Security Policy (CSP)**: Implemented to prevent XSS attacks.
- **Input Sanitization**: All user-generated content is sanitized before rendering to prevent XSS.

## Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/cosmiccrew.git
   cd cosmiccrew
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory with the following variables:

   ```
   OPENWEATHER_API_KEY=your_openweather_api_key
   NASA_API_KEY=your_nasa_api_key
   ```

4. **Run locally**:

   ```bash
   npm start
   ```

5. **Deploy to Vercel**:
   - Connect your GitHub repository to Vercel.
   - Set environment variables in the Vercel dashboard.
   - Deploy!

## Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) for details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenWeatherMap for weather data.
- NASA for astronomical data.
- Vercel for hosting and deployment.

---
