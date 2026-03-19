# Obfuscate

[![Build](https://github.com/inekipelov/swift-obfuscate-macro/actions/workflows/build.yml/badge.svg)](https://github.com/inekipelov/swift-obfuscate-macro/actions/workflows/build.yml)

A Swift macro package that obfuscates string literals at compile time.

## Install

```swift
.package(url: "https://github.com/inekipelov/swift-obfuscate-macro", from: "1.0.0")
```

## Use

```swift
import Obfuscate

let value = #Obfuscate("Hello, world!")
```

## Requirements

Swift 6.2 toolchain with macro support.
iOS 13+, macOS 10.15+, macCatalyst 13+, tvOS 13+, watchOS 6+, visionOS 1+.
