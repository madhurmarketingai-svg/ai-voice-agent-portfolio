# Quick Start - Get Up and Running in 5 Minutes

## What You'll Build

A working AI voice agent that can:
- Listen to what you say
- Understand your words
- Talk back naturally

## Step 1: Install Python (if you don't have it)

Download Python 3.9 or newer from [python.org](https://www.python.org/downloads/)

## Step 2: Download This Project

```bash
# Download the project
git clone https://github.com/madhurmarketingai-svg/ai-voice-agent-portfolio.git

# Go into the folder
cd ai-voice-agent-portfolio
```

## Step 3: Install Dependencies

```bash
# Create a virtual environment (keeps things clean)
python -m venv venv

# Activate it
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# Install everything
pip install -r requirements.txt
```

## Step 4: Get API Keys

You need keys from AI services:

**Option A: OpenAI (Recommended)**
1. Go to [openai.com](https://openai.com)
2. Sign up for an account
3. Get your API key from settings
4. Copy it

**Option B: Anthropic (Claude)**
1. Go to [anthropic.com](https://www.anthropic.com)
2. Get your API key
3. Copy it

## Step 5: Configure

```bash
# Copy the example file
cp .env.example .env

# Edit .env with your favorite text editor
# Add your API keys
```

Your `.env` should look like:
```
OPENAI_API_KEY=sk-your-key-here
LLM_PROVIDER=openai
LLM_MODEL=gpt-4
```

## Step 6: Test It!

```bash
# Run a simple test
python -c "from ai_voice_agent import VoiceAgent; print('Ready to go!')"
```

If you see "Ready to go!" - you're done! 🎉

## Step 7: Make It Talk

Create a file called `test.py`:

```python
from ai_voice_agent import VoiceAgent

# Create the agent
agent = VoiceAgent()

# Test it
print("Agent ready! Say something...")
response = agent.process_voice("Hello!")
print("Agent said:", response)
```

Run it:
```bash
python test.py
```

## Troubleshooting

### "ModuleNotFoundError: No module named 'ai_voice_agent'"
- Make sure you're in the right folder
- Make sure you ran `pip install -r requirements.txt`

### "API key invalid"
- Check your `.env` file
- Make sure your key is correct
- Make sure you have money in your account (free trials run out)

### "Python not found"
- Install Python from [python.org](https://www.python.org/downloads/)
- Restart your computer

## Next Steps

- Read the [full documentation](../README.md)
- Check [advanced examples](./EXAMPLES.md)
- Join our [community discussions](https://github.com/madhurmarketingai-svg/ai-voice-agent-portfolio/discussions)

## Need Help?

- 📧 Email: madhurmarketing.ai@gmail.com
- 💬 [Ask on GitHub Discussions](https://github.com/madhurmarketingai-svg/ai-voice-agent-portfolio/discussions)
- 🐛 [Report a bug](https://github.com/madhurmarketingai-svg/ai-voice-agent-portfolio/issues)

Congrats! You're now ready to use AI Voice Agent! 🚀