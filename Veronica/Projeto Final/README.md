
![Imagem local](./img/internet_mundo.jpg)




<font face="perpetua"><h1>Navegando pela Inclusão: Internet e Computadores no Brasil</h1></font>

<p>Nos últimos anos, especialmente durante e após a pandemia, o acesso à internet cresceu significativamente, assim como as oportunidades de emprego na área de tecnologia. Diante desse cenário, realizamos uma análise para evidenciar dados alarmantes sobre o impacto das vagas de emprego online no mundo, considerando que uma parte considerável da população ainda não possui acesso a computadores e internet em casa.</p>

<p>Os dados utilizados para alimentar nossa aplicação (atualmente em execução apenas localmente) foram extraídos de fontes como o <a href="https://www.ibge.gov.br/estatisticas/sociais/trabalho/17270-pnad-continua.html?edicao=38243&t=resultados" target="_blank">IBGE</a> e <a href="https://www.kaggle.com/datasets/sansuthi/gapminder-internet" target="_blank">Kaggle</a>, com base em informações coletadas nos anos de 2022 e 2023.</p>

<p>Esperamos que essa análise contribua para uma melhor compreensão do acesso à internet e suas oportunidades, sobretudo para empresas que buscam pessoas na área da tecnologia, ajudando a classe minoritária, obtendo um olhar mais humanizado sobre seu desempenho.</p>

<font face="perpetua"><h2>Com os dados em mãos procuramos extrair o máximo de informações e responder algumas das seguintes questões:</h2></font>

<ol>
    <li>Qual o indice de acesso a internet no Brasil comparado a outros países?</li>
    <li>Qual a média de acessos da população brasileira por estado da federação a internet?</li>
    <li>Qual a média de quantos computadores existem por domicilio em cada região do Brasil?</li>
</ol>

<font face="perpetua"><h2>Ferramentas Utilizadas</h2></font>

<p>Para realizar essa análise, utilizamos as seguintes ferramentas:</p>

<ul>
    <li><img align="center" alt="Pandas" height="25" width="35" src="https://logowik.com/content/uploads/images/panda3013.logowik.com.webp">Pandas: Biblioteca Python amplamente utilizada para análise de dados, que nos permite ler e manipular arquivos XLSX (Excel), além de transformar e limpar os dados conforme necessário.</li>
    <li><img align="center" alt="Colab" height="30" width="30" src="https://i.namu.wiki/i/zKS7LsOc2A4ZZR64XnAm8S88HbszoXQPH_T7CY3KFwfwJtemXQwc4Nu3tx5GavmyG-wmgcKs_PfqYbY8xg3iow.webp"> Google Colab: Plataforma para criação de notebooks, facilitando a análise colaborativa dos dados.</li>
    <li><img align="center" alt="Tableau" height="20" width="25" src="https://wallpapers.com/images/hd/tableau-software-logo-design-th525w75z77ccxc9.png">  Tableau: Utilizado para criar dashboards e gráficos apresentados na análise.</li>
</ul>

 <p>O Pandas é uma biblioteca do Python muito utilizada para análise de dados. Com ele podemos ler nossos dados, que é um arquivo XLSX (Excel), e começar a manipular, transformar e limpar, caso necessário. 

 Em nosso arquivo temos as seguintes colunas: brasil e Grande Região, Existência de microcomputador ou tablet no domicílio, Ano x Situação do domicílio, etc
 

<font face="perpetua"><h2>Estrutura dos Dados</h2></font>

Em nosso arquivo, temos as seguintes colunas:
<ul>
    <li>Brasil e Grande Região </li>
    <li>Existência de microcomputador ou tablet no domicílio</li>
    <li>Ano e Situação do domicílio</li>
</ul>

 
 Com esses dados devidamente transformados e limpos foi criado o _dashboard_ (painel onde os gráficos são visualizados).</p>

<font face="perpetua"><h2>Foram gerados os seguintes gráficos:</h2></font>
 
 <ul>
    <li>Gráfico de barras com todos os países que possuem acesso a internet.</li>
    <li>Gráfico de círculo mostrando o acesso a internet por continente.</li>
    <li>Gráfico de pizza sobre a proporção de domicílios com e sem internet no Brasil.</li>
    <li>Dashboard onde pode-se selecionar um estado, visualizar os gráficos e seus rótulos mencionados acima, como mostram as imagens abaixo.</li>
 </ul>

<img src="/img/Captura de tela 2024-10-12 124226.png" alt="dashboard1" width="300" hspace="50">  <img src="/img/Captura de tela 2024-10-12 125037.png" alt="dashboard2" width="300">



<font face="perpetua"><h2>🌟Algumas análises de acordo com o resultado encontrado:</h2></font>

<ul>
    <li>Em 2022, apenas 63,13% da população mundial usava a internet. Isso significa que apenas cerca de dois terços da população global está conectada à rede mundial de computadores. Embora possa parecer um número alto, ainda há uma grande parte da população que permanece offline, destacando disparidades no acesso à tecnologia e à informação e aprofundando o abismo social, sobretudo com o advento da inteligencia artificial.</li> <br>
    <li>A média de acesso à internet no Brasil era de apenas 40,65%. Isso significa que menos da metade da população brasileira estava conectada à rede, destacando uma significativa desigualdade no acesso à tecnologia e à informação em comparação com países com maior percentual de usuários online.
    Pensando nisso reunimos dados de quantos computadores e tablets existem por domicilio no Brasil.</li><br>
    <li>Sobre a média de computadores nas diferentes regiões também revela -se desigualdades. A região Sudeste mais uma vez se destaca, com uma média de 14.866 computadores, evidenciando uma maior disseminação de tecnologia. O Nordeste aparece em segundo lugar, com uma média de 7.775,83 computadores, seguido pelo Sul com 5.046,33 computadores.<br>
    Esses números ilustram as diferenças no acesso à tecnologia entre as regiões, com o Sudeste sendo a mais privilegiada em termos de disponibilidade de computadores.</li><br>
    <li>Em 2023, as médias de computadores nas diferentes regiões do Brasil mostraram apenas pequenas alterações em relação ao ano anterior. Esse cenário indica que, embora tenha havido algumas mudanças, as desigualdades no acesso à tecnologia entre as regiões brasileiras persistem.</li><br>
    <li>A análise mostrou que muitas regiões do Brasil têm um número significativo de domicílios sem computador ou tablet. Isso evidencia desigualdades tecnológicas, especialmente em termos de impacto no desenvolvimento educacional e profissional. O que nos levou a questionar quem são as pessoas que estão efetivamente conseguindo trabalho na área de tecnologia.</li>
</ul>


<font face="courrier"><h3>Autoras do Projeto:</h3></font>

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/101891674?v=4" width=115><br>](https://github.com/TmTeixeira) <a href="https://www.linkedin.com/in/analistatammyteixeira/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>  |  [<img loading="lazy" src="https://avatars.githubusercontent.com/u/171205733?v=4" width=115><br>](https://github.com/veronica-toledo-bm) <a href="https://www.linkedin.com/in/veronica-toledo-bm/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
| :---: | :---: | 

