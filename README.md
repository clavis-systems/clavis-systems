# Hi, I'm Emanuele

I'm an independent researcher in Italy. I work on one question: what can the software around an AI agent, the
host, know and do so that the model makes fewer avoidable mistakes?

## What I'm working on

- **Time outside the model.** Models often ignore the timestamps in their context. In
  [clock-outside-the-model](https://github.com/clavis-systems/clock-outside-the-model) I show that a simple rule in
  the host, "call the tool again when its last result is older than 30 minutes", reaches 96.3% on the TicToc test
  split. It is a benchmark-specific shortcut, not a general freshness policy, and I explain why. I also sketch
  freshness hints for tool results.
- **Wasted edits in coding agents.** I'm measuring, in public agent logs, how coding agents spend calls on edits
  that cannot work: text that is not in the file, edits that were already applied, returns to versions that already
  failed. I'm also testing whether short host notes help a small local model (Gemma) avoid these edits. The results
  are not public yet.
- **Careful comparisons.** [evalstats](https://github.com/clavis-systems/evalstats) compares evaluation results of
  language models with confidence intervals and paired tests.
- **AI for robotics.** I'm also interested in robotics combined with AI, starting from low-cost setups.

## How I work

I write down what I will measure before I look at the test data, and I publish the code and the exact commands.
I use AI assistants: Claude helps me write code and draft text, and Codex reviews the work and rechecks key
results. I make the decisions and I check the results.

To contact me, open an issue in one of my repositories.
