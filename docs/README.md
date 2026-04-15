# Nyxara AI Studio Docs

Nyxara AI Studio is a Unity editor and runtime workflow for turning ARKit-compatible 3D characters into AI companions with a local-first setup.

This docs folder is the public documentation set for the project.

## Start Here

- [Quick Start](./QUICK_START.md)
- [Dependencies for Release](./DEPENDENCIES_FOR_RELEASE.md)
- [What Is Included](./WHAT_IS_INCLUDED.md)
- [Known Limitations](./KNOWN_LIMITATIONS.md)

## Project Docs

- [Release Checklist](./RELEASE_CHECKLIST.md)
- [Changelog](./CHANGELOG.md)
- [Roadmap](./ROADMAP.md)
- [Next Updates](./NEXT_UPDATES.md)
- [License](./LICENSE.txt)

## Important

Nyxara AI Studio can be imported without LLMUnity and Whisper installed.

The package compiles and the demo scene loads in a clean Unity project without these dependencies installed.

When those optional integrations are missing:

- the project should still compile
- the scene should still load
- AI and speech integrations are disabled with warnings instead of hard errors

## Public Repo Scope

This repository is intentionally limited to public documentation.

It does not include:

- Unity project folders
- editor/runtime source code
- system folders
- external repositories
- local models
- local voice assets
- third-party character assets
