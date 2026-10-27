<div align="center">

# PING

### A Voice-First Personal Assistant for iOS

**Speak naturally. Stay organized. Never miss what matters.**

A native iOS application built with Swift and SwiftUI, combining
voice interaction, intelligent reminders, and cloud-powered functionality.

**Swift** · **SwiftUI** · **iOS** · **Cloudflare Workers** · **Cloudflare D1**

</div>

---

## Overview

PING is a native iOS personal assistant independently designed and developed
to make everyday reminder management simpler and more intuitive.

Instead of relying exclusively on forms and menus, PING places natural
voice interaction at the center of the experience.

The application combines native iOS technologies, intelligent reminder
management, and cloud-based services within a carefully designed interface.

---

## Key Features

### Voice-First Interaction

- Create reminders using natural speech.
- Real-time speech recognition and transcription.
- Custom interactive voice interface with animations and haptic feedback.
- Keyboard input as an alternative to voice.

### Intelligent Reminders

- Standard and recurring reminders.
- Location-based reminders.
- Conditional reminders supported by cloud services.
- Reminder organization and completion tracking.

### Native iOS Experience

- Built entirely with Swift and SwiftUI.
- Custom UI components and interactive animations.
- Light and dark appearance support.
- English and Italian localization.
- Interactive onboarding experience.

### Cloud Integration

- Cloudflare Workers for backend functionality.
- Cloudflare D1 for cloud-based data management.
- REST API integration between the iOS application and cloud services.

---

## Technology Stack

| Area | Technologies |
|------|-------------|
| **Language** | Swift |
| **UI Framework** | SwiftUI |
| **Local Persistence** | SwiftData |
| **Speech Recognition** | Apple Speech Framework |
| **Backend** | Cloudflare Workers |
| **Cloud Database** | Cloudflare D1 |
| **Communication** | REST APIs |
| **Development Tools** | Xcode, Git, GitHub |

---

## Application Architecture

PING combines a native iOS application with cloud-based functionality.

```text
                  ┌───────────────────────┐
                  │       PING iOS        │
                  │     Swift / SwiftUI   │
                  └───────────┬───────────┘
                              │
               ┌──────────────┴──────────────┐
               │                             │
      ┌────────▼────────┐          ┌────────▼────────┐
      │ Local Services  │          │ Cloud Services  │
      │                 │          │                 │
      │ Speech          │          │ Cloudflare      │
      │ Reminders       │          │ Workers         │
      │ SwiftData       │          │                 │
      └─────────────────┘          └────────┬────────┘
                                           │
                                  ┌────────▼────────┐
                                  │  Cloudflare D1  │
                                  │    Database     │
                                  └─────────────────┘
```

This architecture allows PING to combine native device capabilities
with cloud-powered reminder functionality.

---

## Screenshots

Application screenshots and a short demonstration will be added
to showcase the user interface and core interactions.

---

## Development & Responsibilities

PING is an independent software engineering project.

I designed and developed the application across multiple areas:

- Native iOS application architecture.
- SwiftUI interface design and implementation.
- Speech recognition and voice interaction.
- Reminder management and application logic.
- Backend integration and cloud functionality.
- Testing, debugging, and iterative improvements.

The project reflects my interest in building complete software
products, from user experience to backend integration.

---

## Project Status

**Active Development**

PING has been built and tested on a physical iPhone.

The application continues to evolve through feature development,
testing, and user experience improvements.

---

## Source Code & Privacy

This repository serves as a **public showcase** of PING.

The original application source code is maintained in a
separate private repository.

This showcase is intended to present the application's
features, architecture, and technical implementation
without distributing its proprietary source code.

---

## Developer

**Francesco Domanico**

Computer Engineering Graduate — Politecnico di Milano  
Based in Toronto, Ontario, Canada

[LinkedIn](https://www.linkedin.com/in/francesco-domanico-288064239/) |
[GitHub](https://github.com/fradom22)

---

<div align="center">

**PING — Designed to make remembering effortless.**

</div>
