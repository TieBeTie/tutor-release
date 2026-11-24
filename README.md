# Tutor: closed test

A voice assistant for Windows 11 with an NVIDIA graphics card. This repository holds only the builds for testers; the code is private.

## Install

1. Download `tutor-setup.exe` from the latest release.
2. Run it. Windows may say "Windows protected your PC": click **More info**, then **Run anyway** (the program is not signed yet).
3. Pick where to install it: the program and its models take about 3 GB, so pick another drive if you keep C: free.
4. Pick the folder of your notes (an Obsidian vault or any folder of notes and PDFs).
5. Wait while the program and the models download. Tutor starts by itself; its icon is by the clock. **F9** opens the microphone.

No administrator rights are needed. Settings go to `%APPDATA%\Tutor`, the tutor's own data to `%LOCALAPPDATA%\Tutor`. Remove it in Windows settings, Installed apps.

Tutor works through Claude Code or Codex, signed in with your own account (the tutor never signs in itself), or through your own model over an OpenAI-style API. The menu by the clock says when one is missing and offers to install it or to sign in.

## What is sent to the author

Only with your consent, chosen at the first start (`share`: everything, numbers only, or nothing; numbers only by default): the journal of each day, a report of the computer once (system, processor, memory, video cards, no names), and your spoken feedback when you leave it («Оставить отзыв» in the menu, or say «я заканчиваю»).

## Models and libraries, and their licences

| Part | Licence | From |
|---|---|---|
| Whisper large-v3-turbo, ggml | MIT (OpenAI; ggml by ggerganov) | Hugging Face, its authors |
| whisper.cpp with CUDA libraries | MIT; NVIDIA CUDA redistributable | this release |
| Silero TTS v5 ru | CC BY-NC 4.0: non-commercial use only | this release, converted for the program |
| Phonon 31M en | Apache-2.0 | this release |
| CAM++ (3D-Speaker) | Apache-2.0 | this release |
| DTLN-aec | MIT | this release |
| Microsoft Visual C++ runtime | Visual C++ redistributable licence | beside the program |
