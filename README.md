# Dado Online

Dado 3D que roda direto no navegador, sem login e sem backend.

**Jogar:** https://fau009.github.io/dado-online/

## O que faz

- Role **1 ou 2 dados** com animação 3D (pulo, giro e quique).
- Com 2 dados, mostra a **soma** e cada valor (ex.: 3 + 4).
- **Histórico** das últimas 12 jogadas, com botão **Zerar histórico**. Trocar a quantidade de dados também zera o histórico.
- Toque nos dados ou aperte **espaço** para rolar.
- Sorteio com `crypto.getRandomValues`, resultado justo de 1 a 6.
- Funciona no celular e respeita a preferência de movimento reduzido do sistema.

## Estrutura

Um único `index.html` (HTML, CSS e JS puros). Publicado pelo GitHub Pages a partir da branch `gh-pages`, que é um espelho da `main`: depois de cada alteração na `main`, enviar também para a `gh-pages` (`git push origin main:gh-pages`).
