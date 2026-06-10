# 🌐 Mini Projeto: Simulador de Renderização Moderna (Next.js)

## 📋 Descrição do Projeto
Este mini projeto foi desenvolvido como atividade prática para a disciplina de Desenvolvimento Web. O objetivo principal é demonstrar, de forma visual e didática, o conceito de **Renderização Híbrida/Moderna** introduzido por frameworks como o **Next.js**.

A aplicação simula em uma única página como o Next.js divide os componentes entre o **Servidor** (focado em performance e SEO) e o **Cliente** (focado em interatividade).

---

## 🏗️ Estrutura Conceitual Demonstrada

O projeto ilustra a coexistência de duas estratégias no mesmo ambiente:

1. **Server Component (SSR/SSG):** Representado pelo bloco verde. Simula o conteúdo que o servidor processa e envia 100% pronto (HTML limpo) para o navegador. Ideal para indexação de motores de busca (SEO) e carregamento instantâneo.
2. **Client Component (CSR):** Representado pelo bloco azul pontilhado. Simula a diretiva `"use client"` do Next.js, onde o JavaScript é executado diretamente no navegador do usuário para permitir interações em tempo real (como o contador de cliques).

---

## 🛠️ Tecnologias Utilizadas
Para garantir a simplicidade e o foco exclusivo no conceito teórico da renderização hibrida, o projeto foi construído utilizando:
* **HTML5:** Estruturação dos blocos de simulação.
* **CSS3:** Estilização e diferenciação visual dos componentes de Servidor e Cliente.
* **JavaScript (Vanilla):** Simulação da reatividade/manipulação de estado no lado do cliente.

---

## 💿 Como Executar o Projeto Localmente

Por se tratar de uma simulação puramente conceitual, você não precisa instalar o Node.js ou gerenciadores de pacotes pesados.

1. Faça o clone ou baixe este repositório.
2. Navegue até a pasta do projeto.
3. Dê dois cliques no arquivo `index.html`.
4. O simulador abrirá instantaneamente no seu navegador padrão.

---

## 👨‍💻 Autores e Desenvolvimento
* **Autores:** Victor Martins,
* **Atividade:** Apresentação Prática - Next.js e Renderização Moderna
