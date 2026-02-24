# Casos de Teste API — Cadastro, Listagem, Atualização e Delete

API utilizada: Serverest

---

## CT01 — Criar usuário com dados válidos

**Pré-condição:**  
Nenhuma  

**Passos:**  
1. Enviar `POST /usuarios` com dados em JSON válido.

**Resultado Esperado:**  
- Status Code: 201  
- Response Body contém:
  - Mensagem de sucesso: Cadastro realizado com sucesso  
  - ID do usuário  

---

## CT02 — Listar Usuário específico

**Pré-condição:**  
Usuário estar cadastrado  

**Passos:**  
1. Enviar `GET /usuarios/{_id}`  

**Resultado Esperado:**  
- Status Code: 200  
- Response Body contém:
  - Campo: `nome`  
  - Campo: `email`  
  - Campo: `password`  
  - Campo: `administrador`  
  - Campo: `_id`  

---

## CT03 — Editar Usuário

**Pré-condição:**  
Usuário estar cadastrado  

**Passos:**  
1. Enviar `PUT /usuarios/{_id}` com dados alterados em JSON.  

**Resultado Esperado:**  
- Status Code: 200  
- Response Body contém:
  - `"message": "Registro alterado com sucesso"`  

---

## CT04 — Deletar Usuário

**Pré-condição:**  
Usuário estar cadastrado  

**Passos:**  
1. Enviar `DELETE /usuarios/{_id}`  

**Resultado Esperado:**  
- Status Code: 200  
- Mensagem de sucesso:
  - Registro excluído com sucesso  
  ou  
  - Nenhum registro excluído  