# 🎨 Random Artist Discovery

Explore the world of art by discovering random artists from the MoMA (Museum of Modern Art) collection.

🔗 **[Try It Live](https://ericdataplus.github.io/random-artist-exploration/)**

## ✨ Features

- **Random Artist Generator** - Discover artists you've never heard of with a single click
- **Embedded Artwork Gallery** - Automatically loads Google Images of the artist's work
- **History Tracking** - See your recently discovered artists and revisit any of them
- **Keyboard Shortcuts** - `Space` for new artist, `Backspace` to go back
- **Mobile Optimized** - Fixed bottom navigation bar for easy use on phones
- **Responsive Design** - Works great on desktop, tablet, and mobile

## 🖼️ How It Works

1. **Data Source**: Uses a CSV of 5,000+ unique artists from the MoMA collection
2. **Random Selection**: Picks a random artist from the dataset
3. **Image Display**: Embeds Google Image search results for that artist's artwork
4. **History**: Keeps track of your last 15 discovered artists

## 🎮 Controls

| Action | Desktop | Mobile |
|--------|---------|--------|
| New Artist | Click "Discover Random Artist" or press `Space` | Tap "New Artist" |
| Go Back | Click "Go Back" or press `Backspace` | Tap "Back" |
| Google Search | Click "Search on Google Images" | Tap "Google" |
| Revisit Artist | Click any name in history | Tap any name in history |

## 🛠️ Tech Stack

- **HTML5** - Structure
- **CSS3** - Styling with CSS variables and flexbox/grid
- **Vanilla JavaScript** - No dependencies, pure JS
- **CSV Data** - Artist names from MoMA dataset

## 📁 Files

```
random-artist-exploration/
├── index.html          # Main app (HTML + CSS + JS)
├── Unique_Artists.csv  # Dataset of 5,000+ artists
└── README.md           # This file
```

## 🚀 Local Development

```bash
# Clone the repo
git clone https://github.com/Ericdataplus/random-artist-exploration.git
cd random-artist-exploration

# Open in browser (need a local server for CSV loading)
python -m http.server 8000
# Then visit http://localhost:8000
```

## 💡 Why I Built This

As someone who loves discovering new things, I wanted a simple way to stumble upon artists I'd never heard of. Art museums have thousands of artists in their collections, but we typically only hear about the famous ones. This tool makes art exploration random and fun!

## 📄 License

MIT License - Feel free to use and modify!

---

Made with 🎨 by [Ericdataplus](https://github.com/Ericdataplus)
