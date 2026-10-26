# Pixelbike

A retro side-scrolling motocross racer. Ride the USA Circuit: ten city tracks, four rivals, and a points season that crowns a champion.

Play at [pixelbike.meckman.org](https://pixelbike.meckman.org).

## Controls

- **Gas:** Z
- **Turbo:** X (faster, but it heats the engine; overheat and it stalls)
- **Change lanes:** ↑ ↓
- **Tilt in the air:** ← → (land level with the track)
- **Start / continue:** Space
- **Quit to title:** Esc

A keyboard is required.

## The season

Ten rounds, raced in order: Los Angeles, Phoenix, Denver, Dallas, Houston, Atlanta, Miami, New York, Chicago, and a night finale in Las Vegas. Points go 25, 20, 16, 13, 11 for 1st through 5th; ties go to whoever has more wins.

The rivals each ride differently: DUSTY is fast and steady, SPIKE is a solid all-rounder, ACE is slower but almost never misses a landing, and VIPER is fast but wild.

## Riding tips

- Gas alone will not keep up. Use turbo in bursts and watch the TEMP gauge.
- Clean landings give a speed boost and cool the engine. Rough landings cost speed; bad ones crash you.
- Running into the back of another bike crashes you. Cutting off a faster rider crashes them.
- Mud slows you down. Change lanes to ride around it.

## Tech

One HTML file: canvas graphics, a 3x5 pixel font, and Web Audio sound (including a synthesized single-cylinder engine with a six-speed gearbox). No frameworks, no assets, no build step.

## Deploy

Static site served as a Cloudflare Worker assets bundle.

```
wrangler deploy
```
