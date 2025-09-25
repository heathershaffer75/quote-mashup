# 🎭 Who Said It? — Setup → Punchline → Wisdom

A tiny, offline HTML game for large-group recovery sessions.

- Show a **Setup** line.
- Let a patient improvise their own completion.
- Click **Show Punchline** for the funny reveal.
- Click **Show Wisdom** for the evidence-based takeaway.
- Keyboard: **P** punchline • **W** wisdom • **N/→** next • **S** shuffle

## How to use on GitHub Pages
1. Create a repo (e.g., `who-said-it`).
2. Add this `index.html` to the root.
3. Enable **Pages** → **Deploy from branch** → root.
4. Open your site and present on the big TV.

## Customize the deck
Edit the `deck` array near the bottom of `index.html`:
```js
const deck = [
  {s:"Setup…", p:"Punchline…", w:"Wisdom…"},
  // add more!
];
```

Have fun & keep it kind — roast the **behaviors**, not the people. ✌️
