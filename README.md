[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zHqjFsRx)
# Diagnóstico de retomada - Teoria da Computação

Esta atividade serve para mapear o que você já domina sobre linguagens formais, autômatos, gramáticas e computabilidade.

Responda individualmente. Use suas palavras. Se usar IA depois da primeira tentativa, registre o uso na seção 7.

## 1. Mapa do que eu lembro

Marque cada tópico como: lembro bem, lembro parcialmente, não lembro, nunca vi ou não tenho certeza.

- alfabeto: lembro bem
- cadeia: lembro bem
- linguagem: não lembro
- gramática: não lembro
- autômato finito: lembro parcialmente
- linguagem regular: não lembro
- linguagem livre de contexto: não lembro
- linguagem sensível ao contexto: não lembro
- linguagem irrestrita: não lembro
- hierarquia de Chomsky: não lembro
- computabilidade: lembro parcialmente
- máquina de Turing: lembro parcialmente

## 2. Definições com exemplo

Explique, com suas palavras e com um exemplo simples, usando o alfabeto `Sigma = {a, b}`.

1. O que é um alfabeto?
  - Um conjunto de símbolos de uma linguagem
2. O que é uma cadeia?
  - Um conjunto de símbolos dentro de um alfabeto
3. O que é uma linguagem?
   - Não sei definir exatamente
4. O que é uma gramática?
   - Também não sei definir

## 3. Linguagens

Considere as linguagens:

```text
L1 = { w em {0,1}* | w termina com 01 }
L2 = { a^n b^n | n >= 0 }
L3 = { a^n b^n c^n | n >= 0 }
```

Para cada linguagem:

1. Três palavras que pertencem à linguagem; 
2. Duas palavras que não pertencem;
3. Qual classe ela provavelmente se encaixa;
4. Motivo em linguagem simples.

L1: 
   1: 101, 001, 0001
   2: 110, 1010
   3: não sei
   4: não sei

L2 e L3: não sei o que quer dizer "a^n" e etc.

## 4. Autômato finito

Considere o autômato abaixo, sobre o alfabeto `{0,1}`:

```text
Estados: q0, q1, q2
Estado inicial: q0
Estado final: q2

Transições:
q0 --0--> q1
q0 --1--> q0
q1 --0--> q1
q1 --1--> q2
q2 --0--> q1
q2 --1--> q0
```
Responda:

1. Qual linguagem esse autômato parece reconhecer?
   - Binário
2. Execute manualmente as cadeias abaixo e diga se aceita ou rejeita:
   - `01`
   - `101`
   - `100`
   - `1101`
   - `111`
3. Monte uma tabela curta mostrando o caminho dos estados para pelo menos duas cadeias.

## 5. Gramática

Considere a gramática:

```text
S -> aS
S -> b
```

Responda:

1. Gere cinco cadeias produzidas por essa gramática.
2. Descreva a linguagem em palavras.
3. Essa gramática parece regular, livre de contexto ou outra classe? Justifique de forma simples.

## 6. Ponto de dificuldade

Escolha um tópico da lista inicial e escreva:

1. o que você entende dele;
2. onde você se confunde;
   - Desde linguagem até hierarquia de chomsky, eu não sei.
3. que tipo de explicação ajudaria: desenho, exemplo, exercício guiado, analogia, prova passo a passo ou lista curta.
   - Definição do conceito e exemplo por um desenho


## 7. Uso de IA, se houver (não usei)

Se você usou IA depois da primeira tentativa, registre:

```text
Pergunta feita:
Resumo da resposta:
Como eu verifiquei:
O que eu alterei na minha resposta:
O que ainda não entendi:
```

## Submissão no Moodle

Depois de finalizar, copie no Moodle:

```text
Repositório:
Commit final:
Autoavaliação: nível atual, maior dificuldade e tópico que precisa ser retomado.
```
