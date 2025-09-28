# Exercícios BD (PT-BR)

Mais de **800 exercícios** em português, organizados por categorias, músculos trabalhados e nível de dificuldade.

Este repositório é uma versão **traduzida** do projeto original [free-exercise-db](https://github.com/yuhonas/free-exercise-db).

---

## 📂 Estrutura do Dataset

O dataset está disponível em **3 versões**, de acordo com o nível de tradução:

---

### 1. `exercises-ptbr-minimal.json`

Tradução básica contendo apenas:

* `id`
* `name` (nome do exercício)
* `instructions` (passo a passo em português)

Exemplo:

```json
{
  "name": "Abdominal 3/4",
  "instructions": [
    "Deite-se no chão e prenda os pés. As pernas devem estar flexionadas nos joelhos.",
    "Coloque as mãos atrás ou ao lado da cabeça. Comece com as costas no chão. Esta é a posição inicial.",
    "Flexione os quadris e a coluna para levantar o tronco em direção aos joelhos.",
    "No topo da contração, o tronco deve estar perpendicular ao chão. Inverta o movimento, descendo apenas 3/4 do caminho.",
    "Repita para a quantidade recomendada de repetições."
  ],
  "id": "3_4_Sit-Up"
}
```

---

### 2. `exercises-ptbr-partial-translation.json`

Tradução **parcial**:

* `name` e `instructions` em português
* Outras propriedades (como `category`, `level`, `primaryMuscles`, etc.) **em inglês**

Exemplo:

```json
{
  "name": "Abdominal 3/4",
  "force": "pull",
  "level": "beginner",
  "mechanic": "compound",
  "equipment": "body only",
  "primaryMuscles": [
    "abdominals"
  ],
  "secondaryMuscles": [],
  "instructions": [
    "Deite-se no chão e prenda os pés. As pernas devem estar flexionadas nos joelhos.",
    "Coloque as mãos atrás ou ao lado da cabeça. Comece com as costas no chão. Esta é a posição inicial.",
    "Flexione os quadris e a coluna para levantar o tronco em direção aos joelhos.",
    "No topo da contração, o tronco deve estar perpendicular ao chão. Inverta o movimento, descendo apenas 3/4 do caminho.",
    "Repita para a quantidade recomendada de repetições."
  ],
  "category": "strength",
  "images": [
    "3_4_Sit-Up/0.jpg",
    "3_4_Sit-Up/1.jpg"
  ],
  "id": "3_4_Sit-Up"
}
```

---

### 3. `exercises-ptbr-full-translation.json`

Tradução **completa**, onde todas as propriedades foram adaptadas para o português:

Exemplo:

```json
{
  "name": "Abdominal 3/4",
  "force": "puxar",
  "level": "iniciante",
  "mechanic": "composto",
  "equipment": "peso-do-corpo",
  "primaryMuscles": [
    "abdominais"
  ],
  "secondaryMuscles": [],
  "instructions": [
    "Deite-se no chão e prenda os pés. As pernas devem estar flexionadas nos joelhos.",
    "Coloque as mãos atrás ou ao lado da cabeça. Comece com as costas no chão. Esta é a posição inicial.",
    "Flexione os quadris e a coluna para levantar o tronco em direção aos joelhos.",
    "No topo da contração, o tronco deve estar perpendicular ao chão. Inverta o movimento, descendo apenas 3/4 do caminho.",
    "Repita para a quantidade recomendada de repetições."
  ],
  "category": "força",
  "images": [
    "3_4_Sit-Up/0.jpg",
    "3_4_Sit-Up/1.jpg"
  ],
  "id": "3_4_Sit-Up"
}
```

---

## 🚀 Como usar

* Escolha o arquivo que melhor se adapta ao seu caso (mínimo, parcial ou completo).
* Faça o parse do JSON no seu projeto e utilize os dados conforme necessário.

---

## 📌 Créditos

* Tradução e adaptação: **Este repositório**
* Base original: [free-exercise-db](https://github.com/yuhonas/free-exercise-db)
