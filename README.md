# Serum Wavetables Collection

A comprehensive collection of wavetables for Xfer Serum, organized for easy browsing and use.

## Download

1. Go to the [Releases](https://github.com/mattetti/SerumWavetables/releases) page
2. Select the desired release version
3. Click **Download Source** to download the wavetable collection

## Installation

1. Locate your Serum Tables folder:
   - Open Serum in your DAW
   - Click the menu icon in Serum's interface
   - Select "Show Serum Presets folder"
   - Navigate to the **Tables** subfolder within the Presets folder

2. Unpack the downloaded archive into the Tables folder

3. Click the wavetable oscillator menu and see the new wavetables

## Structure

This repository contains three main collections:

### Frames

Individual wavetable frames that can be used to create custom wavetables or used directly in Serum. These are single-cycle waveforms sampled from various synthesizers and sound sources.

### WaveTables By Instrument

Wavetables organized by instrument for easy browsing when looking for specific sounds based on known sources.

### WaveTables By Manufacturer Unified

Wavetables organized by manufacturer providing a unified wavetable per manufacturer.

### Meta Tables

Meta tables are special wavetables constructed from different individual frames, combining various timbres and textures into cohesive wavetable sequences. These provide smooth morphing between different sound sources.

## Wavetable Optimization

These wavetables are optimized for disk space efficiency:

- Wavetables contain fewer frames than typical because **Serum's interpolation** fills in the gaps
- This approach reduces disk usage while maintaining high sound quality through Serum's built-in interpolation engine

Frames are still duplicated across different wavetables for the user's convenience, allowing easy access to specific sounds without needing to reconstruct wavetables from individual frames.

## JSON Sidecar Files

Each wavetable may include a `.json` "sidecar file" with the same name as the `.wav` file. These files contain metadata about the wavetable:

- **Source information**: Original frame sources
- **Frame count**: Number of individual frames in the wavetable
- **Categories/Tags**: tags for categorization

The JSON files aren't used by Serum but provide useful context and could be used by wavetable management tools. They are human-readable and can be opened with any text editor so you can explore the details of each wavetable.

## Usage Tips

1. Use the **Frames** folder to build your own custom wavetables
5. Check the JSON files for additional information about each wavetable's origin and characteristics

