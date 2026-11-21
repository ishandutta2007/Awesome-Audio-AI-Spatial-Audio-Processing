# Awesome-Audio-AI-Spatial-Audio-Processing

## Top Audio AI & Spatial Audio Processing Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on AI Speech Enhancement, Real-Time Noise Cancellation, Spatial Audio Engines, Loudness Mastering & Audio Post-Production*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Audio AI & Spatial Audio Processing**. These tools clean, denoise, dereverb, master, spatialize, separate stems, and edit audio streams and recordings using deep neural networks, Ambisonics/HRTF binaural engines, real-time DSP pipelines, and modular audio workstations.



**Examples** include Dolby.io, Descript, Krisp, Auphonic, Cleanvoice AI, Adobe Podcast, LANDR, AudioNodes, Soundop, WavePad, and headroomlabs-ai/headroom (the category leaders and notable community entries). 



**Open-source emphasis**: This section is heavily expanded with every major active project for real-time AI noise suppression (`DeepFilterNet`, `RNNoise`), speech super-resolution (`Resemble Enhance`), spatial/Ambisonics audio engines (`IEM Plug-in Suite`, `Steam Audio`, `Resonance Audio`), source separation (`Demucs`), and multi-track audio editors — ideal for audio engineers, podcasters, game developers, VoIP builders, and AI researchers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Dolby.io](https://dolby.io)**  

  Cloud media and communications API platform offering AI audio enhancement, background noise reduction, dynamic leveling, and spatial audio processing.



- **[Descript (Studio Sound)](https://descript.com)**  

  AI-powered audio and video editor featuring one-click Studio Sound voice isolation, room echo removal, filler-word deletion, and transcript-driven editing.



- **[Krisp](https://krisp.ai)**  

  Real-time AI noise cancellation, voice isolation, and acoustic echo cancellation application and on-device SDK for calls, streaming, and recordings.



- **[Auphonic](https://auphonic.com)**  

  Automated AI audio post-production web service and API providing intelligent leveling, noise/reverb reduction, and broadcast loudness normalization (LUFS).



- **[Cleanvoice AI](https://cleanvoice.ai)**  

  Cloud-based AI podcast editing tool engineered to automatically remove filler words, mouth sounds, breath noises, and dead air across multiple languages.



- **[Adobe Podcast (Enhance Speech)](https://adobe.com)**  

  Browser-based AI voice restoration and audio enhancement platform transforming noisy or echo-heavy speech recordings into studio-grade vocal tracks.



- **[LANDR](https://landr.com)**  

  Cloud-based AI audio mastering, stem separation, and music distribution platform delivering automated EQ, compression, and loudness optimization.



- **[AudioNodes](https://www.audionodes.com/)**  

  Browser-based and desktop modular synthesizer and digital audio workstation (DAW) featuring a visual node patcher, multi-track timeline, and real-time audio effects.



- **[Soundop](https://soundop.com)**  

  Windows audio editor and multitrack workstation combining spectral editing, batch processing, VST/VST3 plugin hosting, and precision mastering tools.



- **[WavePad (NCH Software)](https://nch.com.au)**  

  Cross-platform audio and music editing software offering spectral analysis, noise reduction, batch processing, and DirectX/VST effect chains.





## Open-Source GitHub Projects



- **[DeepFilterNet](https://github.com)**  

  Low-complexity, real-time open-source deep learning framework for full-band (48 kHz) speech enhancement and background noise suppression with Rust/Python and LADSPA/PipeWire plugin support.



- **[Resemble Enhance](https://github.com)**  

  Open-source AI speech denoising and audio super-resolution toolkit that removes background noise and restores high-frequency vocal clarity up to 44.1 kHz.



- **[RNNoise](https://github.com)**  

  Lightweight open-source recurrent neural network noise suppression library in C by Xiph.Org, widely embedded in VoIP, WebRTC, and OBS Studio audio pipelines.



- **[Demucs (Meta Research)](https://github.com)**  

  State-of-the-art open-source hybrid Transformer/waveform music and vocal source separation engine for isolating vocals, drums, bass, and stems.



- **[IEM Plug-in Suite](https://github.com)**  

  Comprehensive open-source collection of spatial audio and Higher-Order Ambisonics (HOA) VST/LV2 plugins for 3D panning, binaural rendering, and room encoding.



- **[Steam Audio (ValveSoftware/steam-audio)](https://github.com)**  

  Open-source physics-based spatial audio SDK providing HRTF binaural rendering, acoustic occlusion, geometry-based reflections, and Ambisonics for games and VR/AR.



- **[Resonance Audio (Google)](https://github.com)**  

  Cross-platform open-source spatial audio SDK reproducing sound waves interacting with 3D environments at scale for mobile, desktop, and XR applications.



- **[Audacity](https://github.com)**  

  Flagship cross-platform open-source multi-track audio editor and recorder supporting OpenVINO AI noise suppression, music separation, spectral editing, and VST3 plugins.



- **[Tenacity](https://github.com)**  

  Community-driven, privacy-respecting open-source multi-track audio editor and recorder forked from Audacity with zero telemetry.



- **[matchering](https://github.com)**  

  Open-source containerized Python library and web app for automated reference-based audio mastering, matching RMS, FR, peak amplitude, and stereo width.



- **[headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom)**  

  Notable open-source context optimization toolkit (included per curated reference; an Apache 2.0 LLM/agent context compression proxy and MCP server rather than an audio DSP tool).



### Additional Strong Open-Source Options



- **[AudioSR](https://github.com)** for open-source diffusion-based audio super-resolution upscaling speech, music, and sound effects to 48 kHz.

- **[librosa](https://github.com)** and **[torchaudio](https://github.com)** for Python audio feature extraction, spectrogram analysis, and deep learning DSP pipelines.

- **[Pedalboard (Spotify)](https://github.com)** for high-performance Python audio processing supporting VST3/Audio Unit plugins, studio effects, and streaming I/O.

- **[SOX (Sound eXchange) & FFmpeg (`loudnorm` / `arnndn`)](https://github.com)** for CLI EBU R128 loudness normalization, RNNoise filtering, and batch audio conversion.

- **[Ardour](https://github.com)** and **[LMMS](https://github.com)** for full-featured open-source multi-track DAW recording, mixing, spatial surround routing, and modular synthesis.



**Frameworks for building custom systems**: Combine **DeepFilterNet** or **Resemble Enhance** for AI vocal cleanup, **Pedalboard + FFmpeg (`loudnorm`)** for automated broadcast mastering, and **IEM Plug-in Suite** or **Steam Audio** for 3D spatial audio production.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI speech enhancement and generative audio restoration models can occasionally introduce vocal artifacts; always audition outputs before final broadcast or commercial release.

- Verify open-source licenses (GPL, LGPL, MIT, Apache 2.0) when integrating spatial audio SDKs or VST plugins into proprietary software products.



---



**Made for audio engineers, podcasters, game audio designers, ML researchers, and open-source contributors.**  

Let's make AI audio enhancement and spatial sound processing more open, transparent, and accessible.
