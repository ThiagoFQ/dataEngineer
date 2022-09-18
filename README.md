# dataEngineer
<h5>Um artigo referenciado sobre Banco de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados. Requisito final para conclusão do Bootcamp Database Experience.</h5>
<p align="center">
<img src="https://user-images.githubusercontent.com/112325834/190880658-bd773ff8-62a8-4f88-9ced-37d9c8b0f3b2.jpg"
</p>

## O Custo do Papel

Com o avanço e o crescimento das novas tecnologias, deixamos de armazenar informações no papel para um armazenamento digital de dados. O ponto de transição ocorreu em 1996, quando o armazenamento digital se tornou mais econômico do que armazenar informações no papel <b>[1]</b>.</p>
Esse processo do crescimento da informação digital tornou-se inseparável dos aspectos de nossas vidas e da sociedade. Como exemplo, a cada dia produzimos mais de 500 milhões de tweets <b>[2]</b>, 333 bilhões de e-mails <b>[3]</b>, 4 milhões de gigabytes de dados do Facebook <b>[4]</b>, 65 bilhões de mensagens do WhatsApp <b>[5]</b> e 720.000 horas de novos conteúdos adicionados no Youtube diariamente <b>[6]</b>, para mencionar apenas essas 4 empresas.</p>
</p>

## Engenheiro de Dados

</p>
Com tudo isso em mente, fica fácil perceber a alta demanda do mercado pelo profissional que, entre outras funções, consegue transformar os dados em um formato útil para análise e a tomada de decisão. Esses profissionais são conhecidos como Engenheiros de Dados que, segundo a Dataquest, classificam-se em 3 categorias <b>[7]</b>:</p>
<b>• Generalista:</b> trabalham para pequenas equipes e/ou empresas e desempenham funções “focadas em dados”. É a melhor forma para o cientista de dados realizar uma transição de carreira para a engenharia de dados.</p>
<b>• Centrado em pipeline:</b> trabalham em empresas de médio porte e possuem o suporte de cientistas de dados. Esse profissional precisa de conhecimento profundo em sistemas distribuídos e ciência da computação.</p>
<b>• Centrado em banco de dados:</b> trabalham em organizações maiores, onde se torna imprescindível o gerenciamento do fluxo de dados. O total domínio de banco de dados relacionais e não relacionais é a regra por aqui.</p>

## Banco de Dados

Dito isso, é possível inferir que a utilização de banco de dados pelos engenheiros de dados é algo fundamental. Umas das definições de banco de dados é: um conjunto de dados estruturados ou informações armazenadas em um sistema de computador, de tal modo que um programa de computador ou uma pessoa possa usar uma linguagem de máquina para buscar e recuperar essas informações <b>(Roman Čerešňák, 2019)</b>.</p>
O programa de computador usado para gerenciar e consultar dados é conhecido como Sistema de Gerenciamento de Banco de Dados (SGBD). As primeiras bases de dados relacionais, <i>Structured Query Language</i> (SQL), ficaram dominantes na década de 1980, enquanto os bancos de dados não relacionais, <i>Not Only Structured Query Language</i> (NoSQL) se tornaram populares nos anos 2000.</p>

## Principais diferenças entre SQL e NoSQL

A diferença mais significativa entre os dois conceitos é que o banco de dados SQL é relacional e possui <i>foreign Keys</i>, diferente do NoSQL que não define relacionamentos. A tabela a seguir ajuda a visualizar algumas dessas diferenças.</p>

<i>Tabela — Diferença entre banco de dados SQL e NoSQL</i></p>
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
      <td>Documentos, <i>key value</i></td>
    </tr>
    <tr>
      <td>Organização de dados</td>
      <td>Um <i>scheme</i> predefinido</td>
      <td><i>Scheme</i> dinâmico</td>
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
      <td><i>Foreign Keys</i></td>
      <td>Documentos aninhados</td>
    </tr>
    <tr>
      <td>Segurança</td>
      <td>Transações, consistência, isolamento</td>
      <td>Não existe</td>
    </tr>
  </tbody>
</table>	
</p>
De forma superficial, o SQL parece superar os benefícios do NoSQL, mas isso não é uma verdade inquestionável. Pois apesar do NoSQL não oferecer nenhum recurso de segurança para nós, ele lê e grava dados, sendo utilizado em aplicativos de BigData, nos quais esperam-se altíssimos volumes de dados, terabytes, por exemplo.</p>
O NoSQL também é usado quando não conhecemos antecipadamente os esquemas do banco de dados que se vai trabalhar, apesar de ter desvantagem por não suportar processamento transacional <b>(Mehmood et al, 2017)</b>.</p>

Torna-se imprescindível para o engenheiro de dados, o conhecimento e o domínio na utilização e manipulação de dados em banco de dados relacionais e não relacionais. Pois apenas assim será possível evoluir na carreira e se destacar na área de atuação.</p>

### Referências

<b>[1]</b> The Conversation / Melvin M. Vopson (17/09/2022): The world’s data explained: how much we’re producing and where it’s all stored.</p>
<b>[2]</b> Visual Capitalist / Racounter (17/09/2022): A Day In Data.</p>
<b>[3]</b> Statista (17/09/2022): Number of sent and received e-mails per day worldwide from 2017 to 2025.</p>
<b>[4]</b> Kinsta / Maddy Osman (16/09/2022): Wild and Interesting Facebook Statistics and Facts (2022).</p>
<b>[5]</b> CNET / Abrar Al-Heeti (16/09/2022): WhatsApp: 65B messages sent each day, and more than 2B minutes of calls.</p>
<b>[6]</b> Statista (17/09/2022): Hours of video uploaded to YouTube every minute as of February 2020.</p>
<b>[7]</b> Dataquest / Vik Paruchuri (17/09/2022): What is a Data Engineer?</p>
Roman Čerešňák, Michal Kvet, Comparison of query performance in relational a non-relation databases, Transportation Research Procedia, Volume 40, 2019, Pages 170-177.</p>
Mehmood, N., Culmone, R. and Mostarda, L. (2017). Modeling temporal aspects of sensor data for MongoDB NoSql database. Journal of Big Data, 4.</p>

![SQL](https://img.shields.io/badge/-SQL-green)
![NoSQL](https://img.shields.io/badge/-NoSQL-brightgreen)


