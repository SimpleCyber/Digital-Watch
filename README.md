# Digital Watch

## Summary
This project is a **digital watch** implemented in pure HTML, CSS, and JavaScript. It dynamically displays the current date, hours, minutes, and seconds, styled with a sleek and modern design. The watch updates in real-time, providing an elegant visual experience.

---

## Features
- Real-time **digital clock** showing:
  - Current hour, minute, and second.
  - Current date in `DD/MM/YYYY` format.
- Modern and minimal **UI design** with:
  - Dark theme.
  - A dash-bordered container.
  - Color-coded elements for clear distinction.
- Fully responsive layout using CSS Flexbox.

---

## Folder Structure
```
project-folder
├── index.html  # Main HTML file
└── styles.css  # Inline CSS for styling (integrated into the HTML)
```

---

## Setup and Usage
1. Download or clone the repository.
2. Open the `index.html` file in any modern web browser.
3. The digital watch will automatically display the current date and time.

---

## How It Works
1. **HTML Structure:**
   - A container (`.main`) holds the watch components.
   - Three boxes (`.box`) represent hours, minutes, and seconds.
   - A date element displays the current date.

2. **CSS Styling:**
   - Dark-themed design with accent colors like `tomato` for the date.
   - Flexbox used for layout alignment and spacing.
   - Fonts set to `cursive` for an aesthetic feel.

3. **JavaScript Logic:**
   - The `time()` function:
     - Fetches the current time and date using the `Date` object.
     - Dynamically updates the content of corresponding elements (`#hour`, `#minute`, `#second`, `#date`).
     - Recalls itself every 500ms for real-time updates.

---

## Future Enhancements
- Add options for changing themes (light/dark mode).
- Enable user-selected time formats (12-hour or 24-hour).
- Implement a stopwatch or countdown timer.


