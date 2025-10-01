# 📝 Tudo Vue - Lista de Tarefas

Um aplicativo simples e intuitivo de lista de tarefas desenvolvido com Vue.js 3, Bootstrap e Vite. Gerencie suas tarefas de forma eficiente com uma interface limpa

## ✨ Funcionalidades

- ✅ **Adicionar tarefas**: Cadastre novas tarefas facilmente
- 🔄 **Marcar como concluída**: Toggle para finalizar/reativar tarefas
- 🎯 **Filtros inteligentes**: Visualize todas, pendentes ou finalizadas
- 📊 **Contador de tarefas**: Acompanhe quantas tarefas estão pendentes
- ⚡ **Performance otimizada**: Construído com Vue 3 e Composition API

## 🚀 Tecnologias Utilizadas

- **Vue.js 3**
- **Vite**
- **Bootstrap 5**
- **JavaScript ES6+**

## 📦 Estrutura do Projeto

```
src/
├── App.vue
├── main.js
└── components/
    ├── Cabecalho.vue
    ├── Formulario.vue
    └── ListaDeTarefas.vue
```

## 🛠️ Instalação e Uso

### Pré-requisitos

- Node.js (versão 16 ou superior)
- npm ou yarn

### Instalação

1. Clone o repositório:

```sh
git clone https://github.com/Sulivan7/tudo-vue.git
cd tudo-vue
```

2. Instale as dependências:

```sh
npm install
```

3. Execute o projeto em modo de desenvolvimento:

```sh
npm run dev
```

4. Abra seu navegador em `http://localhost:5173`

### Build para Produção

```sh
npm run build
```

### Preview da Build

```sh
npm run preview
```

## 🎮 Como Usar

1. **Adicionar Tarefa**: Digite a descrição da tarefa no campo de texto e clique em "Cadastrar"
2. **Marcar como Concluída**: Clique no checkbox ao lado da tarefa
3. **Filtrar Tarefas**: Use o dropdown para ver todas, apenas pendentes ou apenas finalizadas
4. **Acompanhar Progresso**: O header mostra quantas tarefas ainda estão pendentes
