# CardBattle 2

An iOS card game built with Swift and UIKit.

## About

CardBattle 2 is an upgraded version of my original CardBattle app. Two players compete over 10 rounds — each round flips a card and the higher value wins. The twist: your starting side (East or West) is determined by your real-world location.

## Features

- **Location-based gameplay** — uses GPS to assign East/West side based on longitude
- **10 rounds** with a 5-second timer per round
- **Full orientation support** — portrait and landscape
- **Dark mode support** — adapts UI and earth globe images automatically
- **Sound effects** — card flip sounds and victory music
- **Background music** during gameplay
- **Player name** saved locally and shown on the summary screen

## How to Play

1. Enter your name on first launch
2. Allow location access so the app can assign your side
3. Tap **START** — each round a card is flipped for both players
4. After 10 rounds, a summary screen shows the winner

## Tech

- Swift / UIKit
- CoreLocation for GPS
- AVFoundation for audio
- UserDefaults for player data persistence
- Auto Layout with dynamic constraints for orientation changes

## Requirements

- iOS 14+
- Xcode 13+
