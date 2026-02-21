# 🐴 Horse Breeder: A Genetics Game

A fun, educational browser-based game where you breed horses using real Mendelian genetics! Learn how coat color inheritance works while building your dream stable.

![Horse Breeding Game](https://img.shields.io/badge/Game-HTML5-orange) ![License](https://img.shields.io/badge/License-Free_to_Play-green)

## 🎮 How to Play

### Installation

1. **Download all files** from this repository:
   - `horse-breeding-game.html` (the main game file)
   - All `.png` image files (27 horse coat color images)

2. **Place all files in the same folder** on your computer. The game needs the images to be in the same directory as the HTML file.

3. **Open `horse-breeding-game.html`** in any modern web browser (Chrome, Firefox, Safari, Edge)

4. **Start playing!** No internet connection required after download (except for the optional AI helper feature).

### Quick Start Guide

1. **Choose your starter horse** - Pick from three randomly generated horses to begin your stable
2. **Name your horse** - Give your first horse a name
3. **Check your missions** - Look at the top of the screen for your current breeding goals
4. **Breed your first foal:**
   - Click your horse in "Your Stable" to select it
   - Choose a partner from "Available Horses" (opposite gender needed)
   - Click "Breed!" and name your new foal
5. **Advance time** - Click "Advance Year" to age your horses (foals need to be 3+ years old to breed)
6. **Complete missions** - Earn money by breeding horses with the target colors and traits

## 🧬 Game Features

### Genetics System
The game uses real equine color genetics with 6 genes:

| Gene | Effect |
|------|--------|
| **Extension (E)** | E_ = black pigment possible, ee = chestnut |
| **Agouti (A)** | A_ = bay pattern, aa = black |
| **Cream (Cr)** | Dilutes colors (buckskin, palomino, cremello) |
| **Gray (G)** | Progressive graying over time |
| **Roan (Rn)** | White hairs mixed throughout coat |
| **Tobiano (To)** | White spotting pattern |

### 38 Possible Coat Colors
From common colors like Bay, Black, and Chestnut to rare combinations like Cremello Roan Tobiano!

### Breeding & Care
- **Gender system** - Need one stallion (♂) and one mare (♀) to breed
- **Mare cooldown** - Mares can only breed once per year
- **Health system** - Feed ($10) and groom (free) to keep horses healthy
- **Age system** - Horses age each year, retire at 25

### Missions & Rewards
- **Color missions** - Breed specific coat colors for rewards
- **Conformation missions** - Breed horses with high conformation scores
- **Hint buttons** - Click "?" for genetics tips on how to complete each mission

### Competitions
- **Halter Shows** - Judged on conformation
- **Most Colorful** - Judged on coat color rarity
- **Win prizes** - 🥇 $200, 🥈 $100, 🥉 $50
- **Buy competitors** - Purchase horses you competed against

### Pedigree Tracking
- Homebred horses marked with ⭐
- View family trees up to 3 generations
- Track your breeding legacy

### Achievements (26 total!)
Unlock achievements for milestones like:
- Breeding your first foal
- Creating rare color combinations
- Winning competitions
- Reaching earnings goals

### AI Genetics Helper (Optional)
- Built-in chat assistant for genetics questions
- Requires an OpenAI API key
- Get personalized breeding advice based on your stable
- Ask questions like "How do I breed a palomino?"

## 📁 File Structure

```
horse-breeder-game/
├── README.md
├── horse-breeding-game.html
├── bay.png
├── black.png
├── chestnut.png
├── buckskin.png
├── palomino.png
├── smoky_black.png
├── cremello.png
├── perlino.png
├── smoky_cream.png
├── gray.png
├── bay_roan.png
├── blue_roan.png
├── red_roan.png
├── bay_tobiano.png
├── black_tobiano.png
├── chestnut_tobiano.png
├── gray_tobiano.png
├── buckskin_roan.png
├── palomino_roan.png
├── smoky_black_roan.png
├── buckskin_tobiano.png
├── palomino_tobiano.png
├── smoky_black_tobiano.png
├── bay_roan_tobiano.png
├── blue_roan_tobiano.png
├── red_roan_tobiano.png
└── cremello_tobiano.png
```

## 🎯 Tips for Success

1. **Check genotypes** - Hover over horses to see their genetic makeup
2. **Use the hints** - Click "?" buttons next to missions for breeding tips
3. **Plan ahead** - Some rare colors require multiple generations to achieve
4. **Keep diverse genetics** - Maintain horses with different gene combinations
5. **Feed regularly** - Healthy horses are needed to breed and advance time
6. **Enter competitions** - Good way to earn money and find new horses to buy

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No frameworks or build tools required
- **LocalStorage** - API key saved locally in your browser
- **Offline capable** - Works without internet (except AI chat feature)
- **Responsive design** - Works on desktop and tablet

## 📝 License

Free to play and modify for personal use.

## 🐎 Have Fun!

Happy breeding! Can you collect all 38 coat colors?
