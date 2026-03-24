🌾 AgroSustenta

AgroSustenta é uma plataforma web voltada para o rastreamento, controle e avaliação das distribuições de sementes realizadas por cooperativas, armazéns e pela administração do IPA (Instituto Agronômico de Pernambuco).
Nosso objetivo é promover transparência, eficiência e sustentabilidade no processo de distribuição de sementes para os produtores rurais, garantindo que os insumos cheguem dentro da validade e de forma organizada.

🚀 Objetivo do Projeto

A AgroSustenta foi desenvolvida para digitalizar e otimizar o processo de distribuição de sementes, permitindo que os gestores e cooperativas possam:

Rastrear cada lote de sementes desde o armazém até o produtor rural;

Monitorar datas de validade e status de entrega em tempo real;

Receber alertas quando um lote estiver próximo da validade;

Facilitar a comunicação entre cooperativas, armazéns e administração do IPA;

Gerar relatórios e indicadores de desempenho das distribuições.

👥 Público-Alvo
Usuário	Função
🧑‍💼 Administradores do IPA	Acompanham, avaliam e aprovam as distribuições realizadas.
🏢 Armazéns	Gerenciam os estoques, organizam as saídas e monitoram as validades das sementes.
🤝 Cooperativas	Fazem a ponte entre o IPA e os produtores rurais, realizando a entrega das sementes.
🌱 Produtores Rurais	Recebem as sementes e podem acompanhar a origem e o status de suas entregas.
🧩 Funcionalidades Principais

📦 Gestão de Lotes: cadastro, rastreamento e histórico de movimentação;

⏰ Monitoramento de Validade: alertas automáticos para produtos próximos da expiração;

🚚 Status de Entregas: atualização em tempo real sobre pedidos e entregas concluídas;

📊 Painel Administrativo: gráficos e indicadores sobre distribuições e desempenho;

📍 Localização e Rota: acompanhamento da origem e destino dos lotes;

🧾 Histórico de Distribuição: registro completo de cada entrega realizada.

🖥️ Protótipo

🔗 Veja o protótipo do AgroSustenta no Figma:
👉 Acessar protótipo no Figma

🛠️ Tecnologias Utilizadas

Frontend: HTML5, CSS3, JavaScript

Backend: Python (Flask ou Django)

Banco de Dados: MySQL

Design e UI: Figma

Controle de Versão: Git e GitHub

🧠 Benefícios do Sistema

Redução de perdas por vencimento de sementes;

Aumento da transparência nas distribuições;

Melhoria na comunicação entre entidades;

Automação de relatórios e indicadores de desempenho;

Suporte à sustentabilidade e rastreabilidade no setor agro.

🌍 Impacto Sustentável

A AgroSustenta contribui para o Desenvolvimento Sustentável ao:

Evitar desperdício de sementes e insumos agrícolas;

Incentivar a rastreabilidade e a responsabilidade nas distribuições;

Promover a eficiência logística e o uso consciente de recursos públicos.

🧑‍💻 Equipe de Desenvolvimento

Design de Interface: Protótipo desenvolvido no Figma

Desenvolvimento Web: Equipe AgroSustenta

Supervisão Técnica: Instituto Agronômico de Pernambuco (IPA)

## 📋 Sobre o Projeto

Este projeto foi desenvolvido como parte de um protocolo de User Experience (UX), focando em design centrado no usuário. A solução visa resolver problemas como perdas de grãos, falta de controle de estoque e dificuldade na rastreabilidade de sementes.

**Principais Objetivos:**
* **Rastreabilidade:** Acompanhamento do ciclo de vida das sementes via lotes e QR Codes.
* **Gestão:** Painéis de controle (Dashboards) para Cooperativas e Armazéns.
* **Sustentabilidade:** Redução de desperdícios através de controle eficiente.

## 🚀 Funcionalidades

O sistema conta com fluxos distintos para diferentes perfis de usuário:

### 1. 🏠 Institucional (Público)
* Landing Page com apresentação do projeto, missão e parceiros.
* Navegação suave (Smooth Scroll) entre as seções.

### 2. 🚜 Cooperativas
* Cadastro completo da entidade.
* Registro de lotes de sementes (Espécie, Quantidade, Validade).
* **Dashboard Interativo:** Gráficos de desempenho e tabelas de resumo de estoque.
* Histórico detalhado de lotes ativos.

### 3. 🏭 Armazéns
* Fluxo de recebimento e controle de estoque (Entrada/Saída).
* Registro de distribuição para produtores.
* **Dashboard de Monitoramento:** Visualização de saídas recentes e status de entrega.

### 4. 🔍 Rastreabilidade (Público)
* Página de consulta pública via ID do pacote ou QR Code simulado.
* Exibição transparente de dados de produção e origem.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica das páginas.
* **CSS3:** Estilização responsiva, variáveis de cor, Flexbox e CSS Grid.
* **JavaScript (Vanilla):** Interatividade, navegação e manipulação de DOM.
* **Chart.js:** Biblioteca externa para geração dos gráficos nos dashboards.

## 📂 Estrutura de Arquivos

Abaixo, a organização das páginas do projeto:

```text
AgroSustenta/
│
├── index.html                      # Página Inicial (Landing Page)
├── perfil.html                      # Seleção de Perfil (Hub de entrada)
├── style.css                       # Folha de estilos global
├── script.js                       # Lógica e scripts globais
├── README.md                       # Documentação do projeto
│
├── 📂 Fluxo Cooperativa
│   ├── cadastro-cooperativa.html   # Passo 1: Dados da Empresa
│   ├── cadastro-lotes.html         # Passo 2: Registro de Sementes
│   ├── cadastro-estoque.html       # Passo 3: Definição de Estoque
│   ├── dashboard-cooperativa.html  # Painel Principal (Gráficos)
│   └── historico-lotes.html        # Tabelas Detalhadas
│
├── 📂 Fluxo Armazém
│   ├── cadastro-armazem.html               # Passo 1: Dados do Armazém
│   ├── cadastro-estoque-armazem.html       # Passo 2: Controle de Entrada/Saída
│   ├── cadastro-distribuicao-armazem.html  # Passo 3: Distribuição
│   └── dashboard-armazem.html              # Painel Principal (Tabelas e Status)
│
└── 📂 Rastreio
    └── rastreio.html               # Página pública de rastreamento de pacotes
🎨 Design System
O projeto utiliza uma paleta de cores inspirada na natureza e na agricultura sustentável:

Verde Escuro (#1A4A2A): Identidade principal, cabeçalhos e botões primários.

Verde Médio (#3a7d44): Elementos de destaque e tabelas.

Amarelo/Ouro (#e6db74): Botões de ação secundária e destaques visuais.

Branco/Cinza (#f4f4f4): Fundos e áreas de leitura.

📦 Como Executar
Este é um projeto estático (Front-end). Para rodá-lo:

Baixe a pasta do projeto.

Certifique-se de que todas as imagens estão na mesma pasta (ou ajuste os caminhos).

Abra o arquivo index.html em qualquer navegador moderno (Chrome, Firefox, Edge).