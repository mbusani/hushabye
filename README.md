# Hushabye

A calm bedtime and night-waking helper for a 16-month-old who finds it hard to settle and wakes often overnight. Built to be used one-handed, in a dark room, on a phone.

## Features

- **Night log** (Stage 2): one tap for "Woke up" and "Back asleep", with what helped (feed, cuddle, dummy and so on). Inside Claude, both parents share the same log live; elsewhere it's saved on that phone.
- **Settling coach**: when she wakes at night, step-by-step guidance that moves on the longer she's awake, with one-tap red light and sound.
- **Recommendations**: suggestions based on the last few nights in the log (feeds, late bedtimes, long wakings, late naps, early mornings), plus a sleep guide for 16 months.
- **Nap timer and bedtime window**: log naps and get a suggested bedtime based on how long she's been awake, plus a summary of last night.

- **Themes**: Sleepy Owl (aubergine and amber), Whale Song (sea blue and teal), Honey Bear (sage and honey) and Fairy Floss (dusky rose), each in light and dark. Choose Match phone, Light, Dark, or Bedtime (dark from 6 pm to 7 am).
- **Sleep sounds**: white, pink, brown noise and a slow "ocean" swell, generated on the phone (no downloads). Volume control and a fade-out timer (30 min, 1 hr, 2 hrs or all night). Keeps the screen awake while playing.
- **Night light**: a full-screen dim red glow for feeds and resettling, with a brightness slider. Double-tap to turn off.
- **Bedtime routine**: a checklist of the same steps every night (editable), with progress that resets each day. Inside Claude, steps and ticks are shared live between both parents.
- **Ask Claude**: describe what's happening and get short, gentle, practical ideas tailored to a 16-month-old, plus WA helplines (Ngala, healthdirect). Reads the log to spot patterns. Uses the viewer's own Claude account and only works when the app is opened inside Claude.

## How to use (for parents)

Tap **How to use** at the top of the app any time; it also opens the first time.

**Getting set up**
1. Open your Hushabye link in Claude and sign in (a free account is fine).
2. Add your baby's name on the **Ask** tab and tap Save.
3. When both parents are invited, you see the same log live.

**At bedtime**
1. Check the **bedtime window** on the **Log** tab.
2. Follow the steps on the **Routine** tab.
3. Start a sound on the **Sounds** tab: low volume, phone at least 2 metres from the cot.
4. When she's down, tap **Asleep for the night**.

**When she wakes in the night**
1. Tap **Woke up** and follow the settling coach. **Red light** gives a dim glow; double-tap to turn it off.
2. When she's back asleep, tick what helped and tap **Back asleep**.
3. In the morning, tap **Up for the day**.

**During the day**
- Tap **Nap started** and **Nap ended** for each nap; that powers the bedtime window.
- After two or three logged nights, the **Recommendations** card is based on her own pattern.
- Ask Claude questions on the **Ask** tab. It reads your log, and uses your own Claude account.

Logged something late? Tap its time to change it.

## Running it

It's a single file, `index.html`, with no build step.

- **Inside Claude** (recommended): open the published Hushabye artifact. Everything works, including Ask Claude.
- **Anywhere else**: open `index.html` in a browser or host it with GitHub Pages. Sounds, night light and routine work; Ask Claude is hidden.

Outside Claude, the log, settings and routine are saved in the browser on that phone only. The baby's name is never stored in this code.

## Roadmap

- **Stage 3: Patterns.** Weekly view of bedtime, wakings and naps, with a summary to show a child health nurse.

## Safety

Hushabye is a helper, not medical advice. Follow [Red Nose Australia](https://rednose.org.au) safe sleep guidance. For a toddler who seems unwell, call your GP or healthdirect (1800 022 222). In an emergency, call 000.
