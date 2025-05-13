
# Sistema de Gerenciamento de Tarefas com Design Patterns

O sistema permite criar, decorar, notificar e gerenciar tarefas com foco didático na abordagem de 3 Design Patterns, sendo eles Design Pattern Criacional, Design Pattern Estrutural e Design Pattern Comportamental.

---
   ## Aluno:
- Daniel Salgado Magalhães


## Funcionalidades

### Parte 1 — Design Patterns Básicos
Design Pattern -> Tipo -> Implementação -> Mudança
* Factory Method -> Criacional -> Criação de tarefas com diferentes tipos (`pessoal`, `trabalho`, `estudo` e `lazer`) -> A mudança que foi feita é que agora é possível adicionar tarefas de lazer
* Decorator -> Estrutural -> Aplicação dinâmica de recursos como: alta prioridade, etiqueta colorida, data de vencimento -> A mudança que foi feita é que agora é possível qual a etapa o projeto está, entre etapa Inicial, Meio ou Final
* Observer -> Comportamental -> Notificação automática via tela, console e "email simulado" -> A mudança que foi feita é que agora é possível excluir o histórico do Observer

---

### Parte 2 — Design Patterns Avançados

Design Pattern -> Tipo -> Implementação
* Singleton -> Criacional -> Logger centralizado com histórico de ações de uma forma mais ampla que o Observer. Foi pensado para servir como uma plataforma de controle, que posteriormente pode ser salva em um banco de dados grande para puxar backups, por exemplo.
* Adapter -> Estrutural -> Conversão de tarefas simuladas de API externa para o sistema. Foi pensado para servir como um catálogo de tarefas, para em larga escala seja fornecido um documento com todas as tarefas feitas, estão sendo feitas e que estão por fazer
* Command -> Comportamental -> Suporte para desfazer ações como criação de tarefa. Foi pensado como forma de consertar tarefas criadas erradas, ou então que foram atualizadas erradas.
---

## Estrutura de Pastas

```

designpatterns/
├── index.html
├── css/
│   └── styles.css
├── js/
│   ├── app.js
│   ├── models/
│   │   ├── task.js
│   │   └── notification.js
│   ├── patterns/
│   │   ├── adapter.js
│   │   └── command.js
│   │   ├── decorator.js
│   │   ├── factory.js
│   │   ├── observer.js
│   │   ├── singleton.js
│   └── ui/
│       └── ui-controller.js

````

---

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/DanielSalgadoM7/designpatterns.git


2. Abra o arquivo `index.html` em um navegador, neste projeto não é necessário backend ou servidor.

---

## Tecnologias Utilizadas

* JavaScript (ES6)
* HTML5 + CSS3
* Bootstrap 5
* Design Patterns clássicos (GOF)


