# Running-Dashboard
Running Dashboard for support runner without coach

A personal dashboard to support a running program. Single HTML file, no build step.

## Features

- **Overview**: countdown to your next race, current training block, distance this week (logged vs. planned).
- **Profile & Zones**: personal details and heart rate zones 1-5 (Karvonen or percent of max HR).
- **Running Program**: editable weekly plan with target bpm per session and a volume scaler.
- **Training Block**: base, build, peak, and taper phases with a start date.
- **Race Calendar**: A/B/C priority, goal time, and countdown.
- **Strength Training**: editable sessions and exercises.
- **AI Coach**: log workouts and ask for feedback (only active inside Claude).
- **HR Zone Guide**: what each zone is for and what affects heart rate readings.

## Running it

Open `index.html` in a browser, or enable GitHub Pages for this repository.

Outside Claude, all data is stored in the browser's localStorage. The AI Coach tab can still log workouts, but coach feedback requires Claude. An AI coach outside Claude needs a backend that calls the API with an API key.

## Notes

Heart rate zones use an estimated max HR (208 - 0.7 x age) when no max HR is entered. Coach feedback is not medical advice.
