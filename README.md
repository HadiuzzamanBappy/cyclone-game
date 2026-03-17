# Cyclone Game - Scene Generation UI

This repository contains the guidelines, character designs, environmental conditions, and art style configurations for generating illustrations for the **Cyclone Game**, a decision-based storybook kids game set in coastal Bangladesh.

## Project Structure

- `00_References/`: Reference images, inspiration, and mood boards.
- `01_Panels/`: Work-in-progress and raw generated panels.
- `02_Final Delivery/`: Final, curated, and post-processed illustrations ready for the game.
- `MASTER_NOTES.txt`: The master reference file containing all AI generation parameters.

## Scene Generation Prompting Guide

To ensure a consistent visual language across the entire storybook, all AI-generated scenes must adhere to the parameters below.

### 1. Base Art Style

**IMPORTANT:** The following style block MUST be appended to the end of *every* single generation prompt:

> 2D comic book illustration style, bold black outlines, warm muted color palette, South Asian rural Bangladesh setting, no text, no UI, no watermark, 16:9 wide shot.

### 2. Character Descriptions

- **Male Character:** Age 10, short black hair, light brown skin, blue half-sleeve shirt, dark grey shorts, barefoot.
- **Female Character:** Age 10, black hair in two braids, light brown skin, green and yellow frock, barefoot.

### 3. Available Expressions

When describing the characters' faces, use one of the following consistent expressions:
- Neutral
- Worried
- Thinking (with hand on chin)
- Happy / Smiling
- Scared (wide eyes)
- Determined / Serious

### 4. Environments & Locations

- **Tea Stall:** Wooden benches, wooden counter with glass jars, old transistor radio, hanging bare bulb, mud walls.
- **Beach:** Rough ocean waves, fishing boats on shore, coconut trees bending in wind.
- **Village Road:** Dirt pathway, green fields both sides, coconut trees, small houses in distance.
- **Home Interior:** Bamboo walls, tin roof, simple wooden furniture, cot, clay pots, small window.
- **Cyclone Shelter:** Concrete elevated building, green surroundings.

### 5. Weather Conditions

- **Signal 3:** Dark grey overcast sky, moderate wind gently bending palm trees, distant rough sea, light rain starting.
- **Signal 4:** Heavy black storm clouds covering entire sky, strong winds bending trees hard, large waves forming, torrential rain, very dark dramatic atmosphere.
- **Signal 8-10:** Almost pitch black stormy sky, violent destructive winds, massive waves crashing, lightning flashes.

### 6. Lighting Configuration

#### Exterior Scenarios
- **Day (Normal):** Soft natural daylight, slight overcast diffused light, no harsh shadows.
- **Stormy Day:** Dark dramatic natural light, heavy shadow from storm clouds, grey-green tint in atmosphere, no direct sunlight.
- **Night Storm:** Near complete darkness, only lightning flashes as light source, deep blue-black shadows, occasional lightning rim lighting.

#### Interior Scenarios
- **Tea Stall / Home (Day):** Dim warm interior lighting from single hanging bare bulb, warm yellow-orange glow, dark corners, window light blocked by storm outside.
- **Tea Stall / Home (Tense / Dramatic):** Very dim warm tungsten light, heavy shadows on faces, high contrast between lit and dark areas, moody atmosphere.
- **Cyclone Shelter:** Harsh concrete ambient light outside, crowded warm dim interior lighting inside, emergency lantern glow if night scene.

#### Special Scenarios
- **Beach / Shoreline:** Flat grey stormy light, no shadows, white foam on waves catching only light source, dark brooding horizon.
- **Decision Point Scenes (Close-up on child thinking):** Soft dramatic side lighting on face, one side lit warm, other side in shadow, cinematic portrait lighting.

---

### Example Prompt Construction

To create a new scene, combine these modular elements:
`[Character + Expression] + [Location] + [Weather] + [Lighting] + [STYLE BLOCK]`

**Example:**
*Male character, age 10, short black hair, light brown skin, blue half-sleeve shirt, dark grey shorts, barefoot, scared wide eyes. Beach: rough ocean waves, fishing boats on shore, coconut trees bending in wind. Signal 8-10: almost pitch black stormy sky, violent destructive winds, massive waves crashing, lightning flashes. Flat grey stormy light, no shadows, white foam on waves catching only light source, dark brooding horizon. 2D comic book illustration style, bold black outlines, warm muted color palette, South Asian rural Bangladesh setting, no text, no UI, no watermark, 16:9 wide shot.*
