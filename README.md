# Wasteland Radio

A standalone browser app that turns YouTube tab audio into a vintage AM radio: bass cut, narrow treble, speaker distortion, vinyl crackle, static, and wind.

## Listen

1. Download `index.html` and open it in desktop Chrome or Edge.
2. Play a YouTube video in another tab.
3. Click **Tune in to a tab**, select the YouTube tab, and enable **Share tab audio**.
4. Start with **Wasteland AM**, **Pocket radio**, or **Distant station**, then adjust the controls.

Keep both tabs open and leave the YouTube player unmuted. **Power off** releases capture and restores normal audio. All audio in the selected tab, including ads, passes through the effects.

## Source

Everything is in `index.html`: HTML, CSS, and JavaScript. No installation, build step, API key, or server is required. Audio is processed locally with the Web Audio API; it is not recorded or uploaded.

Live tab audio requires desktop Chrome or Edge. Safari, Firefox, and mobile browsers are not supported. The browser prompts you to select a tab each time you connect.

## Validation

JavaScript syntax, YouTube URL validation, distortion-curve bounds and symmetry, and preset frequency ranges were checked. End-to-end browser playback has not yet been verified.
