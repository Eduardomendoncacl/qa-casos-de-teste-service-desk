# CT-001 - Autenticação no Sistema de E-mail (Google Workspace)

**Funcionalidade:** Autenticação / Login  
**Prioridade:** Alta  
**Tipo:** Funcional (Cenário Negativo)  


### Pré-condição
* Acesso à página inicial de login do Google (`https://accounts.google.com`).


### Passos
1. Aceder ao endereço de login do serviço.
2. Informar o e-mail não cadastrado ou incorreto no campo "E-mail ou telefone": `eduardodiasdjs@gmail.com`.
3. Clicar no botão **Avançar**.


### Resultado Esperado
* O sistema deve impeditivamente barrar o avanço do utilizador e exibir a mensagem de erro: **"Não foi possível encontrar essa conta"**.


### Resultado Atual
* O sistema validou a inexistência da conta e exibiu a mensagem de erro conforme esperado.


### Status
* **Pass** 

### Evidência
![Validação de E-mail Inexistente](./CT-001-login.png)
