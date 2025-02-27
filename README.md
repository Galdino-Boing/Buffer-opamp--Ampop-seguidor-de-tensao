# Buffer Op-Amp  
This project explores the versatility of operational amplifiers (Op-Amps) in configurations such as the voltage follower (buffer), with the goal of studying and applying techniques for signal isolation and amplification without altering its form. Using Op-Amps creatively, the project involves the construction and analysis of buffer circuits.

# Ampop seguido de tensão
Este projeto explora a versatilidade dos amplificadores operacionais (AMPops) em configurações como o seguidor de tensão (buffer), com o objetivo de estudar e aplicar técnicas de isolamento e amplificação de sinal sem alteração da sua forma. Utilizando AMPops de forma criativa, o projeto envolve a construção e análise de circuitos buffer.

# Objetivo  
Alterar a forma da onda de saída, com o propósito de isolar e transferir o sinal sem alteração de amplitude ou polaridade, utilizando um amplificador operacional em configuração seguidor de tensão (buffer).

# Utilidade  
Em vez de precisar criar uma fonte de tensão específica, este circuito utiliza um amplificador operacional 741 com três resistores para alterar a organização dos semiciclos do sinal de entrada, ajustando a forma da onda e controlando a tensão de saída.

**Mudança de polaridade:** Um amplificador operacional inversor inverte a polaridade do sinal de entrada, o que é útil em sistemas que exigem sinais com polaridade oposta, como em circuitos diferenciais e amplificadores de instrumentação. Entre as aplicações práticas, destacam-se:  
- Circuitos Diferenciais  
- Sistemas de Áudio  
- Sistemas de Controle  
- Conversores de Polaridade  
- Geradores de Sinal e Modulação  
- Circuitos Lógicos e de Processamento de Sinais  
- Circuitos de Comparação e Detecção  

# Materiais  
O circuito é projetado utilizando três resistores e um amplificador operacional 741, com o objetivo de inverter e amplificar o sinal de saída de forma eficiente.  

A alimentação do CI 741 é fornecida com +12V na perna 7 e -12V na perna 4. A perna 3 do CI é conectada ao terra (ground). O sinal de entrada (input) é aplicado através de um resistor na entrada negativa de sinal do amplificador operacional (perna 2). Um resistor é então conectado entre a entrada negativa de sinal (perna 2) e a saída do amplificador operacional (perna 6), estabelecendo o ganho do circuito. Finalmente, outro resistor é conectado da saída (perna 6) ao terra, completando o circuito de feedback e ajustando o comportamento do amplificador inversor.
