![image](https://github.com/user-attachments/assets/f2a5c9b8-6208-4723-8f46-1d74be421827)
# 🚀 Projeto: Controle de LEDs e Display com Joystick no RP2040

## 📌 Sumário
1. [Introdução](#introdução)
2. [Objetivos](#objetivos)
3. [Componentes Utilizados](#componentes-utilizados)
4. [Funcionamento do Projeto](#funcionamento-do-projeto)
5. [Especificações Técnicas](#especificações-técnicas)
6. [Configuração do Ambiente](#configuração-do-ambiente)
7. [Execução do Projeto](#execução-do-projeto)
8. [Demonstração em Vídeo](#demonstração-em-vídeo)

---

## 📖 Introdução
Este projeto tem como objetivo demonstrar o uso do conversor analógico-digital (ADC) no RP2040 para controlar a intensidade de LEDs RGB e movimentar um quadrado no display OLED SSD1306 utilizando um joystick. Além disso, foram implementadas interrupções e debouncing para a interação com os botões.

## 🎯 Objetivos
- Compreender o funcionamento do ADC no RP2040.
- Controlar a intensidade dos LEDs RGB com base nos eixos X e Y do joystick.
- Movimentar um quadrado no display SSD1306.
- Aplicar o protocolo de comunicação I2C.
- Utilizar interrupções (IRQ) e debouncing para os botões.

## 🛠️ Componentes Utilizados
- **Raspberry Pi Pico W**
- **Joystick** (conectado aos GPIOs 26 e 27)
- **LED RGB** (conectado às GPIOs 11, 12 e 13)
- **Display SSD1306 OLED** (I2C - GPIOs SDA(14) e SCL(15))
- **Botão do Joystick** (GPIO 22)
- **Botão A** (GPIO 5)

## ⚙️ Funcionamento do Projeto
- O **joystick** controla os LEDs RGB:
  - **Eixo X** -> Controla a intensidade do **LED Vermelho**.
  - **Eixo Y** -> Controla a intensidade do **LED Azul**.
- O **quadrado no display SSD1306** se move conforme a posição do joystick.
- O **botão do joystick** alterna o estado do LED Verde e altera a borda do display.
- O **botão A** ativa ou desativa os LEDs RGB.

## 📋 Especificações Técnicas
- **Uso de interrupções (IRQ)** para os botões.
- **Debouncing via software**.
- **Controle de LEDs via PWM**.
- **Protocolo I2C** para comunicação com o display.

## 🔧 Configuração do Ambiente
1. Instale o **VS Code**.
2. Configure o **SDK do Raspberry Pi Pico**.
3. Instale as extensões necessárias para **C/C++ e Raspberry Pi Pico**.
4. Compile e carregue o código na Raspberry Pi Pico W.
5. 1. Clone o repositório deste projeto no GitHub:
   ```bash
   git clone 
   ```
6. Certifique-se de ter o VS Code configurado com a extensão Pico SDK.
7. Abra o projeto no VS Code.
8. Compile e carregue o código para o simulador Wokwi ou para a placa física.
9. Teste as funcionalidades conforme os requisitos das atividades.

## Método alternativo:
1. Baixe o repositório em formato zip.
2. Extraia a pasta.
3. Mova para uma pasta de fácil acesso.
4. Importe a pasta com a extensão Raspberry pi pico disponivel no VS Code.
5. Compile o Programa.

## ▶️ Execução do Projeto
1. Compile e carregue o código na placa.
2. Utilize o joystick para controlar os LEDs e o display.
3. Teste as funcionalidades dos botões.

## 🎥 Demonstração em Vídeo
Confira a demonstração completa no vídeo:
📌 [Link para o vídeo demonstrativo aqui](https://youtu.be/ce3VJb0Dno4) 

---
Desenvolvido por *[Atenilton Santos de Souza Júnior]* 🚀

