# Evidence-Based Estimating, Lite

A lightweight skill for building project estimates from relevant historical work. It separates observed evidence from judgment and makes the resulting effort ranges, assumptions, and uncertainty reviewable.

Read the companion article: [Teaching LLMs to Estimate Projects (Without Letting Them Guess)](https://jmbartelt.com/blog/evidence-based-estimating/).

## Install for Codex

Clone this repository into your Codex skills directory:

```sh
mkdir -p ~/.codex/skills
git clone https://github.com/JMBartelt/evidence-based-estimating-lite.git ~/.codex/skills/evidence-based-estimating-lite
```

Restart Codex to make the skill available. For another agent that supports `SKILL.md` skills, install this repository according to that agent's instructions.

## Use

Give your agent a proposed scope and access to relevant historical records, then ask it to estimate the work. For example:

> Use $evidence-based-estimating-lite to estimate this project. Compare the scope with our completed work and show the low, base, and high effort ranges, evidence, and assumptions.

The skill does not include historical data. If comparable evidence is limited or unavailable, it asks the agent to make that clear and label judgment-based estimates accordingly.
