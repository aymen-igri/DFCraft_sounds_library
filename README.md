# DFCraft Sounds Library

Curated ambient sound library for the DFCraft project.

## About

This repository hosts ambient sounds for focus, relaxation, and meditation. All sounds are stored as MP3 files and accompanied by category images in JPG format. The library contains 37 sound tracks across 4 categories.

## Categories

- **Rain & Thunder** (10 sounds) - Soothing rain and storm sounds for deep focus
- **Nature & Forest** (10 sounds) - Outdoor ambiences and wildlife sounds
- **White Noise** (10 sounds) - Pure focus sounds and noise colors
- **Cafe & Indor** (7 sounds) - Cozy cafe and indoor ambient sounds

## Directory Structure

```
Sounds/              - MP3 audio files organized by category
  Rain/
  Nature & Forest/
  White noise/
  Café & Indor/

Images/              - JPG image files organized by category
  Rain/
  Nature & Forest/
  White noise/
  Café & Indor/

index.json           - Library index with metadata for all sounds and images
```

## Usage

The `index.json` file at the repository root contains all metadata. Each category element includes both its sounds and images:

```json
{
  "categories": [
    {
      "id": "rain",
      "name": "Rain & Thunder",
      "sounds": [ ... ],
      "images": [ ... ]
    }
  ]
}
```

All file paths are relative to the repository root. Use these paths to load assets locally.

## License

See the [LICENSE](LICENSE) file for details. Individual sound attributions are noted in [ATTRIBUTION.md](ATTRIBUTION.md).
