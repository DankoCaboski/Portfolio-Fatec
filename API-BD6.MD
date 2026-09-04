# Sobre mim

Me chamo Willian Danko, tenho 22 anos e sou graduando em banco de dados pela fatec São José dos Campos

Profissionamelte atuo como programador PLC par a na Axis Solutions.

[![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/willian-danko-leite-caboski-5410741b4) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/DankoCaboski)


## Projeto: Sistema de Análise de Dados KPI Cards

[![Generic badge](https://img.shields.io/badge/GitHub-Repositório-blue.svg)](https://github.com/NoDesk-6BD/6sem2025Main)

Parceiro Acadêmico: [Pro4Tech](https://pro4tech.com.br/).

## Resumo do projeto

<p align="justify">A Pro4Tech é uma empresa especializada em Transformação Digital, focada em desenvolver soluções tecnológicas que impulsionam a eficiência, inovação e crescimento de seus clientes. Sua atuação envolve desde a concepção de produtos digitais utilizando metodologias como Design Sprint e Design Thinking, passando pela criação de interfaces intuitivas (UX/UI), desenvolvimento com equipes ágeis e DevOps, até a manutenção e evolução contínua das soluções entregues.</p>

<p align="justify">Além disso, a empresa oferece serviços em desenvolvimento Web e Mobile, Inteligência Artificial, Business Intelligence, Automação de Processos (RPA), Internet das Coisas (IoT), soluções de produtividade e plataformas inteligentes para gestão de Recursos Humanos, sempre buscando transformar dados e tecnologia em resultados estratégicos para seus clientes.</p>

<p align="justify">Foi nesse contexto que a Pro4Tech nos apresentou o desafio de transformar os dados do seu sistema de chamados em informações estratégicas que apoiassem a tomada de decisão. O principal problema enfrentado pela empresa era o grande volume de dados armazenados, que dificultava uma análise rápida dos indicadores de atendimento e da performance operacional.</p>

<p align="justify">Para solucionar essa necessidade, desenvolvemos um Sistema de Análise de Dados — KPI Cards, responsável por coletar os dados diretamente do banco SQL Server da empresa, realizar seu processamento por meio de pipelines de ETL e disponibilizar os resultados em dashboards interativos. Com isso, tornou-se possível acompanhar indicadores como volume de chamados, tempo médio de resolução, produtividade da equipe e outras métricas importantes para a gestão do suporte técnico.</p>

<p align="justify">Um dos pontos mais relevantes do projeto foi a arquitetura adotada para o tratamento dos dados. As informações eram extraídas do SQL Server e migradas por meio dos processos de ETL para o MongoDB, um banco de dados NoSQL que armazena os dados em formato BSON. Essa abordagem trouxe um desafio diferente do modelo relacional com o qual estávamos habituados, exigindo uma nova forma de estruturar e consultar os dados. Ao mesmo tempo, proporcionou um importante ganho de conhecimento sobre bancos NoSQL e ampliou nossa experiência prática com diferentes tecnologias de armazenamento de dados.</p>

<p align="justify">Durante o desenvolvimento, buscamos ir além da simples visualização de dados. Implementamos recursos de Inteligência Artificial para realizar previsões da demanda de chamados utilizando modelos preditivos, permitindo uma melhor antecipação da carga de trabalho da equipe. Outro ponto de destaque foi a preocupação com a segurança e a privacidade das informações, adotando mecanismos alinhados à LGPD, como a anonimização e proteção dos dados dos usuários, além da implementação do aceite dos termos de uso da plataforma.</p>

<p align="justify">Esse projeto proporcionou uma experiência prática na construção de uma solução completa de Business Intelligence, envolvendo integração de dados, engenharia de dados, visualização de informações, inteligência artificial e boas práticas de desenvolvimento de software. Além de entregar uma ferramenta capaz de gerar valor real para o processo de tomada de decisão da empresa, o projeto também ampliou significativamente nosso conhecimento sobre integração entre bancos relacionais e não relacionais, mostrando na prática como diferentes tecnologias podem ser combinadas para atender necessidades específicas de negócio.</p>

## Tecnologias adotadas

Frontend: [Vue 3](https://vuejs.org/guide/quick-start.html) e [Nuxt 4](https://nuxt.com/docs/4.x/getting-started/introduction)

Backend: [Python](https://www.python.org/) e [Fast API](https://fastapi.tiangolo.com/learn/)

Banco de dados e ETL [SQL Server](https://www.microsoft.com/pt-br/sql-server#Get-started), [PostgreSQL](https://www.postgresql.org/docs/17/index.html) e [MongoDB](https://www.mongodb.com/products/self-managed/community-edition)

IA: [IA Prophet](https://facebook.github.io/prophet/)

Infraestrutura: [Docker](https://docs.docker.com/) e [Docker Compose](https://docs.docker.com/compose/)

Metodologia ágil: [JIRA](https://confluence.atlassian.com/jira)

## Projeto em funcionamento

<div align="center">

<a href="http://www.youtube.com/watch?v=KZ-d-pSWn4I" target="_blank">
  <img src="http://img.youtube.com/vi/KZ-d-pSWn4I/0.jpg" width="500" alt="Projeto Integrador 2025-2" />
</a>
<br>
<em>Demonstração do projeto em funcionamento, link para o youtube: <a href="http://www.youtube.com/watch?v=KZ-d-pSWn4I" target="_blank">http://www.youtube.com/watch?v=KZ-d-pSWn4I</a></em>

</div>
<br>

- <p align="justify"><b>Frontend:</b> O Frontend foi desenvolvido com Nuxt 4, Vue 3 e TypeScript, onde foram criados os dashboards, gráficos e KPI Cards responsáveis por apresentar os indicadores de forma clara e intuitiva para os usuários.</p>

- <p align="justify"><b>Backend:</b> O Backend foi desenvolvido em Python e FastAPI, responsável por disponibilizar APIs REST consumidas pelo Frontend. Sua estrutura modular facilitou o desenvolvimento, a organização do código e futuras manutenções.</p>

- <p align="justify"><b>ETL:</b> Os dados eram extraídos do banco SQL Server da Pro4Tech e passavam por um processo de ETL, no qual eram tratados e transformados em indicadores prontos para análise e visualização.</p>

- <p align="justify"><b>MongoDB:</b> Após o processamento, os dados eram armazenados no MongoDB, um banco de dados NoSQL baseado em documentos BSON. Trabalhar com essa tecnologia ampliou meu conhecimento em bancos NoSQL e modelagem orientada a documentos.</p>

- <p align="justify"><b>Infraestrutura:</b> A aplicação foi executada em um ambiente containerizado com Docker Compose, facilitando a integração entre os serviços e garantindo um ambiente padronizado para desenvolvimento e testes.</p>

- <p align="justify"><b>Inteligência Artificial:</b> Como diferencial, utilizamos a biblioteca Prophet para criar previsões da demanda de chamados, agregando recursos de Inteligência Artificial à solução.</p>

- <p align="justify"><b>Segurança:</b> Também foram implementadas práticas alinhadas à LGPD, incluindo proteção dos dados dos usuários e aceite dos termos de uso da plataforma. <a href="https://youtu.be/0WpYJ0nmYtg"  target="_blank"> Vídeo demonstração do funcionamento da implementação da LGPD</a></p>

## Contribuições pessoais

<p align="justify">Atuei inicialmente como desenvolvedor Frontend e, a partir da segunda sprint, também assumi a função de Scrum Master, passando a assumir a coordenação técnica do projeto durante as sprints finais. Além do desenvolvimento, participei do gerenciamento das entregas, revisão de código (Code Review), integração entre os repositórios e da modelagem do banco de dados MongoDB utilizado para armazenamento das métricas processadas pelo ETL.<p>

<p align="justify">Durante este projeto, meus principais desafios foram:</p>

- <p align="justify">Conciliar as funções de desenvolvedor Frontend e Scrum Master.</p>
- <p align="justify">Integrar o Frontend às APIs do Backend.</p>
- <p align="justify">Modelar o banco MongoDB para armazenamento das métricas.</p>
- <p align="justify">Realizar Code Review e integração das Pull Requests.</p>
- <p align="justify">Colaborar na implementação do ETL, IA e requisitos da LGPD.</p>

### Frontend:

<p align="justify"><b>Nuxt 4, Vue 3 e TypeScript:</b> Foi a área em que tive maior participação no desenvolvimento. Contribuí na criação das telas, dashboards e KPI Cards, além da integração entre o Frontend e as APIs do Backend. Essa experiência fortaleceu meus conhecimentos em desenvolvimento de interfaces modernas e consumo de APIs REST.</p>

### SGBD:

<p align="justify"><b>MongoDB (NoSQL):</b> Participei da modelagem do banco responsável por armazenar as métricas geradas pelo processo de ETL. Trabalhar com um banco de dados orientado a documentos foi um dos maiores aprendizados do projeto, permitindo conhecer um paradigma diferente dos bancos relacionais utilizados durante a graduação.</p>

### Gestão e Code Review:

<p align="justify"><b>Scrum Master (JIRA) e GitHub:</b> A partir da segunda sprint assumi a responsabilidade de organizar as atividades da equipe, acompanhar o andamento das entregas e realizar o Code Review das Pull Requests em todos os repositórios do projeto. Essa experiência desenvolveu minha capacidade de liderança, organização e colaboração em projetos utilizando controle de versão.</p>

### ETL, Inteligência Artificial e LGPD:

<p align="justify">Os requisitos envolvendo ETL, Inteligência Artificial e LGPD representaram os principais desafios técnicos deste semestre. Participar da construção do processo de ETL, compreender a utilização do MongoDB como destino dos dados, acompanhar a implementação das previsões utilizando Inteligência Artificial e aplicar conceitos da LGPD ampliaram significativamente minha visão sobre engenharia de dados, segurança da informação e desenvolvimento de soluções voltadas ao ambiente corporativo.</p>

## Aprendizados efetivos

### Hard Skills:

- <p align="justify"><b>Nuxt 4, Vue 3 e TypeScript:</b> Uso autônomo: desenvolvimento da interface da aplicação, criação dos dashboards, KPI Cards e integração do Frontend com as APIs REST disponibilizadas pelo Backend.</p>
- <p align="justify"><b>Python e FastAPI:</b> Uso com ajuda: compreensão da arquitetura do Backend, consumo das APIs e participação na integração entre Frontend e Backend.</p>
- <p align="justify"><b>MongoDB (NoSQL):</b> Uso com ajuda: modelagem do banco de dados destinado ao armazenamento das métricas processadas pelo ETL, adquirindo experiência com bancos orientados a documentos e modelagem NoSQL.</p>
- <p align="justify"><b>ETL e Engenharia de Dados:</b> Uso com ajuda: participação na construção do fluxo de extração, transformação e carga dos dados, compreendendo o processamento das informações entre SQL Server e MongoDB para geração dos indicadores.</p>
- <p align="justify"><b>GitHub:</b> Uso autônomo: realização de Code Review, gerenciamento de Pull Requests e integração dos repositórios durante todo o desenvolvimento do projeto.</p>
- <p align="justify"><b>SCRUM (JIRA):</b> Uso autônomo: atuação como Scrum Master a partir da segunda sprint, organizando as atividades da equipe, acompanhando as entregas e garantindo a continuidade do projeto.</p>
- <p align="justify"><b>Docker Compose:</b> Uso com ajuda: utilização da arquitetura containerizada para integração dos serviços e padronização do ambiente de desenvolvimento.</p>

### Soft Skills:

- <p align="justify"><b>Liderança:</b> Assumir a função de Scrum Master durante o desenvolvimento do projeto fortaleceu minha capacidade de organizar atividades, acompanhar entregas e conduzir a equipe diante dos desafios encontrados ao longo das sprints.</p>
- <p align="justify"><b>Comunicação:</b> A integração entre Frontend, Backend, ETL e banco de dados exigiu comunicação constante entre os integrantes da equipe, principalmente durante as revisões de código e definição das soluções implementadas.</p>
- <p align="justify"><b>Resolução de Problemas:</b> Trabalhar com diferentes tecnologias, como MongoDB, ETL, APIs REST e Inteligência Artificial, exigiu pesquisar, testar soluções e compreender novos conceitos para atender aos requisitos do projeto.</p>
- <p align="justify"><b>Organização:</b> Conciliar as responsabilidades de desenvolvimento com a função de Scrum Master exigiu planejamento, definição de prioridades e acompanhamento contínuo das atividades da equipe.</p>
- <p align="justify"><b>Aprendizado Contínuo:</b> O contato com tecnologias como MongoDB, processos de ETL, Inteligência Artificial e conceitos da LGPD ampliou minha visão sobre desenvolvimento de software e engenharia de dados, agregando conhecimentos importantes para minha formação profissional.</p>

## Conclusão

<p align="justify">Esta API representou um grande passo no meu desenvolvimento acadêmico e profissional. Trabalhar com tecnologias como MongoDB, ETL, Docker e Inteligência Artificial ampliou minha visão sobre como dados podem ser transformados em informações estratégicas para apoiar a tomada de decisões. Além do aprendizado técnico, assumir a responsabilidade de conduzir a equipe como Scrum Master tornou a experiência ainda mais desafiadora e enriquecedora, fortalecendo habilidades de liderança, comunicação e organização. Finalizo este projeto com a sensação de ter evoluído tanto tecnicamente quanto na forma de atuar em equipe e enfrentar desafios reais de desenvolvimento.</p>

</details>
