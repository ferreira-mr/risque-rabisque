# 🎁 Risque & Rabisque • Catálogo Digital de Artesanatos & Presentes

Catálogo interativo, responsivo e moderno para divulgação de produtos artesanais, presentes personalizados e itens de papelaria criativa com envio direto do pedido para o WhatsApp.

🔗 **Link do Catálogo Online (GitHub Pages):**  
[https://ferreira-mr.github.io/risque-rabisque/](https://ferreira-mr.github.io/risque-rabisque/)

---

## ✨ Funcionalidades

- 📱 **100% Responsivo:** Experiência otimizada para celulares, tablets e computadores.
- 🔍 **Busca em Tempo Real:** Pesquisa instantânea por nome ou descrição do produto.
- 🏷️ **Filtro por Categorias:** Navegação fácil entre categorias (Dia das Mães, Dia dos Pais, Aniversários, Lembrancinhas, etc.).
- 👁️ **Visualização Rápida (Quick View):** Modal de detalhes do produto com fotos ampliadas e botão de dúvidas no WhatsApp.
- 🛍️ **Carrinho Interativo:** Adicione itens, ajuste quantidades, veja o total estimado em tempo real.
- 📝 **Campo de Personalização:** O cliente pode preencher nomes, frases, cores e fotos a serem gravadas.
- 💬 **Checkout WhatsApp:** Monta automaticamente o resumo do pedido formatado e direciona para o WhatsApp `(18) 99739-0492`.
- 💾 **Persistência Local:** O carrinho é salvo localmente para não perder a seleção ao recarregar a página.

---

## 🛠️ Como Personalizar

### 1. Alterar o Número do WhatsApp
No arquivo `index.html`, localize a constante:
```javascript
const WHATSAPP_NUMBER = "5518997390492"; // Coloque o DDI + DDD + Número sem espaços ou traços
```

### 2. Adicionar ou Editar Produtos
No arquivo `index.html`, edite o array de objetos `products`:
```javascript
{
    id: 1,
    name: 'Nome do seu Produto',
    category: 'maes', // Categoria correspondente
    badge: 'Mais Vendido', // Opcional (tag no card)
    price: 35.00,
    description: 'Descrição detalhada do produto.',
    image: 'URL_DA_IMAGEM_AQUI'
}
```

---

## 🚀 Publicado com GitHub Pages
Desenvolvido com HTML5, Tailwind CSS e Vanilla JavaScript.
