# Katakana Speed Trainer

An interactive web app for learning and mastering katakana through gamification and spaced repetition.

## Features

- **Progressive Learning**: Characters unlock gradually as you master each level
- **Spaced Repetition System (SRS)**: Smart algorithm that shows you characters based on your performance
- **Multiple Game Modes**:
  - Learn Mode: Structured progression through character rows
  - Practice Mode: Review all learned characters
  - Speed Challenge: 60-second timed drills
  - Word Reading: Practice with real katakana words
- **Progress Tracking**: Stats persist across sessions using browser localStorage
- **Responsive Design**: Works on desktop, tablet, and mobile

## Live Demo

Visit the GitHub Pages site: [Your URL will be here after enabling Pages]

## How It Works

The SRS algorithm tracks your performance on each character:
- Characters you struggle with appear more frequently
- Characters you master appear less often
- Adaptive intervals adjust based on your accuracy (1, 3, 7, 15, 30, 60 questions between reviews)
- Ease factor increases/decreases based on performance
- All progress saved locally in your browser

## Local Development

Simply open `index.html` in a web browser. No build process or server required!

## Deployment

This is a static site that can be hosted anywhere:
- **GitHub Pages**: Enable Pages in repo settings → select main branch → done
- Netlify
- Vercel
- Any static file hosting

No server or database required!

## Privacy

All data is stored locally in your browser using localStorage. Nothing is sent to any server.
