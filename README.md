Sistema de Gestão Orçamentária – PELD Pró-Mata

🔗 Aplicação online:
https://gestaopeldpromata.netlify.app/

📂 Repositório:
https://github.com/leticialmbarros/gestao-peld

📖 Sobre o Projeto

O Sistema de Gestão PELD Pró-Mata é uma aplicação web desenvolvida para apoiar a gestão financeira e administrativa do Projeto de Pesquisa Ecológica de Longa Duração (PELD) realizado na RPPN Pró-Mata.
O sistema foi criado para organizar e registrar despesas vinculadas às atividades científicas do projeto, permitindo o controle detalhado de: despesas; rubricas orçamentárias; grupos de pesquisa; metas científicas; documentação de compras; status de entregas. 
A plataforma busca facilitar a gestão financeira do projeto e preparar os dados para prestação de contas junto às agências de fomento, como: CNPq e FAPERGS

🎯 Objetivos do Sistema

O sistema foi desenvolvido com os seguintes objetivos:

✔ Centralizar os lançamentos financeiros do projeto
✔ Organizar despesas por grupo e subgrupo de pesquisa
✔ Vincular despesas às metas científicas do projeto
✔ Registrar informações administrativas de compras
✔ Monitorar entregas e documentação fiscal
✔ Preparar dados estruturados para análises e dashboards

⚙️ Funcionalidades Principais
💰Registro de Despesas: O sistema permite registrar despesas contendo informações como:
Data da despesa
Membro responsável
Grupo e subgrupo de pesquisa
Rubrica orçamentária
Subcategoria
Fonte da verba
Meta associada
Valor da compra
Forma de pagamento

👥 Organização por Membros do Projeto

Cada despesa pode ser associada a um membro do projeto, permitindo: rastrear quem solicitou ou realizou a despesa, analisar gastos por pesquisador, acompanhar atividades por grupo de pesquisa.

🧬 Classificação por Grupos de Pesquisa

As despesas podem ser vinculadas aos principais grupos do projeto: Vertebrados; Artrópodes; Plantas; DNA Ambiental

Cada grupo possui subgrupos específicos, permitindo maior detalhamento das atividades científicas.

📊 Vinculação com Metas Científicas

Cada despesa pode ser associada a uma meta ou etapa do projeto, permitindo posteriormente: análise da execução financeira das metas, acompanhamento da distribuição de recursos, geração de relatórios científicos e financeiros.

📦 Controle Administrativo de Compras

O sistema registra dados importantes do processo de compra:
data da solicitação
data da compra
fornecedor
número da nota fiscal ou recibo
link do comprovante
quantidade
valor orçado
localização do material

🚚 Monitoramento de Entregas

O sistema permite registrar:
data da entrega
responsável pelo recebimento
situação da entrega
se a entrega está atrasada

Isso facilita o controle logístico dos materiais adquiridos para o projeto.

📎 Controle de Documentação

Cada despesa pode registrar:
número de NF ou recibo
link para comprovante
confirmação de entrega de documentação

Isso facilita a organização dos documentos para prestação de contas.

🧠 Arquitetura do Sistema

O sistema foi desenvolvido como uma aplicação web leve, priorizando simplicidade, facilidade de manutenção e hospedagem gratuita.

Arquitetura geral:

Usuário
   ↓
Interface Web (HTML + CSS)
   ↓
Lógica da Aplicação (TypeScript)
   ↓
Persistência de Dados
   ↓
Google Sheets (base de dados)

Essa arquitetura permite:

edição simples dos dados

integração futura com dashboards

manutenção rápida

🗂 Estrutura do Projeto
gestao-peld
│
├── index.html
│   Interface principal do sistema
│
├── main.ts
│   Lógica da aplicação
│
├── styles.css
│   Estilização da interface
│
├── package.json
│   Dependências do projeto
│
└── README.md
    Documentação do projeto
🚀 Deploy

O sistema é hospedado utilizando Netlify, com deploy automático conectado ao GitHub.

Fluxo de deploy:

GitHub → Netlify → Aplicação Online

🔗 https://gestaopeldpromata.netlify.app/

💻 Executando o Projeto Localmente

Caso deseje rodar o projeto localmente:

1️⃣ Clonar o repositório
git clone https://github.com/leticialmbarros/gestao-peld.git
2️⃣ Entrar na pasta do projeto
cd gestao-peld
3️⃣ Instalar dependências
npm install
4️⃣ Executar o projeto
npm run dev
📊 Roadmap do Projeto

Próximas funcionalidades planejadas:

🔹 Integração completa com Google Sheets

Salvar automaticamente os lançamentos em planilhas.

🔹 Dashboard financeiro

Visualização de:

orçamento executado

despesas por grupo

despesas por meta

execução por rubrica

🔹 Sistema de validação CNPq

Aplicar regras automáticas para identificar despesas vedadas ou restritas.

🔹 Relatórios automáticos

Exportação de relatórios para:

prestação de contas

acompanhamento interno

🔹 Controle de estoque

Monitoramento de materiais adquiridos e sua localização.

👩‍💻 Desenvolvimento

Projeto desenvolvido por:

Letícia Maria Lima Barros

Analista responsável pela organização de dados, gestão financeira e estruturação de sistemas de controle para o projeto PELD Pró-Mata.

📄 Licença

Este projeto foi desenvolvido para uso acadêmico e institucional no contexto do Projeto PELD Pró-Mata.

⭐ Caso este projeto seja útil, considere dar uma estrela no repositório.
