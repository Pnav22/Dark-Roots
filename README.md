# Dark Roots - Tribal Horror Game

A browser-based survival horror game where you manage a tribe struggling to survive in a cursed forest that hungers for human souls.

## Game Overview

Dark Roots is an atmospheric horror survival game where you must keep your tribe alive while facing supernatural threats in a malevolent forest. The trees bleed, the shadows whisper, and something ancient stirs in the depths of the woods.

## Objective

Survive as long as possible while managing your tribe's resources, fear levels, and the ever-increasing danger of the cursed forest.

## How to Play

### Starting the Game
[Play Here](https://dark-roots.vercel.app/)

### Resources
- **Food**: Needed to feed your tribe each day
- **Wood**: Required for building shelters
- **Stone**: Required for building walls
- **Fear**: Accumulated terror that can drive tribe members insane

### Actions
- **Gather Food**: Collect sustenance from the forest (15s cooldown)
- **Chop Wood**: Harvest wood from bleeding trees (20s cooldown)
- **Mine Stone**: Extract stone from bone-filled earth (25s cooldown)
- **Build Shelter**: Construct protection (requires 10 wood, 30s cooldown)
- **Build Wall**: Create fortifications (requires 15 stone, 35s cooldown)
- **Send Scouts**: Explore the forest (40s cooldown, high risk)
- **Perform Ritual**: Attempt to appease forest spirits (requires 5 food, 45s cooldown)

### Tribe Members
Your tribe consists of 5 unique characters:
- **Kael** (Gatherer) - Cautious personality
- **Mira** (Hunter) - Brave personality
- **Thorne** (Builder) - Practical personality
- **Vera** (Scout) - Anxious personality
- **Orin** (Elder) - Wise personality

Each character has unique dialogue that changes based on their fear level and personality.

## Game Mechanics

### Day/Night Cycle
- Each day lasts 2 minutes
- At the end of each day, the tribe consumes food
- Danger and fear increase over time
- Random horror events occur

### Fear System
- Fear accumulates through horrific events
- High fear changes character dialogue
- Characters with over 50 fear may die from terror
- Fear over 100 = Game Over (madness)

### Danger Level
- Represented by a color-coded meter
- Increases through various events and actions
- Reduced by building defenses
- Danger over 100 = Game Over (consumed by forest)

### Survival Conditions
- Keep at least one tribe member alive
- Maintain fear below 100
- Keep danger below 100
- Manage food to prevent starvation

## Features

### Atmospheric Elements
- Dynamic horror events with randomized outcomes
- Character-specific dialogue system
- Atmospheric text that appears on screen
- Visual effects for sanity loss
- Immersive dark fantasy styling

### Horror Elements
- Bleeding trees and cursed forest
- Supernatural disappearances
- Psychological horror through dialogue
- Escalating tension and danger
- Multiple ways to fail

## Technical Details

### Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- No additional installations required

### File Structure
```
dark-roots/
├── index.html          # Complete game file
└── README.md          # This file
```

### Browser Storage
- Game state is stored in memory only
- No persistent save system
- Refresh page to restart

## Customization

### Adjusting Difficulty
You can modify these values in the JavaScript section:

- **Day Length**: Change `dayTimeRemaining: 120` (in seconds)
- **Quote Update Speed**: Modify the quote timer value
- **Resource Gathering**: Adjust random generation ranges
- **Event Frequency**: Change probability values for random events

### Adding Content
- **New Horror Events**: Add to the `horrorEvents` array
- **Character Quotes**: Expand the `characterQuotes` object
- **Scout Reports**: Add to the `scoutReports` array
- **Atmospheric Text**: Add to the `atmosphericTexts` array

## Game Over Conditions

1. **Extinction**: All tribe members die or disappear
2. **Consumed**: Danger level reaches 100%
3. **Madness**: Fear level reaches 100%

## 🎯 Strategy Tips

- Balance resource gathering with defense building
- Monitor fear levels of individual characters
- Use rituals carefully - they can backfire
- Scouting is risky but may provide valuable information
- Build shelters and walls to reduce danger
- Keep food reserves for emergencies

## 🎭 Atmosphere & Theme

Dark Roots draws inspiration from cosmic horror and folk horror traditions, creating an atmosphere of inevitable doom and ancient evil. The forest itself is a character - malevolent, hungry, and patient.

## 🎨 Credits

Created as a browser-based horror survival experience combining resource management with atmospheric storytelling.

## 🎪 Version History

- v1.0: Initial release with core survival mechanics
- v1.1: Added character dialogue system and atmospheric effects
- v1.2: Implemented quote timer system for improved readability

---

*"The forest remembers... and it hungers."*
