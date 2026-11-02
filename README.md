# Cryzix RP — Android starter prototype

This is a small 2D top-down open-world RP starter for Android, built with Kotlin/Canvas.

## Included
- A simple city map with Police, Hospital, City Hall, Garage, Market and Apartments zones.
- Touch-to-move player controls.
- Wi-Fi hotspot TCP host/join prototype (port 7777), intended for 2–4 devices.
- Host phone: tap **HOST Wi-Fi**. Other phones connect to the same hotspot and tap **JOIN IP**, entering the host phone's local IP.

## Important limitations
- This is a starter prototype, not a finished commercial game.
- Wi-Fi multiplayer is a basic position-sync prototype and needs testing/refinement on real Android devices.
- Bluetooth multiplayer is **not implemented yet**. Android Bluetooth RFCOMM requires device discovery, runtime permission handling and a separate transport layer; it is not safe to claim it works in this starter.
- The project source is provided; an APK has not been compiled or signed here.

## Build
1. Install Android Studio (current stable) on a computer.
2. Open this folder as an existing Gradle project.
3. Let Gradle sync, then build/run on Android devices.
4. For release, create a signed APK from **Build > Generate Signed Bundle / APK**.

## Next development milestones
1. Add proper authoritative host state and player slots for 4 players.
2. Add Bluetooth RFCOMM transport and Android 12+ runtime permission flow.
3. Add vehicles, jobs, inventory, money, roleplay interactions, save/load and improved art.
