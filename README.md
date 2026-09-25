# StickS3 Apple FindMy & Proximity Alarm Dashboard

Web Dashboard and Bluetooth LE controller for M5StickS3 running custom firmware with Apple FindMy OpenHaystack tracking and Immediate Alert hardware speaker alarm.

## Features
- **Apple FindMy Network Tracking**: Multilateration map showing real-time and historical Apple crowdsourced location fixes.
- **Audible Speaker Alarm**: Connects wirelessly via Web Bluetooth (Immediate Alert Service `0x1802` / `0x2A06`) to trigger the M5StickS3 internal speaker at maximum volume (`M5.Speaker.setVolume(255)`) with an authentic Apple AirTag chirp sound.
- **Silence On-Device or via Web**: Alarm can be stopped from the web interface or by pressing the front M5 button on the device.
- **Mobile & Desktop Support**:
  - Desktop Chrome / Edge / Brave: Web Bluetooth works natively.
  - iPhone / iPad (iOS): Open via the free [Bluefy Web BLE Browser](https://apps.apple.com/app/bluefy-web-ble-browser/id1492822055) to ring the device directly from your phone.

## Cryptographic Parameters
- **Private Key**: `WUTz8AmIiCKpgsOJjKr6W6+YWnEcCIymolCQzw==`
- **Advertisement Key**: `j/VpdVOqpfmnIoMQ1eZhOS+9WP2SGhUUUd9aUw==`
- **Hashed Adv Key**: `d2u7Ws16DlqMMDWVxx1fOxJYzjQbIsR4sb4hqm/lxqo=`
- **BLE MAC Address**: `CF:F5:69:75:53:AA`
