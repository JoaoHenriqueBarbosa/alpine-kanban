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
- `Alt + ←` / `Alt + →` - Navega para o card na mesma posição na coluna adjacente

### Movimentação de Cards
- `Shift + ↑` / `Shift + ↓` - Move o card para cima/baixo na mesma coluna
- `Shift + ←` / `Shift + →` - Move o card para a coluna da esquerda/direita mantendo a mesma posição

### Movimentação de Tarefas
- `Ctrl + ↑` / `Ctrl + ↓` - Move a tarefa para cima/baixo dentro do card

### Edição
- `Enter` no título - Cria uma nova tarefa no topo do card
- `Ctrl + Enter` no título - Cria novo card abaixo do atual
- `Enter` em uma tarefa - Cria nova tarefa abaixo
- `Ctrl + Enter` em uma tarefa - Cria novo card abaixo do atual
- `Delete` no título - Exclui o card (com confirmação)
- `Delete` em uma tarefa - Exclui a tarefa imediatamente

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
