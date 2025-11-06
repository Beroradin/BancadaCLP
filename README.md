# BancadaCLP
Este repositório contém os arquivos de programação e simulação para o controle de motores elétricos utilizando uma bancada didática com o CLP 300 da WEG. As partidas utilizadas foram: Partida Direta, Partida com Reversão, Partida com Soft Starter e Partida com Inversor de Frequência.

<p align="center">
  <img src="images/Projeto.jpeg" alt="IMAGEM 1" width="526px" />
</p>

## 🎯 Objetivos

O Objetivo principal desse repositório é arquivar os documentos envolvendo a montagem da bancada CLP para o laboratório de Máquinas Elétricas da Universidade Federal do Oeste da Bahia, mantendo como um posterior guia para alunos utilizarem e implementarem melhorias a bancada.

## 🛠️ Ferramentas Utilizadas

- Software de Programação: WEG Programming Suite (WPS)
- Software de Simulação: CADe SIMU (Versão 3.0 ou superior)

## 📑 Programação e Simulação

A programação do projeto foi feita por meio da linguagem Ladder no software WEG Programming Suite (WPS), que é uma linguagem de fácil interpretação e implementação em CLPs. A ideia básica é ter um CLP controlando as partidas dos motores via comutadores ou partidas eletrônicas, tudo isso controlado via uma IHM. A simulação demonstra esse cenário por meio de um CLP, botões, motores, comutadores, partidas eletrônicas e sinalizadores (LEDs). Para acessar o arquivo da programação Ladder basta instalar o WEG Programming Suite, após a instalação, abrir uma configuração que se encontra dentro da pasta documents/PCL300. Para rodar a simulação, basta ter o executável do CADe SIMU, inserir a senha (geralmente é 4962), abrir o arquivo .cad que se encontra na pasta documents do repositório e rodar.

## :camera: Imagens

Aqui se encontra documentado partes do arquivo do WPS e CADe SIMU separado por secções:

### Parte dos motores no WPS
<p align="left">
  <img src="images/WPS_Ladder_Motores.jpeg" alt="IMAGEM 2" width="526px" />
</p>

### Parte dos leds no WPS
<p align="left">
  <img src="images/WPS_Ladder_LEDs.jpeg" alt="IMAGEM 3" width="526px" />
</p>

### Parte auxiliar (timer) no WPS
<p align="left">
  <img src="images/WPS_Ladder_Auxiliar.jpeg" alt="IMAGEM 4" width="526px" />
</p>

### Parte do motor e partida direta/reversão no CADe SIMU
<p align="left">
  <img src="images/CADeSIMU_Motor_DIR_REV.jpeg" alt="IMAGEM 5" width="526px" />
</p>

### Parte do Soft Starter no CADe SIMU
<p align="left">
  <img src="images/CADeSIMU_Soft.jpeg" alt="IMAGEM 6" width="526px" />
</p>

### Parte do Inversor de Frequência no CADe SIMU
<p align="left">
  <img src="images/CADeSIMU_Inversor.jpeg" alt="IMAGEM 7" width="526px" />
</p>

### Parte da sinalização (LEDs) no CADe SIMU
<p align="left">
  <img src="images/CADeSIMU_LEDs.jpeg" alt="IMAGEM 8" width="526px" />
</p>

### Parte do CLP e IHM (Botões) no CADe SIMU
<p align="left">
  <img src="images/CADeSIMU_CLP_IHM.jpeg" alt="IMAGEM 9" width="526px" />
</p>

### Parte da programação Ladder no CADe SIMU
<p align="left">
  <img src="images/CADeSIMU_Ladder.jpeg" alt="IMAGEM 10" width="526px" />
</p>

## ▶️ GIF da Simulação

Gif da Simulação no CADe SIMU de uma partida direta e o eventual desligamento da mesma.

<p align="center">
  <img src="images/CadeSIMUGIF.gif" alt="GIF" width="1815px" />
</p>

## ▶️ Vídeo mostrando o funcionamento da bancada
<p align="center">
    <a href="https://www.youtube.com/shorts/qpB82FC35nQ">Clique aqui para acessar o vídeo</a>
</p>
