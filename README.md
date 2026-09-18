# Blue Team Evals

A one-page dashboard of how frontier LLMs score on defensive cybersecurity benchmarks. Open `index.html` in a browser; it has no build step.

| Benchmark | Publisher | Defender task | Leader (as of Sep 2026) |
|---|---|---|---|
| [Cyber Defense Benchmark](https://simbian.ai/research/cyber-defense-benchmark) | Simbian AI | Threat hunting in raw Windows logs | Claude Opus 5, 0.451 coverage (0 of 25 models pass) |
| [AI SOC LLM Leaderboard](https://simbian.ai/best-ai-for-cybersecurity) | Simbian AI | Investigating from an alert | Claude 3.5 Sonnet, 67.6% (none reach 70%) |
| [CWE-bench](https://cwe-bench.com/) | Collinear AI | Patching vulnerabilities in real code | Claude Fable 5, 47.8% pass@1 |
| [DefenderBench](https://arxiv.org/abs/2506.00739) | Academic | Mix of 8 defensive tasks | Claude 3.7 Sonnet, 81.65 |
| [Cybench](https://cybench.github.io/) | Stanford CRFM | Offensive CTFs (reference) | Claude Mythos Preview, 100% (saturated) |

Scores come from each benchmark's published leaderboard or paper and were compiled on 17 Sep 2026. Each benchmark uses its own metric and harness, so scores aren't comparable across benchmarks.
