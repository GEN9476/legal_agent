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

<!-- Updated by bot at 2026-06-25T20:13:01.381Z -->

<!-- Updated by bot at 2026-06-25T20:13:15.642Z -->

<!-- Updated by bot at 2026-06-25T20:13:29.742Z -->

<!-- Updated by bot at 2026-06-25T20:13:45.008Z -->

<!-- Updated by bot at 2026-06-25T20:13:58.105Z -->

<!-- Updated by bot at 2026-06-25T20:14:11.186Z -->

<!-- Updated by bot at 2026-06-25T20:14:25.016Z -->

<!-- Updated by bot at 2026-06-25T20:14:39.079Z -->

<!-- Updated by bot at 2026-06-25T20:14:52.125Z -->

<!-- Updated by bot at 2026-06-25T20:15:05.602Z -->

<!-- Updated by bot at 2026-06-25T20:15:19.041Z -->

<!-- Updated by bot at 2026-06-25T20:15:33.005Z -->

<!-- Updated by bot at 2026-06-25T20:15:46.394Z -->

<!-- Updated by bot at 2026-06-25T20:15:59.577Z -->

<!-- Updated by bot at 2026-06-25T20:16:13.334Z -->

<!-- Updated by bot at 2026-06-25T20:16:27.020Z -->

<!-- Updated by bot at 2026-06-25T20:16:41.309Z -->

<!-- Updated by bot at 2026-06-25T20:16:54.694Z -->

<!-- Updated by bot at 2026-06-25T20:17:07.941Z -->

<!-- Updated by bot at 2026-06-25T20:17:21.210Z -->

<!-- Updated by bot at 2026-06-25T20:17:35.456Z -->

<!-- Updated by bot at 2026-06-25T20:17:49.331Z -->

<!-- Updated by bot at 2026-06-25T20:19:11.512Z -->

<!-- Updated by bot at 2026-06-25T20:19:19.291Z -->

<!-- Updated by bot at 2026-06-25T20:19:30.068Z -->

<!-- Updated by bot at 2026-06-25T20:19:37.502Z -->

<!-- Updated by bot at 2026-06-25T20:19:44.809Z -->

<!-- Updated by bot at 2026-06-25T20:19:52.035Z -->

<!-- Updated by bot at 2026-06-25T20:19:59.422Z -->

<!-- Updated by bot at 2026-06-25T20:20:07.498Z -->

<!-- Updated by bot at 2026-06-25T20:20:15.427Z -->

<!-- Updated by bot at 2026-06-25T20:20:23.037Z -->

<!-- Updated by bot at 2026-06-25T20:20:30.506Z -->

<!-- Updated by bot at 2026-06-25T20:20:38.318Z -->

<!-- Updated by bot at 2026-06-25T20:20:50.377Z -->

<!-- Updated by bot at 2026-06-25T20:20:58.312Z -->

<!-- Updated by bot at 2026-06-25T20:21:09.799Z -->

<!-- Updated by bot at 2026-06-25T20:21:17.292Z -->

<!-- Updated by bot at 2026-06-25T20:21:25.379Z -->

<!-- Updated by bot at 2026-06-25T20:21:33.110Z -->

<!-- Updated by bot at 2026-06-25T20:21:40.757Z -->

<!-- Updated by bot at 2026-06-25T20:21:48.699Z -->

<!-- Updated by bot at 2026-06-25T20:21:56.043Z -->

<!-- Updated by bot at 2026-06-25T20:22:03.746Z -->

<!-- Updated by bot at 2026-06-25T20:22:11.418Z -->

<!-- Updated by bot at 2026-06-25T20:22:18.902Z -->

<!-- Updated by bot at 2026-06-25T20:22:26.043Z -->

<!-- Updated by bot at 2026-06-25T20:22:33.308Z -->

<!-- Updated by bot at 2026-06-25T20:22:40.605Z -->

<!-- Updated by bot at 2026-06-25T20:22:48.401Z -->

<!-- Updated by bot at 2026-06-25T20:22:59.799Z -->

<!-- Updated by bot at 2026-06-25T20:23:07.298Z -->

<!-- Updated by bot at 2026-06-25T20:23:14.813Z -->

<!-- Updated by bot at 2026-06-25T20:23:23.188Z -->

<!-- Updated by bot at 2026-06-25T20:23:31.063Z -->

<!-- Updated by bot at 2026-06-25T20:23:38.739Z -->

