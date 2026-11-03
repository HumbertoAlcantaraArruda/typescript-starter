## Pré-requisitos

[Node.js](https://nodejs.org/) 24, [Git](https://git-scm.com/) e [VS Code](https://code.visualstudio.com/).

## Como rodar

1. Clone e abra no VS Code:

   ```bash
   git clone https://github.com/HumbertoAlcantaraArruda/typescript-starter.git
   code typescript-starter
   ```

2. No terminal do VS Code (**Ctrl+'**), instale as extensões e as dependências:

   ```bash
   code --install-extension dbaeumer.vscode-eslint --install-extension esbenp.prettier-vscode --install-extension formulahendry.code-runner
   npm install
   ```

3. Recarregue o VS Code: **Ctrl+Shift+P** → `Reload Window`.
4. Abra `src/index.ts` e aperte **Ctrl+Alt+N**.

## Comandos

- `npx tsc`: compila `src` para `dist`
- `npx tsc --noEmit`: verifica erros de tipo
- `npm run lint`: roda o ESLint
