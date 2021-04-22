# Threequencer (prototype)

Threequencer is an in-browser HTML5 (WebGL+WebAudio) three-dimensional step sequencer. There is a working instance at [ray.scot/threequencer](https://ray.scot/threequencer).

## Notes

The software is an alpha release prototype, and is not yet set up for CI/CD or standards-compliant collaborative development. 

The main codebase is currently just inline JavaScript in the main index.html document, using the libraries THREE.js (a wrapper for WebGL), Tone.js (a wrapper for Web Audio) and jQuery (for easy interaction with the DOM). The THREE.js elements are imported as modules.

At present no packaging or compilation is done, so there is no build or src folder. This repo should run as is on any http server it's uploaded to, even one without wider access to the Internet.

## Contributing
Feel free to open issues.

## License
TBC