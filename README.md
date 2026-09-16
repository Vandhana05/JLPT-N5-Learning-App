# 🇯🇵 JLPT N5 Learning App

A beginner-friendly JLPT N5 Japanese learning app built with **React + Material UI (MUI) + Vite**.

## Roadmap
1. Hiragana
2. Katakana
3. Hiragana + Katakana Revision
4. Vocabulary

## Features
- Hiragana and Katakana cards
- Dakuten / Handakuten and combinations
- Side-by-side kana revision
- Vocabulary study cards and flashcards
- Shuffle and browser Japanese speech
- MUI responsive interface
- LocalStorage learning progress
- Firebase Hosting configuration

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## Firebase Hosting
```bash
npm install -g firebase-tools
firebase login
firebase init hosting
npm run build
firebase deploy --only hosting
```
