<p align="center">
  <img src="./assets/banner.svg" alt="Victor Hugo Vieira Tavares, estudante de Engenharia Elétrica na UFCG" width="100%"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3000&pause=1200&color=F2A93B&center=true&vCenter=true&width=640&height=40&lines=Sistemas+el%C3%A9tricos+de+pot%C3%AAncia;Machine+Learning+aplicado+%C3%A0+engenharia+el%C3%A9trica;Pesquisa+no+Laborat%C3%B3rio+de+Alta+Tens%C3%A3o+%C2%B7+UFCG" alt="Sistemas elétricos de potência, Machine Learning aplicado à engenharia elétrica, pesquisa no LAT"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/UFCG-Engenharia_Elétrica-F2A93B?style=flat-square&labelColor=161B22"/>
  <img src="https://img.shields.io/badge/LAT-EMBRAPII-3FB6D9?style=flat-square&labelColor=161B22"/>
  <img src="https://img.shields.io/badge/Industr.IA-Instituto_Atlântico-E5677D?style=flat-square&labelColor=161B22"/>
  <img src="https://img.shields.io/badge/IEEE-PES_UFCG-8B949E?style=flat-square&labelColor=161B22"/>
</p>

<br/>

<table>
<tr>
<td width="62%" valign="top">

### Sobre mim

Sou estudante de Engenharia Elétrica na UFCG. Meu interesse principal é sistemas de potência, em especial transmissão de energia, e gosto de trabalho prático: bancada, campo e simulação.

Uso programação e machine learning como ferramenta para problemas da elétrica: diagnóstico de motores, estabilidade de rede, consumo de energia e inspeção de equipamentos de subestação. Fora da pesquisa, sou monitor, coordeno o ramo do IEEE PES e participo de projetos de extensão.

</td>
<td width="38%" valign="top">

### Em resumo

📍 Campina Grande, PB<br/>
🎓 Engenharia Elétrica · 8º período<br/>
🔬 Pesquisa no LAT · EMBRAPII<br/>
🏭 Bolsista do Industr.IA<br/>
⚡ Coordenador do IEEE PES UFCG<br/>
📫 [victor.hugo.tavares@ee.ufcg.edu.br](mailto:victor.hugo.tavares@ee.ufcg.edu.br)

</td>
</tr>
</table>

## 🔬 Pesquisa

### [Pyron · manutenção preditiva por termografia](https://github.com/hugovieiraz/pyron)

Aplicativo que lê a temperatura de cada pixel do termograma, encontra os componentes (para-raios, terminais) e classifica a severidade pela **NBR 15866**, comparando com a temperatura máxima admissível e com as outras fases. No fim, gera o laudo em PDF.

| Detector de para-raios (RF-DETR) | Temperatura pela barra de cores | Versão rápida (INT8) |
|:---:|:---:|:---:|
| mAP50 **0,86** | erro mediano **0,5 °C** | **~240 ms** por imagem na CPU |

`PyTorch` `ONNX` `FastAPI` `OpenCV` `ReportLab` `C#`

### [Curto entre espiras por termografia · XXI ERIAC](https://github.com/hugovieiraz/curto-espiras-termografia)

Código e artigo do trabalho. A partir de termogramas de um transformador de bancada, o modelo estima quantas espiras estão em curto (de 0 a 600), com intervalo de incerteza e aviso quando a imagem foge do que ele conhece.

| Severidade nunca vista no treino | Nível certo | Motor de indução (11 condições) |
|:---:|:---:|:---:|
| erro médio de **14,8 espiras** em 600 | **97 %** das imagens | F1 **0,997** |

`DINOv2` `MobileNetV3` `scikit-learn` `LaTeX`

## 🧠 Experimentos de Machine Learning

Quatro problemas de engenharia elétrica, cada um com comparação de modelos, validação cruzada e métricas no conjunto de teste.

<p align="center">
  <a href="https://github.com/hugovieiraz/diagnostico-acionamentos-eletricos-ml"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/ml/acionamentos-dark.svg"/><img src="./assets/ml/acionamentos-light.svg" width="49%" alt="diagnostico-acionamentos-eletricos-ml: F1 de 99,9% com Random Forest"/></picture></a>
  <a href="https://github.com/hugovieiraz/electrical-grid-stability"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/ml/rede-dark.svg"/><img src="./assets/ml/rede-light.svg" width="49%" alt="electrical-grid-stability: acurácia de 81,2%"/></picture></a>
  <a href="https://github.com/hugovieiraz/cv-solar-panel-classification"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/ml/solar-dark.svg"/><img src="./assets/ml/solar-light.svg" width="49%" alt="cv-solar-panel-classification: acurácia de 80,3%"/></picture></a>
  <a href="https://github.com/hugovieiraz/appliances-energy-prediction"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/ml/consumo-dark.svg"/><img src="./assets/ml/consumo-light.svg" width="49%" alt="appliances-energy-prediction: RMSE de 92,5 Wh"/></picture></a>
</p>

## 🚀 Experiências e atividades

| | |
|:--|:--|
| 🔬 **Pesquisador** · LAT / EMBRAPII | termografia e visão computacional em subestações |
| 🏭 **Bolsista** · Industr.IA | Residência em TIC, Instituto Atlântico / Softex |
| ⚡ **Coordenador** · IEEE PES UFCG | ramo estudantil de potência e energia |
| 🎮 **Extensão** · MemorIA (Probex) | jogo de memória com IA generativa para revisão escolar |
| 📐 **Monitor** · Cálculo Numérico | UFCG |
| 🤖 **Instrutor** · Robótica Educacional | minicurso para alunos do ensino médio |
| 📄 **Publicações** | Revista Coopex · artigo para o XXI ERIAC |

## 🛠️ Ferramentas

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,pytorch,sklearn,tensorflow,opencv,fastapi,react,latex,git,vscode&theme=dark&perline=10" alt="Python, PyTorch, scikit-learn, TensorFlow, OpenCV, FastAPI, React, LaTeX, Git, VS Code"/>
</p>

<details>
<summary><b>📦 Outros projetos</b></summary>
<br/>

| Projeto | O que é |
|:--|:--|
| [Site do MemorIA](https://github.com/hugovieiraz/Memoria-Site) | site do projeto de extensão |
| [Loja de rações](https://github.com/hugovieiraz/loja-racoes) | app web de vendas, fiado e estoque (React + Vite) |
| [Cálculo Numérico](https://github.com/hugovieiraz/Calculo-Numerico) | raízes, sistemas lineares, interpolação e integrais em Python |

</details>

## 📊 Atividade no GitHub

<p align="center">
  <img src="https://streak-stats.demolab.com?user=hugovieiraz&theme=transparent&hide_border=true&ring=F2A93B&fire=E5677D&currStreakLabel=F2A93B&sideLabels=8B949E&dates=8B949E&currStreakNum=8B949E&sideNums=8B949E&stroke=30363D&locale=pt_BR" alt="Sequência de contribuições"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hugovieiraz/hugovieiraz/output/snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/hugovieiraz/hugovieiraz/output/snake.svg" alt="Animação das contribuições"/>
  </picture>
</p>
