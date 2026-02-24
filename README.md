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

## Estrutura do Projeto

Este repositório contém:

- Casos de teste documentados em formato Markdown
- Organização clara dos fluxos testados
- Estrutura preparada para futura evolução (testes negativos e automação)

---

## Próximos Passos

- Implementar testes negativos
- Adicionar collection do Postman
- Implementar testes automatizados
- Melhorar documentação com evidências (prints ou export da collection)

---

## Autor

Projeto desenvolvido para fins de estudo e prática em Quality Assurance.