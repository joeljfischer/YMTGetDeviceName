# YMTGetDeviceName
This framework gets a friendly device name from the hardware model identifier.

## Description
Standard `UIDevice` can only distinguish between broad device families such as iPhone and iPad.
This framework resolves the hardware model identifier to a friendly device name.

## Installation
### Use Swift Package Manager

- File > Swift Packages > Add Package Dependency
- Add https://github.com/joeljfischer/YMTGetDeviceName
- Select "Up to Next Major" with "5.10.0"

## How to use
### Import
```ViewController.swift
import YMTGetDeviceName
```

### Get device name
```ViewController.swift
print(YMTGetDeviceName.getDeviceName())
```

## Q&A
### What is the range of supported devices?
Supports iPhone and iPad identifiers up to 2026/03/24, including the missing 2024-2026 iPhone and iPad models verified in this update.
