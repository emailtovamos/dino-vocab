# Dino Vocab

A Chrome dinosaur game with a twist — learn Spanish vocabulary while you run.

## Play Online

After pushing to GitHub, the game is live at:

**`https://<your-username>.github.io/<repo-name>/`**

## How to Play

Press **SPACE** or **tap** to start.

### Learning Phase
- Green cacti approach — **jump over them**
- Each jump reveals a Spanish word and its English meaning in the sky
- Two words are shown per round

### Quiz Phase
- A question appears: *"What does [word] mean?"*
- Three brown cacti approach one by one, each with an answer floating above it
- **Crash into** the correct answer (don't jump!)
- **Jump over** wrong answers
- Wrong crash or skipping all three = Game Over

### Controls
- **Space / Up Arrow** — Jump
- **Click / Tap** — Jump (mobile friendly)

## Features

- 40 Spanish-English vocabulary words
- Speed increases gradually each round
- One distractor is always the other word from the same round, forcing you to pay attention
- Score tracks distance + 100 bonus per correct quiz answer
- Single HTML file, no build step, no dependencies
- HiDPI / Retina display support
- Works on desktop and mobile

## Deploy to GitHub Pages

1. Create a new repo on GitHub
2. Push this code:
   ```bash
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. Go to **Settings > Pages** in your GitHub repo
4. Under **Source**, select **GitHub Actions**
5. The included workflow will auto-deploy on every push to `main`
6. Your game will be live at `https://<your-username>.github.io/<repo-name>/`

## Run Locally

Just open `index.html` in any browser. No server needed.
