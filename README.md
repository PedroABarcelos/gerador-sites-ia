# ⚡️ Gerador de Sites com IA

Projeto criado durante um curso gratuito da **DevClub**, onde desenvolvi uma página que utiliza Inteligência Artificial (via API da Groq, rodando o modelo Llama 3.3 70B) para gerar landing pages completas a partir de uma simples descrição de negócio.

## 🖼️ Sobre o projeto

O usuário descreve o tipo de negócio (ex: "Cafeteria", "Pet Shop", "Barbearia") em uma caixa de texto, e a IA gera automaticamente o código HTML/CSS de uma landing page personalizada — com paleta de cores, tipografia e textos pensados para aquele negócio. O código gerado é exibido na tela e a página é renderizada em tempo real dentro de um `iframe`.

## 🚀 Tecnologias utilizadas

- **HTML5**
- **CSS3**
- **JavaScript** (Fetch API, async/await, manipulação de DOM)
- **Groq API** (modelo `llama-3.3-70b-versatile`)

## 🔑 Como rodar o projeto localmente

Este projeto consome a API da Groq, que exige uma chave de autenticação (API Key). Por segurança, a chave **não** está incluída no código.

Para rodar você vai precisar:

1. Criar uma conta gratuita em [console.groq.com](https://console.groq.com)
2. Gerar sua própria API Key
3. Abrir o arquivo `scripts.js` e substituir:
   ```js
   Authorization: "Bearer SUA_CHAVE_API_AQUI",
   ```
   pela sua chave:
   ```js
   Authorization: "Bearer sua_chave_gerada_aqui",
   ```
4. Abrir o arquivo `index.html` no navegador (pode usar a extensão **Live Server** do VS Code)

## 📚 Aprendizados

Este foi um dos meus primeiros projetos praticando:
- Consumo de APIs externas com `fetch`
- Funções assíncronas (`async/await`)
- Manipulação do DOM (`querySelector`, eventos de clique)
- Boas práticas de segurança (nunca expor API keys em repositórios públicos)

## 📌 Status

Projeto concluído para fins de estudo e portfólio.

---

Feito por **Pedro Afonso** durante o curso gratuito da DevClub.
