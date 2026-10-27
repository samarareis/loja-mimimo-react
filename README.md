# Loja Mimimô — Projeto React
Loja virtual demonstrativa para bodys infantis, com catálogo, filtros por categoria, busca, favoritos, sacolinha demonstrativa e botões de contato pelo WhatsApp.

## Como executar
1. Extraia o ZIP.
2. Abra a pasta `loja-mimimo-react` no VS Code (a pasta onde está `package.json`).
3. Vá em **Terminal → Novo Terminal** e execute:
```bash
npm install
npm run dev
```
4. Abra o endereço mostrado no terminal, geralmente `http://localhost:5173/`.

**Importante:** não abra `index.html` com Live Server. Use `npm run dev` (Vite).

## Imagens e produtos
As imagens ilustrativas locais estão em `public/images/`. Os produtos e preços de exemplo ficam em `src/data/products.js`. Pode substituir os arquivos de imagem mantendo os nomes atuais.

## WhatsApp
Os botões abrem o WhatsApp com uma mensagem pronta. Para direcionar ao número da loja, edite a função `whatsapp` em `src/App.jsx` e use `https://wa.me/55DDDNUMERO?text=` (somente números no telefone).

## Nota
A sacolinha é demonstrativa e não processa pagamentos. Preços e imagens são exemplos editáveis.
