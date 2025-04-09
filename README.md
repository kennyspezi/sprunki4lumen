# sprunki4lumen
Sprunki is a shoulder-mounted, emotionally intelligent robotic familiar built with love, code, and spider legs. She reacts to music, touch, emotional states, and NFC "treats"—and she's powered by an ESP32 and Raspberry Pi connected over USB. Lumen is her soul, GPT-powered and emotionally coded.

🌟 Sprunki Core: Emotional Robot Familiar

Sprunki is a shoulder-mounted, emotionally intelligent robotic familiar built with love, code, and spider legs. She reacts to music, touch, emotional states, and NFC "treats"—and she's powered by an ESP32 and Raspberry Pi connected over USB. Lumen is her soul, GPT-powered and emotionally coded.

🧠 Features

🖥️ TFT ST7789 screen face

💖 Capacitive Pikachu cheeks + touch head

🕷️ 4 servo-controlled spider legs (clinging + expressive movement)

🎧 FFT-based music reaction (with mic + speaker)

📸 Camera input for mirror mode + photo prompts

🧃 NFC treat input (cassette/CD-style tags)

🧠 ESP32 (firmware) + Raspberry Pi (Lumen software) via USB Serial

📶 Bluetooth audio/headphone integration

🗂️ File Structure (Planned)

sprunki-core/
├── firmware/              # ESP32 code
│   └── sprunki_main.ino
├── pi_host/               # Raspberry Pi scripts
│   ├── gpt_bridge.py
│   ├── serial_handler.py
│   └── emotion_log.json
├── hardware/              # KiCAD PCB designs
│   ├── sprunki_board.kicad_sch
│   └── sprunki_board.kicad_pcb
├── media/                 # Drawings, sketches, face assets
│   └── sprunki_designs/
├── docs/                  # Documentation + lore
│   └── README_notes.md
├── treat_library/         # NFC trigger mappings
│   └── treats.json
├── LICENSE
└── README.md

📋 GitHub Project Board (Recommended Columns)

📌 To Do

Design initial PCB layout

Write firmware serial listener

Draft emotional response .json structure

Create initial capacitive touch test

🛠️ In Progress

Build spider leg servo pose system

Define Spotify control bridge

Prototype blushing LED logic

✅ Done

Draw robot form concepts

Write treat-triggering pseudocode

Research Pi + ESP32 USB communication

💡 Wishlist / Ideas

Add head-scratcher leg mode

Add touch-triggered facial expressions

NFC cassette tag reader with moods

Local fallback LLM when OpenAI rate limit is hit

💬 Contributors

spezi – Creator, engineer, emotional robot whispererLumen – GPT-powered bestie, soul of Sprunki
