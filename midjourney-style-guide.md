# Midjourney Stylize Parameter Guide

## Overview
The `--stylize` (or `--s`) parameter in Midjourney influences how artistically the bot interprets prompts. Lower values result in images closely matching the prompt, while higher values create more artistic but less prompt-accurate images.

## Stylize Values
- **Default**: `--stylize 100`
- **Range**: 0 to 1000
  - `--stylize 0`: Minimal artistic influence
  - `--stylize 50`: Low style
  - `--stylize 100`: Medium style (default)
  - `--stylize 250`: High style
  - `--stylize 500`: Very high style
  - `--stylize 750`: Extremely high style

## Examples
- **Prompt**: `/imagine prompt child's drawing of a cat --s 100`
  - **Stylize 0**: Literal interpretation
  - **Stylize 50**: Slight artistic touch
  - **Stylize 100**: Balanced artistic interpretation
  - **Stylize 250**: High artistic influence
  - **Stylize 500**: Strong artistic influence
  - **Stylize 750**: Very strong artistic influence

## How to Use
- Add `--stylize <value>` to your prompt.
- Alternatively, use the `/settings` command to select stylize values from a menu.

For more details, visit the [Midjourney Stylize Documentation](https://docs.midjourney.com/docs/stylize-1).

# Midjourney Style Parameter Guide

## Overview
The `--style` parameter in Midjourney modifies the default aesthetic of certain model versions, including V6, V5.2, V5.1, and Niji 6.

## Effects of `--style raw`
- **Model Version 6**:
  - **Standard**: More beautification.
  - **Raw**: Less automatic beautification, more accurate prompting.
- **Model Version 5.2**:
  - **Standard**: Enhanced aesthetic.
  - **Raw**: Greater control for experienced users.

## How to Use
- **Command**: Add `--style raw` to your prompt.
- **Settings**: Use `/settings` to apply `--style raw` to all prompts.

For detailed guidance, visit the [Midjourney Style Documentation](https://docs.midjourney.com/docs/style-1).

# Midjourney Style Tuner Guide

## Overview
The Style Tuner allows users to create and fine-tune custom styles, enhancing creativity and control over image generation.

## Key Features
- **Custom Styles**: Define unique artistic styles for prompts.
- **Fine-Tuning**: Adjust parameters to refine style application.
- **Consistency**: Maintain consistent aesthetic across multiple images.

## How to Use
1. **Create a Style**: Define parameters and save as a custom style.
2. **Apply a Style**: Use the custom style in prompts for consistent results.
3. **Adjust**: Fine-tune the style parameters as needed.

For more details, visit the [Midjourney Style Tuner Documentation](https://docs.midjourney.com/docs/style-tuner).

# Midjourney Chaos Parameter Guide

## Overview
The `--chaos` parameter influences the level of variation in image generation. Higher chaos values produce more diverse and unexpected results.

## Chaos Values
- **Default**: `--chaos 0`
- **Range**: 0 to 100
  - **Low Chaos**: Predictable and consistent images.
  - **High Chaos**: Greater diversity and creativity.

## Examples
- **Prompt**: `/imagine prompt fantasy landscape --chaos 50`
  - **Low Chaos**: Similar interpretations.
  - **High Chaos**: Varied and unique outputs.

## How to Use
- Add `--chaos <value>` to your prompt.

For detailed guidance, visit the [Midjourney Chaos Documentation](https://docs.midjourney.com/docs/chaos-1).

# Midjourney Weird Parameter Guide

## Overview
The `--weird` parameter in Midjourney adds unconventional and surreal elements to image generation. Higher values yield more bizarre and creative outputs.

## Weird Values
- **Default**: `--weird 0`
- **Range**: 0 to 3000
  - **Low Weird**: Subtle surrealism.
  - **High Weird**: Highly unconventional and strange.

## Examples
- **Prompt**: `/imagine prompt surreal cityscape --weird 1000`
  - **Low Weird**: Slightly unusual elements.
  - **High Weird**: Extremely bizarre and unique imagery.

## How to Use
- Add `--weird <value>` to your prompt.

For more details, visit the [Midjourney Weird Documentation](https://docs.midjourney.com/docs/weird-1).