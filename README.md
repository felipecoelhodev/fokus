# Fokus ⏱️

O **Fokus** é uma aplicação web de produtividade que combina a técnica Pomodoro com um sistema de gerenciamento de tarefas (To-Do List). O objetivo é ajudar o usuário a manter o foco em suas atividades e garantir intervalos de descanso necessários para manter a mente descansada.



## 🎯 Sobre o Projeto

Este projeto foi desenvolvido para oferecer uma experiência de imersão no trabalho ou estudo. Através da manipulação dinâmica do DOM e do uso de áudios relaxantes, o Fokus cria o ambiente perfeito para quem precisa de concentração.

## ✨ Funcionalidades

### 🕒 Temporizador Pomodoro
* **Três Modos:** 
    * **Foco:** 25 minutos (ajustável no código).
    * **Descanso Curto:** 5 minutos.
    * **Descanso Longo:** 15 minutos.
* **Interface Dinâmica:** O fundo, as imagens e os textos de incentivo alteram-se automaticamente conforme o modo selecionado.
* **Alertas Sonoros:** Notificações em áudio para início, pausa e conclusão dos ciclos.

### 📝 Gestão de Tarefas (CRUD)
* **Adicionar:** Crie novas tarefas detalhando no que você vai trabalhar.
* **Editar:** Altere o nome de tarefas já existentes através de uma interface intuitiva.
* **Persistência:** Suas tarefas ficam salvas no navegador através do `localStorage`, para que você não perca nada ao fechar a aba.
* **Conclusão Automática:** Ao finalizar um ciclo de foco, a tarefa selecionada é marcada como concluída automaticamente.
* **Limpeza:** Opções para remover tarefas concluídas ou deletar toda a lista.

### 🎵 Imersão Sonora
* Interruptor para ativar/desativar música ambiente relaxante durante o período de foco.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica e tags personalizadas.
* **CSS3:** Design responsivo (Desktop/Mobile), variáveis CSS e temas dinâmicos.
* **JavaScript (ES6+):** * Lógica de temporização (`setInterval`).
    * Manipulação de áudio (`Audio Context`).
    * Persistência com `LocalStorage`.
    * Comunicação entre módulos via `CustomEvents`.
* **Google Fonts:** Utilização das fontes *Montserrat*, *Prata* e *Unbounded*.

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/fokus.git](https://github.com/seu-usuario/fokus.git)
