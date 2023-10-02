# Payment

[![CI](https://github.com/BrunoVieiraSouza/Teste2/actions/workflows/CI.yml/badge.svg)](https://github.com/BrunoVieiraSouza/Teste2/actions/workflows/CI.yml) 
[![Tag](https://img.shields.io/github/v/tag/BrunoVieiraSouza/Teste2)](https://github.com/BrunoVieiraSouza/Teste2/releases)
[![GitHub](https://img.shields.io/github/license/BrunoVieiraSouza/Teste2)](https://github.com/BrunoVieiraSouza/Teste2/blob/main/LICENSE)

## Installation

### [Swift Package Manager (SPM)](https://swift.org/package-manager)

```swift
import PackageDescription
let package = Package(
    name: "<Your Product Name>",
    dependencies: [
       .package(url: "https://github.com/BrunoVieiraSouza/Teste2", .upToNextMajor(from: "1.1.0"))
    ],
    targets: [
        .target(
            name: "<Your Target Name>",
            dependencies: ["Payment"]),
    ]
)
```

## License
Payment is released under the MIT license. See LICENSE for details.
