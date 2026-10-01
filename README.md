<h1 align="center">Ezio Chifunga</h1>

<p align="center">
  <strong>Full Stack Developer</strong> · Saúde digital, engenharia de dados e sistemas acessíveis<br>
  Rio de Janeiro, Brasil
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ezio-chifunga/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="http://lattes.cnpq.br/9796530701066676"><img src="https://img.shields.io/badge/Lattes-0A66A6?style=flat-square&logo=academia&logoColor=white" alt="Lattes"></a>
  <a href="https://orcid.org/0009-0007-8951-7645"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="mailto:eziochifunga.dev@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://medium.com/@eziochifunga"><img src="https://img.shields.io/badge/Medium-000000?style=flat-square&logo=medium&logoColor=white" alt="Medium"></a>
  <a href="https://www.behance.net/eziochifunga"><img src="https://img.shields.io/badge/Behance-1769FF?style=flat-square&logo=behance&logoColor=white" alt="Behance"></a>
</p>

---

## Sobre

Experiência no desenvolvimento de sistemas, especialmente nas áreas de saúde e gestão de dados. Atuo em todo o ciclo de desenvolvimento, do levantamento de requisitos com usuários à definição da arquitetura e implementação das soluções, criação de modelos visuais com atenção à qualidade, integridade e confiabilidade das informações.

Projetos de nutrição, direito processual, varejo e vigilância alimentar. Sou graduando em Análise e Desenvolvimento de Sistemas pela FAETERJ-Rio, com formação técnica em Eletrônica e conhecimentos em design de interfaces.

---

## No que estou trabalhando

### Nutra | Nutraentes - Multiplataforma de nutrição
Ecossistema concebido, arquitetado e implementado integralmente por mim. Reúne aplicativo para o público geral e outro para publico infantil distribuído via Google Play e plataforma de gestão de consultório para profissionais de nutrição.

- Arquitetura distribuída: serviços em Node.js e Go, apps em Flutter, workspace em Angular, base em PostgreSQL migrada de Firestore.
- Camada de RAG sobre base estruturada de regras nutricionais, com busca vetorial em Qdrant.
- Engine de sugestão que entrega caminhos possíveis ao profissionalm assim a decisão clínica permanece com o nutricionista.

`Go` `Python` `Node.js` `Flutter` `Angular` `PostgreSQL` `Qdrant`

