# Screen Zoom Recorder — Free Screen Recorder for Windows 10 & 11 with Audio, Webcam, and Auto-Zoom

**The free screen recorder for Windows that records your screen with audio, webcam overlay, click and keystroke sound effects, watermark, and automatic cinematic zoom on every mouse click. No time limit. No watermark on your recordings. No subscription. No login. No cloud upload.**

Screen Zoom Recorder is a lightweight Windows screen recording app for creators, teachers, developers, gamers, and support teams who need to record their PC screen fast and get a polished MP4 out the door. Capture any monitor or region at up to 60 FPS, encode with H.264 or H.265 hardware acceleration (NVIDIA NVENC, Intel QuickSync, AMD AMF), layer in microphone and system audio, add a webcam picture-in-picture, and draw on the screen live — all in one open Windows app. If you have been searching for a free Loom alternative, an OBS alternative for tutorial videos, or a Camtasia alternative without the price tag, this is built for you.

---

## Download

**[Download the latest installer for Windows 10 or Windows 11 (64-bit)](../../releases/latest)**

No .NET runtime install required. FFmpeg is bundled inside the installer, so the first launch works completely offline.

*After download, if Windows SmartScreen shows "Windows protected your PC", click "More info" then "Run anyway". The installer is safe — it is simply not yet code-signed.*

---

## Screenshots

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/7f96fb07-5dec-4e5e-b3b4-b1ae29af8c0e" alt="Free screen recorder for Windows - Record tab with monitor and region picker" width="480"></td>
    <td><img src="https://github.com/user-attachments/assets/7fca1c91-5e31-4342-b119-605e76669550" alt="Screen recorder with auto zoom on mouse clicks and keystrokes" width="480"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/edb34e4e-7bcd-4852-b397-d29e3f0783be" alt="Screen recorder with audio and webcam overlay settings" width="480"></td>
    <td><img src="https://github.com/user-attachments/assets/61c59a65-bf41-4217-a1a6-b94f8e1b8082" alt="Windows screen recorder H.264 H.265 NVENC QuickSync encoder options" width="480"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/ed502414-ce8c-4e8b-a0df-416b2dd294cc" alt="Screen recorder with watermark and live on-screen preview" width="480"></td>
    <td><img src="https://github.com/user-attachments/assets/b4f43a61-c9ef-4665-9a21-49d1c062146b" alt="Recent screen recordings library - play trim export GIF" width="480"></td>
  </tr>
</table>

---

## Why choose Screen Zoom Recorder

Most free screen recorders for Windows give you a rectangle and a red button. Screen Zoom Recorder adds the polish that normally requires post-production editing:

- **Auto-zoom screen recorder** — the frame gently zooms in on your cursor when you click or type, then eases back out when you pause. Viewers see exactly what you clicked without you saying "over here on the left."
- **Record screen with audio and click sounds** — every mouse click and keystroke gets a natural-sounding audio cue mixed into the final MP4. Your screencasts sound like they were made in a studio.
- **Screen recorder with webcam and watermark** — dial in webcam PIP size and watermark position on the real screen before you hit record. No guessing, no re-shoots.
- **No time limit, no watermark, no login** — record for as long as your disk allows. Your video is yours.
- **Fast workflow** — one global hotkey to start (`Ctrl + Alt + R`), one to stop, one to draw on screen, one to mark chapters for your YouTube description.

---

## Features

### Screen recording

- Record any connected monitor, a custom rectangular region, or a single window area
- Frame rate: 15, 24, 30, or 60 FPS — great for 60fps gameplay recording as well as standard tutorials
- GDI capture (default, reliable on every Windows PC) or DXGI Desktop Duplication (lower CPU, faster refresh, ideal for game recording)
- Countdown timer before recording starts (0, 3, 5, or 10 seconds)
- Pause and resume mid-recording without splitting the file
- Chapter markers written to a sidecar `.chapters.txt` file — paste straight into a YouTube video description for auto-chapters

### Auto-zoom on clicks and typing

