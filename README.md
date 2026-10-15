# WiiU Remote Browser

[![](https://img.shields.io/badge/release-v1.1.0-yellow)](https://github.com/ehzito/WiiU_remote_browser/releases/tag/v1.1.0) [![](https://img.shields.io/badge/status-pre--release-orange)](#)

Remote browser server for Nintendo Wii U. Renders modern sites via macOS Chromium and streams JPEG screenshots to the console's browser. Experimental project with legacy HTML, HTTPS/TLS 1.2 and local auth. Not affiliated with Nintendo.

## Overview

This project turns a modern browser running on macOS into a lightweight remote browser for the Wii U. It renders pages in Chromium, captures the result as JPEG frames, and streams them to the Wii U browser in a way that is usable for simple browsing and testing.

It is still a pre-release and is intended for experimentation and testing on real hardware.

## Features

- Browser rendering via macOS Chromium
- JPEG screen streaming to the Wii U browser
- Local auth flow
- Legacy HTML compatibility considerations
- Experimental support for older browser constraints
- Early prototype workflow for Wii U testing

## Requirements

- macOS 13 (Ventura) or newer
- Apple Silicon / ARM64 build only
- Nintendo Wii U console
- Local network access between the macOS machine and the console

## Download

- Release v1.1.0: https://github.com/ehzito/WiiU_remote_browser/releases/tag/v1.1.0
- Asset: `WiiU_Remote_Browser_v1.1.0.arm64.zip`

## Demo / Gallery

<div align="center">
  <img src="https://github.com/user-attachments/assets/cc575965-02f4-43f6-a85c-f5d92c862d64" width="900" alt="WiiU Remote Browser demo 1" />
</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/ebd17dea-158b-41dc-946c-8b9ea49dc3c9" width="900" alt="WiiU Remote Browser demo 2" />
</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/784890c0-5d7e-4ac5-b578-68db538349f3" width="900" alt="WiiU Remote Browser demo 3" />
</div>

## Current status

- First public release
- Client UI still being translated and currently set to pt-BR
- Minimum tested platform: macOS 13
- Recommended testing platform: macOS 27 (Golden Gate)
- Audio is still not fully working/activating
- Only ARM64 build is currently available

## Notes

This is an experimental project and may not be suitable for production use. It is primarily aimed at testing on Wii U hardware and exploring the limits of streaming browser content to the console.

## License

Add the project license here if one is defined in the repository.

## Contact / Links

- Repository: https://github.com/ehzito/WiiU_remote_browser
- Release: https://github.com/ehzito/WiiU_remote_browser/releases/tag/v1.1.0
