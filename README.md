# CPUMonitor-macOS

A native macOS menu bar app that monitors CPU usage and alerts you when a process has been using high CPU for an extended period.

## Features

- Menu bar icon that fades from green → yellow → red as high CPU duration increases
- Notification with process name and PID after 60 seconds of sustained 90%+ CPU usage
- Optional "Run on Login" via LaunchAgent
- Zero third-party dependencies — pure Swift + AppKit

## Requirements

- macOS 11.0+
- Xcode Command Line Tools (`xcode-select --install`)

## Build & Run

```bash
./build.sh
open build/CPUMonitor.app
```

## Install

```bash
cp -r build/CPUMonitor.app /Applications/
```

## Related

- [CPUMonitor](https://github.com/michaelbrandi/CPUMonitor) — Linux version
