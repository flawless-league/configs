# Flawless Configs

This repository contains game configuration files for Urban Terror, specifically designed for playing, streaming and recording games in the **Flawless League**.

## Overview

These configs are optimized for official content creation:
- **Server Config**: Game config for official Flawless League games (TS & CTF)
- **Streaming Config**: For streamers broadcasting official league games
- **Recording Config**: For creating official videos and highlights

## Installation & Usage

### Server Config Setup

1. **Configs are available on FTW servers automatically and can be executed via this command:**
   ```
   /rcon exec flawless_ts
   /rcon exec flawless_ctf
   ```

1. **Backup your current config** (important - settings may be overwritten!)
   ```
   Copy your existing q3config.cfg / autoexec.cfg to a safe location
   ```

2. **Install the config file**
   - Copy `fl-config-recording.cfg` to your `UrbanTerror/q3ut4/` folder

3. **Install FFmpeg**
   - Place `ffmpeg.exe` in your `UrbanTerror` root folder (same level as the game executable)

4. **Apply the config in-game**
   - Start Urban Terror
   - Open the console (usually `~` key)
   - Execute: `/exec fl-config-recording.cfg; vid_restart`

### Streaming Config Setup
The streaming config will follow the same installation process once available.

## Key Features

### Recording Config Features
- **High-quality recording settings**: 360 FPS capture with optimized encoding
- **Timescale controls**: Keybinds for slow-motion and time manipulation (Z/X/C/V/B/N/M keys)
- **Recording controls**: Start recording (9 key), Stop recording (0 key)
- **Optimized visuals**: Enhanced graphics settings for better video quality
- **Clean HUD**: Minimal interface for professional-looking recordings
- **Screenshot capability**: P key for quick screenshots

## Controls (Recording Config)

| Key | Function |
|-----|----------|
| `9` | Start recording |
| `0` | Stop recording |
| `P` | Take screenshot |
| `Z` | Pause time (timescale 0) |
| `X` | 0.5x speed |
| `C` | Normal speed |
| `V` | 3x speed |
| `B` | 10x speed |
| `N` | 50x speed |
| `M` | 100x speed |
