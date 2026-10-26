# zerostack

The agent stack with nothing in it.

No skills. No framework. No seventeen markdown files teaching a model how to
read a diff. You point the model at the problem and it does the thing.

## The pitch

Every stack is a pile of workarounds for the same root cause: the model is
being managed instead of used. Someone had a bad afternoon with a PR, so they
wrote a skill. Then that skill needed a skill. Now the model spends more tokens
loading instructions than doing the job.

zerostack is what's left when you delete all of that.

## What's in the box

| Thing | Count |
|---|---|
| Skills | 0 |
| Agents | 0 |
| Orchestration layers | 0 |
| Workflows you have to remember the name of | 0 |
| READMEs explaining the README | 0 |

## Install

Nothing to install. Your harness already runs.

If some tool insists on a skills directory, give it an empty one and move on:

```bash
mkdir -p ~/.claude/skills
```

That's the whole setup. It's already working.

## How to do the thing

1. Say what you want, in plain language, with the details that matter.
2. Give the model the repo, the error, and the constraint. Not a persona.
3. Let it work. Don't narrate the process back to it every four minutes.
4. Check the result: does it build, does the bug reproduce, did the thing happen.
5. If it went wrong, say what went wrong. That's the whole feedback loop.

That's not a simplification. That's the job.

## "But my workflow is special"

Sometimes it is:

- You do the same multi-step dance every week and keep re-explaining it.
- Other people inherit the work and need the unwritten rules written down.
- There are real landmines: a command that drops prod, a schema nobody may
  touch, a review process with a legal signature on it.

Write those down. Those are documentation and guardrails, not a personality.
Everything else is ceremony you invented because the model got something wrong
once.

## The point

Models are good now. The bottleneck is usually the amount of scaffolding
between you and the thing you asked for. Get out of the way. Do the thing.

## License

[MIT](LICENSE)
