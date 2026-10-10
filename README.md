# Programa-o-para-carrinho-com-arduino-e-sensor-infravermelho
Projeto acadêmico desenvolvido durante o curso técnico em Eletrônica, utilizando Arduino Uno para controlar um carrinho robótico capaz de seguir uma linha por meio de sensores infravermelhos.

Componentes utilizados

Arduino Uno

Ponte H L298N

Dois motores de corrente contínua (DC)

Dois sensores infravermelhos

Sensor ultrassônico HC-SR04

Protoboard

Suporte para seis pilhas AA recarregáveis

Chassi, rodas e roda boba

Conexões dos sensores infravermelhos

Sensor esquerdo: entrada analógica A0.

Sensor direito: entrada analógica A1.

Controle dos motores

A ponte H L298N é utilizada para controlar o sentido de rotação e a velocidade dos motores.

IN1: pino 7

IN2: pino 8

IN3: pino 10

IN4: pino 9

ENA: pino 6

ENB: pino 11

Observações sobre o desenvolvimento

A função de detecção e desvio de obstáculos do sensor ultrassônico foi desativada na programação para concentrar os testes no seguimento de linha. O sensor permaneceu conectado fisicamente ao circuito.

Durante os testes, foram identificadas dificuldades relacionadas à estrutura mecânica, aos contatos elétricos da alimentação e à lógica de programação. O projeto permitiu estudar a integração entre sensores, microcontrolador e acionamento de motores, além de evidenciar a importância dos ajustes e testes práticos no desenvolvimento de sistemas automatizados.
