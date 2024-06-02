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

# Midjourney Photography Prompts Guide

## Overview
This guide provides over 20 Midjourney prompts for various photographic styles and techniques, incorporating Midjourney V6's improved prompt coherence and realism.

## Key Changes in Midjourney V6
- **Natural Language**: Prompts now use more natural language, avoiding filler words like “award-winning, photorealistic.”
- **Parameters**: 
  - `--style raw` for more literal results.
  - `--stylize` values (0-1000) to balance prompt understanding and aesthetics.

## Categories & Prompts

### Landscape Photography
- **HDR Coastal Landscape**: Vivid details in bright sky and shadowed cliffs.
- **Forest Macro Detail**: Intricate patterns of leaves and textures of tree bark.
- **Panoramic Mountain Range**: Grandiose view capturing the landscape's scale.
- **Long Exposure Starry Night**: Stars as light trails over rolling hills.

### Portrait Photography
- **Black and White Artistic Portrait**: Emphasizes contrasts and textures.
- **Classic Portrait with Natural Lighting**: Captures subtle expressions and skin details.
- **Candid Portrait with Bokeh Background**: Focuses on the subject with a soft background.
- **Dynamic Portrait**: Urban backdrop highlighting a modern look.

### Wildlife & Nature Photography
- **Aerial Photography of a Forest**: Bird's eye view of dense patterns and colors.
- **Selective Focus of Wildflowers**: Detailed close-ups with a blurred background.
- **Underwater Marine Life**: Colorful marine diversity in a coral reef.
- **Macro Butterfly**: Extreme close-up of a butterfly on a flower.

### Architectural Photography
- **35mm HDR Photography**: Details of historic buildings in urban settings.
- **Infrared Photography**: Surreal colors of modern architecture.
- **Black & White Street Photography**: Timeless charm of historical buildings.
- **Night Photography**: Iconic urban landmarks illuminated at night.

### Fashion & Editorial Photography
- **High Speed Photography**: Dynamic fashion moments with energy.
- **Vintage Color Palette**: Retro clothing styles and nostalgic colors.
- **Cinematic Fashion Photography**: Narrative scenes with dramatic lighting.
- **Soft Focus Photography**: Ethereal fashion editorials with delicate fabrics.

### Abstract & Artistic Photography
- **Abstract Selective Color**: Highlights specific elements in monochrome.
- **Time-Lapse Photography**: Abstract streams of color in city life.
- **Light Painting**: Artistic shapes and patterns with dynamic light trails.
- **Abstract Shadow Play**: Geometric patterns from shadows and light.

