# Project Brief — Nashville Numbers

## Vision

An iOS app that teaches musicians the Nashville Number System and puts it to work — so they can walk into any session, rehearsal, or service and play fluently from a number chart in any key.

## Target User

- Worship musicians and church players who need to transpose on the fly
- Session and gigging musicians learning to work without sheet music
- Students building ear training and theory fluency through practical application

## Core Features

### MVP
- [ ] Key selector — set the root key, all numbers resolve to real chords
- [ ] Number chart reader — display a chart in NNS format with chord names shown beneath
- [ ] Instant transposition — change key and the whole chart updates live
- [ ] Chord library — tap any chord to hear it (audio playback)
- [ ] Common number patterns — pre-loaded progressions (1-4-5, 1-5-6-4, etc.)

### V2
- [ ] Chart builder — write your own number charts and save them
- [ ] Practice mode — hear a progression, identify the numbers by ear
- [ ] Chart sharing — export and send charts as text or PDF
- [ ] Capo support — input capo position, see sounding key vs. fret key

### V3
- [ ] Real-time transposition from audio (detect key from mic input)
- [ ] Band mode — shared chart view over local network
- [ ] Song library — community-contributed number charts

## Design Principles

- **Fast to use** — a musician mid-rehearsal shouldn't have to dig
- **Numbers-first UI** — the number is always the primary display, key name is context
- **No music theory gatekeeping** — accessible to beginners, useful to pros

## Open Questions

- Monetization: free with premium chart library? one-time purchase?
- Audio engine: AVFoundation samples vs. synthesized chords
- Onboarding: brief NNS explainer for users who are new to the system

## Milestones

| Phase | Goal |
|---|---|
| 0 — Setup | Repo, Xcode project, basic SwiftUI scaffold |
| 1 — Core | Key selector + number chart reader + transposition |
| 2 — Audio | Chord playback, common progressions |
| 3 — Create | Chart builder + sharing |
| 4 — Polish | Onboarding, design pass, App Store prep |
