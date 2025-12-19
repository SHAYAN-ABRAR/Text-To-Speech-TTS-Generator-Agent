# Text-To-Speech-TTS-Generator-Agent

A simple, efficient Text-to-Speech (TTS) agent. Leverages the quantized **Orpheus-3B-0.1-ft** model from Unsloth for expressive speech generation and the **SNAC 24kHz** neural audio codec for high-fidelity waveform decoding.

This project demonstrates human-like TTS with natural prosody, emotional cues (e.g., `<giggles>`), and optional voice selection – all in a single inference pipeline.

## Features

- Fast inference with Unsloth's optimized loading
- Expressive output supporting paralinguistic tags (laughs, sighs, etc.)
- High-quality 24kHz audio reconstruction via SNAC
- Batch processing for multiple prompts
- Direct audio playback in Jupyter notebooks using IPython.display.Audio
- No additional training required – ready-to-run demo

## Requirements

- Python 3.8+
- GPU with at least 12GB VRAM recommended (works with lower memory via 4-bit quantization)
