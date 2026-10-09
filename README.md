<div align="center">

# ✋ Gesture-Based Web Hand Tracking

### Touch-free interaction using computer vision and MediaPipe Hands

**IT329 · Emerging Web Technologies · King Saud University**

**HTML** · **CSS** · **JavaScript** · **MediaPipe Hands**

[▶ Launch Live Demo](https://yaraaz5.github.io/gesture-based-web-hand-tracking/) · [How It Works](#how-it-works) · [Gestures](#supported-gestures) · [Team](#team)

</div>

---

## Overview

This collaborative university project explores **gesture-based hand tracking on the web** and includes a browser-based interactive demo. It uses the webcam and Google's **MediaPipe Hands** library to track hand landmarks, recognizes selected gestures with JavaScript rules, and triggers visual effects on the page. No separate wearable controller is needed.

The project combines a technical presentation on the technology, its applications and relevant libraries with a working demonstration of the concept.

## How it works

1. The user starts the camera and grants browser permission.
2. MediaPipe estimates **21 hand landmarks** from the camera feed.
3. JavaScript compares finger positions to classify a set of gestures.
4. A recognized gesture triggers a visual effect and updates the on-screen event log.

## Supported gestures

| Gesture | Demo reaction |
|---|---|
| 🖐️ Open Palm | Blue wave effect |
| 👍 Thumbs Up | Green background and particles |
| ✌️ Victory / Peace | Confetti |
| ☝️ Pointing Up | Rocket animation |
| ✊ Closed Fist | Red alert effect |
| 👎 Thumbs Down | Dark pulse |
| 🤟 I Love You / Rock | Purple pulse |

The demo also shows gesture labels, detection counts, and an effect log.

## Try the demo

**[▶ Open the Live Hand Tracking Demo](https://yaraaz5.github.io/gesture-based-web-hand-tracking/)** · [View the HTML source](index.html)

To run it, open the demo from a **secure origin (HTTPS)** or use a local development server such as `http://localhost`; click **Start Camera** and allow webcam access. An internet connection is needed to load MediaPipe and fonts from their CDNs.

**GitHub Pages:** The Pages deployment has completed successfully. Camera permission and browser compatibility are required; actual gesture recognition should be tested in the visitor's browser.

## Technology stack

- **HTML & CSS:** responsive interface and visual presentation
- **JavaScript:** gesture classification, event log, and animation effects
- **MediaPipe Hands:** real-time hand-landmark estimation using the webcam
- **MediaPipe Camera Utils & Drawing Utils:** camera frames and landmark rendering

**Clarification:** The presentation compares MediaPipe, TensorFlow.js Handpose and Handtrack.js; the actual demo uses **MediaPipe Hands**, not all three libraries.

## Important demo notes

- Gesture classification is based on **simple landmark-position rules**. Performance may vary with lighting, hand orientation, camera quality and browser.
- The displayed *confidence percentage* is a **simulated UI value**, not an accuracy score or probability returned by MediaPipe.
- The browser requests camera access. No backend or database is included in this demo.
- This is an **educational prototype**, not a production gesture-recognition system or a sign-language translation application.

## Presentation

📄 **[View the 10-slide Project Presentation (PDF)](Section69235_Group2_GesturedBasedWebHandTracking%20.pdf)** — covers the hand-tracking workflow, applications, tools, and demo. The uploaded presentation should be checked for student IDs before sharing externally.

## Team

Presented as a five-member group project at King Saud University:

- Shahad Alabdulkarim
- Yara Zakzouk
- Rama Aljoudi
- Farah Alhamed
- Noora Alsaiari

---

<sub>Academic demonstration for the IT329 course. Third-party libraries belong to their respective authors.</sub>
