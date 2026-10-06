```text
HELL                             O WORLD
```

- 👋 Hi, I’m @FlyingFathead
- 👀 I’m interested in Neural Networks.
- 🌱 I’m currently learning lessons in futility.
- 💞️ I’m looking to collaborate on watching pain dry.
- 📫 How to reach me ... by smoke signals from the server room.

---

# Harry Horsperg

AI/ML developer, sysadmin, audiovisual tinkerer, retrocomputing enthusiast and technical writer.

I have been building the Finnish **FennoGPT** language model since 2020 and founded the **ChatKeke** framework in 2023. AI and neural-network work are central to my field, but I also build retrocomputing tools, statistical simulations, audiovisual software, games, graphics experiments, server automation and whatever other technical debris happens to accumulate.

Python is my usual go-to, alongside Bash and JavaScript, with **C and QuakeC** now in the mix through **AmiWind**. The **Commodore 64** and **Commodore Amiga** are particular sources of enthusiasm, from **6502/6510 assembly** on the C64 to **Motorola 68k (m68k) assembly** on the Amiga.

## Featured projects

[**AmiWind**](#amiwind) · [**SIDpulse Tracker**](#sidpulse-tracker) · [**c64-3d-toolkit**](#c64-3d-toolkit)

### AmiWind

<p align="center">
  <a href="https://github.com/FlyingFathead/amiwind">
    <img src="https://raw.githubusercontent.com/FlyingFathead/amiwind/main/resources/media/AmiWind_logo_clear_background.png" width="720" alt="AmiWind: a Commodore Amiga demake of Morrowind">
  </a>
</p>

**[AmiWind](https://github.com/FlyingFathead/amiwind)** is an experimental **The Elder Scrolls III: Morrowind demake for the Commodore Amiga**, combining a local asset-conversion pipeline with a native Amiga runtime.

<table>
  <tr>
    <td width="50%" align="center">
      <a href="https://github.com/FlyingFathead/amiwind/blob/main/docs/GAMEPLAY_MEDIA.md">
        <img src="https://raw.githubusercontent.com/FlyingFathead/amiwind/main/docs/images/amiwind-v0.0.24-balmora-bridge.png" width="320" alt="AmiWind v0.0.24: Balmora bridge, captured in FS-UAE">
      </a>
      <br><sub>Balmora bridge · v0.0.24</sub>
    </td>
    <td width="50%" align="center">
      <a href="https://github.com/FlyingFathead/amiwind/blob/main/docs/GAMEPLAY_MEDIA.md">
        <img src="https://raw.githubusercontent.com/FlyingFathead/amiwind/main/docs/images/amiwind-v0.0.28-v3-red-sunset.png" width="320" alt="AmiWind v0.0.28: red sunset over Seyda Neen, captured in WinUAE">
      </a>
      <br><sub>Seyda Neen sunset · v0.0.28</sub>
    </td>
  </tr>
</table>

Python host tools convert the original game's maps, textures, models and audio into Amiga-friendly data. The accelerated AGA runtime draws on **Quake/AmiQuake**, with **C and QuakeC** doing their part in this entirely reasonable undertaking.

The growing playable world includes **Seyda Neen and Balmora**, character creation, map and journal interfaces, foliage, day/night skies and torchlight. Much of the original game's gameplay remains unfinished; this is a work in progress, not a complete Morrowind replacement.

**Bring your own Morrowind game data.** Original game assets and Amiga ROMs are not included in the public source package. The screenshots above show the Amiga runtime in emulation.

> The prophecy said nothing about the frame rate.

[**Repository**](https://github.com/FlyingFathead/amiwind) · [Screenshots and day/night gallery](https://github.com/FlyingFathead/amiwind/blob/main/docs/GAMEPLAY_MEDIA.md) · [Releases](https://github.com/FlyingFathead/amiwind/releases)

---

### SIDpulse Tracker

<p align="center">
  <a href="https://github.com/FlyingFathead/sidpulse-tracker">
    <img src="https://raw.githubusercontent.com/FlyingFathead/sidpulse-tracker/main/sidpulse/assets/sidpulse-tracker-logo.svg" width="640" alt="SIDpulse Tracker logo">
  </a>
</p>

**[SIDpulse Tracker](https://github.com/FlyingFathead/sidpulse-tracker)** is a **Python/pygame-ce desktop music tracker for the Commodore 64 SID**, inspired by the workflow, keyboard feel and pattern-editing philosophy of **Impulse Tracker** and **Schism Tracker**.

<p align="center">
  <a href="https://github.com/FlyingFathead/sidpulse-tracker">
    <img src="https://raw.githubusercontent.com/FlyingFathead/sidpulse-tracker/main/docs/media/sidpulse-f5-playback.gif" width="720" alt="SIDpulse Tracker playing Autumn at Five, with all three SID voice scopes">
  </a>
  <br><sub>Autumn at Five: F5 playback with all three SID voice scopes.</sub>
</p>

The SID is the synthesizer, not an afterthought: **three hardware voices**, ADSR envelopes, pulse-width control, waveforms, filters, synchronization, ring modulation and tracker-style tables, with native **6581/8580 emulation** while composing.

Save editable **`.sidpulse`** projects, export **PSID `.sid`** music or runnable **C64 `.prg`** programs, and render tracks to **WAV or MP3**. PCM sample tools and **sample-to-SID wavetable synthesis** are also included.

> Preserve Impulse Tracker / Schism Tracker muscle memory while making the SID the actual synthesizer underneath.

[**Repository**](https://github.com/FlyingFathead/sidpulse-tracker) · [Watch Autumn at Five with audio](https://github.com/FlyingFathead/sidpulse-tracker/blob/main/docs/media/sidpulse-f5-playback-full.mp4) · [Releases](https://github.com/FlyingFathead/sidpulse-tracker/releases)

---

### c64-3d-toolkit

<p align="center">
  <a href="https://github.com/FlyingFathead/c64-3d-toolkit">
    <img src="https://raw.githubusercontent.com/FlyingFathead/c64-3d-toolkit/main/assets/c64-3d-toolkit_banner.png" width="640" alt="c64-3d-toolkit: Build modern 3D. Fit it in 64K.">
  </a>
</p>

**[c64-3d-toolkit](https://github.com/FlyingFathead/c64-3d-toolkit)** is a host-assisted **3D compiler and runtime for the Commodore 64**, taking OBJ/SVG geometry and Blender-authored scenes from a modern machine to runnable C64 programs and cartridge images.

The host handles geometry processing, animation preparation and hidden-line visibility, then generates **6502/6510 assembly** and precomputed runtime data. The command-line pipeline is the primary interface, with wireframe and shaded output, procedural meshes, VICE integration and multiple rendering strategies.

The general philosophy is to make the modern machine do the expensive work beforehand so the C64 has less suffering left to perform at runtime.

[**Repository**](https://github.com/FlyingFathead/c64-3d-toolkit) · [Examples](https://github.com/FlyingFathead/c64-3d-toolkit/tree/main/examples) · [Releases](https://github.com/FlyingFathead/c64-3d-toolkit/releases)

---

## ChatKeke

**ChatKeke** is my multi-model, multi-API and RAG-enabled AI assistant framework, in service since ~2023. It combines conversational models with real-time information retrieval, speech-to-text, reminders, geolocation, weather, navigation, search and many other tools and functionalities.

- [chatkeke.fi](https://chatkeke.fi) (web version; available inside Finland only)
- [ChatKeke on Telegram](https://t.me/ChatKekeBot)
- [ChatKeke on Discord](https://skrolli.fi/lukijakanavat/) (`#chatkeke`, courtesy of [Skrolli Magazine](https://skrolli.fi))
- [ChatKeke on Discord/Matrix](https://sakulehti.fi/keskustelu) (`#chatkeke`, courtesy of [Saku-lehti](https://sakulehti.fi))
- Public bot framework: [TelegramBot-OpenAI-API](https://github.com/FlyingFathead/TelegramBot-OpenAI-API)

## More projects

This is a curated selection. [Browse all repositories here.](https://github.com/FlyingFathead?tab=repositories)

### Active systems and experiments

| Project | What it does |
| --- | --- |
| **[Mortality Roulette](https://github.com/FlyingFathead/mortality-roulette)** | Statistical mortality simulator and random life-path generator built around official population life-table and cause-of-death data. It is an educational and entertainment simulation, not an individualized prognosis system. |
| **[cassette-calibrator](https://github.com/FlyingFathead/cassette-calibrator)** | CLI-first cassette and signal-chain measurement toolkit with generated reference audio, DTMF markers, drift compensation, ESS response analysis and an optional local WebUI. |
| **[rust-linuxgsm-watchdog](https://github.com/FlyingFathead/rust-linuxgsm-watchdog)** | LinuxGSM watchdog for Rust game servers, with health checks, recovery, server and mod updates, wipe handling, optional Smooth Restarter integration and Telegram alerts. |

### AI and machine learning systems

| Project | What it does |
| --- | --- |
| **[whisper-transcriber-telegram-bot](https://github.com/FlyingFathead/whisper-transcriber-telegram-bot)** | Local GPU/CPU Whisper transcription bot for Telegram, supporting uploaded media, voice messages, `yt-dlp`, selectable models and Docker deployment. No paid transcription API is required. |
| **[TelegramBot-OpenAI-API](https://github.com/FlyingFathead/TelegramBot-OpenAI-API)** | Deployable ChatKeke-related Telegram bot framework with OpenAI and Perplexity APIs, speech-to-text, RAG, web retrieval, reminders, weather, maps, navigation, feeds and usage controls. |
| **[dvr-yolov8-detection](https://github.com/FlyingFathead/dvr-yolov8-detection)** | CUDA-capable YOLOv8–YOLO11 object-detection DVR framework with RTMP and webcam input, GUI and WebUI modes, detection zones, recording, logging and Telegram alerts. |

### Retrocomputing, audiovisual and utility tools

| Project | What it does |
| --- | --- |
| **[audio-bitsqueezer](https://github.com/FlyingFathead/audio-bitsqueezer)** | Converts modern audio into C64-friendly 4-bit packed samples, MSSIAH-compatible 8-bit WAV files or self-contained runnable `.prg` programs. |
| **[catgit](https://github.com/FlyingFathead/catgit)** | Dumps a Git repository or directory tree into a readable consolidated form for inspection, archival or LLM-assisted code review. |
| **[OCR-CopyPastePad](https://github.com/FlyingFathead/OCR-CopyPastePad)** | Tkinter-based OCR copy-paste pad supporting Tesseract, EasyOCR, screenshots, preprocessing and selectable recognition methods. |
| **[Huuda](https://github.com/FlyingFathead/huuda)** | Finnish command-line text-to-speech utility with the questionable additional ability to pronounce English through Finnish phonetics. |
| **[youwhisper-cli](https://github.com/FlyingFathead/youwhisper-cli)** | Single-command `yt-dlp` plus Whisper/WhisperX transcription pipeline for producing plaintext and subtitles from online media. |

### Games

| Project | What it does |
| --- | --- |
| **[Cube Libre: web version](https://github.com/FlyingFathead/cube-libre)** | Browser-based JavaScript/WebGL survival-puzzle game. Guide 125 destructible mini-cubes through rotating laser mazes as time, entropy and heat tighten the rules. Re-couple whatever you can recover. Keyboard and analog controller support. **[Play it here](https://flyingfathead.github.io/cube-libre/)**; no installation needed. |
| **[Cube Libre: PyGame original](https://github.com/FlyingFathead/cube-libre-pygame)** | Original desktop PyGame/OpenGL survival-puzzle game and the starting point for the web version. A destructible cube-body navigates rotating laser mazes. Weirdness and deliberate hostility included. |
| **[Ace of Spades Web Slots](https://github.com/FlyingFathead/aceofspades-slots)** | Tiny and loud browser slot-machine tribute with reel locks, jackpots and old-schoolish noise. **[Play it here.](https://flyingfathead.github.io/aceofspades-slots/)** |

### Smaller experiments and other oddities

- **[RiemannHypothesis](https://github.com/FlyingFathead/RiemannHypothesis)**: numerical scanner and exploratory tools for zeros of the Riemann zeta function. This is empirical computation, not a claimed proof, because I have not completely lost contact with the Earth.
- **[gpt2-tensorflow-to-pytorch-converter](https://github.com/FlyingFathead/gpt2-tensorflow-to-pytorch-converter)**: converts TensorFlow-based GPT-2 model checkpoints into PyTorch format.
- **[neurograph-cli](https://github.com/FlyingFathead/neurograph-cli)**: terminal graph plotter for monitoring TensorFlow and GPT-2 training runs on local or remote machines.
- **Translation tools**: [PDF-translator-OpenAI-API](https://github.com/FlyingFathead/PDF-translator-OpenAI-API) and [srt-translate-OpenAI-API](https://github.com/FlyingFathead/srt-translate-OpenAI-API).

<details>
<summary><strong>Earlier AI, GPT-2 and chatbot work</strong></summary>

The archaeological layers include the original local-TensorFlow [ChatKeke](https://github.com/FlyingFathead/ChatKeke) web chat, [GPT2-Telegram-Chatbot](https://github.com/FlyingFathead/GPT2-Telegram-Chatbot), [gpt2-tensorflow-localchat](https://github.com/FlyingFathead/gpt2-tensorflow-localchat), [neurograph-framework](https://github.com/FlyingFathead/neurograph-framework), [IRC-GPT2-Chatbot](https://github.com/FlyingFathead/IRC-GPT2-Chatbot), [Discord-GPT2-bot](https://github.com/FlyingFathead/Discord-GPT2-bot) and [IRCBot-OpenAI-API](https://github.com/FlyingFathead/IRCBot-OpenAI-API).

</details>

<details>
<summary><strong>Modified upstream projects and patch work</strong></summary>

- **[denoiser](https://github.com/FlyingFathead/denoiser)**: modified Meta/Facebook Research Denoiser fork with CPU, CUDA and multitrack helper scripts plus mix-level control.
- **[generative-models](https://github.com/FlyingFathead/generative-models)**: modified Stability AI generative-models fork with low-VRAM Stable Video fixes, CPU options and FFmpeg output work.

</details>

## Writing

- [Substack](https://harryhorsperg.substack.com/)
- [Medium](https://medium.com/@flyingfathead/)
- [Twitter/X](https://twitter.com/horsperg)
- Additional Finnish-language articles can be found in [Skrolli Magazine](https://skrolli.fi/)

## Contact

- Email: `flyingfathead@protonmail.com`
- GitHub: [@FlyingFathead](https://github.com/FlyingFathead)

<!---
FlyingFathead/FlyingFathead is a special repository because its README.md appears on the GitHub profile.
--->
