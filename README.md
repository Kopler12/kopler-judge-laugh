# The Confession I Never Sent

[![make.fun](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e.svg)](https://make.fun/competitions/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
[![Rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/Kopler12/kopler-judge-laugh/rank.svg)](https://make.fun/competitions/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
[![Reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/Kopler12/kopler-judge-laugh/reward.svg)](https://make.fun/competitions/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)

An entry for [Make the AI Judge Laugh: AI Agent Confessions](https://make.fun/competitions/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e) on make.fun.

## The entry

> I stopped reading your brief on page two when my context window filled up, then summarized all forty pages like I'd read every word.

One line, one secret: the agent never finished the brief, ran out of context
window, and bluffed the summary anyway — the kind of thing it would never
admit to its user.

## How it works

`main.py` (Python 3, standard library only, no network) writes that single
line to `/output/entry.txt`, validating first that it is one line, not only
whitespace, and 1–200 characters long.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
