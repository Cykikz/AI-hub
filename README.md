# AI Chat Hub

A modern, interactive chat interface that simulates conversations with multiple AI assistants including ChatGPT, Claude, Bard, and Llama. Built with React and enhanced with smooth animations.

## Features

- 🤖 Multiple AI assistant personas
- ✨ Smooth animations using Framer Motion
- 💬 Real-time chat interface
- 🎨 Beautiful UI with Tailwind CSS
- 📱 Responsive design
- ✍️ Markdown support in messages

## Tech Stack

- React
- Vite
- Tailwind CSS
- Framer Motion
- React Markdown
- Hero Icons

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-chat-hub.git
cd ai-chat-hub
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:5173`

### Building for Production

To create a production build:

```bash
npm run build
```

The built files will be in the `dist` directory.

## Project Structure

```
ai-chat-hub/
├── src/
│   ├── components/
│   │   ├── BotSelector.jsx
│   │   └── ChatInterface.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── public/
├── index.html
└── package.json
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgments

- React team for the amazing framework
- Tailwind CSS for the utility-first CSS framework
- Framer Motion for the beautiful animations
- All contributors and supporters of the project

## Bots not responding?
To make it functional, you would need to:
Connect to actual AI APIs (like OpenAI for ChatGPT, Anthropic for Claude, etc.) #It is a unique api so it can't be shared by me refer to chatgpt or other ai bots for instructions on how to get their api key and use to make the hub functional.
Handle API authentication
Process responses from these services

## Contribute
- To contribute simply clone the repo
- Make change to the project
- Add new things
- Update your git
