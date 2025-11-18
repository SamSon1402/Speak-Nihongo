# Speak Nihongo 🗣️

> A voice-first Japanese learning game where relationships matter.

<br>

```
Not your usual lingo app.
No textbooks. No flashcards.
Just natural conversations with AI characters who remember, react, and grow with you.
```

<br>

---

## The Concept

**What if learning Japanese felt like making friends in Tokyo?**

This is a language learning game where you don't just practice words — you build real relationships. Talk to AI characters. Get to know them. Watch them respond differently as your bond grows. Say the wrong thing? They might grow distant. Show genuine interest? They'll open up and share their world.

Each conversation affects your relationship. Each relationship unlocks new experiences.

<br>

---

## The Experience

### Meet Your Conversation Partners

**Yuki (ゆき) — The Tokyo Café Barista**  
Warm. Patient. Dreams of traveling the world.  
*Perfect for: Daily life conversations, coffee culture, Shibuya stories*

**Kenji (けんじ) — The Tech Salaryman**  
Direct. Practical. Slightly sarcastic but good-hearted.  
*Perfect for: Work culture, video games, weekend adventures*

**Hana (はな) — The Art Student**  
Poetic. Thoughtful. Opens up slowly.  
*Perfect for: Museums, anime, philosophical topics*

<br>

### How Relationships Work

```
Stranger (0-29%)     →  They're polite but guarded
Acquaintance (30-49%) →  Basic conversations flow
Friend (50-69%)      →  They share their number, suggest hangouts  
Close Friend (70-89%) →  Deep talks, vulnerable moments
Soulmate (90-100%)   →  They might confess their feelings...
```

Every interaction matters. Compliments strengthen bonds. Rushing things too fast? They'll pull away. Ignore them? The relationship deteriorates.

<br>

---

## Features

### 🎭 Living Characters
- **Dynamic expressions** that change with your relationship
- **Unique personalities** — each character responds differently to the same situation
- **Memory systems** — they remember what you've talked about

### 💬 Social Simulation
- **Relationship progression** from stranger to soulmate
- **Unlockable content** at different friendship levels
- **Consequences** for both good and bad interactions
- **Special events** when you reach relationship milestones

### 🎮 Voice-First Design
- Press-to-speak interface
- Japanese conversation practice from day one
- Natural scaffolding and repair strategies
- Real-time feedback on your relationship

### ✨ What You Can Unlock

| Friendship Level | Available Actions |
|-----------------|-------------------|
| Always | Give compliments |
| Friend (50%+) | Ask for phone number, suggest hangouts |
| Close Friend (65%+) | Give gifts, share deeper conversations |
| Soulmate (85%+) | Confess your feelings ❤️ |

<br>

---



<br>

---

## Quick Start

### For Developers

1. **Clone the repository**
```bash
git clone https://github.com/SamSon1402/speak-nihongo.git
cd speak-nihongo
```

2. **Open in browser**
```bash
# Just open the HTML file
open nihongo-voice-game.html
```

That's it. No build process. No dependencies.

<br>

### For Testing

Open browser console (F12) and try these commands:

```javascript
// Jump to Friend level
gameState.relationshipScore = 60
updateRelationship(0)

// Unlock all actions (Soulmate level)
gameState.relationshipScore = 90
updateRelationship(0)

// Trigger love confession
performAction('confess')

// See what happens when relationship is low
gameState.relationshipScore = 15
updateRelationship(0)
```

See `testing-cheatsheet.html` for full testing guide.

<br>

---

## The Tech

**Current State:** Prototype demonstrating core mechanics

```javascript
// Architecture highlights
{
  characters: "3 AI personalities with unique response patterns",
  stateManagement: "Event-driven relationship updates",
  socialSimulation: "Character memory + personality systems",
  voiceInterface: "Simulated (ready for Web Speech API)",
  aiResponses: "Pre-scripted (ready for Claude API)"
}
```

**Built with:**
- Pure HTML/CSS/JavaScript (no frameworks)
- Black & white watercolor aesthetic
- Modular character system
- Production-ready architecture

**Production path:**
- Integrate Web Speech API for real voice
- Connect Claude API for dynamic responses
- Add persistence layer for progress saving
- Deploy with authentication

<br>

---

## Design Philosophy

### Black & White, Like Ink on Paper

The visual design uses only black and white — no colors. This creates:
- Clean, focused experience
- Timeless aesthetic
- Emphasis on content over decoration
- Watercolor transparency effects for depth

Just like learning a language: simple elements, deep complexity.

<br>

---

## Why This Approach?

**Most language apps feel like school.**  
Duolingo gamifies exercises. Rosetta Stone teaches vocabulary. They work, but they feel like study.

**This feels like life.**  
You're not completing lessons. You're making friends. And when you care about someone, you naturally want to communicate better. That's the motivation that actually works.

The fastest way to speak Japanese confidently isn't to study harder.  
It's to speak it every day with people you care about.

<br>

---

## Project Structure

```
speak-nihongo/
│
├── nihongo-voice-game.html    # Main game (single file)
├── testing-cheatsheet.html    # Testing reference
├── FEATURES.md                # Technical documentation
├── DEMO-GUIDE.md              # How to demo the game
└── README.md                  # You are here
```

<br>

---

## Roadmap

### Current Features ✅
- 3 unique AI characters with personalities
- 5-tier relationship progression system
- 6 unlockable actions based on friendship
- Dynamic character expressions
- Special confession events
- Warning system for low relationships

### Coming Soon 🚧
- Real voice recognition (Web Speech API)
- AI-powered responses (Claude integration)
- Progress saving and user accounts
- Additional characters and storylines
- Mobile-optimized experience
- Conversation quality analytics

<br>

---

## Built By

**Sameer M**  
Computer Vision & ML Engineer

Built as a demonstration project for voice-first AI applications and social simulation systems in language learning.

*This project was created in 3 days to show what's possible when you combine conversational AI with emotional game design.*

<br>

---

## Credits

**Concept inspired by:**
- Gaijin Mode's vision for immersive language learning
- The understanding that language is fundamentally social
- Games like Persona and Fire Emblem that make relationships matter

**Design aesthetic:**
- Japanese ink wash painting (墨絵)
- Minimalist watercolor art
- The beauty of black and white

<br>

---

## License

MIT License — Feel free to learn from this, build upon it, or use it as inspiration.

<br>

---

<div align="center">

**Not your usual lingo app.**



<br>

*Speak from day one. Build real relationships. Learn naturally.*

</div>
