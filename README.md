---

## 🛍️ Assistente Virtual da Loja  

Um chatbot inteligente para atendimento ao cliente de uma loja online de eletrônicos, utilizando **Gemini AI** e **Gradio** para uma interface interativa.  

🔹 **Capacidade de chamar funções dinamicamente com IA** – O assistente consegue **decidir e executar automaticamente funções** para consultar pedidos, registrar reclamações e gerar cupons de desconto, tornando o atendimento mais eficiente.  

---

## 🚀 Funcionalidades  
✅ **Consulta de pedidos** – O assistente pode informar o status de um pedido.  
✅ **Registro de reclamações** – O cliente pode enviar imagens de produtos com defeito, e o assistente registra a reclamação.  
✅ **Geração de cupons** – Clientes recorrentes ou insatisfeitos podem receber um cupom de desconto.  
✅ **Respostas automáticas** – O assistente responde perguntas sobre políticas de devolução, troca e outros assuntos da loja.  
✅ **Execução Inteligente de Funções** – O modelo **chama automaticamente** as funções apropriadas com base na conversa.  

---

## 🛠️ Tecnologias Usadas  
- **Python** 🐍  
- **Gradio** (Interface de chatbot)  
- **Google Gemini AI** (Modelo de IA generativa com suporte a chamadas de função)  

---

## 📦 Instalação  

### 1️⃣ Clone o repositório  
```sh
git clone https://github.com/seu-usuario/assistente-sac.git
cd assistente-sac
```

### 2️⃣ Crie um ambiente virtual e ative  
```sh
python3 -m venv .venv
source .venv/bin/activate  # No Windows: .venv\Scripts\activate
```

### 3️⃣ Instale as dependências  
```sh
pip install -r requirements.txt
```

### 4️⃣ Configure a chave da API Gemini  
Crie um arquivo **`.env`** na raiz do projeto e adicione sua chave da API do Google Gemini:  
```
GEMINI_API_KEY=your_api_key_here
```

---

## ▶️ Como Usar  
Inicie o assistente com o seguinte comando:  
```sh
python app.py
```
Ele abrirá automaticamente a interface no navegador.  

---

## 📝 Estrutura do Projeto  
```
assistente-sac/
│── utils/
│   ├── functions.py       # Funções de atualização de pedido, cupons e reclamações
│   ├── geminiAPI.py       # Integração com a API Gemini
│── app.py                 # Código principal do chatbot
│── requirements.txt        # Dependências do projeto
│── README.md               # Documentação do projeto
```

---

## 🤝 Contribuição  
Sinta-se à vontade para abrir **issues** e **pull requests**. 🚀  

---
