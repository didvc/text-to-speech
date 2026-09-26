# VoiceFlow - Advanced Text-to-Speech Application

[![Live Demo](https://img.shields.io/badge/Live_Demo-blue?style=for-the-badge)](https://text-speech.pages.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/issues)
[![GitHub stars](https://img.shields.io/github/stars/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/stargazers)

A modern, feature-rich text-to-speech web application built with React and TypeScript. VoiceFlow provides an intuitive interface for converting text to natural-sounding speech with real-time word highlighting, customizable voice settings, and content management capabilities.

## Screenshots

![VoiceFlow Application Interface](https://res.cloudinary.com/dxowqxqtj/image/upload/v1753415581/text-to-speech/voiceflow-main-screenshot.png)

*VoiceFlow's intuitive interface featuring real-time word highlighting, customizable voice controls, and content management.*

## Features

### Core Functionality
- Text-to-Speech Conversion: High-quality speech synthesis using the Web Speech API
- Real-time Word Highlighting: Visual feedback with animated word highlighting during playback
- Voice Controls: Play, pause, and stop functionality with responsive controls
- Multiple Voice Support: Choose from available system voices with language detection

### Customization
- Adjustable Speech Rate: Control playback speed from 0.5x to 2x
- Pitch Control: Fine-tune voice pitch for optimal listening experience
- Volume Control: Adjust audio output level
- Voice Selection: Choose from available system voices

### Content Management
- Text Library: Organize multiple text documents with titles
- Add/Edit/Delete: Full CRUD operations for text content
- Content Switching: Seamless switching between different texts
- Persistent Storage: Content saved locally in the browser

### User Interface
- Modern Dark Theme: Sleek, eye-friendly dark interface
- Responsive Design: Works perfectly on desktop, tablet, and mobile devices
- Gradient Branding: Beautiful gradient text and visual elements
- Intuitive Controls: User-friendly interface with clear visual feedback

## Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager
- Modern web browser with Web Speech API support

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/didvc/text-to-speech.git
   cd text-to-speech
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser
   Navigate to `http://localhost:5173` to see the application

### Building for Production

```bash
npm run build
# or
yarn build
```

The built files will be available in the `dist/` directory.

## Usage

### Basic Usage
1. Select or Add Text: Choose from the pre-loaded examples or add your own text content
2. Customize Settings: Adjust voice, speed, pitch, and volume to your preference
3. Play: Click the play button to start text-to-speech conversion
4. Follow Along: Watch the real-time word highlighting as the text is read

### Advanced Features
- Content Management: Use the text library to organize multiple documents
- Voice Switching: Experiment with different voices and languages
- Speed Control: Adjust reading speed for comprehension or accessibility needs
- Mobile Support: Full functionality available on mobile devices

## Technology Stack

- Frontend Framework: React 18
- Language: TypeScript
- Build Tool: Vite
- Styling: Tailwind CSS
- Icons: Lucide React
- Speech API: Web Speech API (SpeechSynthesis)

## Browser Compatibility

VoiceFlow works on modern browsers that support the Web Speech API:

- Chrome/Chromium (recommended)
- Edge
- Safari
- Firefox (limited voice selection)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Responsive Design

VoiceFlow is designed to work seamlessly across all device types:
- Desktop: Full feature set with optimized layout
- Tablet: Touch-friendly interface with adaptive controls  
- Mobile: Compact design with essential features accessible

## Contributing

We welcome contributions from the community! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details on how to get started.

### Quick Start for Contributors
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Issues and Support

- Bug Reports: [Create an issue](https://github.com/didvc/text-to-speech/issues/new?template=bug_report.yml)
- Feature Requests: [Request a feature](https://github.com/didvc/text-to-speech/issues/new?template=feature_request.yml)
- Discussions: [Join the conversation](https://github.com/didvc/text-to-speech/discussions)

## Acknowledgments

- Web Speech API for providing the text-to-speech functionality
- React and TypeScript communities for excellent tooling
- Tailwind CSS for the beautiful styling system
- Lucide React for the clean, modern icons

## Project Stats

- Build Size: Optimized for fast loading
- Dependencies: Minimal and carefully selected
- Performance: Smooth 60fps animations and responsive interactions
- Accessibility: WCAG compliant with keyboard navigation support

---

<div align="center">

[Try VoiceFlow Live](https://text-speech.pages.dev) | [Documentation](https://github.com/didvc/text-to-speech/wiki) | [Discussions](https://github.com/didvc/text-to-speech/discussions)

Made by [didvc](https://github.com/didvc)

</div>