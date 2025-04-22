# Frontend Code Quality Config

Minhas configurações de ferramentas que auxiliam na qualidade de código para trabalhar no frontend.

## Índice

- [Descrição](#descrição)
- [Ferramentas Inclusas](#ferramentas-inclusas)
- [Como Usar](#como-usar)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Descrição

Este repositório contém configurações para ferramentas que ajudam a manter a qualidade de código ao desenvolver projetos frontend. As configurações foram projetadas para facilitar a integração e melhorar a consistência e qualidade do código.

## Ferramentas Inclusas

Este repositório inclui configurações para as seguintes ferramentas:

- [ESLint](https://eslint.org/): Para análise estática de código JavaScript.
- [Prettier](https://prettier.io/): Para formatação automática de código.
- [Husky](https://typicode.github.io/husky): Para gerenciamento de hooks Git.
- [Lint-Staged](https://github.com/okonet/lint-staged): Para rodar linters em arquivos staged no Git.

## Como Usar

1. **Clone este repositório**:
   ```bash
   git clone https://github.com/pedroSoaresll/frontend-code-quality-config.git
   ```

2. **Instale as dependências necessárias**:
   Certifique-se de instalar todas as dependências mencionadas nos arquivos de configuração, caso ainda não tenha.

3. **Copie os arquivos de configuração para o seu projeto**:
   - Copie os arquivos relevantes, como `.eslintrc`, `.prettierrc`, e configurações do Husky, para o diretório raiz do seu projeto.

4. **Adicione os scripts ao `package.json` do seu projeto**:
   Para utilizar as ferramentas, adicione os scripts no seu arquivo `package.json`:
   ```json
   {
     "scripts": {
       "lint": "eslint .",
       "format": "prettier --write ."
     }
   }
   ```

5. **Configure os hooks do Git com Husky**:
   Certifique-se de que os hooks estão ativos no seu projeto:
   ```bash
   npx husky install
   ```

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões ou melhorias, sinta-se à vontade para abrir uma [issue](https://github.com/pedroSoaresll/frontend-code-quality-config/issues) ou enviar um [pull request](https://github.com/pedroSoaresll/frontend-code-quality-config/pulls).

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
