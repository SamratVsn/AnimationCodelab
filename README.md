# Animation Codelab

A Jetpack Compose project built while working through Android's **"Animations in Jetpack Compose"** codelab — one of the official Android Developers codelabs focused on animation APIs in Compose.

## About

This repository contains my implementation of the official Compose codelab on animations. Rather than a standalone app, it's a hands-on learning project used to explore how Compose handles animation in a declarative UI framework, following along with Google's guided material and exercises.

The codelab typically centers around animating a simple UI (e.g., an expandable list/card layout), and is used to demonstrate core animation concepts in Compose:

- **`animate*AsState`** — animating a single value (color, size, offset, etc.) in response to a state change
- **`AnimatedVisibility`** — animating the appearance and disappearance of a composable, with enter/exit transitions
- **`updateTransition`** — coordinating multiple animations that run together based on a single state change
- **`rememberInfiniteTransition`** — creating repeating/looping animations
- **Easing and animation specs** — customizing duration, delay, and easing curves (`tween`, `spring`, etc.)

## What I Practiced

Working through this codelab helped me get hands-on with:

- Driving UI animation purely from state changes, in line with Compose's declarative model
- Choosing the right animation API for a given use case (single value vs. coordinated multi-value transitions)
- Customizing animation timing and easing for more natural-feeling motion
- Structuring composables so animated and non-animated logic stay cleanly separated

## Built With

- **Kotlin**
- **Jetpack Compose**
- **Android SDK**
- **Gradle** (Kotlin DSL)

## Project Structure

Standard Android Studio / Gradle project layout:

AnimationCodelab/
├── app/ # Main application module
├── gradle/ # Gradle wrapper files
├── build.gradle.kts # Project-level build config
└── settings.gradle.kts # Module settings


## Running the Project

1. Clone the repo:
```bash
   git clone https://github.com/SamratVsn/AnimationCodelab.git
```
2. Open the project in **Android Studio**.
3. Let Gradle sync, then run on an emulator or physical device.

## Status

This is a completed learning/practice exercise rather than an actively maintained app — kept here as a reference and a record of working through Compose animation fundamentals.

## Author

**[Samrat Parajuli](https://github.com/SamratVsn)** (SamratVsn)
Android Developer · Nepal

- Portfolio: [samratparajuli0.com.np](https://www.samratparajuli0.com.np/)
- GitHub: [github.com/SamratVsn](https://github.com/SamratVsn)
