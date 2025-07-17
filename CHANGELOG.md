## New features

### iOS QuickStart sample app

We’ve added a complete iOS QuickStart sample application to help developers get started quickly with the Sendbird AI Agent SDK for iOS. The sample demonstrates how to initialize the SDK, manage user sessions, handle push notifications, and integrate AI agent conversations into your app with a modern Swift UI. This project includes best practices for session management, theming, and push notification handling, making it easier for developers to build and customize their own AI-powered customer support experiences.

The sample app features:
- Full project files for Xcode, including Info.plist, entitlements, and storyboard resources
- Example implementation of push notification delivery and click tracking
- Ready-to-use UI for logging in, theme switching, and launching AI agent conversations
- Modular code with extension points for customization and integration with extended SDKs (DeskSDK, UIKit)

## Improvements

- Added theme switching support in the sample app to demonstrate both light and dark modes
- Enhanced push notification handling with clear examples for registering, unregistering, and presenting conversations from push payloads
- Provided detailed inline documentation and sample configuration for session management, error handling, and SDK initialization
- Updated onboarding flow in the sample to make it easier to connect, disconnect, and manage user state

## Fixes

- No user-facing bug fixes were included in this release

## Behind the scenes

- Added a new iOS sample app under `ios/Sample/QuickStart` with full source code, project configuration, and assets
- Implemented modular Swift extensions for session, notification, and theme management
- Integrated support for both UIKit and DeskSDK (when available) via conditional compilation
- Provided robust utility classes and extension methods to support rapid prototyping and demo scenarios
- Updated Xcode project files, entitlements, and asset catalogs for a seamless developer experience
