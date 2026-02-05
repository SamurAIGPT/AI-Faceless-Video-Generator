# AI Faceless Video Generator

[![GitHub stars](https://img.shields.io/github/stars/SamurAIGPT/AI-Faceless-Video-Generator?style=social)](https://github.com/SamurAIGPT/AI-Faceless-Video-Generator/stargazers)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/SamurAIGPT/Faceless-Video-Generator/blob/main/FacelessColab.ipynb)

Generate talking face videos from just a topic using AI. Combines script generation, text-to-speech, and face animation to create complete videos automatically.

## Tutorials

- **YouTube**: [Watch Tutorial](https://youtu.be/X1jJzTVOgvw)
- **Medium**: [Read Article](https://medium.com/@anilmatcha/ai-faceless-video-generator-in-python-a-complete-tutorial-f29ea5c47516)

## Demo

https://github.com/SamurAIGPT/Faceless-Video-Generator/blob/main/Demo/Demo1.mp4

## Features

- **Script Generation** - Generate video scripts on any topic using OpenAI GPT
- **AI Voice** - Convert scripts to natural-sounding speech with gTTS
- **Face Animation** - Create realistic talking avatars with SadTalker
- **End-to-End Pipeline** - From topic to video in one workflow
- **Custom Avatars** - Use any face image as your video presenter

## How It Works

```
Topic Input → GPT Script → gTTS Voice → SadTalker Animation → Video Output
```

1. Enter a topic for your video
2. AI generates a compelling script
3. Text-to-speech creates the voiceover
4. SadTalker animates the avatar to match the audio
5. Get your complete talking-head video

## Quick Start

### Option 1: Google Colab (Recommended)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/SamurAIGPT/Faceless-Video-Generator/blob/main/FacelessColab.ipynb)

1. Open the Colab notebook
2. Run all cells
3. Enter your topic and avatar
4. Download your video

### Option 2: Local Installation

```bash
# Clone the repository
git clone https://github.com/SamurAIGPT/AI-Faceless-Video-Generator.git
cd AI-Faceless-Video-Generator

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook FacelessColab.ipynb
```

## Requirements

- Python 3.8+
- OpenAI API key
- GPU recommended for SadTalker (or use Colab)

## API Alternative

Want to skip the setup? Use the [Vadoo AI API](https://docs.vadoo.tv/docs/guide/create-an-ai-video) to generate faceless videos programmatically:

```python
import requests

response = requests.post(
    "https://viralapi.vadoo.tv/api/generate_video",
    headers={"X-API-KEY": "your_api_key"},
    json={"topic": "Your Topic Here"}
)
```

## Tech Stack

| Component | Technology |
|-----------|------------|
| Script Generation | OpenAI GPT |
| Text-to-Speech | gTTS |
| Face Animation | SadTalker |
| Notebook Runtime | Google Colab |

## Contributing

Contributions are welcome! Feel free to submit a Pull Request.

## Follow for Updates

- [Anil Chandra Naidu Matcha](https://twitter.com/matchaman11)
- [Ankur Singh](https://twitter.com/ankur_maker)

## Related Projects

- [AI-Youtube-Shorts-Generator](https://github.com/SamurAIGPT/AI-Youtube-Shorts-Generator) - Generate YouTube Shorts
- [Text-To-Video-AI](https://github.com/SamurAIGPT/Text-To-Video-AI) - Text to video generation
- [AI-Influencer-Generator](https://github.com/SamurAIGPT/AI-Influencer-Generator) - Create AI influencers

## License

MIT License - see [LICENSE](LICENSE) for details.
