# Dashboard de Variação de Faturamento Mensal

## Descrição do Projeto
<p align="left">O projeto consiste em um painel de calcula a variação mensal de faturamento de uma empresa de Telemedicina (dados fictícios). O painel consiste em uma seção de dados gerais do faturamento mensal e dois gráficos: variação por categoria e variação por produtos. Na parte de filtros, é possível filtrar o ano e mês de análise e o painel calculará a variação do mês selecionado imediatamente com o mês anterior.</p>

<h2>Tabela de Conteúdos</h2>
<ul>
  <li><a href="#status-do-projeto">Status do Projeto</a></li>
   <li><a href="#descricao-dos-scripts">Descrição dos Scripts</a></li>
  <li><a href="#features">Features</a></li>
  <li><a href="#deploy">Deploy</a></li>
  <li><a href="#tecnologias-utilizadas">Tecnologias Utilizadas</a></li>
  <li><a href="#autor">Autor</a></li>
</ul>

## Status do Projeto
<h4 align="left"> 🚧 Em construção... 🚧 </h4> <p>O projeto ainda está em desenvolvimento. Algumas funcionalidades estão implementadas, enquanto outras estão em progresso ou planejadas para futuras versões.</p>

## Descrição dos Scripts
<ul>
  <li>
    <strong>eda_matplotlib_pandas.ipynb</strong> - Análise Exploratória dos Dados (EDA) utilizando as bibliotecas <code>matplotlib</code> e <code>pandas</code>. A ideia geral deste notebook foi pensar em um formato interessante para os gráficos do dashboard.
  </li>
  <li>
    <strong>telemedicina_bd_conexao.ipynb</strong> - Notebook dedicado à conexão e manipulação do banco de dados.
  </li>
  <li>
    <strong>str.py</strong> - Script em Python para construir o dashboard com o <code>streamlit</code>.
  </li>
</ul>

## Features
<ul> <li>✅ Painel de Faturamento Mensal com visualização de dados gerais</li> <li>✅ Gráfico de Variação de Faturamento por Categoria</li> <li>✅ Gráfico de Variação de Faturamento por Produto</li> <li>❌ Filtros avançados para comparação de múltiplos períodos</li> <li>❌ Exportação de relatórios em PDF ou Excel</li> </ul>

## Deploy

<p><i>Em breve</i>: O deploy do projeto está em fase de planejamento. Detalhes de acesso e link para o painel online serão disponibilizados assim que concluídos.</p>

## Tecnologias Utilizadas

<ul> <li><b>Python</b>: para manipulação de dados e geração dos cálculos de variação mensal</li> <li><b>Streamlit</b>: para criação do painel interativo e visualização dos gráficos</li> <li><b>Pandas</b>: para análise e transformação de dados.</li> <li><b>Matplotlib</b>: para geração de gráficos de variação de faturamento.</li> <li><b>SQLAlchemy</b>: para conexão com o banco de dados onde os dados de faturamento estão armazenados.</li> </ul>

## Autor

<p>Desenvolvido por <b>Rodrigo Bessa</b>. Entre em contato:</p> <ul> <li><a href="https://linkedin.com/in/rodrigo-bessa">LinkedIn</a></li> <li><a href="mailto:reisrodri@gmail.com">Email</a></li> </ul>
