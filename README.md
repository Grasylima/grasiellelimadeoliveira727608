
Projeto desenvolvido como parte do processo seletivo, com o objetivo de consumir a API pública de registro de Pets e seus Tutores do Estado de Mato Grosso.

A aplicação é uma **SPA (Single Page Application)** desenvolvida em **React + TypeScript**, com foco em organização, legibilidade, boas práticas e soluções simples.

---

##Objetivo do Projeto

Permitir:
- Listar pets cadastrados
- Visualizar informações básicas dos pets
- Buscar pets por nome
- Consumir API autenticada
- Demonstrar organização de código, componentização e boas práticas de frontend

---

##Tecnologias Utilizadas

- React
- TypeScript
- Vite
- CSS puro
- Fetch API
- React Hooks
- Arquitetura em camadas (services / components)
---

##Autenticação

A autenticação é realizada via endpoint:

```
POST /autenticacao/login
```

O token retornado é utilizado nas chamadas subsequentes da API.

> A funcionalidade de refresh token (`PUT /autenticacao/refresh`) foi mapeada, porém não automatizada nesta versão, conforme priorização de escopo.

---
##Funcionalidades Implementadas

###Tela Inicial – Listagem de Pets
- GET /v1/pets
- Exibição em cards
- Nome do pet
- Busca por nome
- Layout responsivo
- Loading e estado vazio

---

##Funcionalidades Planejadas

- Paginação (10 por página)
- Tela de detalhamento do pet
- Exibição de tutor
- Cadastro e edição de pet
- Cadastro e edição de tutor
- Upload de fotos
- Vinculação Pet–Tutor


---

##Como Executar o Projeto


##Autoria

Grasielle Lima de Oliveira
Processo seletivo 