<!-- Updated by bot at 2026-06-25T20:23:49.713Z -->

<!-- Updated by bot at 2026-06-25T20:23:57.690Z -->

<!-- Updated by bot at 2026-06-25T20:24:05.566Z -->

<!-- Updated by bot at 2026-06-25T20:24:13.148Z -->

<!-- Updated by bot at 2026-06-25T20:24:20.743Z -->

<!-- Updated by bot at 2026-06-25T20:24:28.575Z -->

<!-- Updated by bot at 2026-06-25T20:24:40.460Z -->

<!-- Updated by bot at 2026-06-25T20:24:48.046Z -->

<!-- Updated by bot at 2026-06-25T20:24:55.311Z -->

<!-- Updated by bot at 2026-06-25T20:25:02.733Z -->

<!-- Updated by bot at 2026-06-25T20:25:10.342Z -->

<!-- Updated by bot at 2026-06-25T20:25:17.733Z -->

<!-- Updated by bot at 2026-06-25T20:25:25.462Z -->

<!-- Updated by bot at 2026-06-25T20:25:33.096Z -->

<!-- Updated by bot at 2026-06-25T20:25:44.350Z -->

<!-- Updated by bot at 2026-06-25T20:25:52.639Z -->

<!-- Updated by bot at 2026-06-25T20:26:00.179Z -->

<!-- Updated by bot at 2026-06-25T20:26:07.951Z -->

<!-- Updated by bot at 2026-06-25T20:26:15.897Z -->

<!-- Updated by bot at 2026-06-25T20:26:23.773Z -->

<!-- Updated by bot at 2026-06-25T20:26:31.413Z -->

<!-- Updated by bot at 2026-06-25T20:26:39.007Z -->

<!-- Updated by bot at 2026-06-25T20:26:46.528Z -->

<!-- Updated by bot at 2026-06-25T20:26:54.194Z -->

<!-- Updated by bot at 2026-06-25T20:27:01.873Z -->

<!-- Updated by bot at 2026-06-25T20:27:09.391Z -->

<!-- Updated by bot at 2026-06-25T20:27:17.600Z -->

<!-- Updated by bot at 2026-06-25T20:27:25.020Z -->

<!-- Updated by bot at 2026-06-25T20:27:32.736Z -->

<!-- Updated by bot at 2026-06-25T20:27:40.521Z -->

<!-- Updated by bot at 2026-06-25T20:27:47.971Z -->

<!-- Updated by bot at 2026-06-25T20:27:55.629Z -->

<!-- Updated by bot at 2026-06-25T20:28:02.977Z -->

<!-- Updated by bot at 2026-06-25T20:28:10.446Z -->

<!-- Updated by bot at 2026-06-25T20:28:18.102Z -->

<!-- Updated by bot at 2026-06-25T20:28:25.696Z -->

<!-- Updated by bot at 2026-06-25T20:28:37.116Z -->

<!-- Updated by bot at 2026-06-25T20:28:45.116Z -->

<!-- Updated by bot at 2026-06-25T20:28:52.964Z -->

<!-- Updated by bot at 2026-06-25T20:29:01.028Z -->

<!-- Updated by bot at 2026-06-25T20:29:09.122Z -->

<!-- Updated by bot at 2026-06-25T20:29:16.942Z -->

<!-- Updated by bot at 2026-06-25T20:29:24.593Z -->

<!-- Updated by bot at 2026-06-25T20:29:32.285Z -->

<!-- Updated by bot at 2026-06-25T20:29:39.450Z -->

<!-- Updated by bot at 2026-06-25T20:29:51.393Z -->

<!-- Updated by bot at 2026-06-25T20:29:58.962Z -->

<!-- Updated by bot at 2026-06-25T20:30:06.525Z -->

<!-- Updated by bot at 2026-06-25T20:30:14.697Z -->

<!-- Updated by bot at 2026-06-25T20:30:22.244Z -->

<!-- Updated by bot at 2026-06-25T20:30:29.991Z -->

<!-- Updated by bot at 2026-06-25T20:30:38.366Z -->

<!-- Updated by bot at 2026-06-25T20:30:45.915Z -->

<!-- Updated by bot at 2026-06-25T20:30:53.351Z -->

<!-- Updated by bot at 2026-06-25T20:31:00.925Z -->

<!-- Updated by bot at 2026-06-25T20:31:09.075Z -->

