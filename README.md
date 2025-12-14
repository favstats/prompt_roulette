# Prompt Roulette 🎮

A party game that generates unique browser games on the fly using AI! Spin random combinations of themes, genres, and twists to create hilarious, challenging, and creative game prompts that players then build in real-time.

## 🎯 How It Works

1. **Spin the Wheel**: Get a random combination of Theme + Genre + Twist
2. **Copy the Prompt**: AI-ready prompt with all requirements included
3. **Build & Play**: Use any LLM (ChatGPT, Claude, etc.) to generate a game
4. **Judge & Repeat**: Most wins takes the crown!

## 🚀 Quick Start

1. Open [Prompt Roulette](https://favstats.github.io/prompt_roulette/)
2. Press `SPACE` or click **SPIN** to generate a prompt
3. Click **COPY PROMPT** and paste into your favorite AI
4. Ask for a single HTML file game
5. Play, judge, and repeat!

## 🎨 Game Requirements

All generated games must be:
- **FUN & ENGAGING** - Genuinely enjoyable to play
- **BEATABLE** - Winnable in 2-5 minutes by skilled players
- **CLEAR WIN CONDITION** - Obvious victory state
- **IMPRESSIVE DESIGN** - Bold, creative visuals that fit the theme
- **POLISHED UI** - Animations and visual feedback
- **SINGLE HTML FILE** - No external assets required

## 🎭 Difficulty Levels

- **Normal**: Balanced themes and mechanics
- **Chaos**: Social media/tech focused craziness
- **Brainrot**: Gen Z meme culture and internet absurdity

## 🕹️ Controls

- `SPACE` - Spin the wheel
- `C` - Copy prompt to clipboard
- `L` - Open Arcade Lounge (community games)
- `H` - Help/tutorial
- `M` - Toggle sound
- `R` - Restart game

## 🏆 Arcade Lounge

Browse and play games submitted by the community:
- Press `L` to access
- Search functionality
- Auto-loading from submissions
- GitHub Actions automated processing

## 🤝 Contributing Games

Want to share your AI-generated game?

1. Generate a prompt using Prompt Roulette
2. Build your game using any AI tool
3. Submit via the **"Submit Game"** button in Arcade Lounge
4. Fill out the form and paste your HTML code
5. GitHub Actions will automatically process and publish it!

## 🛠️ Technical Details

- **Frontend**: Vanilla HTML/CSS/JavaScript + Tailwind CSS
- **Data**: JSON files for themes, genres, and community games
- **Hosting**: GitHub Pages
- **Automation**: GitHub Actions for game submissions
- **Caching**: Smart caching with fallbacks for offline play

## 📁 Project Structure

```
prompt_roulette/
├── index.html          # Main game interface
├── games.json          # Community submitted games
├── themes.json         # Theme prompts by difficulty
├── genres.json         # Genre options by difficulty
├── twists.json         # Twist modifiers by difficulty
├── submissions/        # Game submission processing
├── games/              # Individual game HTML files
└── .github/            # GitHub Actions workflows
```

## 🎨 Customization

The prompt template can be edited in the code. Key requirements are:
- Winnable gameplay with clear victory conditions
- Engaging mechanics that fit the theme
- Bold design choices
- Polished user experience

## 🤖 AI Prompts

The generated prompts are optimized for AI game generation with:
- Clear technical requirements
- Specific gameplay constraints
- Design guidelines
- Implementation details

## 📜 License

This project is open source and available under standard open source licensing terms. Feel free to fork, modify, and share!

## 👥 Credits

Created by [Fabio Votta](https://github.com/favstats) (@favstats)

Special thanks to the AI game development community and all contributors!

## 🎮 Play Now

[https://favstats.github.io/prompt_roulette/](https://favstats.github.io/prompt_roulette/)

Spin the wheel, generate prompts, build games, have fun! 🎯✨