corekit/
├─ cli/                    # CoreKit CLI source (Go/Rust/Node.js)
│  ├─ corekit              # CLI binary entrypoint
│  └─ plugins/             # CLI commands (install/uninstall/update/...)
│
├─ ios/                    # iOS-specific packages
│  ├─ Package.swift        # Swift Package Manager entry
│  ├─ Sources/
│  │  ├─ CoreKit/          # CoreKit iOS core
│  │  ├─ CoreKitAuth/      # Auth feature (example)
│  │  ├─ CoreKitPhotos/    # Photos feature (example)
│  │  └─ ...
│  └─ Tests/
│
├─ android/                # Android-specific packages
│  ├─ library/             # CoreKit Android core library
│  │  ├─ build.gradle.kts
│  │  └─ src/main/kotlin/…
│  ├─ modules/
│  │  ├─ auth/             # Auth feature (example)
│  │  ├─ photos/           # Photos feature (example)
│  │  └─ ...
│  └─ publish/             # Publishing scripts (MavenCentral/JitPack)
│
├─ templates/              # Editable feature templates
│  ├─ ios/
│  │  ├─ auth/
│  │  └─ photos/
│  └─ android/
│     ├─ auth/
│     └─ photos/
│
├─ generated/              # Auto-generated code (NEVER edit directly)
│  ├─ ios/
│  └─ android/
│
├─ docs/                   # Documentation & guides
│  ├─ getting-started.md
│  └─ modules.md
│
└─ README.md
