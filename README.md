<div align="center">

# Rotina — Alimentação & Treino

**App de uma página para acompanhar refeições e treino diário.** Marca o que cumpriu, vê a barra de progresso e mantém a sequência (streak). Tudo offline, direto no navegador.

</div>

---

## O que é

Um app pessoal que eu uso para manter a rotina em pé: checklist das refeições do dia e dos exercícios do dia, com navegação por data e histórico. Sem login, sem backend e sem build — os dados ficam no `localStorage` do próprio navegador.

## Funcionalidades

- 🍽️ **Alimentação** — checklist de **6 refeições**, progresso (`x/6`) e barra visual
- 💪 **Treino** — exercícios filtrados por **dia da semana**, com séries, descanso e um "como fazer" expansível em cada exercício
- 🔥 **Streak** — conta os dias seguidos em que a meta de refeições foi cumprida (até 60 dias)
- 📅 **Navegação por data** — botões anterior/próximo e um resumo da semana em pontos clicáveis
- 💾 **Persistência local** — tudo salvo no navegador (`localStorage`), sem servidor

## Como funciona por dentro

- Um único `index.html` com HTML + CSS + JavaScript vanilla
- Os dados (refeições e exercícios) são declarados como objetos JS no próprio arquivo
- O treino é um programa **calistênico em casa** — flexões, remada na mesa, uso de mochila e garrafas — dividido em grupos musculares por dia
- Estado do dia carregado/salvo por data, com o histórico de cada dia guardado à parte

## Como usar

Não precisa instalar nada. Abra o `index.html` no navegador.

```bash
git clone https://github.com/sergingroisman/rotina-simples.git
cd rotina-simples
# abra index.html, ou sirva localmente:
python3 -m http.server 8000
```

> O progresso fica salvo no `localStorage` — limpar os dados do navegador apaga o histórico.

## Stack

`HTML` · `CSS` · `JavaScript` (vanilla) — sem dependências, sem frameworks, sem etapa de build.

---

<div align="center">
<sub>Projeto pessoal · disciplina > motivação 💪</sub>
</div>
