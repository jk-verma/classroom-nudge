# 🔔 Classroom Nudge Console

A lightweight, browser-based tool that gives teachers quick audio and visual cues to manage classroom activities — no install required.

## Features

- **Attention** – Rising tone to grab the room's focus
- **Wrap Up** – Clap sound to signal time is almost up
- **Rotate Groups** – Bell chime prompting students to switch
- **Silence** – Shush sound to quiet the class
- **Bell** – Classic doorbell chime with adjustable duration
- **Applause** – Quick clap for positive reinforcement
- **Break / Resume** – Announce breaks and bring the class back
- **Quick Poll** – Flash a YES / NO prompt on screen
- **Custom Timer** – Countdown with an on-screen overlay and end-of-time bell
- **Screen Flash** – Brief visual flash for a silent nudge
- **Fullscreen Mode** – Distraction-free display for projectors

### Controls

| Control | Description |
|---------|-------------|
| **Volume** slider | Adjusts master volume for all sounds |
| **Bell** slider | Sets the doorbell chime duration (0.3 s – 3.0 s) |

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `1` | Attention |
| `2` | Wrap up |
| `3` | Rotate groups |
| `4` | Silence |
| `5` / `Space` | Bell |
| `T` | Start custom timer |
| `P` | Pause / Resume timer |
| `R` | Reset timer |
| `F` | Toggle fullscreen |
| `Esc` | Close overlay / exit fullscreen |

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/jk-verma/classroom-nudge.git
   ```
2. Open `index.html` in any modern browser — that's it!

> **Tip:** Most browsers require a user click before playing audio. Make sure your system volume is turned up for the best experience.

## Tech Stack

- **HTML / CSS / JavaScript** — zero dependencies
- **Web Audio API** — synthesized sounds generated in real time (no audio files needed)

## License

This project is open source.
