# libdovi-builds

Prebuilt [libdovi](https://github.com/quietvoid/dovi_tool/tree/main/dolby_vision) static libraries for cross-platform Dolby Vision RPU processing.

## Platforms

- **Android**: arm64-v8a, armeabi-v7a, x86, x86_64
- **iOS**: arm64, arm64-sim, x86_64-sim
- **macOS**: arm64, x86_64
- **Linux**: x86_64, arm64
- **Windows**: x86_64, arm64

## Usage

Download the archive for your target from [Releases](https://github.com/edde746/libdovi-builds/releases) and link the static library (`libdovi.a` / `dovi.lib`) against your project. The C header is in `libdovi-headers.tar.gz`.

## Building

Trigger the `Build libdovi` workflow manually with a [dovi_tool](https://github.com/quietvoid/dovi_tool/releases) version tag.
