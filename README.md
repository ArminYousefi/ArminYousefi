# Armin Yousefi

**Android Developer** · Kotlin · Jetpack Compose · Real-time & platform-level Android

I build enterprise Android applications: real-time messaging, live video, location tracking, and device management. Since 2025 I have been Android Team Lead of a two-person team, owning architecture decisions, library selection, and code review.

My production work is private to client organizations, so it is not on GitHub. The public repository below shows how I approach an Android client end to end.

## What I work with

| Area | Tools |
|---|---|
| Language | Kotlin (primary), Java |
| UI | Jetpack Compose, Material 3, Navigation |
| Architecture | Clean Architecture, MVVM, modularization, dependency injection with Hilt |
| Async & data | Coroutines, Flow, Room, DataStore, Retrofit, OkHttp |
| Real-time | SignalR, WebSocket, LiveKit |
| Platform APIs | AccessibilityService, MediaProjection, foreground services, WorkManager, DevicePolicyManager, PackageInstaller, CameraX |
| Testing & quality | JUnit, Mockito, UI Automator, LeakCanary, Android Studio Profiler |

## Selected problems I have solved (production, private)

- **Reliable messaging over SignalR:** acknowledgment and retry for undelivered messages, with server sequence numbers to keep message order.
- **Cross-vendor AccessibilityService:** one implementation that behaves consistently across different OEM Android builds.
- **Screen and audio/video streaming:** MediaProjection and LiveKit, including runtime-permission and foreground-service edge cases.
- **Location quality:** Kalman-filter position estimation, with Mahalanobis distance and the Haversine formula to filter invalid fixes.
- **On-demand feature delivery:** a plugin-based Android product where a small core app downloads modules and loads them at runtime from DEX files.

## Featured project

### [AndroidTaskManager](https://github.com/ArminYousefi/AndroidTaskManager)

A multi-user, Jira/Trello-style task board. Real-time sync over raw WebSocket, an offline-first client, token and refresh-token authentication, and drag-and-drop between columns.

## Contact

- Email: [arminyousefi6@gmail.com](mailto:arminyousefi6@gmail.com)
- Telegram: [@Armin_androiddev](https://t.me/Armin_androiddev)
