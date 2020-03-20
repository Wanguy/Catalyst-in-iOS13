# Catalyst for iOS 13

![build](https://img.shields.io/badge/build-passing-brightgreen) [![GitHub](https://img.shields.io/github/license/Wanguy/Catalyst-in-iOS13)](https://github.com/Wanguy/Catalyst-in-iOS13/blob/master/LICENSE) 

## Introduction

Since the introduction of the first iPhone, Apple has been building and maintaining two parallel operating systems: macOS and iOS. Both are based on Darwin but optimized for different types of interaction. As time passed, the apps and features on macOS and iOS started to converge slowly. It became very common for developers to create and support apps that ran on multiple types of Apple devices, from iPhone, iPad and Mac.

<img src="https://i.loli.net/2020/03/20/LpJNKudg4S6RYXs.png" alt="interface" style="zoom:80%;" />

The trouble with building an app that runs on both iOS and Mac is that you need to learn and use two different UI frameworks: UIKit and AppKit. And, therefore need to maintain two distinct codebases. While it is, of course, possible to share some code using frameworks, the entirety of an app's UI-related code effectively needs to be done twice.
With the arrival of Catalyst, it is now possible to bring an iPad app to the Mac using a single, UIKit-based codebase. With minimal effort, your iPad app can function quite well on macOS, and with a bit of additional effort, can become a world-class Mac citizen.

## Requirements

- Xcode 11.0 or later

- Swift 5
- A Mac running macOS Catalina (10.15) or later

- iOS 13 or later

## Setup

```bash
git clone git@github.com:Wanguy/Catalyst-in-iOS13.git
cd Catalyst-in-iOS13
```

## License

Copyright (c) 2015-2020 Wanguy. Released under MIT. See [LICENSE](https://github.com/Wanguy/Catalyst-in-iOS13/blob/master/LICENSE) for details.