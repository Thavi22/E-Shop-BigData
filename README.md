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


