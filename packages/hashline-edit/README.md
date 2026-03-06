# pi-hashline-edit

A [Pi](https://www.npmjs.com/package/@mariozechner/pi-coding-agent) extension that uses a hashline-based file editing strategy to improve the accuracy and efficiency of agents' file-editing abilities, reducing the likelihood of failed edits that require extra turns by the agent.

This editing strategy has improved the edit success rate of Gemini models by 8%, Claude Sonnet 4.5 by 14.4%, etc. and reduced overall token usage, **without requiring any additional training to these models**.

Heavily inspired by/borrowed from Can Bölük's [oh-my-pi](https://github.com/can1357/oh-my-pi) fork of Pi. See their blog post, [I Improved 15 LLMs at Coding in One Afternoon. Only the Harness Changed](https://blog.can.ac/2026/02/12/the-harness-problem/) to understand.
