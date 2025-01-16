# Estrutura do Projeto Figma Plugin


## Visão Geral da Estrutura

Este documento explica cada parte do projeto de forma simples e clara.

## Arquivos Principais

### manifest.json
- É o arquivo de identidade do plugin
- Define nome, versão e permissões
- Diz ao Figma como executar o plugin
```json
{
  "name": "Figma Plugin AI Template",
  "id": "00000000",
  "api": "1.0.0",
  "main": "dist/code.js",
  "ui": "dist/ui.html"
}
```

### package.json
- Lista todas as ferramentas que o projeto usa
- Define comandos para executar o projeto
- Configura ferramentas de desenvolvimento

## Estrutura de Pastas

### 📁 src/
A pasta principal do código fonte, dividida em:

#### 📁 src/app/
Interface visual do plugin:
- **components/**: Elementos visuais reutilizáveis
  - `App.tsx`: Componente principal que define a interface
- **styles/**: Arquivos de estilo
  - `ui.css`: Estilos da interface do plugin
- **assets/**: Imagens e recursos
  - `logo.svg`: Logo do plugin

#### 📁 src/plugin/
Código que interage com o Figma:
- `controller.ts`: Controla as ações do plugin
  - Cria e modifica elementos
  - Responde a ações do usuário
  - Comunica com a interface

#### 📁 src/typings/
Definições de tipos para TypeScript:
- `types.d.ts`: Ajuda o editor a entender o código

### 📁 dist/
- Pasta onde fica o código compilado
- Gerada automaticamente
- Não precisa modificar manualmente

## Fluxo de Funcionamento

1. **Interface do Usuário** (`src/app/`)
   - Usuário interage com botões e campos
   - React gerencia a interface
   - Envia mensagens para o controller

2. **Controller** (`src/plugin/controller.ts`)
   - Recebe ações da interface
   - Manipula elementos no Figma
   - Retorna resultados para a interface

3. **Compilação** (`dist/`)
   - Webpack combina todos os arquivos
   - Gera código que o Figma entende
   - Atualiza automaticamente durante desenvolvimento

## Arquivos de Configuração

### webpack.config.js
- Configura como o código é compilado
- Define como arquivos são processados
- Otimiza o código para produção

### tsconfig.json
- Configura o TypeScript
- Define regras de código
- Garante qualidade e consistência

### .prettierrc.yml
- Configura formatação de código
- Mantém estilo consistente
- Funciona automaticamente no Cursor

## Como Modificar

### Para Mudar a Interface
1. Edite arquivos em `src/app/components/`
2. Modifique estilos em `src/app/styles/ui.css`
3. Adicione imagens em `src/app/assets/`

### Para Adicionar Funcionalidades
1. Modifique `src/plugin/controller.ts`
2. Use a API do Figma para manipular elementos
3. Conecte com a interface via mensagens

### Para Configurar o Plugin
1. Edite `manifest.json` para informações básicas
2. Atualize `package.json` para novas dependências
3. Configure `webpack.config.js` se necessário

## Dicas de Desenvolvimento

### Organização
- Mantenha componentes pequenos e focados
- Use nomes claros para arquivos e funções
- Agrupe código relacionado nas pastas certas

### Boas Práticas
- Teste mudanças frequentemente no Figma
- Mantenha o código organizado
- Use comentários para explicar partes complexas

## Próximos Passos
- Para voltar às instruções de instalação, veja [INSTALACAO.md](INSTALACAO.md)
- Para aprender a usar as IAs no desenvolvimento, consulte [USO-DA-IA.md](USO-DA-IA.md)