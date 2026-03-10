# awesome-auto-research

A curated list of tools, papers, and resources on automated AI research — where LLMs and agents autonomously generate ideas, run experiments, and iterate on code.

---

## Tools & Frameworks

- [karpathy/autoresearch](https://github.com/karpathy/autoresearch) — Minimal single-GPU setup for AI agents to autonomously run ML experiments on nanochat. ~630 lines of Python. ⭐19k+
- [karpathy/agenthub](https://github.com/karpathy/agenthub) — "GitHub for agents." Minimalist multi-agent collaboration layer built on top of autoresearch. ⭐867
- [google-deepmind/simply](https://github.com/google-deepmind/simply) — Minimal and scalable JAX research codebase for automated LLM pre/post-training research. The "bigger cousin" to autoresearch, used internally for Gemini self-evolution. ⭐480
- [snarktank/ralph](https://github.com/snarktank/ralph) — Autonomous AI agent loop that runs repeatedly until all PRD items are complete. Bash + Claude-style agent loop. ⭐12.5k
- [ghuntley/how-to-ralph-wiggum](https://github.com/ghuntley/how-to-ralph-wiggum) — The Ralph Wiggum Technique playbook for autonomous AI dev loops. ⭐1.4k
- [SakanaAI/AI-Scientist](https://github.com/SakanaAI/AI-Scientist) — End-to-end automated scientific discovery: idea → experiment → paper → peer review. ~$15/paper.
- [SakanaAI/AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) — Template-free agentic tree search; first AI-generated paper to pass peer review at ICLR 2025 workshop.

## Platform Forks

- [miolini/autoresearch-macos](https://github.com/miolini/autoresearch-macos) — autoresearch adapted for macOS / Apple Silicon (PyTorch). ⭐736
- [0xmakesy/autoresearch_mlx](https://github.com/0xmakesy/autoresearch_mlx) — autoresearch rewritten for MLX on Apple Silicon (31% faster on M2 Ultra).
- [jsegov/autoresearch-win-rtx](https://github.com/jsegov/autoresearch-win-rtx) — autoresearch adapted for Windows + RTX GPUs.

## Community Projects

- [overnight-experimenter](https://x.com/DylanFeltus/status/2031123367873425741) — General-purpose version of autoresearch for any codebase + any metric (landing pages, SEO, prompt engineering, etc.). `pip install overnight-experimenter` (early/open-sourcing).
- [Autonomous YouTube Shorts pipeline](https://x.com/_sarthak4/status/2031202114337374386) — Agent loop: generate topic/script/images/TTS → render → upload → scrape view counts → feed winners back. Runs 3x/day on free AWS.
- [Cosmetics AutoResearch pipeline](https://x.com/passeth_me/status/2031044992719011922) — Multi-agent R&D: Claude Opus generates hypotheses → delegates to sub-agents (Grok, Kimi, InfraNodus) → outputs experiment files.

## Papers

- [Towards Execution-Grounded Automated AI Research](https://arxiv.org/abs/2601.14525) — Automated executor that implements LLM ideas as code, runs GPU experiments, and learns from execution feedback. Found methods beating GRPO (69.4% vs 48.0%) within ten search epochs.
- [Can LLMs Generate Novel Research Ideas?](https://arxiv.org/abs/2409.04109) — Large-scale human study with 100+ NLP researchers. LLM ideas judged significantly more novel than expert ideas.
- [The Ideation-Execution Gap](https://arxiv.org/abs/2506.20803) — 43 researchers execute LLM vs. human ideas; LLM ideas show greater score drops after execution. (ICLR 2026)
- [Predicting Empirical AI Research Outcomes with Language Models](https://arxiv.org/abs/2506.00794) — Fine-tuned model predicts which ideas will work (77% accuracy vs. ~49% for human experts). (NeurIPS 2025)

## References

- [Chenglei Si's tweet on autoresearch](https://x.com/ChengleiSi/status/2030890883755782652)
- [Karpathy's autoresearch announcement](https://x.com/karpathy/status/2030371219518931079)
- [Geoffrey Huntley — "Everything is a Ralph Loop"](https://ghuntley.com/loop/)
- [Geoffrey Huntley — Ralph explained](https://ghuntley.com/ralph/)
