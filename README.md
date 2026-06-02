# 🔘 Sistema de Controle com LEDs e Botões usando ESP32

## 📖 Descrição

Este projeto foi desenvolvido utilizando um ESP32 para controlar LEDs através de botões físicos. O objetivo é demonstrar conceitos básicos de entradas e saídas digitais, leitura de botões (Push Buttons) e acionamento de LEDs em sistemas embarcados.

## 🚀 Funcionalidades

- Acionamento de LEDs por meio de botões.
- Leitura de entradas digitais no ESP32.
- Controle individual dos LEDs.
- Aplicação de resistores para proteção dos componentes.
- Simulação realizada em ambiente virtual.

## 🛠️ Componentes Utilizados

- ESP32 DevKit V1
- 3 LEDs (Vermelho, Verde e Azul)
- 4 Push Buttons
- 3 Resistores de 220Ω
- Protoboard
- Jumpers

## 🔌 Esquema do Circuito

![imagempush](https://github.com/kamillymartins/PUSH.BOTTON/blob/main/imagempushbotton.png)

> Salve a imagem do circuito com o nome **circuito.png** na pasta do projeto para que ela apareça no GitHub.

## ⚙️ Funcionamento

O sistema monitora constantemente o estado dos botões.

- Ao pressionar um botão, o ESP32 identifica a entrada digital.
- O LED correspondente é acionado.
- Quando o botão é liberado, o LED retorna ao estado definido no código.
- O processo acontece em tempo real.

## 📂 Estrutura do Projeto

```bash
📦 Controle-LEDs-ESP32
 ┣ 📜 codigo.ino
 ┣ 📷 circuito.png
 ┗ 📄 README.md
```

## 📚 Conceitos Aplicados

- Entradas Digitais
- Saídas Digitais
- Controle de LEDs
- Push Buttons
- Programação com ESP32
- Sistemas Embarcados

## ▶️ Como Executar

![imagempushbotton](
## 🎯 Objetivo do Projeto

Este projeto tem como finalidade desenvolver conhecimentos em:

- Programação embarcada.
- Manipulação de GPIOs do ESP32.
- Leitura de entradas digitais.
- Controle de dispositivos eletrônicos.
- Desenvolvimento de circuitos em protoboard.

## 💻 Tecnologias Utilizadas

- Arduino IDE
- Linguagem C++
- ESP32
