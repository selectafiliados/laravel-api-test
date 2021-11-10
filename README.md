# Teste prático - Laravel

Esse teste prático visa avaliar os conhecimentos do candidato a vaga de programador PHP Laravel.

# Objetivos
  - Conhecer um pouco de suas habilidades em:
    - Laravel;
    - Entendimento e análise dos requisitos;
    - Capacidade de inovar;
    - Determinação na busca de soluções;
    - Responsabilidade na tomada de decisões.

# Fique tranquilo
  - Todo e qualquer código desenvolvido nesse teste não será utilizado em quaisquer outros softwares nem comercializados pela Select.
  - O propósito deste teste é apenas avaliar o conhecimento em programaçao do candidato.
  - Lembrando sempre de aplicar boas práticas de SOLID, DDD, Clean Code ou quais quer outra que possa tornar o seu código mais amigável

# Vamos lá! A aplicação é...
Criem uma aplicação utilizando Laravel (API), Postgres e quaisquer outras tecnologias que julgar benéficas ao projeto.

##### Lembrando que deverá sempre pensar em API REST para este projeto.
Não necessita desenvolver os CRUDs.

- Criar um authenticação gerando token e refresh token;
- Criar uma rota protegida
- Criar uma rota para receber dados via REST POST, validando os seguintes campos (nome, email, identidade)
- Persistir os dados recebidos estes dados em um banco de dados Postgres utilizando boas práticas
- Após salvar os dados no banco de dados criar uma réplica destes dados no momento que é recebido enviando para um serviço de fila (RabbitMq), utilizar Jobs para envio dos dados
- Consumir este serviço de fila (RabbiotMQ) e gravar em uma tabela no banco de dados Postgres, utilizar Command para consumir estes dados
- Gravar um Log de toda operaçao em uma tabela do banco de dados

### Prazo de entrega 7 dias 

### Requisitos
- Usar Laravel (Última versão estável);
- Usar banco de dados Postgres;
- Usar o github ou bitbucket;
- Usar (RabbitMQ)
- Usar **Docker e Docker Compose** para iniciar o projeto em DEV
- No demais fique a vontade para utilizar todos os seus conhecimentos e técnicas possíveis.

### Para participar basta...
- Construir a aplicação solicitada;
- Enviar o link do projeto no github ou bitbucket para o e-mail: fabio.farias@selectafiliados.com.br

# Caso precise falar conosco
- Email: fabio.farias@selectafiliados.com.br
- Fone: [21] 99222-0009

Fique a vontade para entrar em contato conosco se você tenha alguma dúvida ou assim que terminar a aplicação.
