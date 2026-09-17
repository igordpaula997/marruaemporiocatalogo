# Catálogo Digital - Marruá Empório

Catálogo digital interativo desenvolvido com foco em alta performance, responsividade e design moderno nas cores verde musgo escuro, verde claro e branco.

## 🚀 Funcionalidades
- **Busca em Tempo Real:** Pesquisa inteligente por nome, descrição ou categoria.
- **Filtro por Categorias:** Navegação rápida entre Facas, Kits, Chaveiros, Canivetes, Chimarrão, etc.
- **Ordenação Flexível:** Por ordem original, preço (crescente/decrescente) e título (A-Z).
- **Galeria de Fotos com Lightbox:** Visualização de imagens em alta resolução com navegação por setas e teclado.
- **Deploy Imediato na Vercel:** Totalmente estático, sem dependências ou necessidade de build.

## 📁 Estrutura do Projeto
- `index.html` - Página principal do catálogo (otimizada para deploy na Vercel).
- `catalogo.html` - Cópia idêntica para abertura direta local.
- `logo.jpg` - Logotipo oficial da Marruá Empório.
- `produtos.js` - Base de dados dos produtos carregada diretamente pelo catálogo.
- `produtos.json` - Dados brutos completos dos 82 produtos em formato JSON.
- `produtos.csv` - Planilha formatada no padrão brasileiro (Excel / UTF-8 com BOM).
- `imagens/` - Diretório contendo as 82 pastas de produtos e 174 imagens em alta resolução.
- `vercel.json` - Configurações de rotas e cache da Vercel.

## 🌐 Como Fazer Deploy na Vercel
1. Crie um repositório no seu GitHub.
2. Faça o envio (`push`) dos arquivos.
3. Acesse a [Vercel](https://vercel.com), clique em **Add New Project**, importe seu repositório e clique em **Deploy**.
