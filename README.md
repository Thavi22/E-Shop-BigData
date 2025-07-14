# E-Shop-BigData

# Aplicação Prática de Tecnologias de Banco de Dados e Big Data em uma Empresa de Comércio Eletrônico

## Introdução

A E-Shop Brasil é uma das maiores plataformas de comércio eletrônico do país, oferecendo uma ampla variedade de produtos — de eletrônicos a itens de moda — e atendendo milhões de clientes em todo o território nacional. Fundada em 2010, a empresa já ultrapassou a marca de 5 milhões de clientes ativos e atualmente processa em média 100 mil pedidos por dia.

Com o crescimento acelerado das operações, surgem também desafios cada vez mais complexos relacionados à gestão eficiente dos dados, personalização da experiência do usuário e otimização da logística. A equipe de Tecnologia da Informação da E-Shop Brasil foi encarregada de desenvolver uma solução que resolva esses problemas com o uso de tecnologias modernas de bancos de dados e Big Data, garantindo resultados escaláveis e sustentáveis.

## Objetivos do Projeto

Este projeto tem como objetivo propor uma solução tecnológica prática e funcional que ajude a E-Shop Brasil a:

- Garantir a segurança e privacidade dos dados dos clientes, em conformidade com a LGPD;
- Personalizar a navegação e as recomendações com base no comportamento de compra dos usuários;
- Melhorar a eficiência das entregas e do controle de estoque, especialmente em regiões mais distantes;
- Integrar e escalar as operações com base em tecnologias modernas e sustentáveis a longo prazo.

A proposta será implementada utilizando bancos de dados relacionais (SQL), bancos de dados não relacionais (NoSQL, com foco em MongoDB) e ferramentas de Big Data como Hadoop e Spark. Toda a infraestrutura será criada de forma padronizada com Docker, e a aplicação será desenvolvida em Python utilizando Streamlit como interface gráfica.

## Tecnologias Utilizadas

- **Docker**: para criação de um ambiente isolado e padronizado.
- **MongoDB**: como banco de dados NoSQL para armazenar os dados do cliente.
- **Python com Streamlit**: para desenvolvimento da aplicação com interface gráfica.
- **Big Data (Hadoop, Spark)**: como referência teórica e técnica para soluções escaláveis.
- **Kaggle** ou dados fictícios: para popular o banco MongoDB com informações simuladas.

## Descrição do Projeto

A proposta foi desenvolvida com foco na praticidade, replicabilidade e organização da infraestrutura utilizando Docker, MongoDB e Streamlit.

### Ambiente com Docker

Para garantir que qualquer usuário consiga executar o projeto localmente com o mesmo ambiente, foi utilizada a tecnologia Docker. O projeto pode ser executado utilizando:

- **Dockerfile**: Criação manual da imagem.
- **docker-compose.yml**: Para subir automaticamente um container com MongoDB.

Com isso, é possível isolar as dependências, padronizar a execução e evitar erros de configuração local.

### Banco de Dados NoSQL – MongoDB

O banco de dados MongoDB será utilizado para armazenar os dados dos clientes e das operações simuladas. Ele é ideal para lidar com dados semi-estruturados e não estruturados, como informações de navegação, carrinhos de compras e histórico de buscas.

Serão realizadas as seguintes operações:
- Inserção de dados
- Edição ou exclusão de registros
- Concatenação de dados entre coleções
- Consultas e leitura com exibição via interface gráfica

### Aplicação em Python com Streamlit

A aplicação principal será desenvolvida em Python utilizando a biblioteca Streamlit para criação de uma interface gráfica simples, onde o usuário poderá:
- Inserir dados diretamente no MongoDB
- Visualizar os dados em tabelas
- Fazer consultas personalizadas
- Executar operações CRUD (Create, Read, Update, Delete)

O código principal será desenvolvido no arquivo `app.py`.

### Dados de Exemplo

