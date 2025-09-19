# Dashboard-Infra
Infra para um Saas de gestão financeira. Usando conceito de repos separados
____________________________________________________________________________________________________________________________________

# 📊 Saas de Análise Financeira

<!-- Exemplo de imagem do topo -->

## 📌 Descrição

Este projeto consiste em um **Dashboard Interativo para análise** de dados financeiros, permitindo a visualização e interpretação de métricas essenciais como:

 - Receitas

 - Despesas

 - Lucro líquido

 - Comparação de períodos

 - Distribuição por categorias
   
 - Visualização da Bolsa de valores
   
 - Comparação de investimentos e dividendos

O objetivo é fornecer uma visão clara e dinâmica para auxiliar na tomada de decisões financeiras.

## 🚀 Funcionalidades

 - 📈 Gráficos Interativos (linhas, barras, pizza, etc.)

 - 📊 Filtros Dinâmicos por data, categoria e região

 - 🏦 Análise de Receita x Despesa

 - 📅 Comparação Anual e Mensal

 - 📤 Exportação de Relatórios (PDF e Excel)

## 🛠️ Tecnologias Utilizadas

 - **Frontend (UI/UX):**  React + Next.js + Tailwind + Recharts

 - **Backend:** NestJS

 - **Banco:** PostgreSQL + Redis + (MongoDB opcional)
 
 - **Segurança:** OAuth2/OpenID, RBAC/ABAC, monitoramento de vazamento, conta temporária SOS
 
 - **Infra:** Docker + Kubernetes + Cloud Provider (AWS/GCP/Azure)
 
 - **Extras:** PWA, relatórios exportáveis, notificações

<pre>📦 dashboard-backend
├── 📁 data
├── 📁 src
│   ├── app.py
│   ├── data_processing.py
│   ├── charts.py
│   └── config.py
├── requirements.txt
├── Dockerfile
└── README.md
 </pre>
<pre>📦 dashboard-frontend
├── 📁 public
├── 📁 src
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   └── components/
├── package.json
├── vite.config.js
├── tailwind.config.js
└── README.md
</pre>
<pre>📦 dashboard-infra
├── docker-compose.yml
├── .env
└── README.md
</pre>

## 📸 Demonstração

Exemplo de Tela do Dashboard:


Gráfico Interativo de Receita vs Despesa:


## 📦 Como Instalar e Rodar
<!-- 1️⃣ Clonar o repositório
git clone https://github.com/seuusuario/dashboard-financeiro.git
cd dashboard-financeiro

2️⃣ Criar ambiente virtual
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

3️⃣ Instalar dependências
pip install -r requirements.txt

4️⃣ Executar aplicação
python src/app.py


Acesse http://localhost:8050 no navegador. -->

## 📊 Fonte dos Dados

- Os dados utilizados neste projeto são reais, extraídos de relatórios públicos e bases como:

- Banco Central do Brasil

- IBGE

- Yahoo Finance

## 🤝 Contribuindo

**Contribuições são bem-vindas!**
 - Para contribuir:

 - Faça um fork do repositório

 - Crie uma nova branch (git checkout -b minha-feature)

 - Faça suas alterações e commit

 - Envie um pull request

## 📝 Licença

Este projeto está sob a licença MIT.
Veja o arquivo LICENSE para mais detalhes.
