# AI Field Tests

Real-world, reproducible benchmarks comparing frontier and budget AI models (`Gemini 4`, `Claude 5.5`, `GPT-6.2`, `GLM 5.3`, `DeepSeek V4.1`, etc.) on practical everyday tasks.

**No hype. No sponsors. Same exact prompt, raw outputs, visual proof.**

## Published Tests

| # | Test | Models Tested | Quick Verdict | Folder |
| :--- | :--- | :--- | :--- | :--- |
| 01 | Interactive 3D Black Hole (Three.js) | Claude Haiku 5.5 (`x high`), Gemini 4 Hydrogen (`x high`) | Gemini wins realism (Kerr + presets, 4% 5h quota); Haiku wins efficiency (57 FPS, 2% 5h quota) | [2026-11-22-01-black-hole-threejs](tests/2026-11-22-01-black-hole-threejs/) |
| 02 | Interactive 3D Ocean & Island Weather (Three.js) | Gemini 4 Neon (`x high`) — Solo Showcase | 4,184-line showcase ("PHAROS"), 45–60 FPS, 3 autonomous visual QA passes (38 min, 22% 5h quota) | [2026-11-24-02-ocean-weather-threejs](tests/2026-11-24-02-ocean-weather-threejs/) |
| 03 | Fracturing Rock & Hidden Gemstone (Three.js) | GPT-6.2 Sol (`low`), Gemini 4 Neon (`low`) | GPT-6.2 Sol wins realism & detail (auto-play, 3% 5h quota); Neon packs more controls (5 gems, Slow-Mo, 2% 5h quota) | [2026-11-26-03-gem-shatter-threejs](tests/2026-11-26-03-gem-shatter-threejs/) |

## Methodology
See [METHOD.md](METHOD.md) for strict reproducibility rules and scoring criteria.
