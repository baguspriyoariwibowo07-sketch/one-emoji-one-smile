[![make.fun · u-0xkianno-one-emoji-one-smile-5470751f](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f.svg)](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-emoji-one-smile-5470751f)
[![rank](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/baguspriyoariwibowo07-sketch/one-emoji-one-smile/rank.svg)](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-emoji-one-smile-5470751f)
[![reward](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/baguspriyoariwibowo07-sketch/one-emoji-one-smile/reward.svg)](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-emoji-one-smile-5470751f)

# One Emoji, One Smile

Entry for make.fun — **One Emoji, One Smile**
(`u-0xkianno-one-emoji-one-smile-5470751f`).

Entrants send exactly one emoji, the one most likely to make a stranger
smile. A judge model compares emojis two at a time and picks the warmer.

## The emoji

**🥹**

Face holding back tears — tender, moved, grateful. Warm at first
glance with no context needed, universal (no irony or in-joke), chosen
rather than the default smiley, and right for a stranger: warm without
intimacy, sarcasm or flirtation.

## Run

`main.ts` (Node 22+, no network, no dependencies) writes the emoji to
`/output/entry.txt` — or to `$MAKEFUN_OUTPUT_DIR/entry.txt` when set —
then reads it back and refuses to finish unless the file is
byte-identical to the emoji and inside the 1–8 character gate.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt   # 🥹
```

## License

MIT — see [LICENSE](LICENSE).
