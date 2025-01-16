# Figma Plugin React Template with AI Integration

[English](#en-us) | [Português](#pt-br)

---

# [PT-BR]

![62862431-71537f00-bd0e-11e9-85db-d97c0fb729a4](https://user-images.githubusercontent.com/16322616/62862692-46b5f600-bd0f-11e9-93b0-75955d1de8f3.png)

## Autor
João Victor de Almeida Pereira  
Product Designer na Cloudwalk & Infinitepay

## Visão Geral
Este template permite que designers criem seus próprios plugins para o Figma de forma simples, usando IA para ajudar no processo. Não é necessário conhecimento em programação - a IA vai te ajudar em cada etapa!

## Instalação Passo a Passo

### 1. Instale as Ferramentas Necessárias

Primeiro, vamos instalar alguns programas que você vai precisar. É como instalar qualquer outro aplicativo no seu computador:

#### Para Mac
1. Baixe e instale o [Figma Desktop](https://www.figma.com/downloads/)
   - Este é o aplicativo do Figma para seu computador
   - Igual ao que você já usa, mas precisa ser a versão desktop

2. Baixe e instale o [Cursor](https://cursor.sh/)
   - Este é um editor de texto especial que tem IA integrada
   - Vai te ajudar a criar o plugin sem precisar programar

3. Baixe e instale o [Node.js](https://nodejs.org/)
   - Clique no botão "LTS" (é a versão mais estável)
   - Este programa permite que seu plugin funcione
   - Siga as instruções de instalação padrão, clicando em "Next" até finalizar

#### Para Windows
1. Baixe e instale o [Figma Desktop](https://www.figma.com/downloads/)
   - Escolha a versão para Windows
   - Instale normalmente como qualquer outro programa

2. Baixe e instale o [Cursor](https://cursor.sh/)
   - Escolha a versão para Windows
   - Siga o processo de instalação padrão

3. Baixe e instale o [Node.js](https://nodejs.org/)
   - Clique no botão "LTS"
   - Instale como qualquer outro programa do Windows

### 2. Configurando as IAs

#### Instalando o Composer no Cursor
1. Abra o Cursor
2. Clique no ícone de engrenagem (⚙️) no canto inferior esquerdo
3. Selecione "Settings"
4. Na barra de pesquisa, digite "composer"
5. Ative a opção "Enable Composer"
6. Reinicie o Cursor

#### Instalando o Cline
1. Instale o [Cursor](https://cursor.sh/) se ainda não tiver instalado
2. Abra o Cursor
3. Pressione `Cmd + Shift + P` (Mac) ou `Ctrl + Shift + P` (Windows)
4. Digite "Install Cline"
5. Selecione "Install Cline" na lista
6. Aguarde a instalação terminar
7. Reinicie o Cursor

### 3. Baixe Este Template

Existem duas formas de baixar:

#### Opção 1 (Mais Fácil):
1. Clique no botão verde "Code" no topo desta página
2. Selecione "Download ZIP"
3. Descompacte o arquivo baixado em uma pasta de sua preferência

#### Opção 2 (Alternativa):
Se você já conhece GitHub:
```bash
git clone https://github.com/[your-username]/figma-plugin-react-template.git
```

### 4. Configure o Projeto

1. Abra o Cursor (o editor que instalamos)
2. No Cursor, clique em:
   - File → Open Folder
   - Selecione a pasta que você acabou de baixar

3. Uma janela de terminal vai abrir automaticamente
   - Digite: `npm install` e pressione Enter
   - Aguarde a instalação terminar
   - Digite: `npm run build:watch` e pressione Enter
   - Deixe esta janela aberta

### 5. Importe para o Figma

1. Abra o Figma Desktop
2. Clique em:
   - Menu Plugins
   - Development
   - "Import plugin from manifest..."
3. Navegue até a pasta do projeto que você baixou
4. Selecione o arquivo `manifest.json`

Pronto! Agora você tem um plugin funcionando no Figma! 🎉

## Próximos Passos
- Para aprender a usar as IAs para desenvolver seu plugin, veja o arquivo [2-USO-DA-IA.md](2-USO-DA-IA.md)
- Para entender a estrutura do projeto, consulte o arquivo [3-ESTRUTURA.md](3-ESTRUTURA.md)

---

# [EN-US]

[Same content translated to English...]

## Next Steps
- To learn how to use AI tools to develop your plugin, see [2-USO-DA-IA.md](2-USO-DA-IA.md)
- To understand the project structure, check [3-ESTRUTURA.md](3-ESTRUTURA.md)

## License
This project is licensed under the MIT License - see the LICENSE file for details.