Para testar o funcionamento do sistema, serão utilizados dados fictícios criados manualmente ou extraídos de plataformas como o [Kaggle](https://www.kaggle.com/), com foco em simular um ambiente realista de e-commerce.

---

## Passos para Execução

### Pré-requisitos:
- Docker instalado na máquina
- Python 

### Passos para rodar o projeto com Docker Compose:

docker-compose up


## Levantamento de Soluções e Análise Crítica

### 1. Quais são as principais causas do problema de gestão de dados e otimização logística na E-Shop Brasil?

A E-Shop Brasil enfrenta uma grande dificuldade para lidar com o volume crescente de dados e com a complexidade das operações logísticas. Entre as principais causas estão:

- Falta de integração entre os sistemas da empresa (loja online, estoque, atendimento);
- Armazenamento de dados de forma não padronizada e difícil de consultar;
- Dificuldade em transformar dados em insights para personalização da experiência do cliente;
- Ineficiência na distribuição de produtos, especialmente em regiões remotas.

Esses fatores, somados, comprometem a agilidade, a previsibilidade e a tomada de decisões estratégicas.

---

### 2. Quais são os principais afetados por esse problema e como eles são impactados?

O impacto é sentido diretamente por dois grupos:

- **Clientes**: sofrem com prazos de entrega não cumpridos, falhas no estoque e recomendações pouco relevantes. Isso gera frustração, reclamações e abandono de carrinhos.
- **A empresa**: perde competitividade, enfrenta altos custos operacionais e prejudica sua reputação no mercado digital. Além disso, pode enfrentar riscos legais por falhas na proteção de dados.

---

### 3. Quais são as possíveis soluções para este problema e quais os prós e contras de cada uma?

**Solução 1: Implementação de um Sistema ERP (Gestão Integrada)**

- *Prós*: centraliza dados, melhora o controle de estoque e integra todas as áreas.
- *Contras*: custo elevado, tempo de implantação e resistência cultural da equipe.

**Solução 2: Uso de Banco de Dados NoSQL (MongoDB)**

- *Prós*: flexibilidade para dados não estruturados, escalabilidade, agilidade na inserção e leitura.
- *Contras*: curva de aprendizado maior, necessidade de adaptação para quem vem de SQL tradicional.

**Solução 3: Adoção de Ferramentas de Big Data (Hadoop, Spark)**

- *Prós*: permite analisar grandes volumes de dados em tempo real, identificar padrões e tomar decisões baseadas em dados.
- *Contras*: demanda infraestrutura robusta e profissionais com conhecimento técnico especializado.

A solução adotada neste projeto combina **NoSQL com MongoDB** e base para expansão com **Big Data**, equilibrando simplicidade de implementação com potencial de crescimento.

---

### 4. Quais são as barreiras ou desafios para resolver esse problema?

- **Resistência interna** à mudança de ferramentas e processos;
- **Falta de recursos financeiros** para adoção de soluções robustas como ERP completo;
- **Necessidade de capacitação** da equipe para operar novas tecnologias;
- **Integração com sistemas legados**, que muitas vezes não foram projetados para interoperar.

O projeto proposto contorna essas barreiras com uma solução leve, prática e acessível, que pode ser expandida gradualmente.

---

### 5. Como este problema se relaciona com os conceitos estudados em aula?

O projeto aplica diretamente os conceitos vistos nas disciplinas de:
- **Banco de Dados NoSQL**, com uso prático do MongoDB;
- **Big Data**, como visão estratégica e expansão futura;
- **Ambientes isolados com Docker**, seguindo boas práticas de padronização;
- **Aplicação real com Streamlit**, conectando teoria com interface gráfica funcional.

Assim, os conhecimentos técnicos foram aplicados em um problema real com clareza e aplicabilidade imediata.

---

### 6. Quais são as implicações a longo prazo se este problema não for resolvido?

- Perda contínua de clientes devido à insatisfação com logística e atendimento;
- Aumento dos custos operacionais com estoques mal gerenciados e retrabalho;
- Risco legal por falhas na proteção de dados dos usuários;
- Redução da competitividade diante de players que já trabalham com dados de forma inteligente e personalizada.

Investir em uma base sólida de dados hoje é o que permitirá à E-Shop Brasil continuar crescendo de forma escalável, eficiente e centrada no cliente.

