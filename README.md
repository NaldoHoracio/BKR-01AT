# Projeto Final da Disciplina de Circuitos Impressos
## BKR-01AT

"Eu gostaria que fosse desenvolvido um equipamento que fosse capaz de medir as vibrações e a temperatura de um gerador em funcionamento. Vou chamá-lo de BKR:01AT. Acredito que, a partir dos dados obtidos, poderemos tirar algumas conclusões que podem aumentar o tempo de vida útil do equipamento. O equipamento deve enviar as leituras para uma central a qual já está pronta se comunica com os sensores em uma rede mesh."

Os equipamentos selecionados para desenvolver esse equipamento são:
- Acelerômetro: LIS2DHTR;
- MCU + Bluetooth: nRF52832-QFAB;
- LED indicativo de sistema ligado (livre escolha, cor verde)
- LED indicativo de problema de vibração detectado (livre escolha, cor vermelha)
- LED indicativo de problema de temperatura detectado (livre escolha, cor vermelha)
- Botão de reset (livre escolha, baixo custo)
- Botão de função 1 (livre escolha, baixo custo)
- Botão de função 2 (livre escolha, baixo custo)
- Alimentação por bateria CR2032 de 3,0V (não precisa comprar, mas precisa ter os furos para soldar a pilha)
- Outros componentes necessários são de livre escolha inclusive a antena;

Restrições:
1. A placa deve ter componentes de apenas um lado;
2. A logomarca da empresa deve aparecer na camada Silk na parte de baixo da placa (onde não tem componentes)
3. A placa tem que ter o formato quadrado nas dimensões 60x60mm
4. A placa deve ter furos de montagem nas quinas superior esquerda e inferior direito com diâmetro de 3,2mm e o centro do furo deve estar a 5mm das duas bordas;
5. A placa será montada por equipamentos automáticos portanto deve conter dois fiduciais posicionados na maior distância possível entre eles na placa;
6. O nome do projeto deve estar presente na parte frontal da placa acompanhado com a versão P1;
7. As bordas a placa devem ser arredondadas;
8. O resistores utilizados devem ser 0402;
9. O equipamento deve ter interface de gravação TC2030;
10. As trilhas de alimentação devem ter 12mil de espessuras e as de sinal 6mil;
11. O Clearence da placa deve ser de 6mil;
12. A trilha da antena deve ser calculada utilizando coplanar wave guide para obter uma impedância de 50 ohms;
13. A trilha deve ser protegida com um shielding por todo o seu comprimento e deve ser cercada por um plano de ground com stitching aplicado a ele.