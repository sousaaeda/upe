# IC-Plan.md – Projeto Front-End

## Objetivo
Definir os Itens de Configuração (ICs) que devem ser controlados neste projeto front-end, garantindo rastreabilidade e consistência.

## Estrutura de Itens de Configuração

### 1. Código-Fonte
- `src/` → componentes, páginas e estilos
- `package.json` e `package-lock.json` → dependências e versões

### 2. Configurações
- `.eslintrc.json`, `.prettierrc` → configuração de linting e formatação
- `.babelrc`, `vite.config.js`, `webpack.config.js` → configs de build
- `.gitignore` → arquivos não versionados

### 3. Documentação
- `README.md`
- `docs/` → guias de instalação e uso

### 4. Testes
- `tests/` → testes unitários (Jest, Vitest, Mocha)
- `cypress/` → testes de integração/end-to-end

### 5. Assets Controlados
- `public/` → imagens, ícones e estáticos relevantes

## Itens Não Versionados
- `node_modules/`
- Arquivos de build (`dist/`, `build/`)
- Logs (`*.log`)
- Arquivos temporários (`*.tmp`)

## Responsabilidades
- Dev Team: manter ICs consistentes
- Configuration Manager: revisar estrutura a cada sprint
