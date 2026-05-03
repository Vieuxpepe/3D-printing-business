# A1 Mini OctoEverywhere Monitoring Setup

## Purpose

Create a future setup for **AI-assisted spaghetti / failure detection** on the **Bambu Lab A1 mini** using **OctoEverywhere Bambu Connect**.

This note exists so the setup idea is easy to recover later without needing to search old conversations.

## Current idea

Use the existing **Raspberry Pi Zero 2 WH** as the always-on device running Bambu Connect, and use a **TP-Link Tapo C200** as the external camera over Wi-Fi / RTSP.

The goal is to improve monitoring beyond the A1 mini built-in camera, especially for miniature printing where small support failures, lifted bases, and spaghetti can be hard to see from the stock camera angle.

## Hardware already considered

| Item | Status | Notes |
|---|---:|---|
| Bambu Lab A1 mini | Already owned | Main printer to monitor |
| Raspberry Pi Zero 2 WH | Already owned | Should be usable for Bambu Connect |
| TP-Link Tapo C200 camera | Already considered | Wi-Fi camera, should be usable through RTSP |
| Home Wi-Fi network | Needed | Printer, Pi, and camera should be on the same local network |

## Important clarification

The **Raspberry Pi Zero 2 WH has built-in Wi-Fi**.

The `W` means Wi-Fi / Bluetooth, and the `H` means the header pins are pre-soldered.

So the Pi does **not** need Ethernet or a USB Wi-Fi dongle for this setup.

## What still needs to be available

| Item | Needed? | Notes |
|---|---:|---|
| microSD card | Yes | 32 GB is a good simple choice |
| micro USB power supply | Yes | Use a stable 5V supply |
| Pi case or printed holder | Recommended | Keeps the Pi protected |
| Camera mount for A1 mini area | Recommended | Can be 3D printed |
| Extra lighting | Optional | Helpful for reliable camera detection |
| USB OTG adapter | Not needed for Tapo C200 | Only needed if using a USB webcam instead |

## Why the Tapo C200 is useful here

The Tapo C200 is not a USB webcam. It is a **Wi-Fi IP camera**.

That means it does not plug into the Pi. Instead, the Pi, printer, and camera communicate through the local network.

Expected setup:

```text
A1 mini  -> Wi-Fi/router
Pi Zero 2 WH running Bambu Connect -> Wi-Fi/router
Tapo C200 camera -> Wi-Fi/router
OctoEverywhere -> connected through Bambu Connect
```

## Camera stream idea

The Tapo C200 should be configured through its app first, then added as an RTSP camera if supported in the OctoEverywhere / Bambu Connect setup.

Common RTSP format to try later:

```text
rtsp://CAMERA_USERNAME:CAMERA_PASSWORD@CAMERA_IP/stream1
```

Lower-quality backup stream:

```text
rtsp://CAMERA_USERNAME:CAMERA_PASSWORD@CAMERA_IP/stream2
```

Use `stream1` first for better image quality. Use `stream2` if the Pi or network struggles.

## Recommended setup order

1. Prepare the Raspberry Pi Zero 2 WH with a fresh microSD card.
2. Connect the Pi to the same Wi-Fi network as the A1 mini.
3. Install and configure OctoEverywhere Bambu Connect on the Pi.
4. Link Bambu Connect to the A1 mini.
5. Confirm that printer status and remote access work first.
6. Set up the Tapo C200 normally in the Tapo app.
7. Enable / configure the camera account needed for RTSP access.
8. Reserve the camera IP address in the router if possible.
9. Add the RTSP stream to the OctoEverywhere external camera setup.
10. Test AI failure detection with a harmless print before relying on it.

## Camera placement for miniature printing

Best first placement:

- Front-left or front-right of the printer
- Slightly above the build plate
- Angled downward toward the nozzle and print surface
- Close enough to see small support failures
- Far enough to see the whole plate

Avoid placing the camera too high. A lower side angle usually catches spaghetti, lifted supports, and failed bases better than a top-down angle.

## Practical recommendation

Start with the hardware already available:

```text
A1 mini + Pi Zero 2 WH + Tapo C200
```

Do not buy a Raspberry Pi 4 immediately.

Only upgrade later if the Pi Zero 2 WH feels unstable, too slow, or has trouble handling the camera stream.

## Security notes

- Keep the RTSP camera stream local to the home network.
- Do not expose the camera directly to the internet.
- Use a unique camera username and password.
- Prefer router DHCP reservation instead of hardcoding random IPs everywhere.

## Future upgrades if needed

| Upgrade | Why |
|---|---|
| Raspberry Pi 4 | More performance and easier USB camera support |
| USB webcam | Simpler direct camera setup if RTSP becomes annoying |
| Better camera mount | More reliable view of miniature failures |
| LED light strip | Helps AI detection by improving visibility |
| Smart plug | Optional power-control workflow, only if safe and properly configured |

## Decision summary

This setup is worth trying because it reuses existing hardware and avoids buying unnecessary parts.

The likely best path is:

```text
Test Pi Zero 2 WH + built-in A1 mini camera first.
Then add Tapo C200 via RTSP for better spaghetti detection.
Only upgrade hardware if the setup is unreliable.
```
