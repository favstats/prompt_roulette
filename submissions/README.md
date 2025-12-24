# Game Submissions

This folder is for community game submissions.

## How to Submit a Game

1. Go to [Prompt Roulette](https://favstats.github.io/prompt_roulette/)
2. Click **Submit Game** in the Arcade Lounge
3. Fill in the form and paste your game HTML
4. Click **Submit Game (need GitHub account)**
5. Paste the JSON in the GitHub form and create a Pull Request

## Where to Find Your Game's HTML Code

After ChatGPT, Claude, or another AI generates your game:

1. **Look for the code block** - It will contain HTML code starting with `<!DOCTYPE html>` or `<html>`
2. **Click the "Copy" button** - In most AI interfaces, there's a small copy button at the top-right of the code block
3. **Paste it in the submission form** - That's the HTML code you need!

### Visual Guide for Common AI Tools

**ChatGPT:**
- The code appears in a gray/dark box
- Hover over the box to see a "Copy code" button in the top-right corner
- Click it, then paste into the submission form

**Claude:**
- The code appears in a highlighted box
- Look for a copy icon (clipboard) at the top-right of the code block
- Click it, then paste into the submission form

**Other AIs:**
- Most show a copy button when you hover over code blocks
- If not, select all the code manually (click at the start, hold Shift, click at the end) and use Ctrl+C (Windows) or Cmd+C (Mac) to copy

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
