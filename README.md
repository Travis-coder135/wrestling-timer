# Wrestling Timer

A phone timer for running wrestling ironman rotations at practice.

- Each wrestler takes a turn as the ironman and faces everyone else in the group. With 4 wrestlers that's 12 bouts: 1v2, 1v3, 1v4, 2v3, 2v4, 2v1, 3v4, 3v1, 3v2, 4v1, 4v2, 4v3.
- Each ironman's 1st, 2nd and 3rd bout uses situation 1, 2 and 3. You type the situations once and the app remembers them.
- Tap **Start**. When the bout ends, the buzzer sounds and the app moves to the next matchup and waits for the next Start.
- Progress is saved on the phone. If the app closes or the phone locks, reopen it and it picks up where it left off.
- It keeps the screen awake while the timer screen is open.

It's a single `index.html` with no build step. It's hosted on GitHub Pages and can be added to the phone's home screen.
