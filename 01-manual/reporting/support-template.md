# Template de QA — Suporte

### TÍTULO: SUPORTE-PROD: [Componente ou funcionalidade] – descrição objetiva do erro relatado

---
### DESCRIÇÃO
[Descreva de forma clara o problema informado pelo cliente. Inclua o comportamento inesperado, 
o que deveria acontecer e qualquer contexto relevante. Use linguagem objetiva.]

---
###  CONFIGURAÇÕES DO USUÁRIO
- **Versão do App (Se aplicável):** [Ex: 1.115.7]  
- **Plataforma (Se aplicável):** [App Android / App iOS / Portal Web / PWA]  
- **Modelo do Dispositivo (Se aplicável):** [Ex: iPhone 11, Samsung A52, Chrome 115.0]  
- **Sistema Operacional (Se aplicável):** [Ex: iOS 17.4 / Android 13 / Windows 11]  
- **Rede utilizada:** [Wi-Fi / 4G / 5G]  
- **E-mail do usuário:** [email@exemplo.com]  
- **Documento:** [CPF/CNPJ, se aplicável]  
- **Nome completo:** [Nome completo do cliente, se relevante]
---
###  STEPS
[Passo a passo para reproduzir o erro reportado pelo usuário]
1. [...]  
2. [...]  
3. [...]  
---
### RESULTADO OBTIDO
Explique o comportamento atual do sistema após os passos acima.  
Descreva mensagens de erro, falhas visuais, **travamentos**, ou comportamentos inesperados.

---

### RESULTADO ESPERADO
[Descreva claramente o que o sistema deveria fazer.  
Isso ajuda a identificar divergência entre comportamento atual e esperado.]

---
###  EVIDÊNCIAS 
- [Prints de tela enviados pelo cliente]  
- [Vídeos demonstrando o problema, se houver]  
- [Logs de erro ou mensagens do sistema]  
- [Prints de mensagens do WhatsApp / Slack / Atendimento, se relevante]  

---
###  ANÁLISE INICIAL / REPLICAÇÃO INTERNA (opcional)
- Tentativa de replicação: [Sim / Não]  
- Resultado da tentativa: [Erro reproduzido com sucesso / Não reproduzido]  
- Observações técnicas: [Ex: erro intermitente, possível cache/local storage, etc.]  
---
###  OBSERVAÇÕES ADICIONAIS (opcional)
- [Detalhes complementares fornecidos pelo cliente]  
- [Orientações já passadas ao cliente (ex: reinstalar app, limpar cache, etc.)]  
- [Hipóteses levantadas]  
- [Existe chamado anterior ou recorrência?]  
---
###  SUGESTÃO DE PRÓXIMOS PASSOS (opcional)
- Validar se o erro está relacionado ao backend/autenticação  
- Verificar se o CPF/email está vinculado corretamente ao perfil  
- Avaliar logs da requisição da API X  
- Acompanhar resposta do cliente com novos testes  
---
