# SinuCartões
O maior campeonato internacional de sinuca da equipe de cartões 🤘 ⚡️ 🎱

## Tabela das Partidas

| Jogador 1   | Jogador 2   | Vencedor    | Vantagem
| ----------- | ----------- | ----------- | :------:
| Branco      | Umbelino    | Umbelino    | [ ]
| Carlos      | Rodrigo     | Rodrigo     | [X]
| Diego       | Ricardo     | Ricardo     | [X]
| Felipe      | Albuquerque | Felipe      | [X]
| Fernando    | Pedro       | Pedro       | [ ]
| Derenevick  | Nil         | Nil         | [ ]
| Beltrame    | Maurício    | Maurício    | [ ]
| Marques     | Snow        | Marques     | [X]
| Branco      | Rodrigo     |             | [ ]
| Umbelino    | Ricardo     | Ricardo     | [X]
| Carlos      | Albuquerque | Albuquerque | [X]
| Diego       | Pedro       |             | [ ]
| Felipe      | Nil         | Felipe      | [ ]
| Fernando    | Maurício    | Fernando    | [ ]
| Derenevick  | Snow        | Snow        | [X]
| Beltrame    | Marques     | Marques     | [X]
| Branco      | Ricardo     | Branco      | [ ]
| Rodrigo     | Albuquerque | Albuquerque | [X]
| Umbelino    | Pedro       | Pedro       | [ ]
| Carlos      | Nil         | Nil         | [X]
| Diego       | Maurício    | Maurício    | [X]
| Felipe      | Snow        | Snow        | [X]
| Fernando    | Marques     | Fernando    | [X]
| Derenevick  | Beltrame    | Beltrame    | [ ]

## Classificação Atual

| PT | VT | Jogador
| -: | -: | -------
| 07 | 02 | Ricardo
| 06 | 02 | Snow
| 06 | 02 | Nil
| 06 | 02 | Maurício
| 06 | 02 | Marques
| 06 | 02 | Fernando
| 06 | 02 | Albuquerque
| 05 | 02 | Felipe
| 04 | 02 | Pedro
| 03 | 01 | Umbelino
| 03 | 01 | Rodrigo
| 03 | 01 | Branco
| 03 | 01 | Beltrame
| 02 | 00 | Derenevick
| 00 | 00 | Diego
| 00 | 00 | Carlos

## Regras
**As regras de cada partida devem ser combinadas entre os jogadores**

## Formato do campeonado
### 1º Classificatória
Primeiramente todos os jogadores irão jogar de 3 vezes pontuando para a fase de mata-mata

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


### 2º Mata-mata
Dependendo do número de inscritos teremos final e semi final ou apenas final.

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
