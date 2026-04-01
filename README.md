# 🌮 Tacos & Burritos - Express

> Status: Finalizado (Tailwind CSS) 👩‍💻

Website temático "Traditional Mexican Taco Restaurant", rápido, direto e performático, pensado para exibir opções deliciosas da gastronomia mexicana.

![Preview do Projeto](https://img.shields.io/badge/Web-Layout-blue?style=for-the-badge&logo=tailwindcss)

## 🔗 Sobre o Projeto
Este website foca em entregar a energia e os tons quentes de um autêntico restaurante de comida rápida e mexicana. Um diferencial incrível deste projeto é a utilização do **Tailwind CSS** para agilizar e padronizar toda a estilização do aplicativo, entregando um visual conciso, simétrico e moderno através da flexibilidade do CSS utilitário.

---

## 🛠️ Tecnologias e Ferramentas
O projeto foge do CSS Vanilla convencional e implementa as diretrizes semânticas de um framework atômico moderno:

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

## 📌 Diferenciais Técnicos
* **Estilização Orientada a Utilitários (Tailwind):** Todas as regras CSS e design responsivo construídos utilizando as convenções atômicas do *Tailwind CSS* direto no HTML (ex: `class="flex flex-col..."`, `bg-yellow-500`).
* **Imagens de Fundo Variáveis:** Utilização do Tailwind para lidar facilmente com imagens de *background* complexas nos murais (*Heros*) da página (`bg-[url(...)]`).
* **Design de Componentes Modulares:** Separação semântica em blocos úteis, como a seção de "Popular Tacos" com múltiplos cartões, além de um rodapé visualmente agradável baseado em flexboxes.

## 🚀 Como executar localmente
1. Garanta que você baixou o conteúdo dessa pasta localmente.
2. Repare que o projeto baseia seu design no arquivo transpilado `output.css` (construído previamente via Tailwind CLI).
3. Abra o arquivo `index.html` diretamente em seu navegador.
4. (Opcional) Caso deseje modificar estilos de forma contínua, você precisará rodar o compilador do tailwind em modo observador a partir de um terminal pelo caminho raiz onde o tailwind está instalado. (Ex: `npx tailwindcss -i ./input.css -o ./output.css --watch`), onde é requisito ter o **Node.js** em sua máquina.
