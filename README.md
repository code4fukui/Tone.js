# Tone.js

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

Tone.js is a Web Audio framework for creating interactive music in the browser.

## Features

- Common DAW (digital audio workstation) features like a global transport for synchronizing and scheduling events
- Prebuilt synths and effects
- High-performance building blocks to create your own synthesizers, effects, and complex control signals

## Installation

Tone.js can be installed locally into a project using `npm`:

```bash
npm install tone      # Install the latest stable version
npm install tone@next # Or, alternatively, use the 'next' version
```

It can also be added directly within an HTML document:

```html
<script src="http://unpkg.com/tone"></script>
<script src="myScript.js"></script>
```

## Hello Tone

```javascript
// create a synth and connect it to the main output
const synth = new Tone.Synth().toDestination();

// play a middle 'C' for the duration of an 8th note
synth.triggerAttackRelease("C4", "8n");
```

## Documentation

- [API](https://tonejs.github.io/docs/)
- [Examples](https://tonejs.github.io/examples/)
- [Demos](https://tonejs.github.io/demos)

## License

Tone.js is released under the [MIT License](https://github.com/Tonejs/Tone.js/blob/dev/LICENSE.md).