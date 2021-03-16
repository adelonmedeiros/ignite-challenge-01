<h1 align="center">
    <h1>Desafio 01 - Ignite Rockeatseat<h1/>
</h1>

## 💻 Sobre o desafio

Nesse desafio, colocamos em prática conceitos aprendidos no Chapter 1 - da jornada Ignite de React

O principal objetivo é a conclusão  de uma pequena aplicação de atividades a fazer, para treinar um pouco mais sobre manipulação do estado no React. 

- Adicionar uma nova tarefa
- Remover uma tarefa
- Marcar e desmarcar uma tarefa como concluída

## 🚀 components/TaskList.tsx

Esse é o componente responsável por todas as funcionalidades da aplicação, é um componente simples, mas onde colocamos em prática várias partes da manipulação do estado.

Concluímos as funcionalidades para as três funções presentes nesse arquivo, que são:

- **handleCreateNewTask**: Deve ser possível adicionar uma nova task no estado de `tasks`, com os campos `id` que deve ser gerado de forma aleatória, `title` que deve ser um texto e `isComplete` que deve iniciar como false.
- **handleToggleTaskCompletion:** Deve alterar o status de `isComplete` para uma task com um ID específico que é recebido por parâmetro.
- **handleRemoveTask:** Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.
