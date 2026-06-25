# 🤖 JusAI – Assistente Jurídico com IA

O **JusAI** é um sistema inteligente de perguntas e respostas jurídicas desenvolvido com **Typescript ( Next.js para frontend)** e **Python (FastAPI para o backend)**. Ele utiliza modelos de linguagem (LLMs) integrados à API do **OpenRouter (modelo Gemini)** para fornecer respostas com base em legislações brasileiras.

---

## 🧠 Funcionalidades

- ✅ Interface de chatbot moderna.
- ✅ Respostas geradas por IA em português do Brasil.
- ✅ Sugestão de links relevantes de fontes públicas jurídicas.
- ✅ Armazenamento de histórico de consultas no MongoDB.
- ✅ Integração com fontes externas.
- ✅ **Contexto de sessão:** a IA utiliza perguntas e respostas anteriores da mesma sessão para manter o raciocínio e dar respostas mais coerentes.
- ✅ Layout responsivo..

---

## 🧱 Tecnologias Utilizadas

| Frontend     | Backend         | IA & Dados          |
| ------------ | --------------- | ------------------- |
| Next.js 14   | FastAPI         | OpenRouter (Gemini) |
| TypeScript   | Python 3.11+    | MongoDB Atlas       |
| Tailwind CSS | Uvicorn         | RAG Tools           |
| React        | CORS Middleware |                     |

---

## 🧪 Requisitos

- Node.js v18+
- Python 3.11+
- MongoDB Atlas (ou local)
- Chave de API do [OpenRouter](https://openrouter.ai/)

---

## 🚀 Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/GEN9476/legal_agent.git
cd legal_agent
```

### 2. Backend (FastAPI)

```bash
cd api_server
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn app:app --reload
```

A API estará em `http://localhost:8000`.

### 3. Frontend (Next.js)

```bash
cd ../frontend
npm install
npm run dev
```

O frontend estará em `http://localhost:3000`

---

## 💡 Exemplo de Uso

- Usuário: "Quais são os meus direitos em caso de demissão sem justa causa?"
- IA: Explica os artigos da CLT e mostra links para Planalto, Jusbrasil etc.
- Usuário: "E se for por justa causa?"
- IA: Compreende o contexto da sessão e responde com base na continuidade.

<!-- Updated by bot at 2026-06-25T20:02:23.108Z -->

<!-- Updated by bot at 2026-06-25T20:05:08.601Z -->

<!-- Updated by bot at 2026-06-25T20:05:45.332Z -->

<!-- Updated by bot at 2026-06-25T20:05:59.491Z -->

<!-- Updated by bot at 2026-06-25T20:06:12.886Z -->

<!-- Updated by bot at 2026-06-25T20:06:27.301Z -->

<!-- Updated by bot at 2026-06-25T20:07:13.655Z -->

<!-- Updated by bot at 2026-06-25T20:07:27.364Z -->

<!-- Updated by bot at 2026-06-25T20:07:40.416Z -->

<!-- Updated by bot at 2026-06-25T20:07:54.172Z -->

<!-- Updated by bot at 2026-06-25T20:08:08.129Z -->

<!-- Updated by bot at 2026-06-25T20:08:32.262Z -->

<!-- Updated by bot at 2026-06-25T20:09:15.449Z -->

<!-- Updated by bot at 2026-06-25T20:09:29.032Z -->

<!-- Updated by bot at 2026-06-25T20:09:43.111Z -->

<!-- Updated by bot at 2026-06-25T20:09:56.396Z -->

<!-- Updated by bot at 2026-06-25T20:10:10.461Z -->

<!-- Updated by bot at 2026-06-25T20:10:59.169Z -->

<!-- Updated by bot at 2026-06-25T20:11:12.609Z -->

<!-- Updated by bot at 2026-06-25T20:11:26.792Z -->

<!-- Updated by bot at 2026-06-25T20:11:39.965Z -->

<!-- Updated by bot at 2026-06-25T20:11:53.010Z -->

<!-- Updated by bot at 2026-06-25T20:12:06.653Z -->

<!-- Updated by bot at 2026-06-25T20:12:20.599Z -->

<!-- Updated by bot at 2026-06-25T20:12:33.841Z -->

<!-- Updated by bot at 2026-06-25T20:12:48.003Z -->
