# Meeting Timer

A reusable meeting agenda timer with built-in notes. Designed with Square/Block's UX language.

**Live app:** https://shilpamohanty5.github.io/meeting-timer/

## Features

- **Configurable agenda** -- Set any meeting title, add/remove/reorder segments with topics, goals, and durations
- **Countdown timer** -- Large visual countdown for each segment with segment and overall meeting progress bars
- **Auto-advance with manual override** -- Timer moves to the next segment automatically, with Pause/Resume and Prev/Next buttons
- **Audio chimes** -- Browser-generated tones at each segment transition (no external files)
- **Overtime tracking** -- Timer turns red and counts up if a segment runs past its allocated time
- **Built-in meeting notes** -- Editable text area for each agenda item, right below the timer
- **Shareable links** -- Agenda is encoded in the URL hash so you can bookmark or share a pre-configured timer
- **Single HTML file** -- No dependencies, no build step, no server required

## Usage

### Quick start

1. Open the [live app](https://shilpamohanty5.github.io/meeting-timer/)
2. Enter your meeting title and agenda segments
3. Click **Load Timer**
4. Click **Start Meeting**

### Sharing a pre-configured timer

After clicking "Load Timer", the URL updates with your agenda encoded in the hash. Share that full URL with attendees and they'll see the same timer with your agenda pre-loaded.

### Running locally

Just open `index.html` in any browser. No server needed.

## Tech

Single self-contained HTML file with vanilla CSS and JavaScript. Audio via Web Audio API. No external dependencies.
