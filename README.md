# Como Baixar e Usar Modelo do GitHub no Overleaf e em Outras Ferramentas

## 1. Baixar o modelo do GitHub
Se o modelo estiver no GitHub, siga estas opções:

### ✅ Opção 1: Download Manual do ZIP
1. Acesse o repositório no GitHub.
2. Clique no botão "Code" (verde).
3. Selecione "Download ZIP".
4. Extraia o arquivo ZIP no seu computador.

### ✅ Opção 2: Clonar com Git (Recomendado)
Se você tem o Git instalado, pode baixar o modelo com este comando no terminal:

No terminal/bash:
git clone https://github.com/emelynfreire/ModeloSlideInovAILab.git ```

## 2. Abrir no Overleaf
Após baixar os arquivos, siga estas etapas para usar no Overleaf:

1. Acesse o Overleaf.
2. Faça login na sua conta.
3. No Painel Inicial, clique em "New Project" → "Upload Project".
4. Selecione o arquivo ZIP do seu modelo e aguarde o upload.
5. O Overleaf irá extrair os arquivos e abrir o projeto automaticamente.

## 3. Usar em Outras Ferramentas
Se quiser editar o modelo localmente, use uma das seguintes opções:

### ✅ Opção 1: TeXworks (Windows)
1. Instale o MikTeX (miktex.org).
2. Abra o `.tex` no TeXworks e compile usando PDFLaTeX.

### ✅ Opção 2: VS Code com LaTeX Workshop
1. Instale o [VS Code](https://code.visualstudio.com).
2. Instale a extensão [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop).
3. Instale o [TeX Live](https://tug.org/texlive).
4. Abra o projeto `.tex` no VS Code e clique em "Build PDF".

### ✅ Opção 3: Overleaf com Git (Sincronização Automática)
Se quiser editar no Overleaf, mas manter sincronizado com o GitHub:

1. No Overleaf, vá em "Menu" > "GitHub Sync".
2. Conecte sua conta do GitHub.
3. Escolha o repositório e clique em "Pull from GitHub" para importar.
