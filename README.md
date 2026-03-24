## 🌱 AgroSustenta
O Agro Sustenta é uma plataforma web para produtores rurais e cooperativas com foco na rastreabilidade, controle e sustentabilidade no uso e distribuição de sementes. Nosso objetivo é centralizar informações agrícolas como processos de fecundação, clima, características de sementes e rastreamento completo da distribuição para melhorar o planejamento de plantio e reduzir perdas.



## 👩‍💻 Equipe desenvolvedora
Dayane Oliveira 
Ingrid Rosendo
Juliana Vasconcelos
Julliane Valentin
Ludmilla Arlane



## ⚙️ Tecnologias utilizadas
O projeto foi construído como uma aplicação Full-Stack, utilizando o seguinte stack de tecnologias:

## 🌐 Frontend
HTML5	
CSS3	
JavaScript

## 💻 Backend e banco de dados
Node.js
Express.js	
MySQL	



## 💡 Funcionalidades principais
O sistema AgroSustenta oferece um conjunto de funcionalidades essenciais para o gerenciamento de sementes:

Cadastro de sementes e lotes: registro detalhado de cada tipo de semente e dos lotes recebidos, incluindo espécie, quantidade, e validade.
Gestão de armazém e estoque: controle físico e lógico do local de armazenamento e das entradas/saídas de lotes.
Registro de distribuição: criação de pedidos de saída de sementes para entrega.
Rastreamento completo: acompanhamento do percurso da semente desde o armazém até o destinatário final.
Validação por cooperativa: confirmação e finalização do processo de entrega pela organização parceira.



## 🔄 Fluxo de dados simplificado
O fluxo de dados da aplicação segue o modelo Full-Stack tradicional, integrando as camadas de apresentação, lógica de negócios e persistência:

Frontend (HTML/CSS/JS): coleta dados do usuário ou solicita dados para exibição.
Comunicação (JavaScript): envia requisições HTTP como GET, POST para a API.
Backend (Node.js/Express.js): recebe a requisição, executa a lógica de negócios e conecta-se ao MySQL para realizar a operação.
Banco de dados (MySQL): armazena e retorna os dados.
Resposta: o backend envia a resposta de volta ao frontend para atualizar a interface.



## 🚀 Como executar
Para rodar este projeto localmente, siga os passos abaixo:

Clone o repositório;
Instale as dependências do Node.js/Express (npm install);
Configure o banco de dados MySQL e as credenciais de conexão no backend;
Inicie o servidor Node.js/Express;
Abra o arquivo index.html no navegador.


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
