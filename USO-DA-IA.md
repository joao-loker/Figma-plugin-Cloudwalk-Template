# Guia de Uso da IA para Criar Plugins


## Trabalhando com o Composer

### 1. Comandos Especiais

#### Usando @web
O comando @web permite que o Composer pesquise informações atualizadas na internet:
```
@web Como criar um plugin para o Figma em 2024?
@web Tendências de design para plugins Figma
```

#### Referenciando Documentação
Para mostrar documentação específica ao Composer:
```
[doc: https://www.figma.com/plugin-docs/api/api-overview/]
Explique como usar esta API para selecionar elementos.
```

#### Modo Agent
O Agent é um assistente mais focado que mantém contexto:
```
/agent "Preciso criar um plugin que exporte elementos"
```
O Agent vai guiar você passo a passo, mantendo o contexto da conversa.

### 2. Estruturando Perguntas Efetivas

#### Template para Criar Funcionalidades
```
Quero criar uma funcionalidade que [objetivo].
Contexto:
- Estou usando o arquivo [nome do arquivo]
- Preciso que [descreva o comportamento desejado]
- Deve funcionar quando [descreva o cenário]

[Cole trecho relevante do código se houver]
```

#### Template para Modificar Código Existente
```
Preciso modificar esta parte do código:
[Cole o código atual]

Objetivo:
- [Descreva o que precisa mudar]
- [Mencione limitações ou requisitos]
- [Explique o resultado esperado]
```

#### Template para Resolver Problemas
```
Estou com um problema no plugin:
- O que deveria acontecer: [descreva]
- O que está acontecendo: [descreva]
- Erro (se houver): [cole a mensagem]

[Cole o código relevante]
```

### 3. Exemplos Práticos

#### Exemplo 1: Criando Interface
```
Quero criar uma interface para meu plugin.
Preciso de:
- Um campo para inserir texto
- Um botão para aplicar o texto aos elementos selecionados
- Uma opção para escolher a fonte

[doc: https://www.figma.com/plugin-docs/api/ui-api/]
Como posso implementar isso?
```

#### Exemplo 2: Manipulando Elementos
```
/agent "Preciso trabalhar com elementos do Figma"

Quero:
- Selecionar todos os textos de uma página
- Mudar a fonte deles
- Manter o tamanho e cor originais

[doc: https://www.figma.com/plugin-docs/api/nodes/]
```

#### Exemplo 3: Exportando Dados
```
Objetivo: Exportar informações dos elementos
Necessidades:
- Pegar nome, posição e tamanho
- Salvar em formato JSON
- Manter hierarquia de grupos

[doc: https://www.figma.com/plugin-docs/api/properties/nodes-exportasync/]
```

### 4. Dicas Avançadas

#### Mantendo Contexto
- Use `/agent` para projetos complexos
- Referencie arquivos específicos do projeto
- Mantenha uma conversa focada em um objetivo

#### Usando Documentação
- Combine `[doc: url]` com perguntas específicas
- Use `@web` para exemplos atualizados
- Peça explicações detalhadas de partes complexas

#### Melhorando o Código
- Solicite revisões de código
- Peça sugestões de otimização
- Pergunte sobre boas práticas

## Melhores Práticas

### 1. Desenvolvimento Gradual
- Comece com funcionalidades simples
- Teste cada parte antes de avançar
- Peça feedback da IA em cada etapa

### 2. Organização
- Mantenha um objetivo claro por sessão
- Documente decisões importantes
- Organize o código em pequenas partes

### 3. Resolução de Problemas
- Isole o problema específico
- Forneça contexto completo
- Use exemplos reproduzíveis

## Próximos Passos
- Para entender a estrutura do projeto, veja [ESTRUTURA.md](ESTRUTURA.md)
- Para voltar às instruções de instalação, consulte [INSTALACAO.md](INSTALACAO.md)