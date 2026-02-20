# 📚 Sistema de Biblioteca Corporativa – Power Apps

Aplicação desenvolvida na **Power Platform** para controle interno de empréstimos de livros corporativos, permitindo consulta, reserva e acompanhamento de status em tempo real.

---

## 🎯 Objetivo do Projeto

Criar um sistema simples, intuitivo e eficiente para controle de empréstimos de livros dentro do ambiente corporativo, reduzindo controles manuais e garantindo rastreabilidade das solicitações.

---

## 🚀 Funcionalidades Implementadas

✔ Consulta de livros disponíveis  
✔ Visualização de detalhes (capa + sinopse)  
✔ Reserva de livros  
✔ Atualização automática de status  
✔ Tela “Meus Empréstimos” filtrada por usuário logado  
✔ Atualização em tempo real da disponibilidade  

---

## 🧠 Regras de Negócio

- Um livro só pode ser reservado se estiver com status **Disponível**
- O usuário visualiza apenas seus próprios empréstimos
- Ao enviar solicitação, o status inicial é definido como **Solicitado**
- A disponibilidade é atualizada automaticamente após reserva

---

## 🏗 Arquitetura da Solução

Usuário  
⬇  
Power Apps (Canvas App)  
⬇  
Power Automate (Fluxos de atualização e controle)  
⬇  
Base de Dados (Excel Online / SharePoint)

---

## 🛠 Tecnologias Utilizadas

- Power Apps (Canvas)
- Power Fx
- Power Automate
- Excel Online / SharePoint
- Microsoft 365

---

## 📂 Estrutura do Repositório

## 🖼️ Telas do Sistema

### Tela Inicial
![Tela Inicial](imagens/tela%20inicial2.png)

### Consulta de Livros
![Tela Consulta](imagens/tela%20livros.png)

### Detalhes do Livro
![Tela Detalhes](imagens/tela%20consulta.png)

### Reserva
![Tela Reserva](imagens/tela%20reserva.png)

### Meus Empréstimos
![Tela Empréstimos](imagens/tela%20empréstimos.png)

---

## 📈 Benefícios Gerados

- Eliminação de controle manual
- Maior organização do acervo
- Redução de conflitos de reserva
- Centralização das informações
- Melhoria na experiência do usuário interno

---

## 📄 Documentação Completa

O manual detalhado do sistema está disponível no arquivo:

![Documentação](documentacao.pdf)

---

## 🔐 Observação

Este projeto foi desenvolvido como solução corporativa interna.  
Dados sensíveis e informações institucionais foram omitidos para fins de portfólio.

---

## 👨‍💻 Desenvolvedor

Paulo Rodrigues  
Especialista em Power Platform  
Automação de Processos | Power Apps | Power Automate

---
