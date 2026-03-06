A collection of extensions, skills, tools and experiments with the [Pi coding agent](https://www.npmjs.com/package/@mariozechner/pi-coding-agent).

## Current offerings

- [**pi-tokenshrink**](./packages/tokenshrink/): reduce a prompt's token count deterministically, without using inference
- [**pi-hashline-edit**](./packages/hashline-edit/): alternate to Pi's built in `edit` tool that improves the accuracy and efficiency of file edits, with high potential to reduce token usage

## Goals

### Local inference

**Privacy**, **self-sufficiency**, **ethics** and **energy conservation** are personal values of mine, so there will be an emphasis on local and low-energy inference sources (e.g. [vLLM](https://docs.vllm.ai/) using local GPUs or CPUs).

Local inference also enables experimentation with open models that have been trained on more carefully curated sets of data.

### Security

Tools and experiments will ideally build on the use of containers or other tools (e.g. [nono](https://nono.sh/)) that limit the blast radius of an agent. [pi-guardrails](https://www.npmjs.com/package/@aliou/pi-guardrails) is a great start, but there are many ways to work around it.

### Do less, better

Avoid maximalism and accelerationism vibes. All code output is authored by a human (me!) who is vouching for its efficacy and understands it before merging it. This is a tool to help developers rubber-duck, clear roadblocks and aid executive function deficiencies by facilitating a bias to action. This is not to enable [inactive gods](https://en.wikipedia.org/wiki/Deus_otiosus) wishing to set a course and walk away. Thus, the output will always be efficient, maintainable, simple code authored for and by humans. Prompting should be optimized for both token efficiency and concise, correct results without agents wasting turns doing the wrong thing.
