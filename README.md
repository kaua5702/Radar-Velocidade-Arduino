# 🚗 Radar de Velocidade Inteligente

Projeto desenvolvido utilizando Arduino Uno e Wokwi.

## 📌 Sobre o projeto

Sistema capaz de medir a distância de um objeto utilizando sensor ultrassônico HC-SR04, calcular sua velocidade aproximada e indicar quando o limite configurado é ultrapassado.

## ⚙️ Componentes utilizados

- Arduino Uno
- Sensor ultrassônico HC-SR04
- Display OLED I2C
- LED verde
- LED vermelho
- Buzzer

## 🔥 Funcionamento

O sensor mede a distância do objeto várias vezes.
Com base na variação da distância ao longo do tempo, o Arduino calcula a velocidade.

Caso a velocidade ultrapasse 5 km/h:

- LED vermelho é ativado
- Buzzer emite alerta

Caso contrário:

- LED verde permanece ligado

## 🧠 Conceitos utilizados

- Sensor ultrassônico
- Comunicação I2C
- Display OLED
- Controle de GPIO
- Cálculo de velocidade
- Filtro de medições

## 🛠️ Plataforma

Desenvolvido no simulador Wokwi.
