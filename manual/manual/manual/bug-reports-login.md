# Bug Reports – Login de Usuário

## BUG01 – Sistema não exibe mensagem de erro ao tentar login com senha incorreta

**Ambiente:** Web – Google Chrome (versão mais recente)

**Pré-condições:**
- Usuário já cadastrado no sistema.
- Aplicação está no ar e acessível.

**Passos para reproduzir:**
1. Acessar a página de login.
2. Preencher o campo “E-mail” com um e-mail cadastrado e válido.
3. Preencher o campo “Senha” com uma senha incorreta para esse usuário.
4. Clicar no botão “Entrar”.

**Resultado esperado:**
- O sistema exibe uma mensagem de erro clara.
- O usuário permanece na tela de login.

**Resultado obtido:**
- O sistema não exibe nenhuma mensagem de erro e mantém o usuário na tela de login, sem feedback sobre o erro.

**Severidade:** Média
