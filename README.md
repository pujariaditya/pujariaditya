# Aditya Pujari

PhD student, University of North Texas — audio machine learning, with a focus on **trust and safety for speech and audio**: watermarking, deepfake forensics, and voice provenance.

## What I build

- **AudioAuth** (IEEE TBIOM 2026) — dual-watermarking framework: frequency-partitioned model + data watermarks for audio integrity verification and source attribution
- **WaveVerify** (IJCB 2025) — FiLM-generator + MoE-detector watermarking system; zero BER under common distortions; beats AudioSeal and WavMark
- **sourcetrace** — codec-residual open-set source tracing of audio deepfakes (EnCodec residual + frozen WavLM-Large; FPR95 1.14% vs published 3.36%)
- **spanmark** — two-route segment localization of partially spoofed speech; cross-corpus SOTA on LlamaPartialSpoof (29.0 EER vs 35.5 best baseline)
- **wavepainter** — multimodal LLM-guided diffusion for text-based speech editing; substitution WER 3.48 vs prior best 4.41
- **cond-ID** — speaker unlearning in zero-shot TTS via conditioning-space identity redirection (XTTS-v2, Tortoise-TTS, IndexTTS-1.5)
- **HiggsAudiov2TokenizerUnofficial** — full PyTorch training pipeline for the Higgs Audio V2 tokenizer (HuBERT semantics + DAC + 8-layer RVQ, 960x downsampling)

## Stack

Python · PyTorch · torchaudio · Hugging Face — WavLM / XLS-R / ECAPA-TDNN / Wav2Vec2 front-ends · EnCodec / DAC / RVQ neural audio codecs · GAN training · sha256-pinned reproducible eval pipelines

## Open to

Internships and full-time roles in audio AI — especially voice provenance, anti-spoofing, and generative audio.

[Google Scholar](https://scholar.google.com) · advisor: Ajita Rattani (UNT)
