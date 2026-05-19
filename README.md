# Mood Companion 🌤️

A dead-simple desktop app to log how you're feeling. One tap and you're done.

No accounts, no cloud, no nonsense — just five buttons and a JSON file on your machine.

## Why?

Most mood-tracking apps ask too much. They want notes, tags, sleep data, dreams, and your firstborn child. By the time you've filled it all out, the feeling has passed.

This app asks one question: **how are you feeling right now?** You tap. It saves. You move on with your day.

## Features

- 🎯 **One tap to log** — five emoji buttons, that's the whole interface
- 💾 **Local storage** — all data stays on your computer in a JSON file
- 🪶 **Zero dependencies** — only Python's standard library, nothing to install
- 📊 **Daily counter** — quietly shows how many times you've logged today
- 🖥️ **Cross-platform** — works on Windows, macOS, and Linux

## Screenshot

> _Add a screenshot here once you've run it!_

## Requirements

- Python 3.8 or newer

That's it. Tkinter ships with Python, so there's nothing to `pip install`.

## Installation

```bash
git clone https://github.com/YOUR_USERNAME/mood-companion.git
cd mood-companion
```

## Usage

```bash
python mood_companion.py
```

On macOS or some Linux distros, you may need `python3`:

```bash
python3 mood_companion.py
```

Tap an emoji. You logged it. Close the window. Done.

## Where is my data?

All entries are saved to:

```
~/.mood_companion_data.json
```

It's a plain JSON file you can open, back up, or delete whenever you want. Each entry looks like:

```json
{
  "timestamp": "2026-05-19T15:42:08.123456",
  "mood": 4
}
```

Mood values: `1` = Very Sad, `2` = Sad, `3` = Neutral, `4` = Happy, `5` = Great.

## Roadmap

Ideas for if this grows beyond one-tap:

- [ ] Mood history view
- [ ] Weekly / monthly trend chart
- [ ] CSV export
- [ ] Optional daily reminder
- [ ] Dark mode
- [ ] Customizable mood scale

## Contributing

Pull requests welcome. Keep it simple — the whole point is that this app does one thing well.

## License

MIT — do whatever you want with it.
