# AI Keyword Extractor

![image](https://github.com/MunDo12138/Keyword_Extractor/assets/66548936/1039de83-fbc5-43b0-a472-d4c9d54ee417)

A modern React web application that uses OpenAI's GPT model to intelligently extract keywords from any text input. Built with React, Vite, and Chakra UI for a clean, responsive user experience.

## Features

- **AI-Powered Extraction**: Leverages OpenAI's text-davinci-003 model for intelligent keyword identification
- **Clean Interface**: Modern UI built with Chakra UI components
- **Real-time Processing**: Instant keyword extraction with loading indicators
- **Input Validation**: User-friendly error handling and toast notifications
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Modal Results**: Keywords displayed in an elegant modal overlay

## Tech Stack

- **Frontend**: React 18 with JSX
- **Build Tool**: Vite for fast development and optimized builds
- **UI Library**: Chakra UI with Emotion for styling
- **Animations**: Framer Motion for smooth interactions
- **API**: OpenAI GPT-3.5 integration

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager
- OpenAI API key

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd keyword-extractor
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your OpenAI credentials:
```env
VITE_OPENAI_API_KEY=your_openai_api_key_here
VITE_OPENAI_API_URL=https://api.openai.com/v1/completions
```

4. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:3000`

## Usage

1. Enter or paste your text into the textarea
2. Click "Extract Keywords" to process the text
3. View the extracted keywords in the modal popup
4. Keywords are automatically formatted with proper capitalization

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally

## Project Structure

```
src/
├── components/
│   ├── Header.jsx          # App header with logo and title
│   ├── TextInput.jsx       # Text input and submission logic
│   ├── KeywordsModal.jsx   # Modal for displaying results
│   └── Footer.jsx          # Footer with OpenAI attribution
├── assets/                 # Images and static assets
├── App.jsx                 # Main application component
├── main.jsx               # Application entry point
└── index.css              # Global styles
```

## Configuration

The app uses environment variables for OpenAI API configuration. Make sure to set up your `.env` file with the required credentials before running the application.

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).