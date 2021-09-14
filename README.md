# BlogPessoal

**Atividade CRUD Back-end blog-pessoal**

O back-end deve possuir 3 camadas:

1- Camada de modelo com o nome de Postagem com os seus atributos apropriados nos vídeo.

2- Uma camada de repositório com o nome PostagemRepository (com capacidade de se comunicar com o banco de dados mysql)

3- Uma camada de Controller com o nome de PostagemController Com 6 endpoints:

--> findAllPostagem = um endPoint com a capacidade de trazer todas as Postagem.

--> findByIDPostagem = um endPoint com uma função de trazer uma única Postagem por id.

--> postPostagem = um endPoint com a função de gravar uma nova Postagem no banco de dados.

--> putPostagem = um endPoint com função de atualizar dados de uma Postagem.

--> deletePostagem = um endPoint com uma função de apagar uma Postagem do banco de dados.

--> Crie o método getByTitulo sem repositório.

--> Crie um método getByTitulo no controller = um endPoint com uma função de trazer uma única Postagem por Título.

**Parte 1 criação da tabela Tema.**

1- Camada de model  com o nome de Tema com os atributos apresentados na video-aula:

2- Uma camada de repository com o nome TemaRepository (com a capacidade de se comunicar com o banco de dados mysql).
3- Uma camada de Controller com o nome de TemaController Com 5 endpoints:

--> findAllTema = um endPoint com a capacidade de trazer todas os temas.

--> findByIDTema = um endPoint com a função de trazer uma unico tema por id.

--> findByDescricaoPostagem = um endPoint com a função de trazer um unico tema por Descricao.

--> postTema = um endPoint com a função de gravar um novo tema no banco de dados.

--> putTema = um endPoint com a função de atualizar dados de um tema.

--> deleteTema = um endPoint com a função de apagar um tema do banco de dados).

**Parte 2 relacionamento com a tabela Postagem.**

4- Camada de model  com o nome de Postagem com os atributos apresentados na video-aula:

5- Crie um relacionamento de um para muitos/muitos para um, para essas models   (um tema para muitas postagem e muitas postagem para um tema) 

IMPORTANTE: Não esqueça de colocar as anotações corretamente para o relacionamento e inibir recursividade através da anotação @JsonIgnoreProperties.

6- Uma camada de repository com o nome PostagemRepository (com a capacidade de se comunicar com o banco de dados mysql).

7- Uma camada de Controller com o nome de PostagemController Com 5 endpoints:

--> findAllPostagem = um endPoint com a capacidade de trazer todas as turmas.

--> findByIDPostagem = um endPoint com a função de trazer uma unica turma por id.

--> findByDescricaoTitulo = um endPoint com a função de trazer uma unica postagem por Titulo.

--> postPostagem = um endPoint com a função de gravar uma nova turma no banco de dados.

--> putPostagem = um endPoint com a função de atualizar dados de uma turma.

--> deletePostagem = um endPoint com a função de apagar uma turma do banco de dados.

**Parte 3 camadas de segurança.**
- Implemente a segurança em modelo basic no back-end de blogPessoal do projeto guia do vídeo.

**Parte 4 Testes no JUnit.**

**Parte 5 Versão final do BackEnd.**

**Parte 6 realizando o deploy e implementando swagger na minha aplicação spring**

- Realize o deploy através do Heroku e implementar o swagger no projeto do blog
pessoal.