- Smooth ease-in and ease-out (no jarring snaps)
- Cursor-tracking soft-follow keeps focus on what your mouse is doing
- Adjustable zoom strength (up to 3.0x)
- Debounced so rapid clicks in the same area don't cause zoom flicker
- Manual override toggle with `Ctrl + Q`
- Turn auto-zoom off entirely for a flat recording

### Record screen with audio

- Record microphone (any DirectShow input device — USB mic, headset, laptop mic)
- Record system audio / desktop sound (via Stereo Mix or the free virtual-audio-capturer driver)
- Synthesized mouse click sound layered onto every click
- Synthesized keystroke sound with 10 natural variants (or drop in your own MP3 samples)
- Audio test button records a 2.5-second sample and shows the peak dB level

### Webcam picture-in-picture (PIP)

- Use any USB webcam or built-in laptop camera
- Rounded, circle, or square shape
- Adjustable size (120 px to 500 px) and opacity (30% to 100%)
- Dock to any corner
- Live on-screen preview before recording so you can position it precisely

### Watermark

- Burn any PNG or JPG logo into every video frame
- Adjustable corner, size (5% to 30% of frame width), and opacity (10% to 100%)
- Live preview so you can position it before hitting record
- Ideal for branding tutorials, product demos, or protected content

### On-screen annotation and drawing tool

- Press `Ctrl + Shift + A` from any app to enter drawing mode
- Tools: pen, arrow, rectangle, highlighter
- 5 color presets (number keys `1`–`5`)
- Strokes auto-fade after 3 seconds so annotations don't clutter the frame
- Undo (`Ctrl + Z`), clear all (`C`), exit (`Esc`)

### Video encoder and quality

- Codecs: H.264 (widest compatibility, plays everywhere) or H.265 / HEVC (smaller file size)
- Hardware accelerated encoding: NVIDIA NVENC, Intel QuickSync, AMD AMF — auto-detected with a real 1-frame test on your GPU
- Software fallback: libx264 / libx265 if no supported GPU is available
- Quality presets: Low, Medium, High, Lossless
- MP4 container with AAC audio — plays in every browser, media player, and video editor

### Screenshot tool

- One-click full-screen or region capture
- Optional 3-second delay for menus, hover states, or tooltips
- Copy directly to clipboard or save as PNG

### Recent recordings library

- Last 8 recordings shown on the main window
- One-click: Play, Show in folder, Export as animated GIF, Trim start and end
- Dead entries (deleted files) auto-cleaned on launch

### System tray icon

- Start / stop recording without opening the main window
- Quick screenshot
- Enter annotation mode
- Show / hide main window
- Exit

### Privacy and settings

- All settings saved locally to `%AppData%\ScreenZoomRecorder\settings.json`
- Remembers your last monitor, quality preset, webcam config, output folder, watermark, and audio choices
- Nothing sent to the internet. No account. No analytics. No telemetry. No cloud upload.

---

## Perfect for

