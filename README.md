🎙️ Local Voice System

Talk. Dictate. Read. Fully offline voice engine for Linux.

⚡ TRY IT FIRST
say "hello world"
🔥 WHAT THIS IS

A local voice interface that lets your machine:

🎙️ Talk back to you
📝 Turn speech into text
📖 Read anything out loud

No cloud. No API keys. Runs on your machine.

⚡ FEATURES
Offline voice assistant core
Neural TTS (XTTS v2)
Fast local TTS fallback (Piper)
Speech-to-text (Whisper)
Simple command-line control
🚀 HOW IT WORKS
🎤 You speak or type
🧠 Whisper converts speech → text
🔊 XTTS / Piper converts text → voice
🔁 Scripts connect everything into one loop
💻 SETUP
1. Install TTS
pip install TTS
2. Generate voice (XTTS)
python -m TTS.bin.synthesize \
--text "hello world" \
--model_name tts_models/multilingual/multi-dataset/xtts_v2 \
--out_path out.wav
3. Play audio
aplay out.wav
🧠 WHY THIS EXISTS

To turn your computer into a private voice OS layer — no cloud, full control, fast local interaction.

🔊 STACK
XTTS v2 → natural neural voice
Piper → fast lightweight TTS
Whisper → speech recognition
Python scripts → system glue
⚡ KEY IDEA

Your machine should be able to listen, think, and speak — locally.

🚀 WHY THIS FORMAT WORKS
instant command at top
zero explanation before value
ultra scannable
copy → run → understand flow
