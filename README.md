# DM Distribuidora de Alimentos

Sistema web para pedidos de farinha de trigo, que tem como principais clientes padarias e fábricas de pão.

### 🔗 [Acesse o site publicado aqui](https://gbschneider.github.io/Projeto-Interface-I-Site-DM/)
ℹ️ Nota: as informações da empresa (endereço, telefone) e as imagens dos produtos utilizadas neste projeto são verídicas, referentes a uma empresa realmente existente. O sistema foi desenvolvido como atividade acadêmica, mas a identidade visual e os dados de contato representam o negócio real.

---

## 📋 Sobre o projeto

Este projeto foi desenvolvido como atividade da disciplina de **Projeto de Interface**, com o objetivo de aplicar conceitos de UX/UI, prototipação e desenvolvimento web em um problema real: a falta de um canal digital organizado para pedidos de farinha de trigo entre distribuidoras e seus clientes (padarias e fábricas de pão).

## ✨ Funcionalidades

- 🏠 **Página Inicial** — apresentação da distribuidora
- 🔑 **Login** — acesso para empresas já cadastradas
- 📝 **Cadastro** — registro de novas empresas clientes
- 🌾 **Produtos** — catálogo de marcas de farinha disponíveis
- 🛒 **Carrinho** — escolha de quantidade, entrega/retirada, forma de pagamento e cálculo automático do total (via JavaScript)
- 📦 **Pedidos** — histórico de compras com status (entregue, em rota, aguardando confirmação)
- 📞 **Contato** — informações da empresa e atalho direto para o WhatsApp

## 🎨 Design

A interface utiliza um efeito de vidro translúcido (*glassmorphism*), com `backdrop-filter` em CSS, sobre imagens de fundo relacionadas ao universo da panificação. A paleta de cores (azul-marinho e dourado) é inspirada na identidade visual da marca.

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura semântica das páginas
- **CSS3** — estilização, layout responsivo e efeitos visuais (glassmorphism, transições)
- **JavaScript** — interatividade do carrinho de compras (cálculo dinâmico de valores)

## 📁 Estrutura do projeto

```
├── index.html          # Página inicial
├── login.html          # Login
├── cadastro.html        # Cadastro de empresas
├── produtos.html        # Catálogo de produtos
├── carrinho.html        # Carrinho de compras
├── pedidos.html          # Histórico de pedidos
├── contato.html          # Contato
├── css/
│   └── style.css        # Folha de estilos principal
└── img/
    ├── logo-dm.png
    ├── hero-farinha.jpg
    └── produtos/          # Fotos das marcas de farinha
```

## 🚀 Como executar localmente

1. Clone este repositório
2. Abra o arquivo `index.html` em qualquer navegador (ou use a extensão "Live Server" no VS Code)

---

Desenvolvido como atividade acadêmica.
