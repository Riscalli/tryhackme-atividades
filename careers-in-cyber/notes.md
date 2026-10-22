# Inside a Computer System

**Sala:** https://tryhackme.com/room/insideacomputer
**Path:** Pre Security > Computer Fundamentals
**Data de conclusão:** 22/10/2026
**Dificuldade:** Fácil
**Tempo gasto:** [ex.: 45 min]

## Objetivo da sala
👌😁Entender quais são os componentes básicos de um computador, a função de cada um e o que acontece desde o momento em que ligamos a máquina até o sistema operacional ser carregado.

## Conceitos principais
- **Componentes de um computador:** todo computador é formado por peças com funções próprias que trabalham juntas. A sala compara essas peças com o corpo humano para facilitar a memorização.
  - Processador, Memória RAM, Armazenamento, Fonte de energia, SSD
- **UEFI (e BIOS):** firmware que inicia os componentes. A BIOS faz o mesmo papel, mas foi em grande parte substituída pela UEFI.
- **POST (Power-On Self Test):** teste feito na inicialização para verificar se os componentes estão presentes, configurados e funcionando.
- **Dispositivo de boot:** a UEFI mantém uma lista ordenada de onde procurar o sistema operacional.
- **Bootloader:** programa que carrega o sistema operacional do dispositivo de boot para a memória RAM e depois entrega o controle a ele.

## Processo de inicialização (boot) em ordem
1. Botão de energia: um sinal libera a energia da fonte.
2. O firmware (UEFI) inicia.
3. O POST testa os componentes.
4. A UEFI seleciona o dispositivo de boot.
5. O bootloader carrega o sistema operacional na RAM e entrega o controle.

## Dificuldades e como resolvi
Minha maior dificuldade foi com as novas expressões em Inglês, mas com analise do contexto foi facilitando.

## O que aprendi
Entendi que os componentes de um computador devem ser preservados para analise florence, que devem ser manuseados e indentificados para que a analise possa ser facil e concludente. Devemos fazer um relatorio de todas as peças aprendidas e as que não estão disponiveis devem ser descartadas.

## Como isso se conecta com minha carreira
Em um SOC, entender como o computador funciona ajuda a interpretar alertas e a saber onde um ataque pode acontecer. A sala destaca que o processo de boot é às vezes alvo de atacantes, e isso é conhecimento importante para quem monitora e defende sistemas. Também ajuda no meu trabalho com redes, porque é base para compreender as necessidades do cliente e os componentes a qual posso auxiliar-lo em resolver alguma discrepancia física.

## Próximos passos
- Próxima sala: Computer Types (Tipos de Computadores)
