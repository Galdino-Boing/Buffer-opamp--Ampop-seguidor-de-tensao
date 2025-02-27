# Inverting opamp
  This project explores the versatility of operational amplifiers (Op-Amps) in various configurations, such as inverting amplifiers, with the goal of studying and applying different signal amplification techniques. Using Op-Amps creatively, the project involves the construction and analysis of amplifier circuits.
# Ampop inversor 
  Este projeto explora a versatilidade dos amplificadores operacionais (AMPops) em diversas configurações, como amplificadores inversores, com o objetivo de estudar e aplicar diferentes técnicas de amplificação de sinal. Utilizando AMPops de forma criativa, o projeto envolve a construção e análise de circuitos amplificadores.
  
  # Objetivo
Alterar a forma da onda de saída, com o propósito de inverter e amplificar o sinal, utilizando um amplificador operacional em configuração inversora.
  
  # Utilidade
  Mudança de polaridade: Um amplificador operacional inversor inverte a polaridade do sinal de entrada, o que é útil em sistemas que exigem sinais com polaridade oposta, como em circuitos diferenciais e amplificadores de instrumentação. Circuitos Diferenciais, Sistemas       de Áudio, Sistemas de Controle, Conversores de Polaridade, Geradores de Sinal e Modulação, Circuitos Lógicos e de Processamento de Sinais, Circuitos de Comparação e Detecção Importancia. 
  
  Em vez de precisar criar uma fonte de tensão específica, este circuito utiliza um amplificador operacional 741 com três resistores para alterar a organização dos semiciclos do sinal de entrada, ajustando a forma da onda e controlando a tensão de saída.

  # Materiais 
  Utilizando três resistores e um amplificador operacional 741, o circuito é projetado para inverter e amplificar o sinal de saída de forma eficiente.
  A alimentação do CI 741 é fornecida com +12V na perna 7 e -12V na perna 4. A perna 3 do CI é conectada ao terra (ground). O sinal de entrada (input) é aplicado através de um resistor na entrada negativa de sinal do amplificador operacional (perna 2). Um resistor é então conectado entre a entrada negativa de sinal(perna 2) e a saída do amplificador operacional (perna 6), estabelecendo o ganho do circuito. Finalmente, outro resistor é conectado da saída (perna 6) ao terra, completando o circuito de feedback e ajustando o comportamento do amplificador inversor.
