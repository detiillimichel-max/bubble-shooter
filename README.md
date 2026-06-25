# BOLHÃO – Bubble Shooter 🫧

Jogo de Bubble Shooter completo em HTML/CSS/JS puro, zero dependências, mobile-first.

## Como jogar

- **Aponte** o dedo (ou mouse) para mirar
- **Toque/clique** para atirar a bolha
- Forme grupos de **3 ou mais bolhas** da mesma cor para explodir
- Bolhas soltas (sem conexão com o teto) **caem automaticamente** — bônus de pontos!
- Limpe o campo antes de acabar as **43 bolhas** para vencer

## Mecânicas

| Recurso | Detalhe |
|---|---|
| Ricochete | A bolha bate nas paredes laterais |
| Linha de mira | Pontilhado mostra a trajetória |
| Próxima bolha | Exibida ao lado do atirador |
| Pop em cadeia | Bolhas soltas caem e valem pontos extras |
| Linha de perigo | Se as bolhas chegarem à linha vermelha, game over |

## Pontuação

| Ação | Pontos |
|---|---|
| Grupo de 3+ bolhas | 10 pts por bolha |
| Bolha caída | 5 pts por bolha |
| ★★★ | ≥ 30 bolhas restantes |
| ★★☆ | ≥ 15 bolhas restantes |
| ★☆☆ | Passou com qualquer pontuação |

## Fases

| Fase | Layout |
|---|---|
| 1 | Triângulo roxo/teal/verde |
| 2 | Faixas coloridas em diagonal |
| 3 | Faixas horizontais puras |
| 4 | Mix aleatório intenso |
| 5 | Grade densa 9 colunas × 6 linhas |

## Deploy (GitHub Pages)

```bash
# 1. Crie repositório público no GitHub
# 2. Faça upload de index.html e README.md
# 3. Settings → Pages → Source: main / root
# Acesse: https://SEU_USUARIO.github.io/NOME_DO_REPO
```

## Estrutura técnica

```
index.html   — jogo completo (single file, ~790 linhas)
README.md    — este arquivo
```

**Tecnologias:** Canvas 2D API · Web Audio API · CSS animations · touch events

## Créditos

Criado por **Michel Detilli** — Bom Jesus dos Perdões-SP, 2026  
v1.0 — 5 fases, física de ricochete, grid hexagonal, efeitos sonoros
