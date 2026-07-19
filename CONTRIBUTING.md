# Contributing

Thanks for helping build Zombie WebGPU Game.

## Before contributing

1. Use the project only for non-commercial purposes.
2. Open an issue before beginning a large feature, narrative rewrite, or asset overhaul.
3. Use only original, generated, public-domain, or properly licensed assets.
4. Record asset sources and generation details in the pull request.
5. Never commit credentials or personal data.

## Development workflow

1. Fork the repository.
2. Create a focused branch from `main`.
3. Make one coherent change.
4. Run the available formatting, lint, build, and test commands.
5. Open a pull request explaining the intent, visual or performance impact, validation performed, and asset provenance.

## WebGPU requirements

- Use Three.js WebGPU APIs and `WebGPURenderer`.
- Do not introduce a WebGL fallback.
- Detect missing WebGPU support and display a clear compatibility message.
- Treat desktop Chrome as the initial target.
- Avoid unbounded draw calls, texture memory, particle counts, or shadow costs.
- Expose expensive visual features through quality settings.

## Generated content

Generated images, textures, audio, models, and code must not imitate protected characters or franchises. Include the tool/model used, the date, and any relevant source references in the pull request.

## Conduct

Be constructive, discuss the work rather than the person, and respect reviewers and contributors.
