# MidJourney Parameters

Parameters are options added to a prompt that change how an image generates. They are always added to the end of a prompt. You can add multiple parameters to each prompt.

## Basic Parameters

- `--aspect` or `--ar` : Change the aspect ratio.
- `--chaos <0–100>` : Vary results, higher values produce unusual generations.
- `--iw <0–2>` : Image weight relative to text weight.
- `--no` : Negative prompting, e.g., `--no plants` removes plants.
- `--quality <.25, .5, or 1>` or `--q <.25, .5, or 1>` : Rendering quality.
- `--repeat <1–40>` or `--r <1–40>` : Create multiple jobs from a single prompt.
- `--seed <0–4294967295>` : Use a seed number for similar images.
- `--stop <10–100>` : Finish a job partway for less detailed results.
- `--style <raw>` : Switch between versions of the Midjourney model.
- `--stylize <number>` or `--s <number>` : Influence Midjourney's default aesthetic.
- `--tile` : Create seamless repeating patterns.
- `--video` : Save a progress video of the initial image grid.
- `--weird <0–3000>` or `--w <0–3000>` : Explore unusual aesthetics.

## Model Version Parameters

- `--niji <4, or 5>` : Focus on anime-style images.
- `--version <1, 2, 3, 4, 5.0, 5.1, 5.2, or 6>` or `--v <1, 2, 3, 4, 5.0, 5.1, 5.2, or 6>` : Use a different version of the Midjourney algorithm.

## Default Values

Model Version 5.2 and 6 share these default values:
- Aspect Ratio: 1:1
- Chaos: 0
- Quality: 1
- Seed: Random
- Stop: 100
- Stylize: 100

For more detailed information, visit the [MidJourney Parameter List](https://docs.midjourney.com/docs/parameter-list).
