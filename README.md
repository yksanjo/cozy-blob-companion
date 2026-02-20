# 🥺 Cozy Blob Companion

An interactive virtual pet that lives in your browser! Take care of your blob, customize it, and watch its personality change based on how you treat it.

![Cozy Blob Companion](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

### 🎮 Core Gameplay
- **Virtual Pet System** - Feed, pet, and play with your blob
- **Personality System** - Your blob's behavior changes based on care
- **Stats Tracking** - Monitor hunger and love levels
- **Care Score** - Track how well you're parenting

### 🎨 Customization
- **Dress Up** - Bows, glasses, hats, and more!
- **Color Options** - 6 pastel colors to choose from
- **Accessories** - Mix and match outfits

### 🧸 Interactive Toys
- **Draggable Toys** - Ball, Teddy Bear, Rubber Duck, Star
- **Physics** - Ball bounces with realistic physics
- **Sounds** - Each toy makes unique sounds
- **Take Outside** - Play with toys in outdoor mode

### 📚 Reading System
- **4 Books** - Story, Science, Art, Music
- **Contentment Boost** - More reading = happier blob
- **No Cooldown** - Read as much as you want!

### 🎭 Personality States

| Personality | Cause | Behavior |
|-------------|-------|----------|
| 😊 Content | Normal care | Normal behavior |
| ✨ Well-Balanced | Love 50-80%, Hunger 50-90% | Perfect behavior |
| 😈 Mischievous | Love > 85% | Steals tarts, plays ball indoors, rejects pets |
| 😢 Lonely | Love < 30%, Hunger < 40% | Too sad to play, rejects interaction |
| 🥺 Warming Up | Was sad, getting care | Slowly accepts love again |

### 😠 Discipline System
- **Yell Button** - Appears when blob misbehaves
- **Justified Yells** - Corrects bad behavior (+care score)
- **Unjustified Yells** - Makes blob worse (-care score)

## 🚀 Quick Start

### Option 1: Open Directly
1. Download `cozy-blob-companion.html`
2. Open in any modern web browser
3. That's it!

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Then open http://localhost:8000
```

### Option 3: GitHub Pages
1. Fork this repository
2. Enable GitHub Pages
3. Access from your custom URL

## 🎯 How to Play

### Basic Care
1. **Feed** - Click egg tarts when hunger is low (+25 hunger)
2. **Pet** - Click the pet button when love is low (+15 love)
3. **Play** - Drag toys out and click to play (+20 love)
4. **Read** - Click books for contentment (+1-5 care score)

### Advanced Tips
- ⚠️ **Don't over-pet!** Love > 85% makes blob evil
- ⚠️ **Don't neglect!** Low stats make blob sad
- ✅ **Balance is key** - Keep both stats between 50-80%
- 📚 **Read daily** - Increases contentment over time
- 😠 **Yell wisely** - Only when blob actually misbehaves

### Evil Blob Behaviors
When your blob gets too much love:
- 🥧 **Steals tarts** - Watch them fly to the blob!
- ⚽ **Plays ball indoors** - Bouncing ball everywhere
- 💢 **Rejects pets** - Won't accept your love

Fix it by:
1. Stop petting temporarily
2. Yell when caught misbehaving (😠 button)
3. Wait for love to decay naturally

## 🛠️ Tech Stack

- **HTML5** - Single file, no dependencies
- **CSS3** - Animations, gradients, custom styles
- **Vanilla JavaScript** - No frameworks
- **Web Audio API** - Generated sound effects
- **Local Storage** - (Future) Save progress

## 🎵 Sound Effects

All sounds are generated using the Web Audio API:
- **Happy** - Ascending chime (C-E-G)
- **Surprised** - Rising squeak
- **Excited** - Bouncy double chime
- **Squish** - Soft boing
- **Squeak** - Teddy bear sound
- **Quack** - Rubber duck sound
- **Twinkle** - Star chime

## 📊 Stats Explained

### Care Score
- **0-30**: Poor care
- **30-60**: Average care
- **60-80**: Good care
- **80-100**: Perfect care

### Personality Indicators
- **Yells**: Total times yelled / justified yells
- **Books Read**: Total books read (increases contentment)

## 🎨 Color Palette

| Color | Hex | Description |
|-------|-----|-------------|
| White | `#ffffff` | Default |
| Pink | `#ffe4e8` | Soft pink |
| Blue | `#e8f4f8` | Sky blue |
| Green | `#f0f8e8` | Mint green |
| Cream | `#fff8e8` | Warm cream |
| Lavender | `#f4e8f8` | Soft purple |

## 🐛 Known Issues

- None currently! Report issues if found.

## 📝 Future Features

- [ ] Save/load system (localStorage)
- [ ] More accessories
- [ ] More personality states
- [ ] Achievements system
- [ ] Multiple blobs
- [ ] Mini-games
- [ ] Seasonal themes

## 🤝 Contributing

Feel free to fork and modify! This is a fun project meant for learning and experimentation.

## 📄 License

MIT License - Do whatever you want with it!

## 👤 Author

Created with ❤️ by @yksanjo

## 🙏 Acknowledgments

Inspired by virtual pets like:
- Tamagotchi
- Neopets
- Pou
- Desktop companions

---

**Enjoy your cozy blob! 🥺💕**
