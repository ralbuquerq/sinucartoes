# SinuCartões
O maior campeonato internacional de sinuca da equipe de cartões

# Formato
## 1º Classificatória
Primeiramente todos os jogadores irão jogar de 3-4 vezes (a ser definido) pontuando para a fase de mata-mata

### Pontuação:
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


## 2º Mata-mata
Dependendo do número de inscritos teremos final e semi final ou apenas final.

### Critérios de classificação:

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

# Inscritos

Branco
Diego
Felipe
Fernando
Giovanni Beltrame
Lucas Marques
Lucas Snow
Rafael Albuquerque
Ricardo
Umbelino