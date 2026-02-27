# Testes de API — CRUD de Usuários

## Descrição do Projeto

Este repositório contém casos de teste manuais para validação dos endpoints de CRUD (Create, Read, Update e Delete) da API Serverest.

O objetivo deste projeto é praticar testes de API utilizando requisições HTTP, validação de status code e validação de estrutura de resposta (response body).

---

## Objetivo

Validar o funcionamento dos seguintes fluxos:

- Cadastro de usuário
- Listagem de usuário específico
- Atualização de usuário
- Exclusão de usuário

---

## Tecnologias e Ferramentas Utilizadas

- Postman
- API Serverest
- Git
- GitHub

---

## Endpoints Testados

| Método | Endpoint            | Descrição                 |
|--------|--------------------|---------------------------|
| POST   | /usuarios          | Criar novo usuário        |
| GET    | /usuarios/{_id}    | Listar usuário específico |
| PUT    | /usuarios/{_id}    | Atualizar usuário         |
| DELETE | /usuarios/{_id}    | Deletar usuário           |

---

## Validações Realizadas

- Verificação de Status Code
- Validação de campos obrigatórios no response body
- Validação de mensagens retornadas pela API
- Teste do fluxo completo de CRUD

---
## Postman Collection

Este repositório também contém a collection do Postman utilizada para executar as requisições e validar os endpoints de CRUD de usuários.

A collection pode ser importada diretamente no Postman para reprodução dos testes.

## Estrutura do Projeto

- Casos de teste documentados em formato Markdown
- Organização clara dos fluxos testados
- Postman collection

---

## Próximos Passos

- Implementar testes negativos
- Implementar testes automatizados
- Melhorar documentação com evidências (prints ou export da collection)

---

## Autor

Projeto desenvolvido para fins de estudo e prática em Quality Assurance.


# English Version

# API Testing — User CRUD

## Project Description
This repository contains **manual test cases** for validating the CRUD (Create, Read, Update, Delete) endpoints of the Serverest API.  

The goal of this project is to practice **API testing** using HTTP requests, status code validation, and response body structure validation.

---

## Objective
Validate the following flows:

- User registration  
- Retrieve a specific user  
- Update a user  
- Delete a user  

---

## Technologies and Tools Used
- Postman  
- Serverest API  
- Git  
- GitHub  

---

## Endpoints Tested

| Method | Endpoint          | Description          |
|--------|-----------------|--------------------|
| POST   | /usuarios        | Create a new user   |
| GET    | /usuarios/{_id}  | Retrieve specific user |
| PUT    | /usuarios/{_id}  | Update user         |
| DELETE | /usuarios/{_id}  | Delete user         |

---

## Validations Performed
- Status code verification  
- Validation of required fields in the response body  
- Validation of messages returned by the API  
- Full CRUD flow testing  

---

## Postman Collection
This repository also contains the **Postman collection** used to execute the requests and validate the user CRUD endpoints.  

The collection can be **imported directly into Postman** to reproduce the tests.

---

## Project Structure
- Test cases documented in **Markdown**  
- Clear organization of tested flows  
- Postman collection included  

---

## Next Steps
- Implement **negative tests**  
- Implement **automated tests**  
- Improve documentation with **evidence** (screenshots or exported collection)  

---

## Author
This project was developed for **study and practice** in Quality Assurance.