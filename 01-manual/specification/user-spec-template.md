# Template de QA — Especificação Funcional

### 1. Identificação
- Projeto: [Nome do sistema ou módulo]
- Versão: [X.Y]
- Data: [dd/mm/aaaa]
- Responsável: [Analista/QA/PO]

---

### 2. Descrição Geral
[Descreva o objetivo principal da funcionalidade.  
Exemplo: "Permitir que o usuário final realize login seguro no sistema, com validação de credenciais e regras de bloqueio."]

---

### 3. Escopo
- O que **faz parte** desta funcionalidade:
  - [Exemplo: Autenticação com e-mail e senha]
  - [Exemplo: Recuperação de senha via e-mail]
- O que **não faz parte**:
  - [Exemplo: Login social com Google/Facebook]

---

### 4. Perfis de Usuário
- **Usuário final**: acessa via app mobile, realiza login e consulta pedidos.  
- **Administrador**: acessa via portal web, gerencia usuários e permissões.  

---

### 5. Fluxo Principal
1. Usuário acessa a tela de login.  
2. Informa credenciais válidas.  
3. Sistema valida contra base de dados.  
4. Em caso de sucesso, redireciona para a tela inicial.  

---

### 6. Fluxos Alternativos
- **Falha de autenticação**: usuário erra senha → exibir mensagem de erro.  
- **Bloqueio**: após 5 tentativas inválidas → bloquear login por 15 minutos.  
- **Esqueci minha senha**: link para reset → envio de e-mail com token.

---

### 7. Regras de Negócio
- Senha deve ter no mínimo 8 caracteres, incluir número e caractere especial.  
- E-mail deve seguir formato válido.  
- O sistema deve registrar logs de tentativas de login.  

---

### 8. Validações
- Campos obrigatórios: e-mail e senha.  
- Mensagem de erro padronizada: “Usuário ou senha inválidos.”  

---

### 9. Integrações
- API de autenticação → endpoint `/auth/login`  
- API de recuperação de senha → endpoint `/auth/reset-password`  

---

### 10. Requisitos Não Funcionais
- Resposta máxima do login: **≤ 2s** em 95% das requisições.  
- Disponibilidade: **99,9%**.  
- Conformidade com LGPD para dados sensíveis.  

---

### 11. Critérios de Aceite
- [ ] Login válido redireciona usuário à tela inicial.  
- [ ] Mensagem de erro exibida em caso de credenciais inválidas.  
- [ ] Bloqueio automático após 5 tentativas falhas.  
- [ ] Envio de e-mail de recuperação de senha.  

---

### 12. Observações
[Espaço para notas adicionais, restrições, dependências ou futuras melhorias.]