## Conclusion
These prompts help explore various photographic techniques and styles using Midjourney V6. For more details and examples, visit the [Midjourney Photography Prompts](https://www.mlq.ai/midjourney-photography-prompts/) guide.

# Midjourney Prompts Guide

## Basic Prompts
- **Definition**: Short text phrases or emojis.
- **Best Practices**: Keep prompts clear and concise for optimal results.

## Advanced Prompts
- **Image URLs**: Influence the style and content. Place at the beginning of the prompt.
- **Text Descriptions**: Combine with image URLs for more detailed prompts.
- **Parameters**: Control aspects like aspect ratio (`--ar`), model version (`--v`), and other settings to refine the image generation.

## Prompting Tips
- **Specificity**: Use specific words and numbers to yield better results.
- **Positive Descriptions**: Describe what you want, not what you don’t want.
- **Key Elements**: Include essential details such as:
  - **Subject**: What the main focus of the image should be.
  - **Medium**: The artistic medium, e.g., photo, painting, sketch.
  - **Environment**: The setting or background of the image.
  - **Lighting**: The light conditions, e.g., bright, dark, natural.
  - **Color**: The color palette or specific colors to be used.
  - **Mood**: The emotional tone or atmosphere of the image.
  - **Composition**: The arrangement of elements within the image.

## Examples
- **Basic Prompt**: "A sunset over the mountains."
- **Advanced Prompt**: "https://example.com/image.jpg A futuristic cityscape at night --ar 16:9 --v 5."

## Common Parameters
- **Aspect Ratio (`--ar`)**: Defines the width to height ratio. Example: `--ar 16:9` for a wide image.
- **Model Version (`--v`)**: Specifies the model version to use. Example: `--v 5` for version 5.

For more detailed guidance, visit the [Midjourney Prompts Documentation](https://docs.midjourney.com/docs/prompts-2).

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

# Midjourney V6 Prompt Examples

## In-Image Text Prompts
1. **MLQ High Tech**
   - Ad for a new tech gadget, with the product name "MLQ" in bold, sleek letters next to an image of the high-tech device in action --ar 16:9 --v 6.0
2. **Hidden Gems of Europe**
   - Travel guide book cover with the title in crisp text overlaid on images of quaint European streets and landmarks --style raw --ar 16:9 --v 6.0
3. **Explore the Alps**
   - Vintage travel poster with the phrase "Explore the Alps" in elegant script, showcasing a serene mountain landscape --ar 16:9 --v 6.0
4. **New Dawn Poster**
   - Sci-fi movie poster with the neon-lit words "NEW DAWN", depicting a futuristic cityscape under a starry sky --ar 16:9 --v 6.0

## Photography Prompts
1. **Urban Optical Reflection**
   - Photograph depicting the reflection of city lights on a rain-soaked street --ar 16:9 --style raw --v 6.0
2. **Macro Flower**
   - Close-up of a dew-kissed rose, details accentuated with a macro lens --ar 16:9 --style raw --v 6.0
3. **Disposable Camera at the Beach**
   - Beach scene with a disposable camera effect --ar 16:9 --style raw --v 6.0
4. **Wide-Angle Cityscape**
   - Wide-angle shot capturing a metropolitan skyline at dusk --ar 16:9 --style raw --v 6.0

## Fashion Prompts
1. **Avant-Garde**
   - Studio portrait capturing avant-garde fashion, bold monochrome palette --ar 16:9 --v 6.0
2. **Bohemian Rhapsody**
   - Outdoor shoot highlighting bohemian style in a wildflower field --ar 16:9 --v 6.0
3. **Urban Chic**
   - Street fashion photo with vibrant city murals as a backdrop --ar 16:9 --v 6.0
4. **Futuristic Fashion**
   - Metallic and holographic materials, model in a silver dress with soft diffused lighting --ar 16:9 --v 6.0

## Wallpaper Prompts
1. **3D Particle Explosion**
   - Vibrant explosion of 3D particles in shades of blue, yellow, and magenta --ar 16:9 --v 6.0
2. **Geometric Sunrise**
   - Abstract geometric forms capturing a sunrise --ar 16:9 --v 6.0
3. **Fluid Metallic**
   - High-definition wallpaper featuring fluid metallic shapes --ar 16:9 --v 6.0
4. **Ethereal Color Flow**
   - Ethereal flow of colors in a 3D animated splash --ar 16:9 --v 6.0

## Comic Book Prompts
1. **Mystery Detective**
   - Comic page with a detective examining clues, chasing a suspect, and unveiling the culprit --ar 16:9 --v 6.0
2. **Hero's Day**
   - Superhero battling a robot, saving a cat, and waving to fans --ar 16:9 --v 6.0
3. **Cyberpunk Chronicles**
   - Neon cityscape with a hacker and a chase on hoverbikes --ar 16:9 --v 6.0
4. **Stoic Knight**
   - Knight practicing, fighting, and returning with a dragon egg --ar 16:9 --v 6.0

## Logo Prompts
1. **Holographic Projection**
   - Sci-fi themed portrait with a holographic Microsoft logo --ar 16:9 --v 6.0
2. **High Tech Exhibit**
   - 3D hologram of the Google logo at a high-tech exhibit --ar 16:9 --v 6.0
3. **Sleek Cars**
   - Tesla logo with futuristic cars --ar 16:9 --v 6.0
4. **Flying Drones**
   - Amazon logo with drones in a neon-lit city --ar 16:9 --v 6.0

## Gaming Prompts
1. **Cyberpunk Character Concept**
   - Rogue hacker with neon-detailed cybernetic enhancements --ar 16:9 --v 6.0
2. **Post-Apocalyptic Scene**
   - Crumbling city with a lone survivor --ar 16:9 --v 6.0
3. **Retro Game**
   - 1980s platform game style --ar 16:9 --v 6.0
4. **Spacecraft Asset**
   - Sleek, futuristic spacecraft design --ar 16:9 --v 6.0

For more details and examples, visit the [Midjourney V6 Prompts Guide](https://www.mlq.ai/midjourney-v6-prompts/).

# Tips for Generative In-Image Text

## Overview
Generating in-image text with Midjourney V6 can yield more accurate and aesthetically pleasing results. Here are some tips to optimize this feature:

### Tips
1. **Use Quotation Marks**:
   - Enclose the text in "double quotes" for better results, as single quotes often do not work properly.

2. **Font Style**:
   - Add descriptive terms like 'calligraphic' to control the font style.

3. **Raw Parameter**:
   - Use `--style raw` to make the text more prominent, though it may reduce artistic elements.

4. **Stylize Values**:
   - Adjust `stylize` values for text size and style balance. Lower values result in bigger, more accurate text; higher values produce fancier, smaller text.

5. **Strong Variations**:
   - Use Strong Variations to refine text if the initial generation is not perfect but the composition is good.

6. **Upscaling**:
   - Use Subtle or Creative upscaling options to sharpen text for clarity.

7. **Image Prompts for Style Transfer**:
   - Transfer the style of one image to another using image prompts to also get the text right.

### Examples
1. **MLQ High Tech**:
   - Ad for a new tech gadget, with the product name "MLQ" in bold, sleek letters next to an image of the high-tech device in action --ar 16:9 --v 6.0

2. **Hidden Gems of Europe**:
   - Travel guide book cover with the title in crisp text overlaid on images of quaint European streets and landmarks --style raw --ar 16:9 --v 6.0

3. **Explore the Alps**:
   - Vintage travel poster with the phrase "Explore the Alps" in elegant script, showcasing a serene mountain landscape --ar 16:9 --v 6.0

4. **New Dawn Poster**:
   - Sci-fi movie poster with the neon-lit words "NEW DAWN", depicting a futuristic cityscape under a starry sky --ar 16:9 --v 6.0

For more detailed guidance, visit the [Midjourney V6 Prompts Guide](https://www.mlq.ai/midjourney-v6-prompts/).

