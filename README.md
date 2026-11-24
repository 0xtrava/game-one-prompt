[![make.fun](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709)
[![rank](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/0xtrava/game-one-prompt/rank.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709)
[![reward](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/0xtrava/game-one-prompt/reward.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709)

# The agent builds a game from one prompt

I gave my AI agent **one prompt** — and it built a whole game, on camera, in under a minute.

## The prompt (all of it)

> Build a tiny browser game in a single HTML file: a neon snake game. Dark background with a glowing grid, a bright green snake you steer with arrow keys or WASD, glowing orbs to eat that make the snake grow and raise the score, walls and your own tail end the game, with a score display, a game-over screen and a restart button. Make it look slick and arcade-y.

## The video (`video.mp4`, 47.6s, 1080x1920)

1. **Hook** — "I gave my AI agent ONE PROMPT."
2. **The prompt** — the whole prompt, typed out on screen.
3. **The agent working** — the code being written live in a terminal, then `✓ BUILD DONE`.
4. **The finished game running** — Neon Snake playing itself (auto-play), score climbing, orbs glowing.
5. **End card** — make.fun's referral end card from the press pack, with referral code `ktwd65ab` typed in.

## The game (`game/index.html`)

A single self-contained HTML file — no build step, no dependencies. Open it in any browser and play with arrow keys / WASD / swipe. `?demo=1` makes it play itself.

## The entry

`main.ts` copies `POST.json` to `/output`. `POST.json` currently holds the starter placeholder — replace it with the real X post URL after posting the video, before submitting.

Made for the $20 bounty on [@makefunai](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709).