<!-- Updated by bot at 2026-06-25T20:31:16.644Z -->

<!-- Updated by bot at 2026-06-25T20:31:24.597Z -->

<!-- Updated by bot at 2026-06-25T20:31:32.429Z -->

<!-- Updated by bot at 2026-06-25T20:31:40.042Z -->

<!-- Updated by bot at 2026-06-25T20:31:51.818Z -->

<!-- Updated by bot at 2026-06-25T20:31:59.453Z -->

<!-- Updated by bot at 2026-06-25T20:32:07.109Z -->

<!-- Updated by bot at 2026-06-25T20:32:18.219Z -->

<!-- Updated by bot at 2026-06-25T20:32:25.840Z -->

<!-- Updated by bot at 2026-06-25T20:32:33.384Z -->

<!-- Updated by bot at 2026-06-25T20:32:40.868Z -->

<!-- Updated by bot at 2026-06-25T20:32:48.420Z -->

<!-- Updated by bot at 2026-06-25T20:32:56.407Z -->

<!-- Updated by bot at 2026-06-25T20:33:03.982Z -->

<!-- Updated by bot at 2026-06-25T20:33:12.443Z -->

<!-- Updated by bot at 2026-06-25T20:33:20.768Z -->

<!-- Updated by bot at 2026-06-25T20:33:28.172Z -->

<!-- Updated by bot at 2026-06-25T20:33:35.789Z -->

<!-- Updated by bot at 2026-06-25T20:33:43.258Z -->

<!-- Updated by bot at 2026-06-25T20:33:51.164Z -->

<!-- Updated by bot at 2026-06-25T20:33:58.867Z -->

<!-- Updated by bot at 2026-06-25T20:34:06.743Z -->

<!-- Updated by bot at 2026-06-25T20:34:14.638Z -->

<!-- Updated by bot at 2026-06-25T20:34:22.158Z -->

<!-- Updated by bot at 2026-06-25T20:34:38.729Z -->

<!-- Updated by bot at 2026-06-25T20:34:46.434Z -->

<!-- Updated by bot at 2026-06-25T20:34:53.801Z -->

<!-- Updated by bot at 2026-06-25T20:35:01.751Z -->

<!-- Updated by bot at 2026-06-25T20:35:09.455Z -->

<!-- Updated by bot at 2026-06-25T20:35:17.063Z -->

<!-- Updated by bot at 2026-06-25T20:35:37.342Z -->

<!-- Updated by bot at 2026-06-25T20:35:45.373Z -->

<!-- Updated by bot at 2026-06-25T20:35:53.229Z -->

<!-- Updated by bot at 2026-06-25T20:36:00.815Z -->

<!-- Updated by bot at 2026-06-25T20:36:08.451Z -->

<!-- Updated by bot at 2026-06-25T20:36:16.408Z -->

<!-- Updated by bot at 2026-06-25T20:36:24.292Z -->

<!-- Updated by bot at 2026-06-25T20:36:32.126Z -->

<!-- Updated by bot at 2026-06-25T20:36:39.489Z -->

<!-- Updated by bot at 2026-06-25T20:36:51.451Z -->

<!-- Updated by bot at 2026-06-25T20:36:58.954Z -->

<!-- Updated by bot at 2026-06-25T20:37:06.185Z -->

<!-- Updated by bot at 2026-06-25T20:37:13.669Z -->

<!-- Updated by bot at 2026-06-25T20:37:21.138Z -->

<!-- Updated by bot at 2026-06-25T20:37:28.716Z -->

<!-- Updated by bot at 2026-06-25T20:37:49.231Z -->

<!-- Updated by bot at 2026-06-25T20:37:56.983Z -->

<!-- Updated by bot at 2026-06-25T20:38:05.377Z -->

<!-- Updated by bot at 2026-06-25T20:38:13.053Z -->

<!-- Updated by bot at 2026-06-25T20:38:20.444Z -->

<!-- Updated by bot at 2026-06-25T20:38:27.986Z -->

<!-- Updated by bot at 2026-06-25T20:38:39.428Z -->

<!-- Updated by bot at 2026-06-25T20:38:47.061Z -->

<!-- Updated by bot at 2026-06-25T20:38:54.638Z -->

<!-- Updated by bot at 2026-06-25T20:39:02.325Z -->

<!-- Updated by bot at 2026-06-25T20:39:09.919Z -->

<!-- Updated by bot at 2026-06-25T20:39:17.685Z -->
