This is a Kotlin Multiplatform project designed for both Android and iOS.

/composeApp is dedicated to code shared across your Compose Multiplatform applications. It includes several subdirectories:

commonMain is used for code that is shared across all platforms.
Other directories are intended for Kotlin code that will be compiled for the specific platform named in the directory. For instance, if you need to utilize Apple's CoreCrypto for the iOS portion of your Kotlin app, the iosMain folder is where you should place those calls.
/iosApp contains the iOS applications. Even if you're using Compose Multiplatform for UI sharing, you still need this entry point for your iOS application. This is also where you should include SwiftUI code for your project.

Learn more about Kotlin Multiplatform: https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html