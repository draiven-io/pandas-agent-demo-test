# pandas-agent-demo-test

Teste técnico para desenvolvedor(a) Fullstack Python.

O objetivo é desenvolver uma aplicação fullstack simples que permita ao usuário fazer perguntas sobre um conjunto de dados em CSV, utilizando um agente LLM com pandas (LangChain) no backend, e um frontend em Next.js com uma interface de chat.

---

## 🚀 O que deve ser feito

### ✅ Funcionalidades esperadas

1. O backend deve:
   - Ser feito com **FastAPI**.
   - Utilizar **LangChain** com **Pandas Agent**.
   - Carregar um CSV (ex: `sales.csv`) com dados fictícios de vendas.
   - Possuir uma rota `/ask` que receba uma pergunta e retorne uma resposta com base no conteúdo do CSV.

2. O frontend deve:
   - Ser feito com **Next.js**.
   - Ter uma interface simples estilo chat (campo de input e botão de enviar).
   - Enviar perguntas para a API e exibir as respostas em tempo real.

3. O projeto deve estar organizado com boas práticas e conter instruções claras de execução no `README.md`.

---

## 🧠 Exemplos de perguntas que o usuário pode fazer

- "Qual foi o total de vendas?"
- "Quais foram os produtos mais vendidos?"
- "Qual foi o mês com maior receita?"
- "Qual o ticket médio por produto?"

---

## ▶️ Como executar

### 🔙 Backend

```bash
cd backend
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### 🔙 Frontend

```bash
cd frontend
npm install
npm run dev
```

## ✅ Entrega esperada

- -Código-fonte versionado no GitHub.

- README.md com instruções claras.

- Organização do código (modularidade, boas práticas).

- Frontend funcional com interação básica via API.