# SinuCartoes&Support  
O maior campeonato internacional de sinuca das equipes cartões e Sustentação 🤘 ⚡️ 🎱

######
**
######

## Regras
**As regras de cada partida devem ser combinadas entre os jogadores**

**<<<Numero de bolas de vantagem será um critério de desempate (Tipo um saldo de gols)>>

## Formato do campeonato

### 1º Classificatória
Primeiramente todos os jogadores irão jogar contra todos pontuando para a fase de mata-mata

#### Pontuação:
A cada partida serão distribuidos 3 pontos entre os jogadores. Se no final da partida nenhuma bola ficar na mesa fica configurado vitória sem vantagem.

Tipo | Pontuação
---- | ---------
Vitória com vantagem | 3
Vitória sem vantagem | 2
Derrota sem vantagem | 1

```javascript
if (numeroDeBolasNaMesa > 0) {
    vencedor = 3;
    perdedor = 0;
} else {
    vencedor = 2;
    perdedor = 1;
} 
```
```

## Classificação Atual

| C  | PT | VT | GP | Jogador
| -: | -: | -: | -: | -------
| 01 | 22 | 07 | 14 | Maurício
| 02 | 18 | 06 |  3 | Albuquerque
| 03 | 12 | 04 |  2 | Beltrame
| 04 | 11 | 04 |  2 | Fernando
| 05 | 10 | 03 |  4 | Derenevick
| 06 | 08 | 03 | -3 | Umbelino
| 07 | 07 | 02 | -7 | Branco
| 08 | 06 | 02 |  0 | Pedro
| 09 | 05 | 02 |  2 | Daniel
| 10 | 06 | 02 |  0 | Rodrigo
| 11 | 05 | 02 |  1 | Diego
| 12 | 05 | 02 |  0 | Carlos
| 13 | 04 | 01 |  1 | Letícia
| 14 | 03 | 01 |  3 | Hunas (Felipe)
| 15 | 03 | 01 |  1 | Zanellato
| 16 | 01 | 00 |  0 | Ricardo
| 17 | 00 | 00 | -1 | Vidotti
| 18 | 00 | 00 | -6 | Bortoli (André)
| 19 | 00 | 00 | 00 | Snow
| 00 | 00 | 00 | 00 | Felipe
| 00 | 00 | 00 | 00 | Stella
| 00 | 00 | 00 | 00 | Cunha (Bruno)
| 00 | 00 | 00 | 00 | Bosquetto (Marcio)
| 00 | 00 | 00 | 00 | Zanese (Paulo)
| 00 | 00 | 00 | 00 | Bruno L.
| 00 | 00 | 00 | 00 | Camargo

### 1º FASE

| Player 1    | Player 2    | Vencedor | Vantagem | Saldo    |
| ----------- | ----------- | -------- | -------- | :------: |

| RODADA 1    | ----------- | -------- | -------- | ---------|
| ----------- | ----------- | -------- | -------- | :------: |
| Snow        | Vidotti     |          |   [ ]    |   [ ]    |
| Carlos      | Bruno L.    |          |   [ ]    |   [ ]    |
| Mauricio    | Zanellato   |          |   [ ]    |   [ ]    |
| Beltrame    | Zanese      |          |   [ ]    |   [ ]    |
| Fernando    | Bortoli     |          |   [ ]    |   [ ]    |
| Pedro       | Bosquetto   |          |   [ ]    |   [ ]    |
| Diego       | Hunas       |          |   [ ]    |   [ ]    |
| Branco      | Cunha       |          |   [ ]    |   [ ]    |
| Umbelino    | Stella      |          |   [ ]    |   [ ]    |
| Albuquerque | Camargo     |          |   [ ]    |   [ ]    |
| Ricardo     | Felipe      |          |   [ ]    |   [ ]    |
| Leticia     | Daniel      |          |   [ ]    |   [ ]    |
| Derenevick  | Rodrigo     |          |   [ ]    |   [ ]    |

| RODADA 2    | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Bruno L.    |          |   [ ]    |   [ ]    |
| Vidotti     | Zanellato   |          |   [ ]    |   [ ]    |
| Carlos      | Zanese      |          |   [ ]    |   [ ]    |
| Mauricio    | Bortoli     | Mauricio |   [x]    |   [3]    |
| Beltrame    | Bosquetto   |          |   [ ]    |   [ ]    |
| Fernando    | Hunas       |          |   [ ]    |   [ ]    |
| Pedro       | Cunha       |          |   [ ]    |   [ ]    |
| Diego       | Stella      |          |   [ ]    |   [ ]    |
| Branco      | Camargo     |          |   [ ]    |   [ ]    |
| Umbelino    | Felipe      |          |   [ ]    |   [ ]    |
| Albuquerque | Daniel      | Daniel   |   [ ]    |   [0]    |
| Ricardo     | Rodrigo     |          |   [ ]    |   [ ]    |
| Leticia     | Derenevick  |          |   [ ]    |   [ ]    |

| RODADA 3    | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Zanellato   |          |   [ ]    |   [ ]    |
| Bruno L.    | Zanese      |          |   [ ]    |   [ ]    |
| Vidotti     | Bortoli     |          |   [ ]    |   [ ]    |
| Carlos      | Bosquetto   |          |   [ ]    |   [ ]    |
| Mauricio    | Hunas       | Mauricio |   [x]    |   [3]    |
| Beltrame    | Cunha       |          |   [ ]    |   [ ]    |
| Fernando    | Stella      |          |   [ ]    |   [ ]    |
| Pedro       | Camargo     |          |   [ ]    |   [ ]    |
| Diego       | Felipe      |          |   [ ]    |   [ ]    |
| Branco      | Daniel      |          |   [ ]    |   [ ]    |
| Umbelino    | Rodrigo     | Rodrigo  |   [ ]    |   [0]    |
| Albuquerque | Derenevick  |          |   [ ]    |   [ ]    |
| Ricardo     | Leticia     |          |   [ ]    |   [ ]    |

| RODADA 4    | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Zanese      |          |   [ ]    |   [ ]    |
| Zanellato   | Bortoli     |          |   [ ]    |   [ ]    |
| Bruno L.    | Bosquetto   |          |   [ ]    |   [ ]    |
| Vidotti     | Hunas       |          |   [ ]    |   [ ]    |
| Carlos      | Cunha       |          |   [ ]    |   [ ]    |
| Mauricio    | Stella      |          |   [ ]    |   [ ]    |
| Beltrame    | Camargo     |          |   [ ]    |   [ ]    |
| Fernando    | Felipe      |          |   [ ]    |   [ ]    |
| Pedro       | Daniel      |          |   [ ]    |   [ ]    |
| Diego       | Rodrigo     |          |   [ ]    |   [ ]    |
| Branco      | Derenevick  |Derenevick|   [x]    |   [2]    |
| Umbelino    | Leticia     |          |   [ ]    |   [ ]    |
| Albuquerque | Ricardo     |Albuquerqu|   [ ]    |   [0]    |

| RODADA 5    | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Bortoli     |          |   [ ]    |   [ ]    |
| Zanese      | Bosquetto   |          |   [ ]    |   [ ]    |
| Zanellato   | Hunas       |          |   [ ]    |   [ ]    |
| Bruno L.    | Cunha       |          |   [ ]    |   [ ]    |
| Vidotti     | Stella      |          |   [ ]    |   [ ]    |
| Carlos      | Camargo     |          |   [ ]    |   [ ]    |
| Mauricio    | Felipe      |          |   [ ]    |   [ ]    |
| Beltrame    | Daniel      |          |   [ ]    |   [ ]    |
| Fernando    | Rodrigo     |          |   [ ]    |   [ ]    |
| Pedro       | Derenevick  |          |   [ ]    |   [ ]    |
| Diego       | Leticia     |          |   [ ]    |   [ ]    |
| Branco      | Ricardo     |          |   [ ]    |   [ ]    |
| Umbelino    | Albuquerque | Umbelino |   [x]    |   [1]    |

| RODADA 6    | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Bosquetto   |          |   [ ]    |   [ ]    |
| Bortoli     | Hunas       |          |   [ ]    |   [ ]    |
| Zanese      | Cunha       |          |   [ ]    |   [ ]    |
| Zanellato   | Stella      |          |   [ ]    |   [ ]    |
| Bruno L.    | Camargo     |          |   [ ]    |   [ ]    |
| Vidotti     | Felipe      |          |   [ ]    |   [ ]    |
| Carlos      | Daniel      |          |   [ ]    |   [ ]    |
| Mauricio    | Rodrigo     |          |   [ ]    |   [ ]    |
| Beltrame    | Derenevick  |          |   [ ]    |   [ ]    |
| Fernando    | Leticia     |          |   [ ]    |   [ ]    |
| Pedro       | Ricardo     |          |   [ ]    |   [ ]    |
| Diego       | Albuquerque |          |   [ ]    |   [ ]    |
| Branco      | Umbelino    | Umbelino |   [ ]    |   [0]    |

| RODADA 7    | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Hunas       |          |   [ ]    |   [ ]    |
| Bosquetto   | Cunha       |          |   [ ]    |   [ ]    |
| Bortoli     | Stella      |          |   [ ]    |   [ ]    |
| Zanese      | Camargo     |          |   [ ]    |   [ ]    |
| Zanellato   | Felipe      |          |   [ ]    |   [ ]    |
| Bruno L.    | Daniel      |          |   [ ]    |   [ ]    |
| Vidotti     | Rodrigo     |          |   [ ]    |   [ ]    |
| Carlos      | Derenevick  |Derenevick|   [x]    |   [2]    |
| Mauricio    | Leticia     |          |   [ ]    |   [ ]    |
| Beltrame    | Ricardo     |          |   [ ]    |   [ ]    |
| Fernando    | Albuquerque |Albuquerqu|   [x]    |   [2]    |
| Pedro       | Umbelino    | Pedro    |   [x]    |   [1]    |
| Diego       | Branco      | Diego    |   [x]    |   [1]    |

| RODADA 8    | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Cunha       |          |   [ ]    |   [ ]    |
| Hunas       | Stella      |          |   [ ]    |   [ ]    |
| Bosquetto   | Camargo     |          |   [ ]    |   [ ]    |
| Bortoli     | Felipe      |          |   [ ]    |   [ ]    |
| Zanese      | Daniel      |          |   [ ]    |   [ ]    |
| Zanellato   | Rodrigo     |          |   [ ]    |   [ ]    |
| Bruno L.    | Derenevick  |          |   [ ]    |   [ ]    |
| Vidotti     | Leticia     |          |   [ ]    |   [ ]    |
| Carlos      | Ricardo     |          |   [ ]    |   [ ]    |
| Mauricio    | Albuquerque | Mauricio |   [ ]    |   [0]    |
| Beltrame    | Umbelino    | Beltrame |   [x]    |   [3]    |
| Fernando    | Branco      | Fernando |   [x]    |   [2]    |
| Pedro       | Diego       |          |   [ ]    |   [ ]    |

| RODADA 9    | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Stella      |          |   [ ]    |   [ ]    |
| Cunha       | Camargo     |          |   [ ]    |   [ ]    |
| Hunas       | Felipe      |          |   [ ]    |   [ ]    |
| Bosquetto   | Daniel      |          |   [ ]    |   [ ]    |
| Bortoli     | Rodrigo     |          |   [ ]    |   [ ]    |
| Zanese      | Derenevick  |          |   [ ]    |   [ ]    |
| Zanellato   | Leticia     |          |   [ ]    |   [ ]    |
| Bruno L.    | Ricardo     |          |   [ ]    |   [ ]    |
| Vidotti     | Albuquerque |          |   [ ]    |   [ ]    |
| Carlos      | Umbelino    |          |   [ ]    |   [ ]    |
| Mauricio    | Branco      | Mauricio |   [x]    |   [2]    |
| Beltrame    | Diego       |          |   [ ]    |   [ ]    |
| Fernando    | Pedro       | Fernando |   [ ]    |   [0]    |

| RODADA 10   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Camargo     |          |   [ ]    |   [ ]    |
| Stella      | Felipe      |          |   [ ]    |   [ ]    |
| Cunha       | Daniel      |          |   [ ]    |   [ ]    |
| Hunas       | Rodrigo     |          |   [ ]    |   [ ]    |
| Bosquetto   | Derenevick  |          |   [ ]    |   [ ]    |
| Bortoli     | Leticia     |          |   [ ]    |   [ ]    |
| Zanese      | Ricardo     |          |   [ ]    |   [ ]    |
| Zanellato   | Albuquerque |          |   [ ]    |   [ ]    |
| Bruno L.    | Umbelino    |          |   [ ]    |   [ ]    |
| Vidotti     | Branco      |          |   [ ]    |   [ ]    |
| Carlos      | Diego       |          |   [ ]    |   [ ]    |
| Mauricio    | Pedro       | Mauricio |   [x]    |   [1]    |
| Beltrame    | Fernando    |          |   [ ]    |   [ ]    |

| RODADA 11   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Felipe      |          |   [ ]    |   [ ]    |
| Camargo     | Daniel      |          |   [ ]    |   [ ]    |
| Stella      | Rodrigo     |          |   [ ]    |   [ ]    |
| Cunha       | Derenevick  |          |   [ ]    |   [ ]    |
| Hunas       | Leticia     |          |   [ ]    |   [ ]    |
| Bosquetto   | Ricardo     |          |   [ ]    |   [ ]    |
| Bortoli     | Albuquerque |Albuquerqu|   [x]    |   [3]    |
| Zanese      | Umbelino    |          |   [ ]    |   [ ]    |
| Zanellato   | Branco      |          |   [ ]    |   [ ]    |
| Bruno L.    | Diego       |          |   [ ]    |   [ ]    |
| Vidotti     | Pedro       |          |   [ ]    |   [ ]    |
| Carlos      | Fernando    | Carlos   |   [x]    |   [3]    |
| Mauricio    | Beltrame    | Mauricio |   [x]    |   [3]    |

| RODADA 12   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Daniel      |          |   [ ]    |   [ ]    |
| Felipe      | Rodrigo     |          |   [ ]    |   [ ]    |
| Camargo     | Derenevick  |          |   [ ]    |   [ ]    |
| Stella      | Leticia     |          |   [ ]    |   [ ]    |
| Cunha       | Ricardo     |          |   [ ]    |   [ ]    |
| Hunas       | Albuquerque | Hunas    |   [x]    |   [3]    |
| Bosquetto   | Umbelino    |          |   [ ]    |   [ ]    |
| Bortoli     | Branco      |          |   [ ]    |   [ ]    |
| Zanese      | Diego       |          |   [ ]    |   [ ]    |
| Zanellato   | Pedro       |          |   [ ]    |   [ ]    |
| Bruno L.    | Fernando    |          |   [ ]    |   [ ]    |
| Vidotti     | Beltrame    |          |   [ ]    |   [ ]    |
| Carlos      | Mauricio    | Mauricio |   [x]    |   [4]    |

| RODADA 13   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Rodrigo     |          |   [ ]    |   [ ]    |
| Daniel      | Derenevick  |          |   [ ]    |   [ ]    |
| Felipe      | Leticia     |          |   [ ]    |   [ ]    |
| Camargo     | Ricardo     |          |   [ ]    |   [ ]    |
| Stella      | Albuquerque |          |   [ ]    |   [ ]    |
| Cunha       | Umbelino    |          |   [ ]    |   [ ]    |
| Hunas       | Branco      |          |   [ ]    |   [ ]    |
| Bosquetto   | Diego       |          |   [ ]    |   [ ]    |
| Bortoli     | Pedro       |          |   [ ]    |   [ ]    |
| Zanese      | Fernando    |          |   [ ]    |   [ ]    |
| Zanellato   | Beltrame    |          |   [ ]    |   [ ]    |
| Bruno L.    | Mauricio    |          |   [ ]    |   [ ]    |
| Vidotti     | Carlos      |          |   [ ]    |   [ ]    |

| RODADA 14   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Derenevick  |          |   [ ]    |   [ ]    |
| Rodrigo     | Leticia     |          |   [ ]    |   [ ]    |
| Daniel      | Ricardo     |          |   [ ]    |   [ ]    |
| Felipe      | Albuquerque |          |   [ ]    |   [ ]    |
| Camargo     | Umbelino    |          |   [ ]    |   [ ]    |
| Stella      | Branco      |          |   [ ]    |   [ ]    |
| Cunha       | Diego       |          |   [ ]    |   [ ]    |
| Hunas       | Pedro       |          |   [ ]    |   [ ]    |
| Bosquetto   | Fernando    |          |   [ ]    |   [ ]    |
| Bortoli     | Beltrame    |          |   [ ]    |   [ ]    |
| Zanese      | Mauricio    |          |   [ ]    |   [ ]    |
| Zanellato   | Carlos      |          |   [ ]    |   [ ]    |
| Bruno L.    | Vidotti     |          |   [ ]    |   [ ]    |

| RODADA 15   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Leticia     | Leticia  |   [x]    |   [1]    |
| Derenevick  | Ricardo     |          |   [ ]    |   [ ]    |
| Rodrigo     | Albuquerque | Rodrigo  |   [x]    |   [1]    |
| Daniel      | Umbelino    |          |   [ ]    |   [ ]    |
| Stella      | Pedro       |          |   [ ]    |   [ ]    |
| Branco      | Diego       |          |   [ ]    |   [ ]    |
| Cunha       | Fernando    |          |   [ ]    |   [ ]    |
| Hunas       | Beltrame    |          |   [ ]    |   [ ]    |
| Bosquetto   | Mauricio    |          |   [ ]    |   [ ]    |
| Bortoli     | Carlos      |          |   [ ]    |   [ ]    |
| Zanese      | Vidotti     |          |   [ ]    |   [ ]    |
| Zanellato   | Bruno L.    |          |   [ ]    |   [ ]    |
| Felipe      | Camargo     |          |   [ ]    |   [ ]    |

| RODADA 16   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Ricardo     |          |   [ ]    |   [ ]    |
| Leticia     | Albuquerque |          |   [ ]    |   [ ]    |
| Derenevick  | Umbelino    |          |   [ ]    |   [ ]    |
| Rodrigo     | Branco      | Branco   |   [ ]    |   [0]    |
| Daniel      | Diego       |          |   [ ]    |   [ ]    |
| Felipe      | Pedro       |          |   [ ]    |   [ ]    |
| Camargo     | Fernando    |          |   [ ]    |   [ ]    |
| Stella      | Beltrame    |          |   [ ]    |   [ ]    |
| Cunha       | Mauricio    |          |   [ ]    |   [ ]    |
| Hunas       | Carlos      |          |   [ ]    |   [ ]    |
| Bosquetto   | Vidotti     |          |   [ ]    |   [ ]    |
| Bortoli     | Bruno L.    |          |   [ ]    |   [ ]    |
| Zanese      | Zanellato   |          |   [ ]    |   [ ]    |

| RODADA 17   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Albuquerque |          |   [ ]    |   [ ]    |
| Ricardo     | Umbelino    |          |   [ ]    |   [ ]    |
| Leticia     | Branco      | Branco   |   [ ]    |   [0]    |
| Derenevick  | Diego       | Diego    |   [ ]    |   [0]    |
| Rodrigo     | Pedro       |          |   [ ]    |   [ ]    |
| Daniel      | Fernando    |          |   [ ]    |   [ ]    |
| Felipe      | Beltrame    |          |   [ ]    |   [ ]    |
| Camargo     | Mauricio    |          |   [ ]    |   [ ]    |
| Stella      | Carlos      |          |   [ ]    |   [ ]    |
| Cunha       | Vidotti     |          |   [ ]    |   [ ]    |
| Hunas       | Bruno L.    |          |   [ ]    |   [ ]    |
| Bosquetto   | Zanellato   |          |   [ ]    |   [ ]    |
| Bortoli     | Zanese      |          |   [ ]    |   [ ]    |

| RODADA 18   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Umbelino    |          |   [ ]    |   [ ]    |
| Albuquerque | Branco      |Albuquerqu|   [ ]    |   [0]    |
| Ricardo     | Diego       |          |   [ ]    |   [ ]    |
| Leticia     | Pedro       |          |   [ ]    |   [ ]    |
| Derenevick  | Fernando    |          |   [ ]    |   [ ]    |
| Rodrigo     | Beltrame    | Beltrame |   [x]    |   [1]    |
| Daniel      | Mauricio    | Daniel   |   [x]    |   [2]    |
| Felipe      | Carlos      |          |   [ ]    |   [ ]    |
| Camargo     | Vidotti     |          |   [ ]    |   [ ]    |
| Stella      | Bruno L.    |          |   [ ]    |   [ ]    |
| Cunha       | Zanellato   |          |   [ ]    |   [ ]    |
| Hunas       | Zanese      |          |   [ ]    |   [ ]    |
| Bosquetto   | Bortoli     |          |   [ ]    |   [ ]    |

| RODADA 19   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Branco      |          |   [ ]    |   [ ]    |
| Umbelino    | Diego       |          |   [ ]    |   [ ]    |
| Albuquerque | Pedro       |Albuquerqu|   [x]    |   [1]    |
| Ricardo     | Fernando    |          |   [ ]    |   [ ]    |
| Leticia     | Beltrame    |          |   [ ]    |   [ ]    |
| Derenevick  | Mauricio    |          |   [ ]    |   [ ]    |
| Rodrigo     | Carlos      |          |   [ ]    |   [ ]    |
| Daniel      | Vidotti     |          |   [ ]    |   [ ]    |
| Felipe      | Bruno L.    |          |   [ ]    |   [ ]    |
| Camargo     | Zanellato   |          |   [ ]    |   [ ]    |
| Stella      | Zanese      |          |   [ ]    |   [ ]    |
| Cunha       | Bortoli     |          |   [ ]    |   [ ]    |
| Hunas       | Bosquetto   |          |   [ ]    |   [ ]    |

| RODADA 20   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Diego       |          |   [ ]    |   [ ]    |
| Branco      | Pedro       |          |   [ ]    |   [ ]    |
| Umbelino    | Fernando    | Fernando |   [x]    |   [2]    |
| Albuquerque | Beltrame    |Albuquerqu|   [x]    |   [2]    |
| Ricardo     | Mauricio    |          |   [ ]    |   [ ]    |
| Leticia     | Carlos      |          |   [ ]    |   [ ]    |
| Derenevick  | Vidotti     |Derenevick|   [x]    |   [1]    |
| Rodrigo     | Bruno L.    |          |   [ ]    |   [ ]    |
| Daniel      | Zanellato   |          |   [ ]    |   [ ]    |
| Felipe      | Zanese      |          |   [ ]    |   [ ]    |
| Camargo     | Bortoli     |          |   [ ]    |   [ ]    |
| Stella      | Bosquetto   |          |   [ ]    |   [ ]    |
| Cunha       | Hunas       |          |   [ ]    |   [ ]    |

| RODADA 21   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Pedro       |          |   [ ]    |   [ ]    |
| Diego       | Fernando    |          |   [ ]    |   [ ]    |
| Branco      | Beltrame    | Beltrame |   [ ]    |   [0]    |
| Umbelino    | Mauricio    | Umbelino |   [ ]    |   [0]    |
| Albuquerque | Carlos      |          |   [ ]    |   [ ]    |
| Ricardo     | Vidotti     |          |   [ ]    |   [ ]    |
| Leticia     | Bruno L.    |          |   [ ]    |   [ ]    |
| Derenevick  | Zanellato   |Zanellato |   [x]    |   [1]    |
| Rodrigo     | Zanese      |          |   [ ]    |   [ ]    |
| Daniel      | Bortoli     |          |   [ ]    |   [ ]    |
| Felipe      | Bosquetto   |          |   [ ]    |   [ ]    |
| Camargo     | Hunas       |          |   [ ]    |   [ ]    |
| Stella      | Cunha       |          |   [ ]    |   [ ]    |

| RODADA 22   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Fernando    |          |   [ ]    |   [ ]    |
| Pedro       | Beltrame    | Pedro    |   [ ]    |   [0]    |
| Diego       | Mauricio    |          |   [ ]    |   [ ]    |
| Branco      | Carlos      | Branco   |   [ ]    |   [0]    |
| Umbelino    | Vidotti     |          |   [ ]    |   [ ]    |
| Albuquerque | Bruno L.    |          |   [ ]    |   [ ]    |
| Ricardo     | Zanellato   |          |   [ ]    |   [ ]    |
| Leticia     | Zanese      |          |   [ ]    |   [ ]    |
| Derenevick  | Bortoli     |          |   [ ]    |   [ ]    |
| Rodrigo     | Bosquetto   |          |   [ ]    |   [ ]    |
| Daniel      | Hunas       |          |   [ ]    |   [ ]    |
| Felipe      | Cunha       |          |   [ ]    |   [ ]    |
| Camargo     | Stella      |          |   [ ]    |   [ ]    |

| RODADA 23   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Beltrame    |          |   [ ]    |   [ ]    |
| Fernando    | Mauricio    | Fernando |   [ ]    |   [0]    |
| Pedro       | Carlos      |          |   [ ]    |   [ ]    |
| Diego       | Vidotti     |          |   [ ]    |   [ ]    |
| Branco      | Bruno L.    |          |   [ ]    |   [ ]    |
| Umbelino    | Zanellato   |          |   [ ]    |   [ ]    |
| Albuquerque | Zanese      |          |   [ ]    |   [ ]    |
| Ricardo     | Bortoli     |          |   [ ]    |   [ ]    |
| Leticia     | Bosquetto   |          |   [ ]    |   [ ]    |
| Derenevick  | Hunas       |          |   [ ]    |   [ ]    |
| Rodrigo     | Cunha       |          |   [ ]    |   [ ]    |
| Daniel      | Stella      |          |   [ ]    |   [ ]    |
| Felipe      | Camargo     |          |   [ ]    |   [ ]    |

| RODADA 24   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Mauricio    |          |   [ ]    |   [ ]    |
| Beltrame    | Carlos      | Beltrame |   [x]    |   [3]    |
| Fernando    | Vidotti     |          |   [ ]    |   [ ]    |
| Pedro       | Bruno L.    |          |   [ ]    |   [ ]    |
| Diego       | Zanellato   |          |   [ ]    |   [ ]    |
| Branco      | Zanese      |          |   [ ]    |   [ ]    |
| Umbelino    | Bortoli     |          |   [ ]    |   [ ]    |
| Albuquerque | Bosquetto   |          |   [ ]    |   [ ]    |
| Ricardo     | Hunas       |          |   [ ]    |   [ ]    |
| Leticia     | Cunha       |          |   [ ]    |   [ ]    |
| Derenevick  | Stella      |          |   [ ]    |   [ ]    |
| Rodrigo     | Camargo     |          |   [ ]    |   [ ]    |
| Daniel      | Felipe      |          |   [ ]    |   [ ]    |

| RODADA 25   | ----------- | -------- | ---------| ---------|
| ----------- | ----------- | -------- | :------: | :------: |
| Snow        | Carlos      |          |   [ ]    |   [ ]    |
| Mauricio    | Vidotti     |          |   [ ]    |   [ ]    |
| Beltrame    | Bruno L.    |          |   [ ]    |   [ ]    |
| Fernando    | Zanellato   |          |   [ ]    |   [ ]    |
| Pedro       | Zanese      |          |   [ ]    |   [ ]    |
| Diego       | Bortoli     |          |   [ ]    |   [ ]    |
| Branco      | Bosquetto   |          |   [ ]    |   [ ]    |
| Umbelino    | Hunas       |          |   [ ]    |   [ ]    |
| Albuquerque | Cunha       |          |   [ ]    |   [ ]    |
| Ricardo     | Stella      |          |   [ ]    |   [ ]    |
| Leticia     | Camargo     |          |   [ ]    |   [ ]    |
| Derenevick  | Felipe      |          |   [ ]    |   [ ]    |
| Rodrigo     | Daniel      |          |   [ ]    |   [ ]    |


####################### - Fim da 1 Fase - ########################################

### 2º Mata-mata

Teremos quartas de final. Cada embate deverá ser disputado com "melhor de 3".

#### Critérios de classificação:

1. Pontuação
2. Número de vitórias

```javascript
jogadores.sort((j1, j2) => {
    if (j1.pontos != j2.pontos) {
        return j2.pontos - j1.pontos;
    }

    return j2.vitorias - j1.vitorias;
});
```
