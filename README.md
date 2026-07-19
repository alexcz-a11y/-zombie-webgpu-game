# Zombie WebGPU Game

A community-built, non-commercial narrative zombie web-game demo powered by Three.js and WebGPU.

> Status: pre-production. The first milestone is a polished vertical-slice demo focused on visual quality, atmosphere, and narrative presentation.

## Vision

Build a desktop-Chrome WebGPU experience with cinematic environments, detailed characters, destruction effects, and a story-first structure. Development should remain iterative: establish a playable vertical slice, validate performance, then increase asset and scene fidelity.

## Technical direction

- Latest compatible Three.js release
- `WebGPURenderer` via `three/webgpu`
- WebGPU required; no WebGL fallback
- Desktop Chrome is the initial supported browser
- User-adjustable quality settings for lighting, shadows, environment detail, effects, resolution scale, and post-processing
- Measured performance budgets and graceful quality scaling

## Community principles

- Non-commercial collaboration and use
- Original, generated, or properly licensed assets only
- Document asset provenance and third-party licenses
- Keep pull requests focused and reviewable
- Never commit API keys, tokens, or private data

## Project structure

The application scaffold and production asset structure will be created in the first Codex Cloud implementation task. Until then, this repository contains project governance and environment-ready metadata.

## Contributing

Contributions, testing, performance reports, story ideas, and accessibility feedback are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## License

This project is available for non-commercial purposes under the [PolyForm Noncommercial License 1.0.0](LICENSE). It is source-available rather than OSI-approved open source. Third-party dependencies and assets remain subject to their own licenses.
