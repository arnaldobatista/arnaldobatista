## Olá, eu sou o Arnaldo 👋

Desenvolvedor full stack de produto — daqueles que operam o que constroem. Vivo em TypeScript e Python, mas desço para Go, Rust, Swift ou Kotlin quando o problema pede. O que me interessa é a parte difícil: fibra ótica, tempo real, visão computacional e IA rodando local.

- 💼 &nbsp; Desenvolvedor Full Stack na <a href="https://www.alternativamais.com.br">Alternativa Mais</a>.
- 🔓 &nbsp; Identifiquei uma das maiores brechas de segurança na <a href="https://www.nuvemshop.com.br/">NUVEMSHOP</a>.

### No que eu trabalho

A maior parte do meu código é fechado (produto e cliente), mas dá para descrever a engenharia. Alguns dos sistemas que mantenho em produção:

| Domínio | O que é |
|---|---|
| **Provedor de internet / fibra** | Central do assinante, 2ª via e PIX por URA, logs RADIUS, e monitoramento de rede FTTH: alarmes de OLT por SNMP, detecção de rotas de fibra paradas e clientes afetados no mapa |
| **Operação de campo** | Vistorias técnicas com checklist e foto, inventário por técnico, frota e abastecimento, com integrações reais de NF-e por IMAP, ponto eletrônico e WhatsApp — um dos sistemas passa de 175 mil linhas, 89 entidades e 123 migrations |
| **Videomonitoramento com visão computacional** | Ingestão de câmeras em **Go** + ffmpeg, inferência em **NVIDIA DeepStream** (TensorRT, ONNX, YOLOv9, leitura de placas via Triton), API **NestJS** e painel **Next.js** com vídeo ao vivo por **WebRTC** |
| **Acessibilidade e leitura** | Leitor de EPUB com narração sincronizada palavra a palavra, com apps nativos iOS e Android e servidores de TTS neural rodando local |
| **Interação natural** | Controle do mouse por gestos de mão via webcam (**MediaPipe** + helper nativo em **Rust**), com inferência 100% local — não grava imagem |

O padrão do back-end é **NestJS + TypeORM + PostgreSQL**; o do front, **Next.js / React + Tailwind**. Repliquei esse esqueleto (auth, RBAC, auditoria, multiempresa) em cinco produtos e acabei extraindo num template próprio.

### Como eu construo

- **Modelo local em vez de API paga por uso** — TTS (Kokoro, Chatterbox), alinhamento forçado de áudio com Qwen3, LLM via Ollama; servidores de modelo próprios que carregam e descarregam por ociosidade.
- **Decisões contra o caminho fácil** — contrato OpenAPI que quebra o build se divergir, *schema-reconciler* forward-only no lugar de migrations frágeis, `mypy --strict`, permissão separada só para leitura de dados sensíveis.
- **Teste e CI de verdade onde importa** — um dos sistemas tem 126 arquivos de teste; outro publica APK assinado em CI self-hosted.

### Projeto público

**[tradutor-de-videos](https://github.com/arnaldobatista/tradutor-de-videos)** — Dubla vídeos do YouTube para português do Brasil e toca a dublagem no próprio player, no lugar do áudio original. Tudo local, sem custo por uso. Um motor em Python (pipeline de 9 estágios: baixa o áudio, separa a voz original, traduz, gera a voz sintética, encaixa no tempo e mixa respeitando o teto de −14 LUFS do YouTube), uma extensão de Chrome que sincroniza a dublagem com o vídeo, e um app de barra de menus em Swift que mantém o motor de pé.

O resto é código de produto e de cliente, em repositório privado.

### Stack

**Linguagens** &nbsp; TypeScript · Python · Go · Swift · Kotlin · Rust · JavaScript

**Back-end** &nbsp; NestJS · Node · TypeORM · PostgreSQL · Redis · BullMQ · FastAPI

**Front-end** &nbsp; Next.js · React · React Native · SwiftUI · Jetpack Compose

**Vídeo & IA** &nbsp; DeepStream · TensorRT · ONNX · YOLO · MediaPipe · ffmpeg · WebRTC · TTS local

**Infra** &nbsp; Docker · Linux · GitHub Actions

### Formação

Análise e Desenvolvimento de Sistemas — <a href="https://www.unopar.com.br">UNOPAR</a> · Engenharia de Software — <a href="https://www.anhanguera.com">Anhanguera</a> · Pós em Ciência de Dados e Analytics Avançados — UNOPAR · Pós em Arquitetura e Governança de Dados — UNOPAR

### Onde me encontrar

[![Linkedin: Arnaldo Batista](https://img.shields.io/badge/-arnaldobatista-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/arnaldbatista)
