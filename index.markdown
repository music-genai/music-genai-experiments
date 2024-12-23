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
<div style="margin: 10px; border: 2px solid grey; border-radius: 15px;">
  <script src="https://cdn.jsdelivr.net/combine/npm/tone@14.7.58,npm/@magenta/music@1.23.1/es6/core.js,npm/focus-visible@5,npm/html-midi-player@1.5.0"></script>
  <midi-visualizer type="piano-roll" id="myVisualizer"></midi-visualizer>
  <midi-player
    src="{{ site.baseurl }}/midi/layla_non_commercial_sample.mid"
    sound-font visualizer="#myVisualizer">
  </midi-player>
</div>
- Acknowledgement: The tool for playing and displaying MIDI files is from [cifkao/html-midi-player](https://github.com/cifkao/html-midi-player){:target="_blank"}.