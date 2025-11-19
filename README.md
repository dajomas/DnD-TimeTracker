# DISCLAIMER

This Readme file and the HTML file are fully created using [Perplexity.ai](https://perplexity.ai)

# D&D Time Tracker

A feature-rich, browser-based timer designed for tabletop RPGs (especially Dungeons & Dragons), with persistent storage, visually appealing time display, and advanced countdown tracking for spells and effects.

## Features

- **Fancy Main Time Display**  
  Shows total elapsed time as “X days HH:MM:SS” in a stylish clock format.

- **Session Time Controls:**  
  - Start, pause, resume, and reset total campaign/session time
  - Easily advance the clock by arbitrary “Combat Round”, “Short Rest”, or “Long Rest” increments—including custom durations

- **Fully Customizable Rests**  
  - Edit durations for rounds, short rests, and long rests  
  - Units clearly displayed after each input for clarity

- **Powerful Countdown Timers**  
  - Add any number of independent, customizable countdown timers for spells, effects, or DM tasks  
  - Specify duration in hours, minutes, and seconds

- **Per-Timer Color Picker**  
  - Assign a unique flashing color to each timer on expiration
  - Pick colors directly from a palette and see them update live

- **Iteration Counters**  
  - Each timer displays two counters:
    - **Session Counter:** increases when you “Restart”, resets to 1 if you “Reset”
    - **Total Counter:** always increases on “Restart,” never resets unless deleted or “Reset Total” is pressed

- **Advanced Timer Actions**
  - Pause/Resume individual timers
  - Remove, reset, or restart any timer
  - “Reset Total” button for each timer resets only the total counter
  - “Reset All Timers” resets all countdowns’ time, colors, and per-session iteration counters (but NOT the total counter)

- **Persistent Storage**  
  All configuration and state are saved in your browser using localStorage.  
  Closing or refreshing the page will NOT erase your session!

## Usage

1. **Open the App**  
   Download or copy the code from this repository and open the HTML file in your browser.

2. **Manage Time**
   - The top area shows elapsed campaign time in a bold, easy-to-read format.
   - Start/pause/resume/reset the session using the main buttons.
   - Manually add time for combat rounds or resting by clicking the provided “Add ...” buttons.

3. **Configure Durations**
   - Set your preferred durations for combat rounds, short rests, and long rests in the control grid.
   - Units are shown beside each field.
   - Click “Save Durations” to persist your choices.

4. **Countdown Timers**  
   - Specify H:M:S and click “Add Countdown.”  
   - Each timer can be paused/resumed/removed or restarted; pick a color for the flashing effect on zero.
   - The number in `[]` shows the per-session count; second number shows total restarts.

5. **Persistence**  
   - All settings, timers, and counters persist automatically across browser sessions.

## Tech Stack

- HTML5, CSS3, vanilla JavaScript—no dependencies!
- All logic/progress stored via browser’s `localStorage`

## Customization

- Tweak the CSS for different color schemes or clock layout.
- Modify the JavaScript for house-rule specific time increments or additional tracker features.
- Add new timer types or change the max limits as needed.

## License

This project is released under the MIT License.  
Feel free to reuse, adapt, or expand for your games and campaigns.

***

Happy DM’ing, and may you never lose track of your torch’s last flicker!
