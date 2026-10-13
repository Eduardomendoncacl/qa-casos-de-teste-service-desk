# CT-002 - Abertura de Chamado N1

**Funcionalidade:** Abertura de chamados
**Prioridade:** Crítica

**Passos:**
1. Logado no sistema, clicar em "Novo Chamado"
2. Selecionar Categoria: "Problemas de Rede - Sem Internet"
3. Prioridade: Alta
4. Descrição: "Usuário sem acesso à internet, protocolo TCP/IP com falha"
5. Clicar em Salvar

**Resultado Esperado:**
Chamado criado com ID, status "Aberto", SLA iniciado, e registro no histórico do GLPI/Jira.

**Cenário Negativo:**
CT-002.1 - Tentar abrir chamado sem preencher categoria -> Sistema deve exibir mensagem "Campo obrigatório"
