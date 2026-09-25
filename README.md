## Olá, eu sou o Arnaldo 👋

Desenvolvedor full stack. Passo a maior parte do tempo em TypeScript e Python, e a parte do trabalho que me interessa de verdade é a difícil: vídeo em tempo real, inferência em GPU e sistema que não pode cair.

- 💼 &nbsp; Desenvolvedor Full Stack na <a href="https://www.alternativamais.com.br">Alternativa Mais</a>.
- 🔓 &nbsp; Identifiquei uma das maiores brechas de segurança na <a href="https://www.nuvemshop.com.br/">NUVEMSHOP</a>.

### No que eu trabalho

Meu dia a dia é uma plataforma de videomonitoramento com visão computacional. O código é fechado, mas a engenharia dá para descrever:

| Camada | Como é feita |
|---|---|
| Ingestão de vídeo | Serviço próprio em **Go**, com ffmpeg, cuidando dos fluxos das câmeras |
| Visão computacional | **NVIDIA DeepStream** com TensorRT e ONNX, detecção com YOLOv9, worker dedicado a leitura de placas e modelos servidos por Triton |
| API | **NestJS** com 50 módulos, 130 entidades no TypeORM, Postgres, filas em BullMQ/Redis e autenticação JWT |
| Painel | **Next.js** com 64 telas em React e Radix, vídeo ao vivo por WebRTC e eventos por WebSocket |
| Qualidade | Workflow de CI que mede qualidade de visão a cada mudança, com benchmarks versionados |

Somando os quatro serviços, passa de 400 mil linhas de código, sem contar dependências.

### Projeto público

**[tradutor-de-videos](https://github.com/arnaldobatista/tradutor-de-videos)** — Dubla vídeos do YouTube para português do Brasil com tudo rodando local, sem custo por uso. Motor em Python que baixa o áudio, separa a voz original, traduz, gera a voz sintética, encaixa no tempo e mixa; extensão de Chrome que toca a dublagem em sincronia com o player; app de barra de menus em Swift que mantém o motor de pé.

O resto é código de cliente e fica em repositório privado.

### Stack

**Linguagens** &nbsp; TypeScript · Python · Go · Kotlin · Swift

**Back-end** &nbsp; NestJS · Node · TypeORM · Postgres · Redis · BullMQ

**Front-end** &nbsp; React · Next.js · React Native

**Vídeo e IA** &nbsp; DeepStream · TensorRT · ONNX · YOLO · ffmpeg · WebRTC

**Infra** &nbsp; Docker · Linux · GitHub Actions

### Formação

Análise e Desenvolvimento de Sistemas — <a href="https://www.unopar.com.br">UNOPAR</a> · Engenharia de Software — <a href="https://www.anhanguera.com">Anhanguera</a> · Pós em Ciência de Dados e Analytics Avançados — UNOPAR · Pós em Arquitetura e Governança de Dados — UNOPAR

### Onde me encontrar

[![Linkedin: Arnaldo Batista](https://img.shields.io/badge/-arnaldobatista-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/arnaldbatista)
