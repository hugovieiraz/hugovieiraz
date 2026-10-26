<p align="center">
  <img src="./assets/banner.svg" alt="Victor Hugo Vieira Tavares — Engenharia Elétrica UFCG" width="100%"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=1100&color=FFB020&center=true&vCenter=true&width=720&height=42&lines=Termografia+%2B+Vis%C3%A3o+Computacional+em+ativos+de+alta+tens%C3%A3o;Machine+Learning+aplicado+a+sistemas+el%C3%A9tricos;Pesquisador+no+LAT+%C2%B7+EMBRAPII+%7C+Industr.IA" alt="Texto animado"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Engenharia_Elétrica-UFCG-FFB020?style=flat-square&labelColor=0D1117"/>
  <img src="https://img.shields.io/badge/Pesquisa-LAT_·_EMBRAPII-4CC9F0?style=flat-square&labelColor=0D1117"/>
  <img src="https://img.shields.io/badge/Industr.IA-Instituto_Atlântico-FF5C7A?style=flat-square&labelColor=0D1117"/>
  <img src="https://img.shields.io/badge/IEEE-PES_UFCG-00629B?style=flat-square&labelColor=0D1117"/>
</p>

## ⚡ Sobre mim

Estudante de Engenharia Elétrica na **UFCG**, em Campina Grande – PB. Pesquiso no **Laboratório de Alta Tensão (LAT)** como usar **câmeras térmicas e visão computacional** para achar falhas em equipamentos de subestação antes que virem defeito: o modelo identifica a peça, mede a temperatura e compara com a norma.

## 🔥 Projetos em destaque

### [Pyron — manutenção preditiva por termografia](https://github.com/hugovieiraz/pyron)

Aplicativo que lê a temperatura de cada pixel do termograma, encontra os componentes (para-raios, terminais) e classifica a severidade pela **NBR 15866** (temperatura máxima admissível e ΔT entre fases), gerando o laudo em PDF.

| Detector de para-raios (RF-DETR) | Temperatura pela barra de cores | Versão rápida (INT8) |
|:---:|:---:|:---:|
| mAP50 **0,86** | erro mediano **0,5 °C** | **~240 ms** por imagem na CPU |

`PyTorch` `ONNX` `FastAPI` `OpenCV` `ReportLab` `C#`

### [Curto entre espiras por termografia — XXI ERIAC](https://github.com/hugovieiraz/curto-espiras-termografia)

Código e artigo: a partir de termogramas de um transformador de bancada, estima **quantas espiras estão em curto** (de 0 a 600), com intervalo de incerteza e aviso quando a imagem foge do que o modelo conhece.

| Severidade nunca vista no treino | Nível certo | Motor de indução (11 condições) |
|:---:|:---:|:---:|
| erro médio **14,8 espiras** de 600 | **97 %** das imagens | F1 **0,997** |

`DINOv2` `MobileNetV3` `scikit-learn` `LaTeX`

## 🧠 Experimentos de Machine Learning

| Projeto | Problema | Modelos |
|:--|:--|:--|
| [Diagnóstico de acionamentos elétricos](https://github.com/hugovieiraz/diagnostico-acionamentos-eletricos-ml) | 11 condições de operação de um motor a partir de sinais de corrente | Árvore, KNN, SVM, Random Forest · MLflow |
| [Estabilidade da rede elétrica](https://github.com/hugovieiraz/electrical-grid-stability) | rede inteligente estável ou instável | Perceptron, Regressão Logística |
| [Consumo de eletrodomésticos](https://github.com/hugovieiraz/appliances-energy-prediction) | prever o consumo em Wh pelo clima da casa | Regressão linear (gradiente e mínimos quadrados) |
| [Falhas em placas solares](https://github.com/hugovieiraz/cv-solar-panel-classification) | 6 classes: limpa, poeira, neve, fezes de ave, dano físico e elétrico | MobileNetV2 + Data Augmentation |

## 🚀 Experiências e atividades

- 🔬 **Pesquisador no LAT · EMBRAPII** — termografia e visão computacional em subestações
- 🏭 **Bolsista do Industr.IA** — Residência em TIC, Instituto Atlântico / Softex
- 🔋 **Coordenador do IEEE Power & Energy Society** — Ramo Estudantil UFCG
- 🎮 **Extensão MemorIA (Probex)** — jogo de memória com IA generativa para revisão escolar
- 📐 **Monitor de Cálculo Numérico** — UFCG
- 🤖 **Minicurso de Robótica Educacional** — para alunos do ensino médio
- 📄 **Publicações** — Revista Coopex · artigo para o XXI ERIAC

## 🛠️ Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=py,pytorch,sklearn,tensorflow,opencv,fastapi,react,latex,git,vscode&theme=dark" alt="Python, PyTorch, scikit-learn, TensorFlow, OpenCV, FastAPI, React, LaTeX, Git, VS Code"/>
</p>

<details>
<summary><b>📦 Outros projetos</b></summary>

<br/>

| Projeto | O que é |
|:--|:--|
| [Site do MemorIA](https://github.com/hugovieiraz/Memoria-Site) | esqueleto do site do projeto de extensão |
| [Loja de rações](https://github.com/hugovieiraz/loja-racoes) | app web para controle de vendas, fiado e estoque (React + Vite) |
| [Cálculo Numérico](https://github.com/hugovieiraz/Calculo-Numerico) | métodos numéricos em Python: raízes, sistemas lineares, interpolação, integrais |

</details>

## 📊 Atividade

<p align="center">
  <img src="https://streak-stats.demolab.com?user=hugovieiraz&theme=transparent&hide_border=true&ring=FFB020&fire=FF5C7A&currStreakLabel=FFB020&sideLabels=9DA7B3&dates=6E7B8B&currStreakNum=E6EDF3&sideNums=E6EDF3&stroke=2D3B50&locale=pt_BR" alt="Sequência de contribuições"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hugovieiraz/hugovieiraz/output/snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/hugovieiraz/hugovieiraz/output/snake.svg" alt="Animação das contribuições"/>
  </picture>
</p>

## 📫 Contato

<p align="left">
  <a href="mailto:victor.hugo.tavares@ee.ufcg.edu.br"><img src="https://img.shields.io/badge/victor.hugo.tavares@ee.ufcg.edu.br-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>
