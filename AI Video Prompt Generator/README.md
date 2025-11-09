# AI Video Prompt Generator

Transform your simple ideas into professional, detailed video prompts optimized for AI video generation platforms like Runway ML, Pika Labs, and Stable Video Diffusion.

## Features

- 🎬 **Professional Prompt Generation** - AI-powered conversion of simple ideas into detailed, technical video prompts
- 🔌 **Multi-Provider Support** - Works with OpenRouter, OpenAI, Anthropic, Groq, and Together AI
- 🎨 **Customizable Settings** - Configure duration, aspect ratio, and visual style
- ✏️ **Live Editing** - Edit generated prompts directly in the interface
- 💾 **Local Storage** - API keys stored securely in your browser
- 📋 **One-Click Copy** - Instant clipboard copy for generated prompts

## Setup

1. Download the HTML file
2. Open it in your browser
3. Select your AI provider
4. Enter your API key
5. Start generating!

## Supported AI Providers

### OpenRouter
Multiple model options available:
- Claude 3.5 Sonnet (Recommended)
- GPT-4 Turbo & GPT-4o
- Llama 3.1 (70B & 405B)
- Gemini Pro 1.5
- Custom model support

### Direct Providers
- OpenAI (GPT-4)
- Anthropic (Claude)
- Groq (Llama models)
- Together AI

## Usage

1. **Configure API**
   - Select your AI provider from dropdown
   - Enter your API key
   - (OpenRouter only) Choose a model or enter custom model

2. **Describe Your Video**
   - Enter your video idea (simple or detailed)
   - Set duration (3-15 seconds)
   - Choose aspect ratio (16:9, 9:16, 1:1, 4:3)
   - Select style (Cinematic, Realistic, Animated, etc.)

3. **Generate & Use**
   - Click "Generate Professional Prompt"
   - Edit if needed
   - Copy and paste into your video generation tool

## API Keys

Get your API keys from:
- **OpenRouter**: [openrouter.ai](https://openrouter.ai)
- **OpenAI**: [platform.openai.com](https://platform.openai.com)
- **Anthropic**: [console.anthropic.com](https://console.anthropic.com)
- **Groq**: [console.groq.com](https://console.groq.com)
- **Together AI**: [api.together.xyz](https://api.together.xyz)

## Privacy

- ✅ All API keys stored locally in your browser
- ✅ No backend server or database
- ✅ API calls made directly to your chosen provider
- ✅ Zero data collection

## Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Active internet connection
- Valid API key from supported provider

## Tech Stack

- Pure HTML/CSS/JavaScript
- Tailwind CSS (CDN)
- Direct API integration (no backend needed)

## License

MIT License - Feel free to use and modify

## Contributing

Issues and pull requests welcome!

---

**Note**: This is a client-side only application. Your API keys never leave your browser except when making direct calls to your chosen AI provider.
