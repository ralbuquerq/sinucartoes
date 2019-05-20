# SinuCartões 
O maior campeonato internacional de sinuca da equipe de cartões e Sustentação 🤘 ⚡️ 🎱


```

## Classificação Atual

| PT | VT | Jogador
| -: | -: | -------
| 10 | 04 | Pedro
| 09 | 03 | Maurício
| 09 | 03 | Fernando
| 09 | 03 | Albuquerque
| 07 | 02 | Snow
| 07 | 02 | Ricardo
| 07 | 02 | Branco
| 06 | 02 | Umbelino
| 06 | 02 | Nil
| 06 | 02 | Marques
| 06 | 02 | Felipe
| 05 | 02 | Beltrame
| 03 | 01 | Rodrigo
| 02 | 01 | Diego
| 02 | 01 | Carlos
| 02 | 00 | Derenevick

### "Primeira" rodada

| Jogador 1   | Jogador 2   | Vencedor    | Vantagem
| ----------- | ----------- | ----------- | :------: 
| Snow        | Vidotti		   |             | [ ] 
 Carlos 	 Bruno L.		[  ] 
 Mauricio	 Zanelatto		[  ] 
 Beltrame 	 Zanese		[  ] 
 Fernando 	 Bortoli		[  ] 
 Pedro 	 Bosquetto		[  ] 
 Diego 	 Hunas		[  ] 
 Branco 	 Cunha		[  ] 
 Umbelino 	 Stella		[  ] 
 Albuquerque 	 Higor		[  ] 
 Ricardo 	 Felipe		[  ] 
 Leticia	 Nil		[  ] 
 Derenevick 	 Rodrigo		[  ] 


| Jogador 1   | Jogador 2   | Vencedor    | Vantagem
| ----------- | ----------- | ----------- | :------:
| Branco      | Umbelino    | Umbelino    | [ ]
| Carlos      | Rodrigo     | Rodrigo     | [ ]
| Diego       | Ricardo     | Ricardo     | [X]
| Felipe      | Albuquerque | Felipe      | [X]
| Fernando    | Pedro       | Pedro       | [ ]
| Derenevick  | Nil         | Nil         | [ ]
| Beltrame    | Maurício    | Maurício    | [ ]
| Marques     | Snow        | Marques     | [X]
| Branco      | Rodrigo     | Branco      | [X]
| Umbelino    | Ricardo     | Ricardo     | [X]
| Carlos      | Albuquerque | Albuquerque | [X]
| Diego       | Pedro       | Pedro       | [X]
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
