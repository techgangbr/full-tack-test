# 🏆 Desafio Técnico - Desenvolvedor Full-Stack

Bem-vindo ao nosso desafio técnico! O objetivo deste teste é avaliar suas habilidades no desenvolvimento **full-stack**, incluindo modelagem de banco de dados, criação de API e implementação de um frontend funcional.

---

## 📌 Objetivo
Você deverá desenvolver um **CRUD de quadras de tênis**, criando um sistema capaz de:

- **Cadastrar** uma quadra
- **Listar** todas as quadras, com a opção de filtrar apenas as disponíveis
- **Editar** as informações de uma quadra
- **Alterar** a disponibilidade de uma quadra (disponível ou não)
- **Excluir** uma quadra

---

## 🏗 Requisitos do Projeto

### 📂 Banco de Dados
Crie uma tabela `courts` com os seguintes campos:
- `id` (UUID ou auto-incremento)
- `name` (string, nome da quadra)
- `location` (string, endereço/localização da quadra)
- `available` (boolean, indicando se a quadra está disponível para uso)
- `created_at` (timestamp)
- `updated_at` (timestamp)

---

### ⚙️ Backend (API RESTful)
A API deve conter os seguintes endpoints:

- **Criar uma quadra** → `POST /courts`
- **Listar todas as quadras** → `GET /courts?available=true`
- **Buscar uma quadra por ID** → `GET /courts/:id`
- **Editar uma quadra** → `PUT /courts/:id`
- **Alterar disponibilidade da quadra** → `PATCH /courts/:id/availability`
- **Excluir uma quadra** → `DELETE /courts/:id`

> 💡 **Diferenciais**: Uso de autenticação JWT, documentação com Swagger, middlewares para validação e tratamento de erros.

---

### 🎨 Frontend
A interface deve conter:
- Uma **lista de quadras**, com opção para filtrar **apenas quadras disponíveis**.
- Um **formulário** para criar/editar quadras.
- Um botão para **alterar a disponibilidade** da quadra.
- Um botão para **excluir** uma quadra.

> 💡 **Diferenciais**: Utilização de bibliotecas como React Query, Zustand, Material UI/Tailwind.

---

## 🚀 Como Participar
1. **Fork** este repositório.
2. Crie uma **branch com o seu nome**: `git checkout -b nome-sobrenome`.
3. Implemente a sua solução seguindo os requisitos.
4. Envie um **pull request** com sua branch.

---

## 📊 Critérios de Avaliação
- ✅ Código limpo e organizado 
- ✅ Boas práticas de versionamento (commits semânticos) 
- ✅ Modelagem correta do banco de dados 
- ✅ Qualidade e segurança da API 
- ✅ Experiência do usuário no frontend 
- ✅ Extras como testes automatizados e documentação são bem-vindos! 

---

## 💬 Dúvidas?
Caso tenha dúvidas, fique à vontade para entrar em contato!

---

Boa sorte! 🚀