**[→ nutraentes.com.br](https://nutraentes.com.br/)**

### SIDIAT - Insegurança alimentar em recorte intraurbano
Trabalho de conclusão de curso. Sete bases públicas brasileiras reunidas em um único banco PostgreSQL para leitura territorial de insegurança alimentar no município do Rio de Janeiro.

- Sete pipelines de coleta em Python: data.rio/IPP, PNAD Contínua/SIDRA, DIEESE, IPCA/INPC, CONAB-PROHORT, SISVAN e IBGE. Usando carga idempotente e manifesto de procedência por camada.
- Oito schemas com escopos geográficos incompatíveis entre si (bairro, setor censitário, município, região metropolitana, UF, entreposto de atacado), com as regras de cruzamento documentadas para impedir agregação silenciosamente errada.
- Aplicação em Next.js com doze painéis públicos e área de trabalho autenticada, formulário domiciliar com roteiro recalculado a cada resposta e regras de integridade aplicadas no servidor.

`Python` `PostgreSQL` `Next.js` `TypeScript` `GeoJSON`

**[→ sidiat.com.br](https://sidiat.vercel.app/)**

### AuditaData-Health - Privacidade e equidade medidas juntas
Middleware que recebe microdados do DATASUS e devolve datasets pseudonimizados, agregados sob privacidade diferencial com orçamento de ε contabilizado, e relatório de auditoria de equidade e proveniência.

- Arquitetura em sete camadas desacopladas, com contrato entre módulos em Parquet acompanhado de manifesto (hash do input, versão do código, parâmetros, timestamp).
- Pseudonimização multinível com cofre de chaves, verificação de k-anonimato e API REST por perfil de consumidor.
- Auditoria de fairness por raça, sexo e município, com teste de permutação, model card e datasheet gerados automaticamente.
- Invariantes de privacidade implementadas como testes que quebram o build.

> O ruído que protege o indivíduo é o mesmo que pode apagar a desigualdade do grupo.

`Python 3.11` `uv` `Docker` `PySUS` `Parquet` `W3C PROV`

**[→ Repositório](https://github.com/EzioChifunga/AuditaData-Health)**

---

## Stack

**Linguagens**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Front-end e mobile**

![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)

**Back-end e dados**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Design**

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Adobe XD](https://img.shields.io/badge/Adobe_XD-FF61F6?style=flat-square&logo=adobexd&logoColor=white)
![Photoshop](https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square&logo=adobephotoshop&logoColor=white)

---

## Repositórios públicos

| Projeto | O que é | Stack |
|---|---|---|
| **[AuditaData-Health](https://github.com/EzioChifunga/AuditaData-Health)** | Middleware de pseudonimização e auditoria de equidade para bases do SUS | Python |
| **[color-blind-assistive-module](https://github.com/EzioChifunga/color-blind-assistive-module)** | Módulo assistivo para daltonismo e discromatopsias, derivado da iniciação científica no INT | — |
| **[study-organizer](https://github.com/EzioChifunga/study-organizer)** | Registro de sessões de estudo sem banco de dados: cada sessão vira nota Markdown com YAML frontmatter em cofre do Obsidian | Java · JavaFX |
| **[Corujinha](https://github.com/EzioChifunga/Corujinha)** | Sistema de gerenciamento de bibliotecas acadêmicas para acesso e inventário de acervo | Dart · Flutter |
| **[Spring-Cloud-Boot-Confluent-Kafka](https://github.com/EzioChifunga/Spring-Cloud---Boot-Confluent-Kafka)** | Estudo de mensageria distribuída com Spring Cloud e Kafka | Java |
| **[precat-rio-radar](https://github.com/EzioChifunga/precat-rio-radar)** | Radar de precatórios | TypeScript |
| **[water-falls-visual](https://github.com/EzioChifunga/water-falls-visual)** | Camada de visualização do projeto Water Falls | TypeScript |
| **[portfolio-artistico](https://github.com/EzioChifunga/portfolio-artistico)** | Portfólio de Pinturas e Desenhos | TypeScript |

---

## Como eu trabalho

**Converso com quem vai usar.** Nos sistemas que desenvolvi, procuro entender o problema diretamente com as pessoas envolvidas antes de definir uma solução. No Nutra, conversei com nutricionistas, psicólogos, professores, diretores de escolas e clínicas e pais de crianças atípicas. No Horto e no Comjuntos, trabalhei ouvindo alunos, professores e responsáveis.

**Uso os dados para entender o problema, não só para preencher tabelas.** Quando diferentes bases apresentam valores diferentes para o mesmo alimento, por exemplo, não considero automaticamente que uma delas está certa. Comparo as fontes, avalio a qualidade dos dados e registro as incertezas. Esse cuidado também está presente na documentação do escopo geográfico do SIDIAT.

**Penso em acessibilidade desde o início.** Comecei a estudar o tema em 2023, inicialmente com foco em interfaces para pessoas com daltonismo e baixa visão. Mais recentemente, retomei essa pesquisa para investigar os problemas de acessibilidade que podem surgir quando interfaces geradas por IA chegam à produção sem uma revisão adequada.


---

<p align="center">

  <img src="https://github-readme-stats.vercel.app/api?username=EzioChifunga&show_icons=true&hide_border=true&count_private=true&theme=transparent" alt="Estatísticas do GitHub" height="150">

  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EzioChifunga&layout=compact&hide_border=true&theme=transparent" alt="Linguagens mais usadas" height="150">

</p>

<p align="center">
  <em>Aberto a colaboração em saúde digital, dados públicos, acessibilidade e criação de identidade.</em><br>
  <a href="mailto:eziochifunga.dev@gmail.com">eziochifunga.dev@gmail.com</a>
</p>
