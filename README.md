# Nyxara AI Studio

Public documentation for Nyxara AI Studio.

This repository is intentionally docs-only. It does not include Unity project folders, source code, external runtimes, local models, or third-party character assets.

## What This Repo Contains

- Product overview
- Quick start documentation
- Dependency setup guidance
- Release and packaging notes
- Changelog and roadmap
- License information

## Main Docs

- [Docs Index](./docs/README.md)
- [Quick Start](./docs/QUICK_START.md)
- [Dependencies](./docs/DEPENDENCIES_FOR_RELEASE.md)
- [What Is Included](./docs/WHAT_IS_INCLUDED.md)
- [Known Limitations](./docs/KNOWN_LIMITATIONS.md)
- [Release Checklist](./docs/RELEASE_CHECKLIST.md)
- [Changelog](./docs/CHANGELOG.md)
- [Roadmap](./docs/ROADMAP.md)
- [Next Updates](./docs/NEXT_UPDATES.md)
- [License](./docs/LICENSE.txt)

## Important

Nyxara AI Studio supports optional external integrations such as LLMUnity, Whisper, and Piper.

The package compiles and the demo scene loads in a clean Unity project without these dependencies installed.

These integrations are not included in this repository.

If they are not installed in a Unity project:

- AI generation is disabled
- Speech-to-text is disabled
- Text-to-speech is disabled

The package is designed to import safely and degrade gracefully when optional integrations are missing.

## External Dependencies

- LLMUnity: https://github.com/undreamai/LLMUnity
- whisper.unity: https://github.com/Macoron/whisper.unity
- Piper: https://github.com/rhasspy/piper/releases
- sherpa-onnx: https://github.com/k2-fsa/sherpa-onnx

Recommended model:

- Gemma 3 4B IT (Q4_K_M GGUF)
- https://huggingface.co/Aldaris/gemma-3-4b-it-Q4_K_M-GGUF

Piper voices:

- https://huggingface.co/rhasspy/piper-voices

## Notes

- This public repo is for documentation only.
- It does not redistribute source files, project files, or bundled dependencies.
- For package support and setup guidance, start with the [Docs Index](./docs/README.md).
