# Martin

The front page of a generational AI system: one voice-first layer that sits on top of the machine, with everything the family and the corporation need behind it.

Full project context — the profile, the working agreement, and where Martin is going — lives in [`Greg705/Greg-Generational-AI/MARTIN_CONTEXT.md`](https://github.com/Greg705/Greg-Generational-AI/blob/main/MARTIN_CONTEXT.md).

## First principle

The security of the family — access, physical safety, and money — comes before any feature. Every decision in this repo answers to that first.

## Shape of the thing

- **Voice layer** — the default way in. Greeting on open, listening, spoken commands.
- **Corporation** — commissioning paperwork, books, money, legal, code.
- **Family** — doorbell timelapse, house twin, photos and family tree, socials, calendar.
- **The machine itself** — Mac and files, mail and drive, the vault.

## Where it stands — v0.2

`index.html` is the whole thing. Open it in a browser; nothing to install, nothing to run.

**Live:**

- **Listening.** The orb uses the browser's speech recognition — Chrome on the Mac does this properly. Where it isn't available, the page says so and the text bar does the same job.
- **Speaking.** Martin replies aloud when *Voice on* is switched on in the top rail, and always replies in text.
- **Commands.** Open any area by name, `what's next`, `build this next`, `lock down`, `dark mode`, `what time is it`, `help`, and `stop` to interrupt him mid-sentence.
- **Areas.** Every tile opens a panel explaining what that area is actually for, with a notes field that remembers what you write.
- **Asked for, not built yet.** Anything Martin can't do is written down in the words it was asked in, rather than quietly swallowed. A weak keyword match deliberately falls through to that list instead of guessing — better a logged "book me a flight" than an opened Books panel.
- **Keyboard.** `/` to type, space for the orb, Escape to back out.

Everything is kept in the browser, not on a server.

**Not live:** everything behind the tiles. They're the map, not the machine. The lock is a screen, not security — real locking arrives with the vault.

Built in short steps, one at a time, growing as the real work clarifies what's needed.
