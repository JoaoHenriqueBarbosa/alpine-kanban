# Alpine Kanban
Aplicação de Kanban com reatividade simples utilizando Alpine.js

Um quadro Kanban minimalista que roda diretamente no navegador, sem necessidade de backend. Utiliza Alpine.js para a interatividade e localStorage para persistência dos dados.

## Características

- Interface limpa e intuitiva
- Funciona offline
- Salva automaticamente no localStorage
- Suporte a drag & drop
- Exportação e importação de dados em JSON
- Navegação completa por teclado

## Atalhos de Teclado

### Navegação
- `↑` / `↓` - Navega entre elementos editáveis na mesma coluna
- `Alt + ↑` / `Alt + ↓` - Navega apenas entre títulos dos cards na mesma coluna
- `Alt + ←` / `Alt + →` - Navega para o card mais próximo na coluna adjacente

### Movimentação de Cards
- `Shift + ↑` / `Shift + ↓` - Move o card para cima/baixo na mesma coluna
- `Shift + ←` / `Shift + →` - Move o card para a coluna da esquerda/direita
- Mantendo `Alt` pressionado preserva a posição vertical relativa do card

### Edição
- `Enter` no título de um card sem tarefas - Cria uma nova tarefa
- `Enter` em uma tarefa - Cria nova tarefa abaixo
- `Ctrl + Enter` em uma tarefa - Cria novo card abaixo do atual

## Como usar

### Online
Acesse: [https://joaohenriquebarbosa.github.io/alpine-kanban/](https://joaohenriquebarbosa.github.io/alpine-kanban/)

### Offline
Existem duas formas de baixar o arquivo para uso offline:

- Forma 1: Baixe o arquivo index.html diretamente:
  - Clique [aqui](https://joaohenriquebarbosa.github.io/alpine-kanban?download=true)

- Forma 2: Clone o repositório:
  ```bash
  git clone https://github.com/joaohenriquebarbosa/alpine-kanban.git
  ```

Após baixar, basta abrir o arquivo HTML em qualquer navegador moderno. Não requer instalação ou configuração adicional.
