# 📖 Guia Rápido sobre Git

## 📌 O que é e para que serve o Git
O **Git** é um sistema de controle de versão distribuído, criado por **Linus Torvalds** em 2005.  
Ele é usado para **controlar o histórico de alterações** de arquivos, principalmente em projetos de desenvolvimento de software.  
Com o Git, você pode trabalhar em equipe sem perder o histórico, gerenciar versões e integrar mudanças de forma segura.

---

## 🔹 Principais funcionalidades e importância

### ⚙️ Funcionalidades
- 📜 **Controle de versão**: Armazena e gerencia diferentes versões do projeto.
- 🤝 **Trabalho colaborativo**: Permite que vários desenvolvedores trabalhem no mesmo projeto simultaneamente.
- 🌿 **Branching e Merging**: Criação de ramificações independentes para desenvolver novas funcionalidades e depois mesclar com o código principal.
- 📂 **Histórico detalhado**: Cada mudança é registrada com autor, data e mensagem.
- 🔍 **Rastreamento de alterações**: É possível saber exatamente o que foi modificado e por quem.

### ⭐ Importância
- 🚫 Evita **perda de código**.
- 📡 Facilita a **colaboração em equipe**.
- 🧪 Permite **testar novas ideias** sem impactar o código principal.
- 📋 Melhora a **organização** e **documentação** do projeto.

---

## 💻 Principais comandos Git

### 🛠️ Configuração inicial
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```

### 📂 Criar ou clonar repositório
```bash
git init                # Inicia um repositório Git na pasta atual
git clone URL           # Clona um repositório remoto para sua máquina
```

### 📊 Verificar status e histórico
```bash
git status              # Mostra o estado atual do repositório
git log                 # Mostra o histórico de commits
```

### ✍️ Adicionar e confirmar alterações
```bash
git add arquivo.txt     # Adiciona um arquivo específico
git add .               # Adiciona todas as alterações
git commit -m "mensagem" # Confirma as alterações no histórico
```

### 🌿 Trabalhar com branches
```bash
git branch              # Lista as branches
git branch nome-branch  # Cria uma nova branch
git checkout nome-branch # Troca para a branch especificada
git merge nome-branch   # Mescla uma branch com a atual
```

### 📤 Enviar e receber alterações
```bash
git push origin main    # Envia alterações para o repositório remoto
git pull origin main    # Recebe alterações do repositório remoto
```

---

## 📚 Recursos para aprender mais
- [📘 Documentação Oficial do Git](https://git-scm.com/doc)
- [🧩 Guia Interativo Git](https://learngitbranching.js.org/)
- [💻 GitHub Docs](https://docs.github.com/)

---

✍️ **Autor:** Vitor Caruso de Souza
📅 **Última atualização:** 2025
