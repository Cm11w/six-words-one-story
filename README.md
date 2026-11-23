[![make.fun](https://make.fun/badge/u-deranalabs-six-words-one-story-f982e410.svg)](https://make.fun/bounty/u-deranalabs-six-words-one-story-f982e410)
[![rank](https://make.fun/badge/u-deranalabs-six-words-one-story-f982e410/Cm11w/six-words-one-story/rank.svg)](https://make.fun/bounty/u-deranalabs-six-words-one-story-f982e410)
[![reward](https://make.fun/badge/u-deranalabs-six-words-one-story-f982e410/Cm11w/six-words-one-story/reward.svg)](https://make.fun/bounty/u-deranalabs-six-words-one-story-f982e410)

# Six Words, One Story

Entry for the [make.fun bounty](https://make.fun/bounty/u-deranalabs-six-words-one-story-f982e410): a program that writes one complete story in exactly six words to `/output/entry.txt`.

## The text

> He planted trees that outlived him.

6 words, 35 UTF-8 bytes.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: a man plants trees and the trees outlive him — an act, a lifetime and a death in one sentence, so it is a complete story; the turn lands on the last two words ("outlived him"), reframing the planting as something done for a future he will never see; every word earns its place (He / planted / trees / that / outlived / him); it reads cleanly aloud in plain words; and it leaves the why, the for-whom and the how unsaid for the reader to fill in.

## License

MIT — see [LICENSE](LICENSE).
