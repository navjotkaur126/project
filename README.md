# project
# Song Lyrics Player

An interactive web application that synchronizes song lyrics with audio playback.

## 📋 Project Overview

**song.html** is a music player application featuring synchronized lyrics display. As the song plays, lyrics highlight in real-time and automatically scroll to keep the current lyric visible.

## ✨ Features

- **Audio Player** - Built-in HTML5 audio controls with play/pause functionality
- **Synchronized Lyrics** - Lyrics automatically highlight as they're sung in the song
- **Interactive Lyrics** - Click on any lyric to jump to that specific part of the song
- **Smooth Scrolling** - Current lyric automatically scrolls into view using smooth animation
- **Hover Effects** - Beautiful gradient hover effect on lyrics for better interactivity
- **Responsive Design** - Dark theme with elegant styling and smooth transitions
- **Auto-Pause** - Song automatically pauses when reaching the end

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and audio element
- **CSS3** - Styling, flexbox, animations, and gradients
- **JavaScript (Vanilla)** - Event listeners, DOM manipulation, time tracking

## 📝 How It Works

1. Each lyric line is associated with start and end timestamps
2. JavaScript listens to the audio's `timeupdate` event
3. When the current playback time falls within a line's time range, that line is marked as active
4. Active lines are highlighted with gold color and increased font size
5. The active line automatically scrolls into the center of the view
6. Users can click any lyric to jump to that part of the song

## 🎯 Key JavaScript Concepts Demonstrated

- **Event Listeners** - `addEventListener` for `timeupdate` and `click` events
- **DOM Manipulation** - `classList.add()`, `classList.remove()` for active state
- **Data Attributes** - Using `data-start` and `data-end` attributes for timing
- **Smooth Scrolling** - `scrollIntoView()` with smooth behavior
- **Floating Point Comparison** - Time-based conditionals for lyric synchronization

## 🎶 The Song

**"Finding Her"** - A poetic Hindi song about longing and memories, perfectly suited for lyric synchronization demonstration.

## 📂 Files Required

- `song.html` - Main HTML file with embedded CSS and JavaScript
- `songs.mp3` - Audio file (required for audio playback)

## 🚀 How to Use

1. Ensure `songs.mp3` is in the same directory as `song.html`
2. Open `song.html` in a web browser
3. Click play on the audio player to start
4. Watch lyrics highlight in real-time as the song plays
5. Click any lyric to jump to that timestamp

## 🎨 Styling Highlights

- Dark background (#111) for better readability
- Gold accent color (#ffd700) for active lyrics
- Pink gradient hover effect (#e1788a to #bf0c62)
- Smooth transitions on all interactive elements
- Custom scrollbar styling for clean appearance

---

Perfect for learning DOM manipulation, event handling, and interactive web design! 🎓

