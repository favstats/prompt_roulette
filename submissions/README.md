# Game Submissions

This folder is for community game submissions.

## How to Submit a Game

1. Go to [Prompt Roulette](https://favstats.github.io/prompt_roulette/)
2. Click **Submit Game** in the Arcade Lounge
3. Fill in the form and paste your game HTML
4. Click **Submit Game (need GitHub account)**
5. Paste the JSON in the GitHub form and create a Pull Request

## What Happens Next

When your PR is merged:
1. A GitHub Action automatically processes your submission
2. The HTML is extracted to `games/your-game.html`
3. Your game is added to `games.json`
4. Your game appears in the Arcade Lounge!

## Submission Format

Each submission is a JSON file with this structure:

```json
{
  "title": "My Awesome Game",
  "author": "YourName",
  "theme": "Theme used",
  "genre": "Genre used",
  "twist": "Twist used",
  "difficulty": "normal",
  "description": "Brief description",
  "submitted": "2025-01-15",
  "html": "<!DOCTYPE html>..."
}
```

## Questions?

Open an issue or contact [@favstats](https://github.com/favstats).
