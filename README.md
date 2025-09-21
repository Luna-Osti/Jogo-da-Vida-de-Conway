# Jogo-da-Vida-de-Conway
Aplicação em java para calcular iterações de um Jogo da Vida de Conway aprimorado

==========================================
        INFORMAÇÕES — JOGO DA VIDA
==========================================

O que é o Jogo da Vida?

O Jogo da Vida (ou “Game of Life”) é um autômato celular criado por John Conway. É uma simulação onde células em um tabuleiro evoluem automaticamente, sem necessidade de interação do usuário durante as iterações.


Regras Originais do Jogo

Cada célula pode estar VIVA ou Morta, e o próximo estado depende dos vizinhos ao redor:

1.Uma célula viva com menos de 2 vizinhos vivos morre (solidão).

2.Uma célula viva com 2 ou 3 vizinhos vivos continua viva (sobrevivência).

3.Uma célula viva com mais de 3 vizinhos vivos morre (superpopulação).

4.Uma célula morta com exatamente 3 vizinhos se torna viva (reprodução).


Tipos de Células e Comportamentos

Neste jogo, cada célula tem um tipo específico representado por um caractere especial (por exemplo: ‘+’, ‘@’, ‘&’, ‘#’, ‘.’).

1.Clássica (‘+’) → Segue as regras originais de Conway.

2.Forte (‘@’) → Só morre com menos de 2 vizinhos vivos; revive com mais de 4.

3.Tímida (‘&’) → Morre se tiver qualquer vizinho vivo; revive se todos estiverem \tmortos.

4.Matemática (‘#’) → Vive se o número de vizinhos for ímpar; revive se for par.

5.Borda (‘.’) → Sempre morta; usada apenas para delimitar o tabuleiro.


Funcionalidades do Programa

-Exibir o tabuleiro com as células e suas bordas.

-Avançar uma única iteração ou várias iterações seguidas.

-Escolher quantas iterações avançar (1 ⪯ n ⪯ 100) e intervalo entre elas (0 ⪯ t ⪯ \t2000 ms).

-Editar manualmente o tabuleiro, alterando tipos e estado das células, e também tamanho do tabuleiro.

-Abrir e salvar arquivos com a configuração do jogo.

-Visualizar explicações sobre os tipos de células.



Arquivos de configuração

Cada arquivo contém:

Dois inteiros m e n (linhas e colunas).

m x n caracteres indicando tipos das células.

m x n bits (0 = morta, 1 = viva).

Exemplos disponíveis nos arquivos.

=============
CUIDADOS
============

-Durante a edição, CERTIFIQUE-SE QUE CADA TABULEIRO ESTEJA PREENCHIDO NO MESMO PADRÃO QUE ORIGINALMENTE CARREGADOS.

-Toda célula separada por um espaço.

-Ao editar o tamanho, certifique-se que o tabuleiro não possui irregularidades (linhas ou colunas maiores que outras), ou espaços e qebras de linha adicionais.


Objetivo do jogo:

Observar e explorar a evolução dos padrões das células. Não há pontuação nem condução de vitória: o foco é a experiência visual e a análise do comportamento emergente
======================================================================================================================
