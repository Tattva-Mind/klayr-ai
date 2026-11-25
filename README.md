# Klayr

> The answer, before you finish nodding.

Klayr is an AI interview co-pilot for your desktop. It listens to your live interview, shows a short, accurate answer in your own voice (about two seconds after the question), and keeps your resume in mind so answers use your real projects and numbers.

**Website:** [klayr.tattvamind.com](https://klayr.tattvamind.com) · **Status:** Beta (Mac and Windows)

---

## Download

Get the latest build from the [Releases](../../releases) page. Beta versions are marked **Pre-release**.

| Platform | File |
|----------|------|
| macOS, Apple Silicon (M1 or later) | `KlayrAI_x.x.x_aarch64.dmg` |
| macOS, Intel | `KlayrAI_x.x.x_x64.dmg` |
| Windows (recommended) | `KlayrAI_x.x.x_x64-setup.exe` |
| Windows (managed or enterprise installs) | `KlayrAI_x.x.x_x64_en-US.msi` |
| Linux | `.AppImage` or `.deb` |

Exact file names can differ slightly between versions; pick the one that matches your system.

---

## Install

Beta builds are not code-signed yet, so macOS and Windows ask you to confirm the first launch once. It is safe to continue.

### macOS

1. Open the `.dmg` and drag **KlayrAI** to **Applications**.
2. If macOS says the app cannot be verified or is damaged, right-click the app and choose **Open**, or go to **System Settings → Privacy & Security** and click **Open Anyway**.
3. Alternatively, run this once in Terminal:
   ```
   xattr -cr /Applications/KlayrAI.app
   ```
4. Allow **Microphone** and **Screen Recording** when asked.

### Windows

1. Run the installer.
2. If you see **Windows protected your PC**, click **More info → Run anyway**.
3. Allow microphone access when asked.

### Linux

```
chmod +x KlayrAI_*.AppImage
./KlayrAI_*.AppImage
```

---

## What it does

- **Live answers:** hears the interviewer through your system audio and streams an answer as soon as the question ends.
- **Your resume, your voice:** answers draw on your resume and the job description. Stories that are not in your resume are clearly tagged.
- **Interview types:** software engineering, behavioral, coding, system design, data science and product management.
- **Coding questions:** working code with honest complexity, plus a built-in code runner.
- **System design:** structured answers with diagrams.
- **Floating panel:** a small always-on-top window for quick questions during a call.
- **Screen scan:** reads a question off your screen when it is not spoken.
- **Practice mode:** mock interviews with a score and feedback after each round.
- **Session history:** replay past sessions, with analytics.
- **Light and dark themes.**

Klayr provides the AI. There is no API key to set up.

---

## Pricing

Your first hour is free. After that you can subscribe to **Pro** (12 hours of live sessions per month) or buy one-time credit packs that never expire. 1 credit is 1 minute of live session. Current prices are on the [pricing page](https://klayr.tattvamind.com/pricing).

---

## Privacy

Klayr streams live interview audio to a speech-to-text provider (Deepgram) and sends transcript text, screen content you scan, and your resume and job text to AI providers to write answers. Account and usage data are stored on AWS. We do not sell your data. Read the details in the [Privacy Policy](https://klayr.tattvamind.com/privacy) and [Terms](https://klayr.tattvamind.com/terms). You are responsible for following the rules of your interviewer and employer and the laws on recording where you are.

---

## Requirements

- macOS 13 or later, Windows 10 or later (64-bit), or a recent 64-bit Linux desktop
- An internet connection
- A Klayr account (email, Google or LinkedIn)

---

## Updates

Klayr checks for updates automatically and installs them when you approve.

---

## Support

Questions or bugs: see [klayr.tattvamind.com/support](https://klayr.tattvamind.com/support) or email [support@tattvamind.com](mailto:support@tattvamind.com). Please include your Klayr version, operating system, and the steps that led to the problem.

---

*Built by [Tattva Mind](https://github.com/Tattva-Mind)*
