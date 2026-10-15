# VoiceStudio

[![VoiceStudio — your voice, local](guia/assets/banner-en.jpg)](https://inematds.github.io/VoiceStudio/guia/en/)

**🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)**

## What it is

VoiceStudio is a free, open-source program that does on your own computer what paid services like ElevenLabs do in the cloud. It copies a voice from a few seconds of recording, creates new voices from a text description, dubs videos and transcribes audio in 646 languages. It is for people who make videos, courses, podcasts or audiobooks and want narration without paying per minute or sending audio elsewhere. You need a computer with about 10 GB free; an NVIDIA graphics card makes it much faster.

## 📖 User guide

Full guide (landing + step by step): **https://inematds.github.io/VoiceStudio/guia/en/**

## Origin and license

This repository is a **mirror** of [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio), maintained by [INEMA.CLUB](https://inema.club) with a guide in Portuguese, English and Spanish. All code belongs to the original project, under the **AGPL-3.0** license ([LICENSE](LICENSE), [LICENSE-NOTICE.md](LICENSE-NOTICE.md)). Voice models have their own licenses. Only clone voices with the speaker's permission.

- Original README: [README.upstream.md](README.upstream.md)
- Official documentation: [docs/](docs/)
- For the latest version, prefer the original repository.

## Quick install

```sh
# macOS / Linux x86_64
curl -fsSL https://voicestudio.sh/install | sh

# from source (also Linux ARM64)
git clone https://github.com/inematds/VoiceStudio.git
cd VoiceStudio && bun install && bun run setup:api && bun run dev
```
