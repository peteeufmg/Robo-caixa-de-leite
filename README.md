# Robô Carrinho Movido a Som (Grito)

Este projeto é um protótipo educativo de um carrinho controlado por som. Ele utiliza um circuito eletrônico simples para captar ruídos próximos ao microfone, amplificar o sinal e ativar um motor que movimenta o carrinho.

## Visão Geral

O robô é construído sobre um chassi de papelão, inspirado em caixa de leite, e foi desenvolvido como parte de uma atividade do PETEE-UFMG em parceria com o OptmaLab.

O circuito opera como um detector de som: o microfone de eletreto capta o grito ou ruído ambiente e converte a pressão sonora em um sinal elétrico fraco. Esse sinal entra em um amplificador baseado no LM741, onde é amplificado e condicionado. Em seguida, transistores fazem a chaveamento do motor DC, permitindo que a energia da bateria 9V seja dirigida ao motor apenas quando o som ultrapassa um limiar definido pelo potenciômetro. Assim, o carrinho permanece parado em silêncio e avança quando um som forte é detectado.

O funcionamento básico é:
- o microfone capta o som;
- o sinal de áudio é amplificado pelo circuito;
- o sinal amplificado aciona o motor DC;
- o robô se move quando o som é detectado.

## Objetivo do Projeto

- Demonstrar controle de um veículo simples por som.
- Construir um protótipo de baixo custo e fácil manutenção.
- Criar um projeto didático para exposições e demonstrações.

## Componentes Principais

- Microfone de eletreto 6x3 com terminal
- Circuito integrado LM741 (amplificador operacional)
- Transistor BC337-25
- Transistor 2N3904
- Capacitores disco cerâmico 104 (100 nF) x2
- Resistores 220 Ω x2
- Resistores 10 kΩ x2
- Resistor 180 kΩ x1
- Potenciômetro multivoltas 10 kΩ
- LED 5 mm
- Chave gangorra liga/desliga
- Conectores tipo bornes x2
- Motor DC 6V-9V
- Bateria 9V
- Quatro rodas e eixo traseiro com engrenagem
- Chassi de papelão / caixa de leite
- Protoboard para montagem do circuito

## Como Funciona

1. O microfone capta o ruído ou o grito próximo ao protótipo.
2. O sinal analógico é enviado para o amplificador operacional LM741.
3. O LM741, junto com resistores, transistores e capacitores, amplifica o sinal de entrada.
4. O sinal amplificado é usado para ativar o motor DC.
5. O motor move o carrinho e permite a locomoção do robô.

## Montagem

1. Fixe o protoboard no topo do chassi de papelão.
2. Conecte o microfone de eletreto à entrada do circuito.
3. Monte o LM741 e os transistores BC337-25 e 2N3904 no protoboard.
4. Insira os capacitores cerâmicos e os resistores conforme o esquema.
5. Ligue o potenciômetro 10 kΩ para ajuste da sensibilidade do som.
6. Conecte o motor DC e a bateria 9V.
7. Instale a chave liga/desliga entre a bateria e o circuito.
8. Monte as rodas e o eixo traseiro no chassi de papelão.
9. Verifique todas as conexões antes de energizar.

## Testes Iniciais

- Ligue o protótipo usando a chave gangorra.
- Fale ou bata palmas próximo ao microfone.
- Ajuste o potenciômetro para calibrar a sensibilidade do sistema.
- Observe se o motor gira somente quando o som é detectado.

## Manutenção

### Inspeção Visual
- Verifique se os fios não estão soltos ou com mau contato no protoboard.
- Confira a polaridade correta do microfone, transistores e alimentação.
- Garanta que o chassi de papelão esteja firme e as rodas girando livremente.

### Componentes Críticos
- Substitua a bateria 9V quando o motor ficar fraco ou não girar.
- Teste o microfone se o carrinho não responder a nenhum som.
- Cheque o motor DC separadamente para confirmar funcionamento.
- Se o LM741 estiver com mau funcionamento, ele pode ser substituído por outro operacional compatível.

### Ajustes
- Use o potenciômetro para ajustar a sensibilidade ao som.
- Caso o carrinho responda a ruídos de fundo, aumente a resistência do ajuste ou use um filtro adicional.
- Se o carrinho não se move, revise o esquema e certifique-se de que o sinal do amplificador está chegando ao motor.

### Reparo
- Troque componentes danificados um por um.
- Se o protoboard estiver desgastado, refaça a montagem em um novo protoboard ou em placa de circuito impresso.
- Para maior durabilidade, considere soldar as conexões em uma placa de circuito após validar o projeto.

## Melhoria e Evolução

- Adicionar um circuito de filtragem para reduzir ruídos indesejados.
- Substituir o LM741 por um amplificador operacional mais moderno e estável.
- Implementar um sensor de intensidade sonora ajustável com maior precisão.
- Usar um chassi mais resistente e peças plásticas ou impressas em 3D.

## Uso Educacional

Este protótipo é ideal para demonstrações em feiras de ciências e eventos acadêmicos. Ele oferece um exemplo prático de eletrônica analógica, sensores de som e controle de motores.

## Referências

- Projeto desenvolvido em parceria com o OptmaLab (UFMG) para o PETEE-UFMG.
- Baseado no relatório "Carrinho Movido a Som".
