# Rhythm Master 3D

A browser-based 3D rhythm game built with Three.js and Tone.js, featuring dynamic music generation, special effects, and multiple difficulty levels.

## Features

### Gameplay
- 4-lane rhythm gameplay with keyboard controls (D, F, J, K)
- Three difficulty levels: Easy, Medium, and Hard
- Combo system with score multipliers
- Special mode activation with space bar
- Pause functionality (ESC key)
- Real-time hit feedback and particle effects
- Energy bar for special moves
- Progress tracking and end-game results

### Music System
- Three unique tracks:
  - Synthwave Nights
  - Electronic Pulse
  - Dubstep Dimension
- Dynamic music generation using Tone.js
- Adaptive BPM system
- Layered audio with:
  - Melodic patterns
  - Basslines
  - Drum patterns (kick, snare, hi-hat)
- Real-time audio effects (reverb, delay, compression)

### Visual Effects
- 3D graphics powered by Three.js
- Dynamic lighting and shadows
- Particle effects system
- Responsive lane indicators
- Custom skybox with star field
- Track-specific color schemes
- Animated notes with rotation and scaling effects
- Visual feedback for hits and combos

### UI Features
- Clean, modern interface
- Real-time score display
- Combo counter
- Multiplier indicator
- Energy bar
- Song information display
- Progress bar
- Pause menu
- Detailed results screen with rankings

## Technical Details

### Dependencies
- Three.js (3D graphics)
- Tone.js (Audio synthesis and sequencing)

### Performance
- Optimized particle system
- Efficient note management
- Adaptive rendering

### Responsive Design
- Adjusts to window size
- Mobile-friendly layout
- Consistent performance across devices

## Controls
- D, F, J, K: Hit notes in corresponding lanes
- SPACE: Activate special mode (when energy bar is full)
- ESC: Pause game

## Scoring System
- Perfect: 100 points
- Great: 75 points
- Good: 50 points
- Miss: 0 points
- Combo multiplier increases every 10 hits
- Special notes award double points

## Rankings
- S Rank: >95% accuracy
- A+ Rank: >90% accuracy
- A Rank: >80% accuracy
- B Rank: >70% accuracy
- C Rank: >60% accuracy
- D Rank: >50% accuracy
- F Rank: <50% accuracy

## Setup
1. Include Three.js and Tone.js libraries
2. Host on a web server
3. Open in a modern web browser
4. Select track and difficulty
5. Click "START GAME" to begin

## Browser Requirements
- Modern web browser with WebGL support
- JavaScript enabled
- Audio support

## Development
The game is built with vanilla JavaScript and uses modern web technologies. The code is structured with clear separation of concerns between game state, audio, graphics, and UI components.
