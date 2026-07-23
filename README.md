<div align="center">
   
![hq720](https://github.com/user-attachments/assets/6dc9a9c0-ea99-4461-9fff-e390f43f4790)
<img width="686" height="auto" alt="{F6FD968C-145C-4A92-BE12-45C6349B010E}" src="https://github.com/user-attachments/assets/f93f6f2e-d564-4cc8-88ea-d47e41728234"/> <br><br>
   
# Web Game Assistant

[Demo Online](#demo-online) • [Como Usar](#como-usar) • [Como Obter a Chave da API](#como-obter-a-chave-da-api-do-gemini)

![HTML5](https://img.shields.io/badge/HTML5-25.5%25-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-31.9%25-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-42.6%25-F7DF1E?logo=javascript&logoColor=black)
![Gemini](https://img.shields.io/badge/Google-Gemini%20AI-8E75B2?logo=googlegemini&logoColor=white)
![Deploy](https://img.shields.io/badge/deploy-Vercel-black?logo=vercel&logoColor=white)

</div>

---

### Sumário
- [Sobre](#sobre)
- [Demo Online](#demo-online)
- [Como Obter a Chave da API do Gemini](#como-obter-a-chave-da-api-do-gemini)
- [Como Usar](#como-usar)
- [Tecnologias](#tecnologias)
- [Estrutura do Projeto](#estrutura-do-projeto)

# Sobre

**Web Game Assistant** é um projeto construído durante o **NLW Agents**, evento gratuito da [Rocketseat](https://www.rocketseat.com.br/). A aplicação integra a **IA do Gemini** (Google) para funcionar como um assistente que ajuda jogadores a melhorarem sua performance em jogos online, respondendo dúvidas e dando dicas diretamente pelo navegador.

# Demo Online

O projeto está publicado na Vercel e pode ser testado diretamente aqui:

👉 [nlw-agents-trilha-iniciante.vercel.app](https://nlw-agents-trilha-iniciante.vercel.app/)

> ⚠️ Para usar a IA é necessário informar sua própria **chave de API do Gemini** (veja abaixo como obter uma gratuitamente).

# Como Obter a Chave da API do Gemini

1. Acesse o [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Faça login com sua conta Google.
3. Aceite os termos de uso da API.
4. Clique em **"Create API key"**.
5. Copie a chave gerada.
6. Cole a chave no campo solicitado na página do projeto.

# Como Usar

Como o projeto é totalmente client-side (HTML, CSS e JavaScript puros), não há build nem dependências de backend para rodar localmente:

```sh
git clone https://github.com/cmarinho-dev/web-game-assistant.git
cd web-game-assistant
```

Basta abrir o arquivo `index.html` no navegador (ou servir a pasta com uma extensão como Live Server), informar sua chave da API do Gemini quando solicitado e começar a usar o assistente.

# Tecnologias

- **HTML5** — estrutura da página;
- **CSS3** — estilização da interface;
- **JavaScript** — lógica da aplicação e integração com a API do Gemini;
- **Gemini API** — inteligência artificial responsável pelas respostas do assistente;
- **Vercel** — hospedagem do deploy.

# Estrutura do Projeto

```
web-game-assistant/
├── assets/        # Imagens e recursos estáticos
├── index.html     # Página principal
├── script.js      # Lógica da aplicação e chamadas à API do Gemini
└── style.css      # Estilos da interface
```

---

<div align="center">

Projeto desenvolvido durante o NLW Agents da Rocketseat 🚀

</div>
