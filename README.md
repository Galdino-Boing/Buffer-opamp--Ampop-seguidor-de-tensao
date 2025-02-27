# Buffer Op-Amp  
This project explores the versatility of operational amplifiers (Op-Amps) in configurations such as the voltage follower (buffer), with the goal of studying and applying techniques for signal isolation and amplification without altering its form. Using Op-Amps creatively, the project involves the construction and analysis of buffer circuits.

# Ampop seguido de tensão
Este projeto explora a versatilidade dos amplificadores operacionais (AMPops) em configurações como o seguidor de tensão (buffer), com o objetivo de estudar e aplicar técnicas de isolamento e amplificação de sinal sem alteração da sua forma. Utilizando AMPops de forma criativa, o projeto envolve a construção e análise de circuitos buffer.

# Objetivo  
Alterar a forma da onda de saída, com o propósito de isolar e transferir o sinal sem alteração de amplitude ou polaridade, utilizando um amplificador operacional em configuração seguidor de tensão (buffer).

# Utilidade  
Este circuito utiliza um amplificador operacional 741 com um resistores para isolar o sinal de entrada, mantendo a forma da onda inalterada e controlando a corrente de saída, sem modificar a amplitude ou polaridade do sinal.

**Manutenção da polaridade e amplificação sem distorção:** Um amplificador operacional seguidor de tensão (buffer) mantém a polaridade do sinal de entrada, amplificando o sinal sem inverter ou alterar sua forma. Este comportamento é útil em sistemas que precisam de isolamento de sinal sem modificações na polaridade ou amplitude. Entre as aplicações práticas, destacam-se:

- Isolamento de Circuitos de Alta Impedância
- Amplificação de Sinal de Áudio
- Integração de Sensores e Instrumentos
- Circuitos de Medição e Monitoramento
- Amplificadores de Instrumentação
- Circuitos de Transmissão de Sinal
- Interfaces de Circuitos com Impedâncias Diferentes

# Materiais  
O circuito é projetado utilizando um amplificador operacional 741 e um resistore, com o objetivo de isolar o sinal de entrada e transferi-lo para a saída sem alteração de amplitude ou polaridade, mantendo a eficiência no fornecimento de corrente.

A alimentação do CI 741 é fornecida com +12V na perna 7 e -12V na perna 4. A perna 3 do CI é conectada ao sinal de entrada. Saída do amplificador operacional (perna 6) é ligada na segunda perna do ci 741. Finalmente, um resistor é conectado da saída (perna 6) ao terra, completando o circuito de feedback e ajustando o comportamento do amplificador inversor.
