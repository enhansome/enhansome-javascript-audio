# Awesome JavaScript Audio with stars

JavaScript tools, libraries and components for creating/managing audio, sounds and music.

## Articles and videos

### Music theory

* [Let's learn about waveforms](https://pudding.cool/2018/02/waveforms/) - really nice interactives to teach waveforms by Pudding.cool [source code](https://github.com/joshwcomeau/waveforms) ⭐ 1,481 | 🐛 4 | 🌐 JavaScript | 📅 2018-02-21
* [The Physics of Music](https://pages.mtu.edu/~suits/Physicsofmusic.html) by Michigen Tech
* [JS Dynamic Audio Synth Tutorial](https://keithwhor.com/music/) - make a [synth piano keyboard](https://mrcoles.com/piano/) from scratch, covers lots of theory
* [Principles of Sound Synthesis](http://www.acoustics.salford.ac.uk/acoustics_info/sound_synthesis/) - or, why synths can't do guitars
* [Drum patterns and exercises](https://www.ethanhein.com/wp/my-nyu-masters-thesis/drum-patterns-and-exercises/) - master thesis by Ethan Hein, with nice circle system
  * [Video: Play With Your Rhythm - Drum Patterns](https://www.youtube.com/watch?v=tm2BgO1VaRY) - nice explanation of various drums patterns
  * [Video: Play With Your Rhythm - Build a beat](https://www.youtube.com/watch?v=kpSudIoepgY) - follow up to the above video
  * [Doc: Play With Your Rhythm](https://docs.google.com/spreadsheets/d/19_3BxUMy3uy1Gb0V8Wc-TcG7q16Amfn6e8QVw4-HuD0/edit#gid=0) - spreadsheet showing notations for all patterns
* [solfej.io/chords](https://www.solfej.io/chords) - search any chord to hear it, and see how to play on various instruments
* [solfej.io/scales](https://www.solfej.io/chords) - search any scales to hear it, and see how to play, and which chords are in the scale

### Web Audio API

* [MSDN: Basic concepts behind Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Basic_concepts_behind_Web_Audio_API)
* [MSDN: Using the Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Using_Web_Audio_API)
* [MSDN: Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/)
* [MSDN: Web Audio, best practices](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Best_practices)
* [HTML5 Rocks: Scheduling Web Audio with Precision](https://www.html5rocks.com/en/tutorials/audio/scheduling/) (web audio performance)
* [HTML5 Rocks: Developing Game Audio with the Web Audio API](https://www.html5rocks.com/en/tutorials/webaudio/games/) - mixing, fixing clipping, 3d sound, ..
* [MSDN: AudioNode](https://developer.mozilla.org/en-US/docs/Web/API/AudioNode) - generic interface for representing audio (an audio source, filter, gain mixer, output, ...)
* [MSDN: AudioBuffer](https://developer.mozilla.org/en-US/docs/Web/API/AudioBuffer) - a short audio asset residing in memory, created from an audio file
* [MSDN: AudioBufferSourceNode](https://developer.mozilla.org/en-US/docs/Web/API/AudioBufferSourceNode) - for audio with stringent timing/accuracy requirements
* [MSDN: OfflineAudioContext](https://developer.mozilla.org/en-US/docs/Web/API/OfflineAudioContext) - for generating sounds to buffer, fast as possible, no need to playback
* [MSDN: Controlling multiple parameters with constantSourceNode](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Controlling_multiple_parameters_with_ConstantSourceNode)
* [MSDN: Creating a simple synth](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Simple_synth)
* [Drum Sounds in Web Audio](https://dev.opera.com/articles/drum-sounds-webaudio/) - creating drums sounds using the Web Audio API
* [MSDN: Visualizations with Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Visualizations_with_Web_Audio_API)
* [Visualizations with Audio API and D3](https://blog.scottlogic.com/2016/01/06/audio-api-with-d3.html) - tutorial on music visualisation with D3, [demo](https://wpferg.uk/MusicVisualisation/)
* [Music frequency visualizer with D3](https://www.bignerdranch.com/blog/music-visualization-with-d3-js/) - nice short guide, with [repo](https://github.com/bignerdranch/music-frequency-d3) and [demo](https://bignerdranch.github.io/music-frequency-d3/)
* [Visualising Sound with D3](https://medium.com/better-programming/visualizing-sound-with-d3-and-web-audio-api-435ffea88f30) - covers and demos various different visualisations

### Web MIDI API

* [Playing MIDI in JavaScript](https://medium.com/swinginc/playing-with-midi-in-javascript-b6999f2913c3) - lots of good examples and code samples
* [Web MIDI Examples](https://webmidi-examples.glitch.me/) - nice, short example code snippets
* [CSS Tricks: Dip your toes into hardware with Web MIDI](https://css-tricks.com/dip-your-toes-into-hardware-with-webmidi/) - covers anatomy of a MIDI signal, MIDI notes
* [Keith McMillen: Making Music in the Browser with Web MIDI API](https://www.keithmcmillen.com/blog/making-music-in-the-browser-web-midi-api/)
* [Smashing Magazine: Web MIDI API](https://www.smashingmagazine.com/2018/03/web-midi-api/)

## Books

* [Web Audio API](https://webaudioapi.com/book/Web_Audio_API_Boris_Smus_html/toc.html) - for JS developers, game devs, etc. Written by Boris Smus.
* [Programming Electronic Music in Pure Data (PD)](http://www.pd-tutorial.com/english/index.html)

## Libraries: Web Audio API

* [howler.js](https://github.com/goldfire/howler.js) ⭐ 25,335 | 🐛 417 | 🌐 JavaScript | 📅 2025-11-23 - cross-browser audio library, 7kb, with multi-track, caching, falls back to HTML5 audio
* [kittykatattack/sound.js](https://github.com/kittykatattack/sound.js) ⭐ 318 | 🐛 17 | 🌐 JavaScript | 📅 2024-04-25 - micro library to load, generate and play sounds
* [webaudio-peaks](https://github.com/naomiaro/webaudio-peaks) ⭐ 58 | 🐛 5 | 🌐 JavaScript | 📅 2023-01-07 - small library to get peaks from audio
* [scriptify/sountility](https://github.com/scriptify/sountility) ⭐ 50 | 🐛 1 | 🌐 JavaScript | 📅 2026-05-03 - includes many small packages for adding, mixing, toggling effects on AudioNodes
* [notthetup/smoothfade](https://github.com/notthetup/smoothfade) ⭐ 39 | 🐛 0 | 🌐 JavaScript | 📅 2023-03-09 - smooth fade between AudioNodes

## Libraries: Web MIDI API

* [cwilso/WebMIDIAPIShim](https://github.com/cwilso/WebMIDIAPIShim) ⭐ 387 | 🐛 8 | 🌐 JavaScript | 📅 2018-11-28 - popular polyfill, used by Jazzsoft, among others. [Test it here](https://cwilso.github.io/WebMIDIAPIShim/)
* [jazz-soft/WebMIDIAPIShim](https://github.com/jazz-soft/WebMIDIAPIShim) ⚠️ Archived - MIDI polyfill for `navigator` in older browsers and Node

These can play MIDI files, and handle MIDI input/output messages from MIDI instruments, etc:

* [mudcube/MIDI.js](https://github.com/mudcube/MIDI.js) ⚠️ Archived - can play midi files using the given soundFonts
  * [midi-js-soundfonts](https://github.com/gleitz/midi-js-soundfonts) ⭐ 780 | 🐛 7 | 📅 2022-03-09 - pre-rendered, MIDI soundfonts for use with MIDI.js
* [grimmdude/MidiWriterJS](https://github.com/grimmdude/MidiWriterJS) ⭐ 604 | 🐛 9 | 🌐 JavaScript | 📅 2026-06-16 - an API for programmatically generating multi-track MIDI files and JSON objects
* [jazz-soft/JZZ](https://github.com/jazz-soft/JZZ) ⭐ 593 | 🐛 19 | 🌐 JavaScript | 📅 2026-02-01 - MIDI library for Node and Browsers
* [grimmdude/MidiPlayerJS](https://github.com/grimmdude/MidiPlayerJS) ⭐ 398 | 🐛 7 | 🌐 JavaScript | 📅 2026-06-22 - multi-track MIDI player/parser
* [colxi/MidiParser](https://github.com/colxi/midi-parser-js) ⭐ 244 | 🐛 13 | 🌐 JavaScript | 📅 2023-08-12 - a binary MIDI file reader for browser/Node, converts a MIDI binary file to a JSON object
* [dingram/jsmidgen](https://github.com/dingram/jsmidgen) ⭐ 237 | 🐛 22 | 🌐 JavaScript | 📅 2025-11-16 - generate MIDI files from javascript
* [node-easymidi](https://github.com/dinchak/node-easymidi) ⭐ 196 | 🐛 4 | 🌐 JavaScript | 📅 2026-03-05 - a wrapper around [node-midi](https://github.com/justinlatimer/node-midi) ⭐ 759 | 🐛 28 | 🌐 JavaScript | 📅 2022-12-12 to make things easier
* [jazz-soft/web-midi](https://github.com/jazz-soft/web-midi) ⭐ 35 | 🐛 3 | 🌐 JavaScript | 📅 2025-04-26 - WebMIDI API for browsers only
* [jazz-midi-electron](https://github.com/jazz-soft/jazz-midi-electron) ⭐ 29 | 🐛 0 | 🌐 JavaScript | 📅 2025-04-05 - WebMIDI API for Electron
* [igorski/zMIDI](https://github.com/igorski/zMIDI) ⭐ 19 | 🐛 2 | 🌐 JavaScript | 📅 2026-02-07 - small MIDI library, an easy interface to working with Web MIDI
* [hoch/spiral](https://github.com/hoch/spiral) ⭐ 9 | 🐛 3 | 🌐 JavaScript | 📅 2015-10-30 - lightweight WebAudio/WebMIDI library

These are tools for managing MIDI instruments (hardware instruments/devices):

* [webmidi](https://github.com/djipco/webmidi) ⭐ 1,710 | 🐛 7 | 🌐 JavaScript | 📅 2026-08-13 - control MIDI instruments/messages with ease
* [Midi-Connector](https://github.com/nuc/Midi-Connector) ⚠️ Archived - for connecting your MIDI device to `aconnect` (one of the ALSA tools)
* [jazz-soft/JZZ-midi-Gear](https://github.com/jazz-soft/JZZ-midi-Gear) ⭐ 21 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-23 - get info about your MIDI device
* [AndrejHronco/midi-ports](https://github.com/AndrejHronco/midi-ports) ⭐ 16 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-11 - small library to manage attached MIDI ports and devices
* [tween-midi-editor](https://github.com/tuomashatakka/tween-midi-editor) ⭐ 10 | 🐛 11 | 🌐 TypeScript | 📅 2026-07-27 - MIDI tween editor

## Developer tools

* [google/audion](https://github.com/google/audion) ⭐ 393 | 🐛 25 | 🌐 TypeScript | 📅 2026-06-24 - adds a new tab to Chrome DevTools with a node editor to view your AudioNodes
* [Pure Data](https://puredata.info/) - develop your own synths and patches

## Music theory

Tutorials and teachers:

* [scribbletune/johann](https://scribbletune.github.io/johann/) - Generate chord & scale charts to practice - for guitar, piano and PC keyboard ([repo](https://github.com/scribbletune/johann) ⭐ 60 | 🐛 30 | 🌐 TypeScript | 📅 2026-04-28)
* [play-along](https://github.com/bobbyrne01/play-along) ⭐ 21 | 🐛 7 | 🌐 JavaScript | 📅 2023-01-05 - learn the drums using a sequencer-like UI
* [Keystack](https://github.com/danielgamage/keystack) ⭐ 4 | 🐛 8 | 🌐 JavaScript | 📅 2023-04-18 - A web-based circular visualizer for keyboards (circle of fifths).
* [harmonizer](https://github.com/flosSoftware/harmonizer) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2019-09-02 - interactive piano that teaches harmony and rhythm theory
* [funklet](http://funklet.com/) - learn famous drum beats using an interactive sequencer

## Sound assets

Sounds that can be downloaded and used in your JS applications:

### SoundFonts

Instruments and sounds you can attach to MIDI notes (using the Web MIDI API):

* [surikov/webaudiofont](https://github.com/surikov/webaudiofont) ⭐ 985 | 🐛 3 | 🌐 HTML | 📅 2026-03-26 - use full GM set of musical instruments to play MIDI and single sounds or effects
* [midi-js-soundfonts](https://github.com/gleitz/midi-js-soundfonts) ⭐ 780 | 🐛 7 | 📅 2022-03-09 - pre-rendered, MIDI soundfonts for use with MIDI.js
* [soundfont-player](https://github.com/danigb/soundfont-player) ⚠️ Archived - nice little library for loading and playing sound fonts
* [colinbdclark/sf2-parser](https://github.com/colinbdclark/sf2-parser) ⭐ 58 | 🐛 0 | 🌐 JavaScript | 📅 2018-05-14 - a SoundFont 2 parser, extracted from [sf2synth.js](https://github.com/gree/sf2synth.js) ⭐ 54 | 🐛 5 | 🌐 JavaScript | 📅 2020-12-28
* [PatrickWolleb/SoundFontJS](https://github.com/PatrickWolleb/SoundFontJS) ⭐ 39 | 🐛 3 | 🌐 JavaScript | 📅 2025-08-13 - Node JS CLI for creating MIDI.JS ready sound fonts
* [skratchdot/soundfont2mp3](https://github.com/skratchdot/soundfont2mp3) ⭐ 14 | 🐛 2 | 🌐 JavaScript | 📅 2018-12-05 - a command line tool for extracting single note mp3s from soundfont files
* [midijssf-from-sf2-pmb](https://github.com/mk-pmb/midijssf-from-sf2-pmb) ⭐ 6 | 🐛 2 | 🌐 JavaScript | 📅 2017-09-25 - utilities for converting soundfonts to MIDI.js format
* [letoribo/percussion-soundfonts](https://github.com/letoribo/percussion-soundfonts) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2015-11-18 - soundfonts for JZZ.synth.MIDI.js
* [timbre\_soundfonts.js](https://github.com/skratchdot/timbre.soundfont.js) ⭐ 4 | 🐛 4 | 🌐 JavaScript | 📅 2014-04-25 - soundfonts for [timbre.js](https://github.com/mohayonao/timbre.js/) ⚠️ Archived
* [ryanwhite04/soundfonts](https://github.com/ryanwhite04/soundfonts) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2018-08-26 - includes [lots of instruments](https://ryanwhite04.github.io/soundfonts/), in mp3 and ogg
* [montyanderson/soundfont-parser](https://github.com/montyanderson/soundfont-parser) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2017-09-06 - soundfont parser that gets the detais/contents of .sfz files
* [danigb/sampler.js](https://github.com/danigb/sampler.js) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2015-12-06 - simple sampler, defines instruments as JSON, with base64 mp3s in them
* [sccherry/soundfont](https://github.com/sccherry/soundfont) ⚠️ Archived - soundfont piano player, uses 'FluidR3\_GM', 'MusyngKite', 'FatBoy' ([demo](https://stevecherry.net/soundfont/#index))

### Instrument recordings

High quality recordings of instruments, nicely organised into separate files, in MP3, WAV or similar format.

* ?

## Sound creation

Programmatically create notes, chords, intervals, effects, etc:

* [Tone.js](https://github.com/Tonejs/Tone.js) ⭐ 14,707 | 🐛 59 | 🌐 TypeScript | 📅 2026-08-21 - A Web Audio framework for making interactive music in the browser
* [teoria](https://github.com/saebekassebil/teoria) ⭐ 1,375 | 🐛 25 | 🌐 JavaScript | 📅 2019-12-01 - create notes, chords, scales, intervals.. get notes form intervals, and more..
* [beep.js](https://github.com/stewdio/beep.js) ⭐ 1,369 | 🐛 3 | 🌐 JavaScript | 📅 2015-05-10 - a JavaScript toolkit for building browser-based synthesizers
* [timbre.js](https://github.com/mohayonao/timbre.js/) ⚠️ Archived - JavaScript library for objective sound programming (archived)
* [tonejs-instruments](https://github.com/nbrosowsky/tonejs-instruments) ⭐ 541 | 🐛 5 | 🌐 JavaScript | 📅 2023-06-01 - instrument presets for Tone.js
* [octavian](https://github.com/stevekinney/octavian) ⭐ 181 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-10 - utilities for reasoning about musical notes, frequencies, and intervals
* [simpleTones](https://github.com/escottalexander/simpleTones.js) ⭐ 89 | 🐛 4 | 🌐 JavaScript | 📅 2022-12-07 - create tones of a specfic note - add sawtooth, sine, triangle, etc, to modify
* [scribbletune](https://scribbletune.com/) - generate chord progressions, scales, beats, save as MIDI clips, with [a teacher app](https://github.com/scribbletune/johann) ⭐ 60 | 🐛 30 | 🌐 TypeScript | 📅 2026-04-28 and [sampler](https://github.com/scribbletune/sampler) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2019-12-08
* [note-parser](https://github.com/danigb/note-parser) ⭐ 55 | 🐛 1 | 🌐 JavaScript | 📅 2017-04-04 - Given a string, obtain a hash with note properties (including midi number and frequency)
* [btwael/zazate.js](https://github.com/btwael/zazate.js) ⭐ 48 | 🐛 1 | 🌐 JavaScript | 📅 2019-05-07 - make notes, tones, scales, chords, harmonies.. loads of functions
* [midiflip](https://github.com/1j01/midiflip) ⭐ 43 | 🐛 0 | 🌐 JavaScript | 📅 2022-07-26 - transpose, flip, reverse notes, etc
* [Flocking](https://github.com/colinbdclark/Flocking) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2024-07-10 - declaratively create sounds, synths, effects, etc, as JSON objects, supports mouse/trackpad
* Also see [LFOs](#LFOs) and [Synths](#Synths) sections.

### Low frequency oscillators ("LFOs"):

These produce sounds which oscillate between two values on a low frequency, following a given waveform. LFOs are usually used to create effects like pitch wobble, tremelo, and wah-wah-wah stuff. These effect are then applied to notes, synths or instruments.

* [scijs/periodic-function](https://github.com/scijs/periodic-function) ⭐ 57 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-11 - oscillator modifiers (sawtooth, square, sine, pulse, step, interpolate, etc) as JS functions, normalized 0..1
* [mohayonao/wave-tables](https://github.com/mohayonao/wave-tables) ⚠️ Archived - JSON files defining various sounds/instruments as wave tables
* [audiojs/audio-oscillator](https://github.com/audiojs/audio-oscillator) ⚠️ Archived - Generate periodic oscillation into an array/audiobuffer using a simple API
* [TheTeapot418/LFO.js](https://github.com/TheTeapot418/LFO.js) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2017-08-05 - a simple LFO in JavaScript, includes presets: sine, triangle, square, sawtooth, noise
* [diversen/wave-table-oscillators](https://github.com/diversen/wave-table-oscillators) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2018-08-02 - wrappers around the wave tables above (allows you to use them)
* [2xAA/LFO.js](https://github.com/2xAA/LFO.js) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2017-07-18 - a fork of the above

### Pure Data (PD) patches

* [sebpiq/WebPd](https://github.com/sebpiq/WebPd) ⭐ 999 | 🐛 9 | 🌐 TypeScript | 📅 2026-07-02 - use your [Pure Data](https://puredata.info/) [patches](https://puredata.info/community/member-downloads/patches) in Javascript

## Sound editing

### Sound effects/processing

* [wad](https://github.com/rserota/wad) ⭐ 1,981 | 🐛 3 | 🌐 JavaScript | 📅 2025-11-06 - advanced processing/manipulating of sound files
* [tuna](https://github.com/Theodeus/tuna) ⭐ 1,827 | 🐛 4 | 🌐 JavaScript | 📅 2026-04-06 - an audio effects library for the Web Audio API
* [alemangui/pizzicato](https://github.com/alemangui/pizzicato) ⭐ 1,712 | 🐛 78 | 🌐 JavaScript | 📅 2025-07-09 - excellent sound shaping effects, [nice demos](https://alemangui.github.io/pizzicato/) showing guitar sounds
* [scriptify/Chnl](https://github.com/scriptify/Chnl) ⭐ 41 | 🐛 0 | 🌐 JavaScript | 📅 2017-03-26 - makes it easy to attach lots of effects to a single AudioNode of any kind

### Sound samplers:

Samplers make it easy to import, chop up, and extract parts of an audio file (usually WAV or MP3).

* [waveform-playlist](https://github.com/naomiaro/waveform-playlist) ⭐ 1,670 | 🐛 58 | 🌐 TypeScript | 📅 2026-08-17 - very nice multi-track WAV editor, similar to Audacity :)
* [hya-wave](https://wav.hya.io/#/fx) - nice online WAV editor

### ADSR envelopes

Modify a sound with more/less attack, delay, sustain, release, etc.

* [mohayonao/adsr-envelope](https://github.com/mohayonao/adsr-envelope) ⭐ 44 | 🐛 0 | 🌐 JavaScript | 📅 2015-11-06 - attack, delay, sustain, release and MORE, lots of options
* [itsjoesullivan/envelope-generator](https://github.com/itsjoesullivan/envelope-generator) ⭐ 34 | 🐛 3 | 🌐 JavaScript | 📅 2017-04-04 - nice and complete, lots of options
* [mmckegg/adsr](https://github.com/mmckegg/adsr) ⚠️ Archived - attack, delay, sustain, release envelopes
* [audio-contour](https://www.npmjs.com/package/audio-contour) - A 5 stage audio envelope generator.. nice UI to edit WAV forms

### Sound equalizers

* [GraphicalFilterEditor](https://github.com/carlosrafaelgn/GraphicalFilterEditor) ⭐ 50 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-28 - very powerful sound shaping :)
* [eAudio](https://github.com/DIDAVA/eAudio) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2020-04-27 - the "Extended HTML Audio Object" - adds an equalizier

### Vocoders

For Editing and adding effects to vocals.

* [cwilso/vocoder](https://github.com/cwilso/vocoder) ⭐ 364 | 🐛 15 | 🌐 JavaScript | 📅 2022-09-21 - a 28-band vocoder - a "robotic voice" processor

## MIDI instruments

Frontends and UIs to load & your play your sounds.

### Drum pads / MPC / MPD

* [cwilso/MIDIDrums](https://github.com/cwilso/MIDIDrums) ⭐ 357 | 🐛 7 | 🌐 JavaScript | 📅 2018-01-14 - MIDI version of Shiny Drum Machine
* [completejavascript/drum-machine](https://github.com/completejavascript/drum-machine) ⭐ 22 | 🐛 0 | 🌐 JavaScript | 📅 2022-04-07 - simple react based MPD
* [dburles/ssu16](https://github.com/dburles/ssu16) ⭐ 10 | 🐛 1 | 🌐 JavaScript | 📅 2019-06-22 - very slick Akai-like MPC, with step sequencing, sample import, much more
* [dusanpopov/Drum-machine](https://github.com/dusanpopov/Drum-machine) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2021-02-03 - an AKAI-like MPC
* [Introduction-to-Programming-Term-1-Project](https://github.com/wtznc/Introduction-to-Programming-Term-1-Project) ⚠️ Archived - USB MIDI drum pad and keyboard, uses `p5`, `ZMIDI`
* [webmaeistro/drum-machine](https://github.com/webmaeistro/drum-machine) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2019-11-19 - nice, simple one, no lag, works well
* [electric-drums-pwa](https://github.com/1XWebbyX1/electric-drums-pwa) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2019-01-24 - simple, buttons at bottom, good performance

### Guitar

* [vitaliy-bobrov/js-rocks](https://github.com/vitaliy-bobrov/js-rocks) ⭐ 190 | 🐛 30 | 🌐 TypeScript | 📅 2024-02-21 - lots of nice electric guitar effects, amps and cabinets
* [1j01/guitar](https://github.com/1j01/guitar) ⭐ 128 | 🐛 20 | 🌐 JavaScript | 📅 2026-04-21 - drag over the strings to play
* [ronkot/ks-guitar](https://github.com/ronkot/ks-guitar) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2018-04-11 - play chords with keyboard keys, and strum with up/down keys

### Piano

* [WarpPrism/AutoPiano](https://github.com/WarpPrism/AutoPiano) ⚠️ Archived - feature-packed, large piano
* [Wscats/piano](https://github.com/Wscats/piano) ⭐ 1,171 | 🐛 13 | 🌐 JavaScript | 📅 2026-03-31 - nice piano, decent sounds, can make it play for you
* [qwerty-hancock](https://github.com/stuartmemo/qwerty-hancock) ⭐ 275 | 🐛 7 | 🌐 TypeScript | 📅 2025-12-28 - simple JS piano component for larger projects, see [qwerty hancock](https://stuartmemo.com/qwerty-hancock/)
* [midi-with-node](https://github.com/Pomax/midi-with-node) ⭐ 31 | 🐛 0 | 🌐 JavaScript | 📅 2018-03-25 - a web based GUI & NodeJS backend that can register as a MIDI device in your DAW
* [iBundin/Open-Web-Piano](https://github.com/iBundin/Open-Web-Piano) ⭐ 31 | 🐛 0 | 🌐 JavaScript | 📅 2017-04-13 - nice piano, user-friendly: supports choosing a MIDI device on load
* [tri-chromatic-keyboard](https://github.com/1j01/tri-chromatic-keyboard) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2016-08-27 - nice, easy way to play piano for those who *can't* play piano (different key layout)
* [TomerAberbach/piano](https://github.com/TomerAberbach/piano) ⚠️ Archived - very nice sounding piano, simple UI
* [noodle-doodle](https://github.com/Pomax/noodle-doodle) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2019-12-24 - a nice piano roll, [demo here](https://pomax.github.io/noodle-doodle/)

### Sequencers & Trackers

Use (often) grid-based, stepped/looping sequencer UIs to generate beats, riffs, bass-lines, loops and so on.

* [SpessaSynth](https://github.com/spessasus/SpessaSynth) ⭐ 392 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-18 - MIDI player with tracker, loads of settings
* [efflux-tracker](https://github.com/igorski/efflux-tracker) ⭐ 260 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-22 - browser based music tracker ([here](https://www.igorski.nl/application/efflux/)) driving a modular synth environment with MIDI support
* [tinysynth](https://github.com/n1k0/tinysynth) ⚠️ Archived - a nice little sequencer, easy to use, nice UI, generate random tracks
* [hatsumatsu/108](https://github.com/hatsumatsu/108) ⭐ 213 | 🐛 2 | 🌐 JavaScript | 📅 2018-02-28 - a slick, minimalist circular beat sequencer
* [web-drum-sequencer](https://github.com/stufreen/web-drum-sequencer) ⭐ 174 | 🐛 27 | 🌐 JavaScript | 📅 2023-08-03 - A drum machine and sequencer built with the Web Audio API, React, and Redux
* [nicolas-van/sonant-x-live](https://github.com/nicolas-van/sonant-x-live) ⭐ 103 | 🐛 9 | 🌐 JavaScript | 📅 2024-10-08 - piano keyboard, filters, synth, sequencer, uses [sonant-x](https://github.com/nicolas-van/sonant-x) ⭐ 249 | 🐛 2 | 🌐 JavaScript | 📅 2025-06-18
* [da-beat-sequencer](https://github.com/juniorheptachords/da-beat-sequencer) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2017-04-05 - lightweight MIDI and audio sequencer
* [andrefcasimiro/midikrew](https://github.com/andrefcasimiro/midikrew) ⭐ 1 | 🐛 6 | 🌐 JavaScript | 📅 2024-11-19 - full fledged music sequencer, built with React
* [drum-sequencer](https://github.com/bweave/drum-sequencer) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2018-01-02 - lightweight sequencer, simple UI
* [drum-machine](https://github.com/GK-Hynes/drum-machine) ⚠️ Archived - simple sequencer, based on React

### Synths

Generate and edit your own sounds, voices and sound effects.

* [stevengoldberg/juno106](https://github.com/stevengoldberg/juno106) ⭐ 529 | 🐛 7 | 🌐 JavaScript | 📅 2015-08-19 - a Roland Juno 106 synth
* [hundredrabbits/Marabu](https://github.com/hundredrabbits/Marabu) ⭐ 489 | 🐛 6 | 🌐 JavaScript | 📅 2025-04-16 - powerful synth, with GUI
* [webaudio-tinysynth](https://github.com/g200kg/webaudio-tinysynth) ⭐ 272 | 🐛 5 | 🌐 JavaScript | 📅 2022-12-20 - webaudio-tinysynth is a small synthesizer written in JavaScript with GM like timbre map
* [nicolas-van/sonant-x](https://github.com/nicolas-van/sonant-x) ⭐ 249 | 🐛 2 | 🌐 JavaScript | 📅 2025-06-18 - lightweight synth library
* [errozero/poly-synth](https://github.com/errozero/poly-synth) ⭐ 54 | 🐛 0 | 🌐 JavaScript | 📅 2021-05-25 - fully-fledged synth, with GUI, presets, etc
* [francoisgeorgy/BS2-Web](https://github.com/francoisgeorgy/BS2-Web) ⭐ 50 | 🐛 12 | 🌐 JavaScript | 📅 2025-01-21 - a very polished web interface for the BassStation II synth
* [jssynth](https://github.com/jstrait/jssynth) ⭐ 40 | 🐛 1 | 🌐 JavaScript | 📅 2026-05-12 - powerful synth and sequencer
* [sf2synth.js](https://github.com/logue/sf2synth.js) ⭐ 35 | 🐛 6 | 🌐 TypeScript | 📅 2026-07-31 - a WebMidiLink based synthesizer with SoundFont support
* [okaybenji/subpoly](https://github.com/okaybenji/subpoly) ⭐ 21 | 🐛 0 | 🌐 JavaScript | 📅 2016-12-10 - small multi-voice (polyphonic) synth, define sounds as JS objects
* [okaybenji/submono](https://github.com/okaybenji/submono) ⭐ 12 | 🐛 2 | 🌐 JavaScript | 📅 2018-04-13 - small mono-voice (monophonic) synth, define sounds as JS objects
* [ronkot/ks-guitar-synth](https://github.com/ronkot/ks-guitar-synth) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2018-04-11 - guitair synth, using [Karplus-Strong](http://en.wikipedia.org/wiki/Karplus%E2%80%93Strong_string_synthesis) algorithm. See [ks-guitar](https://github.com/ronkot/ks-guitar) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2018-04-11 for UI.
* [diversen/pluggable-synth](https://github.com/diversen/pluggable-synth) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2018-08-12 - small synth, lightweight piano UI, supports MIDI or keyboard
* [Tinusw/webAudioSynth](https://github.com/Tinusw/webAudioSynth) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2017-08-28 - has 2 oscillators with XY pads, and a piano keyboard
* [kevin-chau/minimoog.js](https://github.com/kevin-chau/minimoog.js) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2017-02-10 - a Minimoog synth
* [ZulfadhliM/web-synth](https://github.com/ZulfadhliM/web-synth) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2018-05-01 - basic synth with LFO modulation and XY pad, React-based
* [d3-synth](https://roadtolarissa.com/synth/) - synth sounds, with circular tracker UI. Very nice, clean code

### Multi-instruments

These are more complete - they have multiple instruments.

* [midi-sounds-react](https://github.com/surikov/midi-sounds-react) ⭐ 131 | 🐛 0 | 🌐 JavaScript | 📅 2018-04-23 - nice examples of using soundfonts, includes a simple music sequencer
* [WebMIDICon](https://github.com/dtinth/WebMIDICon) ⭐ 98 | 🐛 19 | 🌐 TypeScript | 📅 2023-11-28 - nice collection of online instruments
* [terrible-techno](https://terrible-techno.firebaseapp.com/) - nice UI

## Complete DAWs

A "DAW" is a digital audio workstation - an all-round music production app

* [zrythm](https://github.com/zrythm/zrythm) ⭐ 3,100 | 🐛 2 | 🌐 C++ | 📅 2026-08-21 - requires isgn up. A highly automated and intuitive DAW
* [gridsound](https://github.com/gridsound/daw) ⭐ 1,855 | 🐛 28 | 🌐 JavaScript | 📅 2026-07-28 - a lovely open source DAW, uses Web Audio API
* [TReactor](https://github.com/kevin-chau/TReactr) ⭐ 34 | 🐛 18 | 🌐 JavaScript | 📅 2022-12-22 - a Traktor clone, written in React
* [XinDaw](https://github.com/dotgreg/XinDaw) ⭐ 29 | 🐛 1 | 🌐 JavaScript | 📅 2026-04-02 - a multiscreen Web-based DAW designed for audio\&video live performances (Tone.js/React/Meteor)
* [audionodes](https://audionodes.com/online/) - very user-friendly, node editor based DAW (not open source)
* [audiotool](https://www.audiotool.com/) - requires sign up. Lots of tools and features, also available as a Chrome extension
* [soundation](https://soundation.com/) - requires sign up. Sleek looking DAW, looks similar to Non-DAW

## UI components and libraries

### React components

* [r-audio](https://github.com/bbc/r-audio) ⭐ 182 | 🐛 10 | 🌐 JavaScript | 📅 2024-11-27 - WebAudio API using JSX
* [TReactor](https://github.com/kevin-chau/TReactr) ⭐ 34 | 🐛 18 | 🌐 JavaScript | 📅 2022-12-22 - a Traktor clone, written in React
* [kedromelon/mdlr](https://github.com/kedromelon/mdlr) ⭐ 8 | 🐛 8 | 🌐 JavaScript | 📅 2017-03-16 - like above, but more for sound generation (oscillators, tones, waveforms, synths)
* [react-midi-device-provider](https://github.com/halvves/react-midi-device-provider) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2021-09-02 - simple MIDI device/messages handler for react
* [react-music](https://www.npmjs.com/package/react-music) - define sounds, effects, etc, using JSX
* [midi-sounds-react](https://www.npmjs.com/package/midi-sounds-react) - 1500 instruments

### Visual waveform generators

* [katspaugh/wavesurfer.js](https://github.com/katspaugh/wavesurfer.js) ⭐ 10,382 | 🐛 36 | 🌐 TypeScript | 📅 2026-08-21 - generate navigable waveforms
* [bbc/peaks.js](https://github.com/bbc/peaks.js) ⭐ 3,403 | 🐛 64 | 🌐 JavaScript | 📅 2025-11-08 - UI component for interacting with waveforms
* [WFPlayer](https://github.com/zhw2590582/WFPlayer) ⚠️ Archived - an audio waveform generator, nice features
* [audio-oscilloscope](https://github.com/mathiasvr/audio-oscilloscope) ⭐ 96 | 🐛 9 | 🌐 JavaScript | 📅 2023-01-06 - waveform vizualiser for HTML5 Canvas
* [waveplayer.js](https://github.com/michaeldzjap/waveplayer.js) ⭐ 81 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-09 - mp3 player that produces wavforms
* [chrisweb/waveform-visualizer](https://github.com/chrisweb/waveform-visualizer) ⭐ 35 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-30 - waveform generator
* [audio-to-svg-waveform](https://github.com/invokemedia/audio-to-svg-waveform) ⭐ 25 | 🐛 0 | 🌐 JavaScript | 📅 2017-12-01 - simple, generates SVGs, nothing else
* [patidar-suresh/audio-waveform](https://github.com/patidar-suresh/audio-waveform) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2020-10-23 - uses HTML5 Canvas and requestAnimationFrame

### Node editors

Also known as "graph editors".

Link your sounds, effects, inputs & outputs together with a drag and drop interface:

* [cwilso/WebAudio](https://github.com/cwilso/WebAudio) ⭐ 501 | 🐛 10 | 🌐 JavaScript | 📅 2020-05-07 - awesome, easy-to-use node editor, with [demo](https://webaudioplayground.appspot.com)
* [g200kg/WebAudioDesigner](https://github.com/g200kg/WebAudioDesigner) ⭐ 161 | 🐛 3 | 🌐 JavaScript | 📅 2017-12-21 - nice node based sound designer [demo](https://g200kg.github.io/WebAudioDesigner/)
* [dataflow-webaudio](https://github.com/forresto/dataflow-webaudio) ⭐ 56 | 🐛 1 | 🌐 JavaScript | 📅 2014-08-11 - Dataflow graph editor + Web Audio API - [demo](https://forresto.github.io/dataflow-webaudio/)
* [tai2/webaudiocomposer](https://github.com/tai2/webaudiocomposer) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2014-11-23 - audio node-editor with a patch-based UI, like Quartz composer

### Audio visualization

* [preziotte/party-mode](https://github.com/preziotte/party-mode) ⭐ 803 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-15 - a d3 based visualizer with lots of options
* [kelvinau/circular-audio-wave](https://github.com/kelvinau/circular-audio-wave) ⭐ 281 | 🐛 14 | 🌐 JavaScript | 📅 2024-05-18 - circular audio waves powered by E-charts
* [margox/vudio.js](https://github.com/margox/vudio.js) ⭐ 255 | 🐛 4 | 🌐 JavaScript | 📅 2024-03-06 - very nice bouncing bars, can place or align at top, bottom, left, right or center
* [pts.js](https://ptsjs.org/) - a powerful creative coding and visualization library

### Other UI

* [paulrosen/abcjs](https://github.com/paulrosen/abcjs) ⭐ 2,327 | 🐛 244 | 🌐 HTML | 📅 2026-08-09 - for rendering music notation
* [nexus-js/ui](https://github.com/nexus-js/ui) ⭐ 874 | 🐛 45 | 🌐 JavaScript | 📅 2025-07-03 - very nice UI toolkit for web based MIDI instrument [UI components](https://nexus-js.github.io/ui/) (used by nofft, above)
* [g200kg/webaudio-controls](https://github.com/g200kg/webaudio-controls) ⭐ 370 | 🐛 20 | 🌐 JavaScript | 📅 2025-10-04 - web components aimed at VST instruments, DAWs, etc
* [ISNIT0/webaudio-generator](https://github.com/ISNIT0/webaudio-generator) ⭐ 62 | 🐛 8 | 🌐 TypeScript | 📅 2022-12-08 - a UI for generating Web Audio API code
* [g200kg/input-knobs](https://github.com/g200kg/input-knobs) ⭐ 60 | 🐛 2 | 🌐 HTML | 📅 2021-10-31 - turns `<input>` tags into sliders, knobs, etc
* [williamfields/nofft.js](https://github.com/williamfields/nofft.js) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2017-09-04 - Javascript library for creating MIDI-responsive visuals

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
