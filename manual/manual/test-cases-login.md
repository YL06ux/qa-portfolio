# Casos de Teste – Login de Usuário

## MCT01 – Login com credenciais válidas

**Objetivo:** Verificar se o usuário consegue logar com e-mail e senha válidos.

**Pré-condições:**
- Usuário já cadastrado no sistema.
- Aplicação está no ar e acessível.

**Passos:**
1. Acessar a página de login.
2. Preencher o campo “E-mail” com um e-mail válido e cadastrado.
3. Preencher o campo “Senha” com a senha correta desse usuário.
4. Clicar no botão “Entrar”.

**Resultado esperado:**
- O sistema redireciona o usuário para a página inicial (home).
- O nome do usuário logado é exibido na interface.

---

## MCT02 – Login com senha incorreta

**Objetivo:** Verificar se o sistema impede o login quando a senha está incorreta e exibe mensagem de erro adequada.

**Pré-condições:**
- Usuário já cadastrado no sistema.
- Aplicação está no ar e acessível.

**Passos:**
1. Acessar a página de login.
2. Preencher o campo “E-mail” com um e-mail válido e cadastrado.
3. Preencher o campo “Senha” com uma senha inválida para esse usuário.
4. Clicar no botão “Entrar”.

**Resultado esperado:**
- O sistema exibe uma mensagem de erro clara (ex.: “E-mail ou senha inválidos.”).
- O usuário NÃO consegue logar.
- O usuário permanece na tela de login.
