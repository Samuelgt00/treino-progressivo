# Treino PRO

App de registo de treinos de ginásio, numa única página (`index.html`).

- Cronómetro de treino com pausa e estimativa de calorias.
- Planos de treino A, B, C, A-2 e C-2, com registo de repetições e carga por série.
- Vídeo de demonstração (YouTube) para cada exercício.
- Gráfico de evolução de cargas (Chart.js).

Os dados ficam guardados no próprio navegador (`localStorage`), por isso o
histórico é por dispositivo.

## Editar

- Exercícios de cada treino: procure `estruturaTreino` em `index.html`.
- Vídeos dos exercícios: procure `bancoVideosExercicios`.
- Cores: o bloco `:root` no topo do `<style>`.

## Publicar

O site é estático, sem passo de build: basta publicar a pasta tal como está.
