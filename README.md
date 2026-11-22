# Tutor: closed test

A voice assistant for Windows 11 with an NVIDIA graphics card. This repository holds only the builds for testers; the code is private.

## Install

1. Download `tutor-setup.exe` from the latest release.
2. Run it. Windows may say "Windows protected your PC": click **More info**, then **Run anyway** (the program is not signed yet).
3. Pick the folder of your notes when asked (an Obsidian vault or any folder of notes and PDFs).
4. Wait while the models download (about 4 GB). Tutor starts by itself; its icon is by the clock. **F9** opens the microphone.

The program goes to `%LOCALAPPDATA%\Programs\Tutor`, its settings to `%APPDATA%\Tutor`, its own data to `%LOCALAPPDATA%\Tutor`. No administrator rights are needed.

## Models and their licences

| Model | Licence | From |
|---|---|---|
| Parakeet TDT 0.6B v3, int8 ONNX | CC-BY-4.0 (NVIDIA; ONNX by istupakov) | Hugging Face, its authors |
| Whisper large-v3-turbo, ggml | MIT (OpenAI; ggml by ggerganov) | Hugging Face, its authors |
| whisper.cpp with CUDA libraries | MIT; NVIDIA CUDA redistributable | this release |
| Silero TTS v5 ru | CC BY-NC 4.0: non-commercial use only | this release, converted for the program |
| Phonon 31M en | Apache-2.0 | this release |
| CAM++ (3D-Speaker) | Apache-2.0 | this release |
| DTLN-aec | MIT | this release |
