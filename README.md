# AIBits Academy — Generative AI track: lab notebooks

The 42 hands-on labs for the three-course AIBits Academy track:

1. **Hands-On Deep Learning with Python** — 13 labs
2. **Generative AI and Large Language Models with Python: A Deep Dive** — 17 labs
3. **AI Agents and Agentic AI with Python** — 12 labs

Every notebook opens in Google Colab from the badge at the top of the file, or from the
**Open in Colab** button on its chapter page in the course.

## How the labs are built

- **Free tier only.** Colab's free runtime plus free hosted LLM API tiers. No paid service
  and no local model is ever required.
- **Real data.** Labs load real public datasets, not synthetic ones.
- **An offline fallback in every lab.** If a dataset URL is unreachable or you have no API
  key, each notebook falls back to a bundled or simulated path and still earns full marks.
  Nothing here fails because a third party is down.
- **Scaffolded, not solved.** The labs are structured with `TODO`s and `assert`s that prove
  the mechanism works once you fill them in. They are the exercise, not the answer key.
- **Bring your own key.** Where a hosted model is used, the notebook reads `LLM_API_KEY` /
  `LLM_BASE_URL` from Colab secrets or the environment. No key is distributed in this repo,
  and none is needed to complete a lab.

## The cast

The labs are set at **Beacon AI**, a fictional applied-AI company, and its six fictional
client organizations — Lumina Health, Kestrel Logistics, Meridian Bank, Orbit Retail,
Fernwood Media and Cobalt Manufacturing. Any resemblance to a real organization is
coincidental; no real company's data appears anywhere in this repository.

## Security labs

Course 2 Lab 13 and Course 3 Lab 9 are **defensive** security exercises. They attack a
self-contained toy application built inside the notebook, using well-documented public
techniques, in order to then defend it and measure the reduction. They contain no exploit
against any real system or service.

## Repository layout

```
course-1-deep-learning/   lab-00 … lab-11
course-2-generative-ai/   lab-00 … lab-16
course-3-ai-agents/       lab-00 … lab-11
ml/                       Machine Learning End To End: one notebook per lesson (see ml/README.md)
```

## Source and updates

This repository is **generated**. The notebooks are authored in a private course repository
and mirrored here; edits made directly to this repo will be overwritten. Please open an issue
rather than a pull request.

## License

[CC BY-NC-SA 4.0](LICENSE) — free to use, share and adapt for non-commercial purposes with
attribution, under the same license. The notebooks themselves are free to open and run.
