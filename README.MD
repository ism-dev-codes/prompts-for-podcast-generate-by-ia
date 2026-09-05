<div align="center">

# 🎙️ Automação e Geração de Podcast com IAs Generativas

![AWS](https://img.shields.io/badge/AWS-AWS%20re%2FStart-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)
![IA Generativa](https://img.shields.io/badge/Pipeline-IA%20Generativa-blueviolet?style=for-the-badge)

<p align="center">
  <b>Projeto de criação de conteúdo multimídia utilizando uma esteira (pipeline) de prompts estruturados e ferramentas de IA Generativa.</b>
</p>

</div>

---

## 📌 Visão Geral do Projeto

Este projeto demonstra a criação e automação de um podcast completo do zero utilizando ferramentas de Inteligência Artificial. A proposta foi construir uma **esteira de produção (pipeline)** estruturada em prompts, onde cada etapa (roteirização, síntese de voz, arte visual e pós-produção de áudio) alimenta a fase seguinte do processo criativo.

### 🎯 Objetivos Técnicos
* Engenharia de Prompt para estruturação de roteiros técnicos e narrativos.
* Síntese de voz neural (Text-to-Speech) com inteligência emocional.
* Geração de assets visuais para capa utilizando modelos de difusão de imagem.
* Edição e equalização de áudio para distribuição.

---

## 🎧 Demonstração do Resultado

<div align="center">
  <img src="assets/capa-podcast.jpg" alt="Capa do Podcast" width="300" style="border-radius: 8px;"/>
  
  <br/><br/>

  <audio src="output/podcast_editado.MP3" controls title="Podcast Editado"></audio>
</div>

---

## 💻 Stack Tecnológica & Ferramentas

| Etapa | Ferramenta | Aplicação |
| :--- | :--- | :--- |
| **Roteirização** | ChatGPT (OpenAI) | Criação da estrutura do episódio, falas e ganchos |
| **Síntese de Voz** | ElevenLabs | Geração de áudio realista via Text-to-Speech |
| **Identidade Visual** | Midjourney | Geração da arte de capa com prompts visuais |
| **Edição e Mixagem** | CapCut / Audacity | Tratamento de áudio, remoção de ruídos e efeitos sonoros |

---

## 📁 Estrutura do Repositório

```text
├── assets/
│   └── capa-podcast.jpg       # Arte visual da capa do podcast
├── output/
│   └── podcast_editado.MP3    # Arquivo final de áudio processado
├── src/
│   └── prompts/               # Coleção de prompts utilizados no projeto
│       ├── roteiro.md         # Prompt estruturado do roteiro
│       └── imagem_capa.md     # Prompt do Midjourney
└── README.md                  # Documentação do projeto
