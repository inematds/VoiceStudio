# VoiceStudio

[![VoiceStudio — sua voz local](guia/assets/banner.jpg)](https://inematds.github.io/VoiceStudio/guia/)

**🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)**

## O que é

O VoiceStudio é um programa gratuito e de código aberto que faz no seu computador o que serviços pagos como o ElevenLabs fazem na nuvem. Ele copia uma voz a partir de alguns segundos de gravação, cria vozes novas a partir de uma descrição em texto, dubla vídeos e transcreve áudio em 646 idiomas. Serve para quem produz vídeo, curso, podcast ou audiolivro e quer narração sem pagar por minuto nem enviar o áudio para fora. Precisa de um computador com uns 10 GB livres; com placa de vídeo NVIDIA fica bem mais rápido.

## 📖 Guia de uso

Guia completo (landing + passo a passo): **https://inematds.github.io/VoiceStudio/guia/**

## Origem e licença

Este repositório é um **espelho** de [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio), mantido pelo [INEMA.CLUB](https://inema.club) com o guia em português, inglês e espanhol. Todo o código é do projeto original, sob a licença **AGPL-3.0** ([LICENSE](LICENSE), [LICENSE-NOTICE.md](LICENSE-NOTICE.md)). Os modelos de voz têm licenças próprias. Clone vozes só com permissão de quem fala.

- README original (inglês): [README.upstream.md](README.upstream.md)
- Documentação oficial: [docs/](docs/)
- Para instalar a versão mais recente, prefira o repositório original.

## Instalação rápida

```sh
# macOS / Linux x86_64
curl -fsSL https://voicestudio.sh/install | sh

# código-fonte (também Linux ARM64)
git clone https://github.com/inematds/VoiceStudio.git
cd VoiceStudio && bun install && bun run setup:api && bun run dev
```
