# Template de QA — Matriz de Testes

Esta matriz conecta **User Stories**, **Casos de Teste**, **Bugs** e **Chamados de Suporte**.  
Cada item possui link direto para os templates correspondentes neste repositório.

---

| Req/US   | Link Origem                                                                 | CT      | Caso de Teste                                                                 | Tipo  | Criticidade | Status |
|:--------:|-----------------------------------------------------------------------------|:-------:|-------------------------------------------------------------------------------|:-----:|:-----------:|:------:|
| US-001   | [User Story](../reporting/user-story-template.md)                           | [CT-001](../planning/test-plan-template.md#caso-de-teste-ct-001) | Login com credenciais válidas             | FUNC  | Alta        | ⬜ |
| US-001   | [User Story](../reporting/user-story-template.md)                           | [CT-002](../planning/test-plan-template.md#caso-de-teste-ct-002) | Bloqueio após 5 tentativas inválidas      | FUNC  | Alta        | ⬜ |
| US-002   | [User Story](../reporting/user-story-template.md)                           | [CT-003](../planning/test-plan-template.md#caso-de-teste-ct-003) | Recuperação de senha com envio de e-mail | API   | Média       | ⬜ |
| US-003   | [User Story](../reporting/user-story-template.md)                           | [CT-004](../planning/test-plan-template.md#caso-de-teste-ct-004) | Cadastro de novo usuário (campos obrigatórios) | FUNC | Alta | ⬜ |
| BUG-001  | [Bug Report](../reporting/bug-template.md#bug-001-exemplo)                  | –       | Erro no filtro de data                                                        | BUG   | Crítica     | ❌ |
| BUG-002  | [Bug Report](../reporting/bug-template.md#bug-002-exemplo)                  | –       | Carrinho duplicando itens                                                     | BUG   | Alta        | ⬜ |
| SUP-001  | [Chamado de Suporte](../reporting/support-template.md#suporte-001-exemplo)  | –       | Ticket de login não concluído                                                 | SUP   | Média       | 🚫 |
| SUP-002  | [Chamado de Suporte](../reporting/support-template.md#suporte-002-exemplo)  | –       | Cliente não recebe notificações push                                          | SUP   | Média       | ⬜ |

---

## 📊 Métricas (exemplo)

- Total de Casos de Teste: **7**  
- Executados: **0**  
- Aprovados: **0**  
- Reprovados: **1 (BUG-001)**  
- Cobertura estimada: **~75%** dos requisitos mapeados

---

## ✅ Checklist de Cobertura
- [ ] Login & Autenticação
- [ ] Recuperação de Senha
- [ ] Cadastro
- [ ] Carrinho
- [ ] Checkout
- [ ] Notificações
- [ ] Integrações API
- [ ] Performance básica

---

## 📄 Notas de Execução
- Rodada planejada: **[data aqui]**  
- Ambiente principal: **[Homolog / Produção]**  
- Tempo estimado: **[x horas]**  
- Riscos conhecidos: **[listar aqui]**
