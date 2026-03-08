# GameDemo (Xcode Project)

This folder is where your Xcode project lives.

## Getting Started

1. Open Xcode and create a new project:
   - **File → New → Project**
   - Choose **iOS → App**
   - Set the product name to `GameDemo`
   - Set the language to **Swift**
   - Save the project **into this folder** (`GameDemo/`)

2. Your project folder will look like:
   ```
   GameDemo/
   ├── GameDemo.xcodeproj
   ├── GameDemo/
   │   ├── AppDelegate.swift
   │   ├── SceneDelegate.swift
   │   ├── ViewController.swift (or GameScene.swift for SpriteKit)
   │   ├── Assets.xcassets
   │   └── Info.plist
   └── GameDemoTests/
   ```

3. Once created, you can run the app on a simulator by pressing **⌘ + R** in Xcode.

## Notes
- Do **not** commit the `DerivedData/` or `.xcuserstate` files — these are already excluded by the root `.gitignore`.
- If you use Swift Package Manager for dependencies, commit your `Package.resolved` file so teammates get the same versions.
