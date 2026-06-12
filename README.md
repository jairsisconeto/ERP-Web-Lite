# 🏢 ERP Web Lite

![Status](https://img.shields.io/badge/Status-Concluído-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

Um sistema de gestão (ERP) simplificado, responsivo e 100% *Client-Side*, desenvolvido para auxiliar micro e pequenos comerciantes na transição do controle manual (cadernos) para a organização digital.

🔗 **Acesse o sistema online:** [ERP Web Lite - Live Demo](https://jairsisconeto.github.io/ERP-Web-Lite/)

---

## 🎯 Objetivo do Projeto

Este projeto tem como propósito oferecer uma ferramenta digital acessível e de custo zero para pequenos empreendedores locais. Operando inteiramente no navegador do usuário, o sistema elimina a necessidade de infraestrutura de servidores pagos, garantindo segurança e persistência de dados localmente.

### 🎓 Contexto Acadêmico
Desenvolvido como parte do **Projeto de Extensão I** do curso de **Análise e Desenvolvimento de Sistemas** da Faculdade Anhanguera, unindo a teoria da engenharia de software com a prática do impacto social na comunidade.

---

## 🚀 Funcionalidades Principais

*   **📊 Dashboard (Visão Geral):** Painel analítico com cálculos automáticos de faturamento, total de vendas e gráficos dos produtos mais populares.
*   **📦 Gestão de Produtos (CRUD):** Cadastro completo de itens com controle de preço, quantidade atual e definição de estoque mínimo para alertas de reposição.
*   **🛒 Frente de Caixa (PDV):** Terminal de vendas rápido, com adição de itens ao carrinho, cálculo automático de subtotais/totais e baixa automática no estoque.
*   **🧾 Cupom Não Fiscal:** Geração de recibos de venda para controle do cliente e do lojista no momento da finalização.
*   **💾 Persistência Local:** Todos os registros são salvos de forma segura no `localStorage` do navegador, garantindo que nenhum dado seja perdido ao fechar a aba.

---

## 🛠️ Tecnologias Utilizadas

A arquitetura do projeto foi pensada para ser leve, não exigindo dependências externas (Zero-Dependencies):

*   **HTML5:** Estruturação semântica das páginas.
*   **CSS3 (Flexbox/Grid):** Interface moderna, modular e totalmente responsiva (Mobile First).
*   **JavaScript (Vanilla ES6+):** Lógica de negócios, manipulação do DOM e processamento de dados do PDV.
*   **Web Storage API (`localStorage`):** Banco de dados local no lado do cliente.
*   **GitHub Pages:** Deploy e hospedagem gratuita.

---

## ⚙️ Como executar o projeto localmente

Como o sistema é processado no lado do cliente, rodar a aplicação localmente é extremamente simples:

1. Clone este repositório para a sua máquina:
```bash
   git clone [https://github.com/jairsisconeto/ERP-Web-Lite.git](https://github.com/jairsisconeto/ERP-Web-Lite.git)
