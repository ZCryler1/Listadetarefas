# ✅ Desafio: Lista de Tarefas (To-Do List) com HTML, CSS e JavaScript
Desafio 1 do Copilot (do copilot para mim)

## 🎯 Objetivo
Criar uma aplicação web onde o usuário pode adicionar, visualizar, marcar como concluída e remover tarefas. Tudo salvo no `localStorage` (navegador).

---

## 🧰 Tecnologias permitidas
- HTML
- CSS
- JavaScript
- `localStorage` (para salvar as tarefas mesmo ao recarregar a página)

---

## 🧱 Funcionalidades

### 1. Adicionar Tarefa
- Campo de texto + botão "Adicionar".
- Ao clicar, a tarefa aparece na lista.

### 2. Listar Tarefas
- Tarefas são exibidas na tela.
- Se recarregar a página, a lista continua igual (graças ao `localStorage`).

### 3. Marcar como Concluída
- Clique em uma tarefa para riscar ou mudar a cor.
- Pode usar uma classe CSS `.concluida`.

### 4. Remover Tarefa
- Botão “🗑️” ao lado de cada tarefa para removê-la da lista e do localStorage.

---

## 🧠 Desafios extras (opcional)
- Botão "Limpar tudo"
- Filtro: mostrar todas / concluídas / não concluídas
- Editar uma tarefa já criada
- Tema claro/escuro com `localStorage`

---

## 💡 Dicas
- Use `addEventListener` para eventos de clique.
- Use `localStorage.setItem()` e `localStorage.getItem()` para salvar e recuperar tarefas.
- Trabalhe com arrays de objetos para organizar as tarefas.
- Salve o array como JSON com `JSON.stringify()` e recupere com `JSON.parse()`.

---

## 🗂️ Estrutura de Arquivos sugerida

```
todo-app/
├── index.html
├── style.css
└── script.js
```

---

## ✅ Entrega
- A aplicação deve funcionar 100% no navegador, sem precisar de servidor.
- Responsiva (opcional) para funcionar bem em celular também.



## O Readme foi escrito por IA e corrigido por mim.
- Este foi um desafio proposto pela própria IA, ele possui 3 niveis este é o nivel 1 o 2 e 3 vou postar em outro momento.
