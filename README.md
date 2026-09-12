# desafio-projeto-visaojr

Projeto desenvolvido como parte do processo seletivo para o Programa Trainee da **Visão Jr.**, simulando um fluxo seguro e colaborativo de desenvolvimento com Git e GitHub.

---

## 📌 Cenário e Objetivo
Demonstrar na prática a resolução de gargalos comuns em equipes de desenvolvimento (como sobrescrita de arquivos e falta de rastreabilidade) através de um fluxo estruturado de branches e Pull Requests.

---

## 🛠️ Tecnologias Utilizadas
* HTML5 (marcação semântica e acessibilidade)
* CSS3 (estilização e boas práticas com BEM)
* Git & GitHub (controle de versão, branches e PRs)
* GitHub Projects (gestão visual das tarefas)

---

## 🌿 Fluxo de Branches Adotado
O versionamento seguiu o fluxo seguro de branches por funcionalidade:

* `main`: Código de produção final integrado.
* `dev`: Branch base de integração contínua das tarefas concluídas.
* `task/nome-da-tarefa`: Branches temporárias para desenvolvimento de cada feature:
  * `task/criacao-pagina-principal` (TASK-01)
  * `task/implementacao-header` (TASK-02)
  * `task/implementacao-footer` (TASK-03)

Cada entrega passou por abertura de Pull Request apontando para a `dev`, simulação de code review, merge e posterior integração final para a `main`.

---
