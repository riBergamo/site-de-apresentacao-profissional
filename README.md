# 📅 Sistema de Agendamento
Apresentação Profissional com Agendamento por Banco de Dados
___

## 🚀 Funcionalidades

### 🔹 Back-end (API REST - Spring Boot)
- **Criar agendamento** com os campos:
  - Nome
  - Data de nascimento
  - Serviço
  - Data
  - Horário
  - Mensagem (opcional)
- **Listar agendamentos** já existentes (ainda não add no front).
- **Excluir (cancelar) agendamento** (ainda não add no front).
- **Validação de conflito**: não permite agendar em um horário já ocupado (`409 Conflict`).

### 🔹 Front-end (HTML + JS)
- **Página principal** (`index.html`): apresentação do profissional, com informações de contato e botão para agendar.
- **Página de agendamento** (`agendamento.html`):
  - Formulário para registrar novos agendamentos.
  - Avisos ao usuário:
    - ✅ Mensagem de sucesso quando o agendamento é salvo.
    - ⚠️ Aviso quando o horário já está ocupado (`409`).

---

## 🛠️ Tecnologias Utilizadas
- **Back-end**: Java, Spring Boot, Spring Data JPA, Hibernate, Banco de Dados (PostgreSQL).
- **Front-end**: HTML, CSS, JavaScript (fetch API).
- **Ferramentas**: IntelliJ IDEA, Git/GitHub.

---

## ▶️ Como rodar o projeto

### 🔧 Back-end
1. Clone este repositório:
   ```bash
   https://github.com/riBergamo/site-de-apresentacao-profissional.git
