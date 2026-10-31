# Hushabye

A calm bedtime and night-waking helper for a 16-month-old who finds it hard to settle and wakes often overnight. Built to be used one-handed, in a dark room, on a phone.

## Features

- **Night log** (Stage 2): one tap for "Woke up" and "Back asleep", with what helped (feed, cuddle, dummy and so on). Inside Claude, both parents share the same log live; elsewhere it's saved on that phone.
- **Settling coach**: when she wakes at night, step-by-step guidance that moves on the longer she's awake, with one-tap red light and sound.
- **Recommendations**: suggestions based on the last few nights in the log (feeds, late bedtimes, long wakings, late naps, early mornings), plus a sleep guide for 16 months.
- **Nap timer and bedtime window**: log naps and get a suggested bedtime based on how long she's been awake, plus a summary of last night.

- **Sleep sounds**: white, pink, brown noise and a slow "ocean" swell, generated on the phone (no downloads). Volume control and a fade-out timer (30 min, 1 hr, 2 hrs or all night). Keeps the screen awake while playing.
- **Night light**: a full-screen dim red glow for feeds and resettling, with a brightness slider. Double-tap to turn off.
- **Bedtime routine**: a checklist of the same steps every night (editable), with progress that resets each day.
- **Ask Claude**: describe what's happening and get short, gentle, practical ideas tailored to a 16-month-old, plus WA helplines (Ngala, healthdirect). Reads the log to spot patterns. Uses the viewer's own Claude account and only works when the app is opened inside Claude.

## Running it

It's a single file, `index.html`, with no build step.

- **Inside Claude** (recommended): open the published Hushabye artifact. Everything works, including Ask Claude.
- **Anywhere else**: open `index.html` in a browser or host it with GitHub Pages. Sounds, night light and routine work; Ask Claude is hidden.

Outside Claude, the log, settings and routine are saved in the browser on that phone only. The baby's name is never stored in this code.

## Roadmap

- **Stage 3: Patterns.** Weekly view of bedtime, wakings and naps, with a summary to show a child health nurse.

## Safety

Hushabye is a helper, not medical advice. Follow [Red Nose Australia](https://rednose.org.au) safe sleep guidance. For a toddler who seems unwell, call your GP or healthdirect (1800 022 222). In an emergency, call 000.
