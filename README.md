# dataEngineer
<h5>Um artigo referenciado sobre Banco de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados. Requisito final para conclusão do Bootcamp Database Experience.</h5>
<p align="center">
<img src="https://user-images.githubusercontent.com/112325834/190880658-bd773ff8-62a8-4f88-9ced-37d9c8b0f3b2.jpg"
</p>
</p>

## Introdução

</p>
Com o avanço e o crescimento das novas tecnologias, deixamos de armazenar informações no papel para um armazenamento digital de dados. O ponto de transição ocorreu em 1996, quando o armazenamento digital se tornou mais econômico do que armazenar informações no papel [1].</p>
Esse processo do crescimento da informação digital tornou-se inseparável dos aspectos de nossas vidas e da sociedade. Como exemplo, a cada dia produzimos mais de 500 milhões de tweets [2], 333 bilhões de e-mails [3], 4 milhões de gigabytes de dados do Facebook [4], 65 bilhões de mensagens do WhatsApp [5] e 720.000 horas de novos conteúdos adicionados no Youtube diariamente [6], para mencionar apenas essas 4 empresas.</p>
</p>

## Engenheiro de Dados

</p>
Com tudo isso em mente, fica fácil perceber a alta demanda do mercado pelo profissional que, entre outras funções, consegue transformar os dados em um formato útil para análise e a tomada de decisão. Esses profissionais são conhecidos como Engenheiros de Dados que, segundo a Dataquest, classificam-se em 3 categorias [7]:</p>
•	Generalista: trabalham para pequenas equipes e/ou empresas e desempenham funções “focadas em dados”. É a melhor forma para o cientista de dados realizar uma transição de carreira para a engenharia de dados.</p>
•	Centrado em pipeline: trabalham em empresas de médio porte e possuem o suporte de cientistas de dados. Esse profissional precisa de conhecimento profundo em sistemas distribuídos e ciência da computação.</p>
•	Centrado em banco de dados: trabalham em organizações maiores, onde se torna imprescindível o gerenciamento do fluxo de dados. O total domínio de banco de dados relacionais e não relacionais é a regra por aqui.</p>
</p>

## Banco de Dados

</p>
Dito isso, é possível inferir que a utilização de banco de dados pelos engenheiros de dados é algo fundamental. Umas das definições de banco de dados é: um conjunto de dados estruturados ou informações armazenadas em um sistema de computador, de tal modo que um programa de computador ou uma pessoa possa usar uma linguagem de máquina para buscar e recuperar essas informações (Roman Čerešňák, 2019).</p>
O programa de computador usado para gerenciar e consultar dados é conhecido como Sistema de Gerenciamento de Banco de Dados (SGBD). As primeiras bases de dados relacionais, Structured Query Language (SQL), ficaram dominantes na década de 1980, enquanto os bancos de dados não relacionais, Not Only Structured Query Language (NoSQL) se tornaram populares nos anos 2000.</p>
</p>

## Principais diferenças entre SQL e NoSQL

</p>
	A diferença mais significativa entre os dois conceitos é que o banco de dados SQL é relacional e possui foreign Keys, diferente do NoSQL que não define relacionamentos. A tabela a seguir ajuda a visualizar algumas dessas diferenças.</p>

<table>
  <thead>
    <th>Propriedade
    <th>SQL
    <th>NoSQL
  </thead>
  <tbody>
    <tr>
      <td>A forma de armazenar os dados</td>
      <td>Tabelas</td>
      <td>Documentos, key value</td>
    </tr>
    <tr>
      <td>Organização de dados</td>
      <td>Um scheme predefinido</td>
      <td>Scheme dinâmico</td>
    </tr>
    <tr>
      <td>Escalabilidade</td>
      <td>Vertical (maior ram, processador mais robusto)</td>
      <td>Horizontal (mais servidores, instâncias)</td>
    </tr>
    <tr>
      <td>Linguagem de consulta</td>
      <td>SQL padronizado</td>
      <td>Linguagem de consulta própria</td>
    </tr>
    <tr>
      <td>Relações de dados</td>
      <td>Foreign Keys</td>
      <td>Documentos aninhados</td>
    </tr>
    <tr>
      <td>Segurança</td>
      <td>Transações, consistência, isolamento</td>
      <td>Não existe</td>
Tabela — Diferença entre banco de dados SQL e NoSQL</p>

De forma superficial, o SQL parece superar os benefícios do NoSQL, mas isso não é uma verdade inquestionável. Pois apesar do NoSQL não oferecer nenhum recurso de segurança para nós, ele lê e grava dados, sendo utilizado em aplicativos de BigData, nos quais esperam-se altíssimos volumes de dados, terabytes, por exemplo.</p>
O NoSQL também é usado quando não conhecemos antecipadamente os esquemas do banco de dados que se vai trabalhar, apesar de ter desvantagem por não suportar processamento transacional (Mehmood et al, 2017).</p>
Torna-se imprescindível para o engenheiro de dados, o conhecimento e o domínio na utilização e manipulação de dados em banco de dados relacionais e não relacionais. Pois apenas assim, será possível evoluir na carreira e se destacar na área de atuação.</p>
</p>

### Referências

</p>
[1] The Conversation / Melvin M. Vopson (17/09/2022): The world’s data explained: how much we’re producing and where it’s all stored.</p>
[2] Visual Capitalist / Racounter (17/09/2022): A Day In Data.</p>
[3] Statista (17/09/2022): Number of sent and received e-mails per day worldwide from 2017 to 2025.</p>
[4] Kinsta / Maddy Osman (16/09/2022): Wild and Interesting Facebook Statistics and Facts (2022).</p>
[5] CNET / Abrar Al-Heeti (16/09/2022): WhatsApp: 65B messages sent each day, and more than 2B minutes of calls.</p>
[6] Statista (17/09/2022): Hours of video uploaded to YouTube every minute as of February 2020.</p>
[7] Dataquest / Vik Paruchuri (17/09/2022): What is a Data Engineer?</p>
Roman Čerešňák, Michal Kvet, Comparison of query performance in relational a non-relation databases, Transportation Research Procedia, Volume 40, 2019, Pages 170-177.</p>
Mehmood, N., Culmone, R. and Mostarda, L. (2017). Modeling temporal aspects of sensor data for MongoDB NoSql database. Journal of Big Data, 4.</p>