- **Recording YouTube tutorial videos** — auto-zoom, chapter markers, and burned-in click sounds make your tutorials look professionally edited without a second pass in a video editor
- **Recording online meetings** — record a Zoom meeting, record a Google Meet, record a Microsoft Teams call, or record any web-based conference (host permission required per platform's rules)
- **Making software demos and product walkthroughs** — the classic use case, made faster by the automatic cursor zoom
- **Recording online courses and lectures** — teachers, trainers, and Udemy / Skillshare / Teachable creators
- **Recording gameplay** — capture at 60 FPS with GPU-accelerated H.265 for smaller files at high visual quality
- **Making bug reports and support videos** — quick capture with a system-tray shortcut, no full app launch needed
- **Recording webinars and presentations** — with webcam PIP so your face is on screen the whole time
- **Classroom and remote-teaching recordings** — draw on screen live to highlight what students should focus on
- **Screencast recording for documentation** — export short clips as animated GIFs for embedding in READMEs, wikis, or bug tickets
- **Voice-over screen recording** — separate microphone track lets you narrate over the action

---

## How to record your screen on Windows 10 or Windows 11

1. **Launch Screen Zoom Recorder** from your Start Menu.
2. On the **Record** tab, pick your monitor. To record only part of the screen, click **Region** and drag a rectangle. Choose your FPS — 30 for most tutorials, 60 for gameplay or motion-heavy content.
3. On the **Effects** tab, keep **Auto Zoom** on for a cinematic tutorial look, or turn it off if you want a plain flat recording.
4. On the **Audio & Video** tab, tick **Record Mic** and pick your microphone. Tap **Test** and speak — the peak dB meter should light up green.
5. To record system audio (desktop sound, browser tabs, game audio), tick **Record System Audio**. This needs Stereo Mix or virtual-audio-capturer enabled (see requirements below).
6. Optional: enable **Webcam** and pick your camera. Adjust size, shape (rounded / circle / square), and opacity from the live preview.
7. Optional: enable **Watermark** and pick a PNG or JPG logo. Position it in the live preview.
8. Choose your **Output** folder. This is where your MP4 will be saved.
9. Press the big red **Start Recording** button, or hit `Ctrl + Alt + R` from any app.
10. The main window minimizes and a floating recording indicator appears in the corner.
11. Click, type, talk. Auto-zoom follows automatically.
12. Press `Ctrl + Alt + R` again (or click stop on the indicator) to finish. Your MP4 opens in your chosen folder.

That is the entire workflow. Chapter markers (`Ctrl + M`), on-screen annotation (`Ctrl + Shift + A`), and screenshots are all optional add-ons.

---

## Keyboard shortcuts

| Action | Shortcut |
|---|---|
| Start / stop screen recording (global) | `Ctrl + Alt + R` |
| Enter on-screen annotation mode (global) | `Ctrl + Shift + A` |
| Toggle auto-zoom manually | `Ctrl + Q` |
| Pause / resume recording | `Ctrl + P` |
| Mark chapter (writes to `.chapters.txt`) | `Ctrl + M` |

### Annotation mode extras

| Key | Action |
|---|---|
| `P` / `A` / `R` / `H` | Switch tool (Pen / Arrow / Rectangle / Highlighter) |
| `1` – `5` | Switch color |
| `Ctrl + Z` | Undo last stroke |
| `C` | Clear canvas |
| `Esc` | Exit annotation mode |

---

## System requirements

| Requirement | Details |
|---|---|
| Operating system | Windows 10 (build 1809 or later) or Windows 11, 64-bit |
| Processor | Any x64 CPU from the last decade. Hardware video encoding is used automatically when available. |
| Memory | 4 GB RAM minimum, 8 GB recommended for 60 FPS or 4K capture |
| Storage | ~350 MB for the app, plus space for your recordings (roughly 100 MB per minute at 1080p 30 FPS High quality) |
| .NET runtime | Not required — bundled inside the installer |
| FFmpeg | Not required — bundled inside the installer |
| Internet | Not required for recording. Used only as a fallback if the bundled FFmpeg file is deleted. |

### How to enable system audio recording on Windows

Windows does not expose desktop audio to apps by default. Enable one of:

- **Stereo Mix** — right-click the speaker icon in the system tray, open Sound settings, and enable Stereo Mix under Recording devices. Some sound drivers hide this — check your sound card / laptop manufacturer if it is missing.
- **Virtual audio capturer** — install the free `virtual-audio-capturer` driver. Works on every Windows PC and is the same approach most streaming apps use.

Microphone recording works out of the box on every Windows PC.

---

## FAQ

### Is this a free screen recorder for Windows?

Yes. Screen Zoom Recorder is completely free to download and use. There is no trial period, no subscription, no login, no cloud account, and no watermark burned into your recordings.

### Is there a screen recorder with no time limit for Windows?

Yes — Screen Zoom Recorder has no recording time limit. Record as long as you have disk space.

### Does the free version add a watermark to my videos?

No. Your MP4 recordings never carry a Screen Zoom Recorder watermark. You can optionally add your own logo watermark, but that is your choice.

### How do I record my screen on Windows 10 or Windows 11 with audio?

Install Screen Zoom Recorder, open the Audio & Video tab, tick **Record Mic** (and optionally **Record System Audio**), then press `Ctrl + Alt + R` or the red Start Recording button. See the step-by-step above.

### Can I record my screen with a webcam overlay?

Yes. Enable **Webcam** on the Audio & Video tab, pick your camera, and adjust size, shape, and opacity. Position it with the live preview before recording.

### How do I record a Zoom meeting on Windows?

Start Screen Zoom Recorder, pick the monitor Zoom is running on (or draw a region around the Zoom window), enable microphone and system audio, then hit `Ctrl + Alt + R`. Make sure you have permission to record — check Zoom's and your organization's policies first.

### How do I record a Google Meet or Microsoft Teams call?

Same as Zoom — Screen Zoom Recorder captures the screen regardless of which meeting app you are in. Enable system audio to capture what other participants say. Always follow platform terms of service and your organization's recording policy.

### Can I record online classes and lectures?

Yes. Use the Region picker to draw a rectangle around the video area, enable system audio to capture the teacher's voice, and start recording. Chapter markers are handy for jumping to sections later.

### Can I record gameplay in 60 FPS?

Yes. Set the FPS to 60 on the Record tab and choose the H.264 or H.265 hardware encoder (NVENC / QuickSync / AMF) for smooth low-CPU capture.

### What video format does the screen recorder save?

MP4 container with H.264 (widely compatible) or H.265 / HEVC (smaller file size) video and AAC audio. MP4 plays in every browser, media player, and video editing app (DaVinci Resolve, Premiere Pro, Shotcut, CapCut, etc.).

### How much disk space do recordings use?

Rough guide at 1080p 30 FPS: Low ~30 MB per minute, Medium ~60 MB, High ~100 MB, Lossless ~500 MB. 4K and 60 FPS scale up proportionally.

### Can I record 4K screen?

Yes if your monitor is 4K — Screen Zoom Recorder captures your monitor at native resolution. Use a hardware encoder (NVENC / QuickSync / AMF) for smooth 4K performance.

### Can I edit the video after recording?

The Recent library has a Trim button that lets you cut the start and end without re-encoding. For deeper editing, open the MP4 in any editor (DaVinci Resolve, Adobe Premiere Pro, Shotcut, CapCut, iMovie for Mac, etc.).

### Can I export a screen recording as an animated GIF?

Yes — from the Recent library, click Export GIF next to any recording. Great for embedding short clips in READMEs, bug tickets, Slack messages, or product docs.

### Does it work offline?

Yes. The installer bundles everything including FFmpeg. Zero internet required for recording or playback.

### Does it collect any data or send telemetry?

No. Nothing is sent to the internet. No analytics. No crash telemetry. No account. Your recordings never touch a server unless you upload them yourself.

### Which GPUs support hardware-accelerated encoding?

- **NVIDIA** — GTX 600 series or newer supports NVENC
- **Intel** — 2nd-gen Core (Sandy Bridge) or newer with integrated graphics enabled supports QuickSync
- **AMD** — Radeon HD 7000 series or newer supports AMF / VCE

If no hardware encoder is available, the app automatically falls back to libx264 / libx265 software encoding, which uses more CPU but works on any Windows PC.

### Where are recordings saved?

In the folder you choose on the Record tab. Defaults to your Windows `Videos` folder.

### Where are settings stored?

At `%AppData%\ScreenZoomRecorder\settings.json`. Delete that file to reset everything to defaults.

### How do I uninstall Screen Zoom Recorder?

Settings → Apps → Installed apps → Screen Zoom Recorder → Uninstall. To also wipe saved settings, delete the folder `%AppData%\ScreenZoomRecorder`.

### Why does Windows warn me when I install the app?

The installer is not yet code-signed with an Authenticode certificate. Click "More info" then "Run anyway". Code signing is planned for a future release.

### Is it a Loom alternative? Or an OBS / Camtasia alternative?

Yes to all three, with different strengths:

- **Loom alternative** — Loom is subscription-based, cloud-first, and has recording length limits on the free tier. Screen Zoom Recorder is fully free, fully local, and has no time limit or account.
- **OBS Studio alternative** — OBS is amazing for livestreaming but has a steep learning curve for basic tutorial recording. Screen Zoom Recorder is a one-window app that hides the complexity while still using the same underlying FFmpeg + hardware encoders.
- **Camtasia alternative** — Camtasia costs hundreds of dollars and is really a full video editor. Screen Zoom Recorder focuses on recording plus lightweight trim / GIF export. Pair it with any free video editor for full editing.
- **Bandicam / Screencastify / ShareX alternative** — see the comparison table below.

---

## Screen Zoom Recorder vs. other screen recorders

| Feature | Screen Zoom Recorder | OBS Studio | Loom | Camtasia | ShareX | Bandicam | Xbox Game Bar |
|---|---|---|---|---|---|---|---|
| Fully free | Yes | Yes | Free tier limits | Paid | Yes | Free trial only | Yes |
| No watermark on recordings | Yes | Yes | Free tier limit | Yes (paid) | Yes | Watermark on free | Yes |
| No recording time limit | Yes | Yes | Free tier limits | Yes | Yes | Watermarked after time | Yes |
| Auto-zoom on clicks | **Yes** | No | No | Yes (post) | No | No | No |
| Click and key sound FX | **Yes (synth)** | No | No | Add manually | No | No | No |
| Webcam PIP overlay | Yes | Yes | Yes | Yes | No | Yes | No |
| Live watermark burn-in | Yes | Yes | No | Yes | No | Yes | No |
| On-screen annotation | Yes | No | Basic | Yes | Partial | Yes | No |
| Chapter markers for YouTube | Yes | No | No | No | No | No | No |
| One-click GIF export | Yes | No | Via cloud | No | Yes | No | No |
| Hardware encoding (NVENC / QSV / AMF) | Yes | Yes | Cloud-side | Yes | No | Yes | Yes |
| Fully offline, no account | Yes | Yes | No | Yes | Yes | Yes | Yes |
| Learning curve | Low | High | Low | Medium | Medium | Low | Low |
| Best for | **Tutorial creators** | Livestreamers | Async work videos | Full-featured video editing | Screenshot power users | Gameplay clips | Casual Xbox / gameplay |

Screen Zoom Recorder is not trying to replace OBS for livestreaming or Camtasia for full video editing. It is optimized for one thing — recording polished tutorial and demo videos on Windows, fast, for free.

---

## Support and updates

- Report bugs and request features: [open a GitHub issue](../../issues)
- Version history and download all releases: [releases page](../../releases)

---

## License

Screen Zoom Recorder is proprietary software distributed under the license terms shown in the installer.

The bundled `ffmpeg.exe` is a separate program licensed under GPL v3+. It is invoked by Screen Zoom Recorder as a child process (no library linking, no source code incorporation). The two are distributed as an aggregate in the same installer. Full attribution, source pointer, build metadata, and SHA-256 of the bundled FFmpeg binary are in `THIRD_PARTY_NOTICES.txt` inside your installed folder.

---

<sub>Keywords: screen recorder Windows 10, screen recorder Windows 11, free screen recorder, screen recorder no watermark, screen recorder with audio, screen recorder with webcam, record screen with sound, screen recording software for PC, best free screen recorder, HD screen recorder, 4K screen recorder, 60fps screen recorder, tutorial screen recorder, gameplay recorder, screencast software, Windows screen capture, desktop recorder, MP4 screen recorder, H.264 H.265 HEVC recorder, NVENC screen recorder, QuickSync recorder, Loom alternative, OBS alternative, Camtasia alternative, Bandicam alternative, Screencastify alternative, ShareX alternative, record Zoom meeting, record Google Meet, record Microsoft Teams, record online class, record webinar, YouTube tutorial recorder, auto zoom screen recorder, screen recorder with annotation, screen recorder with click sounds.</sub>
