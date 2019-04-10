# SinuCartões
O maior campeonato internacional de sinuca da equipe de cartões 🤘 ⚡️ 🎱

> Dúvidas e sugestões favor abrir uma issue


## Tabela das Partidas

> Gerada randomicamente por https://tabelas.alhur.es/

| Jogador 1          | Jogador 2          | Vencedor           | Vantagem
| ------------------ | ------------------ | ------------------ | :------:
| Branco             | Umbelino           |                    | [ ]
| Carlos             | Rodrigo            |                    | [ ]
| Diego              | Ricardo            |                    | [ ]
| Felipe             | Rafael Albuquerque |                    | [ ]
| Fernando           | Pedro              |                    | [ ]
| Giovane Derenevick | Nil                |                    | [ ]
| Giovanni Beltrame  | Maurício           |                    | [ ]
| Lucas Marques      | Lucas Snow         |                    | [ ]
| Branco             | Rodrigo            |                    | [ ]
| Umbelino           | Ricardo            |                    | [ ]
| Carlos             | Rafael Albuquerque |                    | [ ]
| Diego              | Pedro              |                    | [ ]
| Felipe             | Nil                |                    | [ ]
| Fernando           | Maurício           |                    | [ ]
| Giovane Derenevick | Lucas Snow         | Lucas Snow         | [X]
| Giovanni Beltrame  | Lucas Marques      |                    | [ ]
| Branco             | Ricardo            |                    | [ ]
| Rodrigo            | Rafael Albuquerque |                    | [ ]
| Umbelino           | Pedro              |                    | [ ]
| Carlos             | Nil                |                    | [ ]
| Diego              | Maurício           |                    | [ ]
| Felipe             | Lucas Snow         |                    | [ ]
| Fernando           | Lucas Marques      |                    | [ ]
| Giovane Derenevick | Giovanni Beltrame  |                    | [ ]

## Classificação Atual

| PT | VT | Jogador
| -: | -: | -------
| 03 | 01 | Lucas Snow
| 00 | 00 | Umbelino
| 00 | 00 | Rodrigo
| 00 | 00 | Ricardo
| 00 | 00 | Rafael Albuquerque
| 00 | 00 | Pedro
| 00 | 00 | Nil
| 00 | 00 | Maurício
| 00 | 00 | Lucas Marques
| 00 | 00 | Giovanni Beltrame
| 00 | 00 | Giovane Derenevick
| 00 | 00 | Fernando
| 00 | 00 | Felipe
| 00 | 00 | Diego
| 00 | 00 | Carlos
| 00 | 00 | Branco

## Regras
**As regras da partida devem ser combinadas entre os jogadores**

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
