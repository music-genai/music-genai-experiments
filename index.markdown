---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# layout: home
---

# Music GenAI Experiment Results

## Factors
- Model Parameter Size
- Attention Mechanism Type

## MIDI File

<script src="https://cdn.jsdelivr.net/combine/npm/tone@14.7.58,npm/@magenta/music@1.23.1/es6/core.js,npm/focus-visible@5,npm/html-midi-player@1.5.0"></script>

<midi-player
  src="https://github.com/music-genai/music-genai-experiments/blob/main/_midi/layla_non_commercial_sample.mid"
  sound-font visualizer="#myVisualizer">
</midi-player>
<midi-visualizer type="piano-roll" id="myVisualizer"></midi-visualizer>