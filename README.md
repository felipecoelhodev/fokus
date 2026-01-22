# Fokus ⏱️

O **Fokus** é uma aplicação web de produtividade que combina um timer baseado na técnica Pomodoro com uma lista de tarefas (To-Do List). O objetivo é ajudar usuários a maximizar o foco em atividades específicas e gerenciar seus períodos de descanso de forma visual e auditiva.



## 🚀 Funcionalidades

### 🕒 Gerenciamento de Tempo (Pomodoro)
* **Três Modos:** 
     * **Foco:** Ciclos de 25 minutos.
    * **Descanso Curto:** Pausas de 5 minutos.
    * **Descanso Longo:** Pausas de 15 minutos.
* **Troca de Contexto Dinâmica:** A interface (fundo, imagens e textos) altera-se completamente de acordo com o modo selecionado através da manipulação do DOM e atributos `data-contexto`.
* **Feedback Auditivo:** Alertas sonoros para início, pausa e finalização dos ciclos, além de opção de música ambiente relaxante via interruptor (toggle).

### 📝 Gestão de Tarefas (CRUD)
* **Criação de Tarefas:** Adicione tarefas com descrições detalhadas.
* **Persistência de Dados:** Integração com `localStorage` para que as tarefas permaneçam salvas mesmo após fechar o navegador.
* **Foco Ativo:** Exibição em destaque da tarefa que está sendo executada no momento.
* **Ações em Massa:** Menu dropdown para limpar rapidamente tarefas concluídas ou remover toda a lista.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica e tags de formulário.
* **CSS3:** Layouts com Flexbox, variáveis nativas para temas dinâmicos, transições suaves e responsividade (Mobile/Tablet/Desktop).
* **JavaScript (ES6+):** * Manipulação de eventos e DOM.
    * Gerenciamento de áudio dinâmico.
    * Persistência de dados com objetos JSON e LocalStorage.



---

## 📂 Estrutura de Arquivos

* `index.html`: Estrutura principal da aplicação.
* `styles.css`: Estilização e lógica de temas (Contextos).
* `script.js`: Lógica principal do cronômetro e interações de áudio.
* `script-crud.js`: Lógica de gerenciamento das tarefas e armazenamento.

---

## ⚙️ Como executar o projeto

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/fokus.git](https://github.com/seu-usuario/fokus.git)
    ```
2.  **Navegue até a pasta:**
    ```bash
    cd fokus
    ```
3.  **Abra o arquivo principal:**
    Basta abrir o `index.html` em qualquer navegador moderno.

---

## 🎨 Design

A interface foi projetada para ser imersiva. As cores mudam conforme o estado mental desejado:
- **Roxo/Escuro:** Foco intenso.
- **Verde/Ciano:** Descanso curto.
- **Azul:** Descanso longo.

---
**Desenvolvido por felipecoelhodev.**
