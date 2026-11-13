# 🎓 Database Application

**Um catálogo de vídeos para explorar tecnologias de bancos de dados, integração e análise de dados.**

Este projeto reúne apresentações relacionadas à disciplina **Database Application**, sob a orientação do **Professor Alex Souza**. A proposta é aproximar os conceitos das ferramentas: conhecer diferentes tecnologias, entender suas aplicações e encontrar demonstrações para continuar estudando.

O catálogo contém **33 vídeos cadastrados**, com autoria, descrição, imagem e tags. A página permite pesquisar os conteúdos e abrir as apresentações no YouTube.

[**▶ Acessar o catálogo**](https://aasouzaconsult.github.io/database_application/) · [**📄 Explorar o código**](index.html) · [**👤 Portfólio de Alex Souza**](https://github.com/aasouzaconsult/portfolio-dados)

## O que você encontra

| Área de estudo | Exemplos presentes no catálogo |
| --- | --- |
| **Bancos de dados e serviços de dados** | CockroachDB, Supabase, IBM Db2, Firebase e ArangoDB. |
| **NoSQL, grafos e busca** | Neo4j, Couchbase, Redis, Cassandra, BaseX e Elasticsearch. |
| **Plataformas e consultas analíticas** | BigQuery, Databricks, Snowflake, PrestoDB, DuckDB e Vertica. |
| **Integração e processamento de dados** | Talend, Pentaho, Apache NiFi, Apache Kafka e Apache Hop. |
| **Aplicações e conectividade** | APIs, Python com PostgreSQL, PHP com MySQL e Node.js. |
| **Visualização e exploração** | Google Looker, Tableau e análise exploratória com Databricks. |
| **Conceitos e outros temas** | Data Warehouse, bancos vetoriais, séries temporais e SQL Server Profiler. |

Os vídeos são introdutórios e demonstrativos. Cada apresentação possui seu próprio recorte; o catálogo pode ser usado como apoio às aulas e ponto de partida para aprofundamento.

## Como usar o catálogo

1. Abra a página e explore os cartões de vídeos.
2. Digite um termo no campo de pesquisa, como `SQL`, `ETL`, `Python` ou o nome de uma tecnologia.
3. Clique na imagem do vídeo para abrir a apresentação no YouTube em uma nova aba.
4. Apague o texto da busca para voltar a visualizar todo o catálogo.

A busca considera **título, descrição, autor e tags**, sem diferenciar maiúsculas de minúsculas. Quando você digita vários termos, todos precisam aparecer nas informações do vídeo. As tags são exibidas nos cartões; o filtro é realizado pelo campo de pesquisa.

## Funcionalidades

- **Busca enquanto você digita**, sem recarregar a página.
- **Cartões com créditos**, descrição e identificação dos temas.
- **Layout responsivo**, com adaptação da grade para telas menores.
- **Acesso direto ao YouTube** a partir das imagens.
- **Mensagem de busca sem resultados** e imagem alternativa quando uma miniatura não carrega.
- **Catálogo mantido em um único arquivo**, facilitando a atualização dos conteúdos.

## Tecnologias e estrutura

A página utiliza **HTML, CSS e JavaScript**, sem frameworks ou dependências externas de interface. O catálogo está declarado no próprio código e é filtrado no navegador; não é necessário configurar banco de dados ou backend para executar a página.

```text
database_application/
├── index.html    # Página, estilos, catálogo de vídeos e lógica de busca
├── img/          # Imagens utilizadas nos cartões
└── README.md     # Apresentação e orientações do projeto
```

| Parte | Responsabilidade |
| --- | --- |
| **HTML** | Estrutura do cabeçalho, pesquisa, grade de vídeos e rodapé. |
| **CSS** | Cores, cartões, animações e adaptação para diferentes telas. |
| **JavaScript** | Dados dos vídeos, renderização, pesquisa e abertura dos links. |

## Como executar localmente

### Opção 1 — abrir no navegador

Clone o repositório:

```bash
git clone https://github.com/aasouzaconsult/database_application.git
cd database_application
```

Abra o arquivo `index.html` no navegador, mantendo a pasta `img/` ao lado dele. Também é possível baixar o repositório em **Code → Download ZIP** e extrair os arquivos.

### Opção 2 — usar um servidor local

Se tiver Python instalado, execute na pasta do projeto:

```bash
python -m http.server 8000
```

Depois, acesse [http://localhost:8000](http://localhost:8000).

A página e a pesquisa usam os arquivos locais. Para assistir às apresentações no YouTube, é necessário acesso à internet.

## Catálogo de apresentações

Os títulos e créditos abaixo correspondem aos vídeos cadastrados em `index.html`.

| Apresentação | Autoria |
| --- | --- |
| [Google BigQuery](https://www.youtube.com/watch?v=f9OEhaD54d4) | Jose Ernane Feijao Junior |
| [CockroachDB](https://www.youtube.com/watch?v=3V645c1Ellg) | João Esdras |
| [Supabase](https://www.youtube.com/watch?v=TbBknriWZuE) | Marcos Bandeira Saraiva |
| [Databricks](https://www.youtube.com/watch?v=OSTtAMJebv4) | Leone Félix |
| [Data Warehouse](https://www.youtube.com/watch?v=hU64rUQB7Qc) | Jorge Airton |
| [Python + PostgreSQL](https://www.youtube.com/watch?v=BP-l4y5eT88) | Paulo Cesar Paiva da Mota |
| [Talend](https://www.youtube.com/watch?v=iTtz--HEetY) | Ryane Ferreira Feitosa |
| [Neo4J](https://www.youtube.com/watch?v=8w5L9UHXG80) | Amanda da Costa Felix |
| [Snowflake](https://youtu.be/bc9d1V-6Qg4) | Levi Nogueira |
| [API´s](https://youtu.be/n6JPPVSt568) | Josué Araújo |
| [Pentaho](https://youtu.be/5PjEatX29Ag) | Samyla Sotero |
| [Apache Nifi + MongoDB](https://youtu.be/5uIDaB3O-4s) | Dhenzel Lima |
| [Elasticsearch](https://youtu.be/hjhaE-Y2n2Y) | Antonio Yan |
| [PrestoDB](https://youtu.be/830QTGXeDVk) | João Victor |
| [DuckDB](https://www.youtube.com/watch?v=S4OdOU-tyOs) | João Prudêncio |
| [Google Looker](https://www.youtube.com/watch?v=TiY5QPcbmf8) | Lucas Feitosa |
| [Couchbase](https://youtu.be/uAUZYrS7LtQ) | Nicolle Luisa |
| [Firebase](https://www.youtube.com/watch?v=UxZLqDm_QNc) | Anthony Silva |
| [SQL Server Profiler](https://www.youtube.com/watch?v=Xi8wXgRhtMI) | Davi Marques |
| [Redis](https://www.youtube.com/watch?v=jZX4X52pjBo) | Luana Oliveira |
| [Apache Kafka](https://www.youtube.com/watch?v=Mb3XhTAbcVs) | Gustavo Schiavo |
| [Apache Cassandra](https://www.youtube.com/watch?v=at3RWYD97bE) | Marina Santos |
| [BaseX](https://www.youtube.com/watch?v=GaCSNG79aRw) | Vinicius Mendes |
| [Séries Temporáis](https://www.youtube.com/watch?v=6BxUOpuxU80) | Gabriel Lopes |
| [IBM DB2](https://www.youtube.com/watch?v=xrlVxKtMnvs) | Caio Faheina |
| [ArangoDB](https://www.youtube.com/watch?v=p2_tAE7aV3E) | Raimundo Nonato |
| [Banco Vetorial](https://www.youtube.com/watch?v=jmqbVy0Vs5A) | Ryan Gurgel |
| [Vertica (OpenText Analytics)](https://www.youtube.com/watch?v=3au-u-lyOYs) | Levi Bernardo |
| [Apache Hop](https://www.youtube.com/watch?v=Vkvrb4MFhDQ) | Iarley Alves |
| [Tableau](https://youtu.be/Qwco-_fsaXg?si=KdFNkQdGm1hISHJb) | Paulo Cesar Paiva da Mota |
| [PHP + MySQL](https://youtu.be/SbGHG-szYkk) | Raimundo Nonato |
| [Node js](https://youtu.be/dcY5_oY6-b4) | Lucas Feitosa |
| [AED com Databricks](https://www.youtube.com/watch?v=UYEfDd-UIgw) | Davi Marques |

## Como adicionar ou atualizar um vídeo

1. Adicione a miniatura à pasta `img/`.
2. Abra `index.html` e localize o array `videosData`.
3. Inclua um objeto com os dados da apresentação, seguindo o formato abaixo.
4. Salve o arquivo e confira a imagem, o link e a busca no navegador.

```javascript
{
    title: "Título da apresentação",
    author: "Nome de quem apresenta",
    description: "Resumo do conteúdo e da demonstração.",
    image: "img/nova-miniatura.jpg",
    youtubeUrl: "https://www.youtube.com/watch?v=ID_DO_VIDEO",
    tags: ["SQL", "Integração", "Prática"]
}
```

Separe os objetos por vírgulas e mantenha os nomes dos campos. Escolha tags que ajudem outras pessoas a encontrar o assunto e confira se o nome da imagem corresponde exatamente ao arquivo, incluindo maiúsculas e minúsculas.

A função `addVideo(videoData)` também está disponível no JavaScript para adicionar um item durante a execução. Essa inclusão fica apenas na memória da página; para manter o vídeo após recarregar, registre-o em `videosData`.

## Créditos e contato

Cada apresentação tem sua autoria identificada no catálogo. Os vídeos são acessados por links externos e permanecem hospedados no YouTube, sob responsabilidade dos respectivos canais.

**Professor Alex Souza**

[LinkedIn](https://www.linkedin.com/in/alex-souza/) · [Instagram](https://www.instagram.com/alexsouzamsc/) · [Blog técnico](https://medium.com/blog-do-zouza) · [X](https://x.com/alexsouza_sql) · [Portfólio](https://github.com/aasouzaconsult/portfolio-dados)
