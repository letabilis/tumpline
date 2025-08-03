---
title: "Business Process Modeling Notation"
description: "A notação oficial para BPM"
author: "sdLn"
date: "2025-08-03"
categories: ["Governança de TI"]
---


# Business Process Modeling Notation (BPMN)

## Definição

## Objetivo
Prover recursos e elementos para modelar os processos de negócio.

Permitir a compreensão dos processos de negócio por analistas de negócio, gerentes, técnicos, usuários e stakeholders.

## Elementos
### Objetos de Fluxo
#### Gateways
São denominados de Pontos de Ativação de caráter condicional ou incondicional.

Atuam como decisores de fluxo do processo e são representados por diamantes/losangos.

O **Gateway Baseado em Eventos** utiliza lógica semelhante ao **Gateway Exclusivo**: o primeiro evento a ocorrer será o que dará sequência no fluxo do processo. 
Em vez de um dado/informação como condição, o que determina a sequência do fluxo é a ocorrência de um evento. 
Um caso de uso frequente é quando os próximos passos dependem de eventos distintos: por exemplo – a chegada de uma mensagem OU uma condição que se torne verdadeira OU um determinado prazo atingido. 

![Figura 1 - Gateways Disponíveis](assets/bpmn/gateways.png)

#### Eventos
Representam a espera de que um fato aconteça para iniciar/prosseguir a execução do processo ou então sinalizar de que o processo produzirá a ocorrência de um fato durante ou ao término de sua execução.

Existem diversas forma de iniciar uma modelagem BPMN:
    - evento de ínicio
    - o recebimento de uma mensagem
    - uma temporal
    - regra de negócio
    - erro


![Figura 2 - Eventos Disponíveis](assets/bpmn/eventos.png)

#### Atividades
Representam um trabalho que será executado dentro do processo, podem ser divididas em subprocessos, de caráter composto, ou tarefas, de caráter atômico (não pode ser decomposta), e são simbolizados por quadrados.

|   Tipos/Características            | Execução  |  Comportamento                                                |     Ícones           |
|---------------|-----------|---------------------------------------------------------------|----------------------|
| Automatizadas | Softwares |      Consistentes, rápidas, menos sujeitas a enganos humanos. |    Engrenagens/Raios |
|  Manuais      | Pessoas   | Potenciais atrasos, variabilidade, enganos humanos.           |    Mãos/Nenhum       |



![Figura 3 - Atividades Disponíveis](assets/bpmn/atividades.png)




