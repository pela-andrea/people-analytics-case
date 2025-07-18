<h1>Case Técnico - RH | Análise e Visualização de Dados</h1>
<p>Este repositório contém a entrega completa do case técnico solicitado, com foco em análise de dados de Recursos Humanos. Foram seguidos os critérios de documentação, versionamento, análise e visualização de dados.</p>
<hr>

<h3> Sumário </h3>
<ul>
    <li> <a href='info'> Informações Gerais </a>
        <ul>
            <li> <a href='#objetivo'> Objetivo </a> </li>
            <li> <a href='#instrucoes'> Instruções </a> </li>
</ul>
</ul>
<hr>
<ul>
    <li> 
        <a href='dev'>Desenvolvimento </a>
        <ul>
            <li> <a href='#estrutura'> Estrutura Repositório </a> </li>
            <li> <a href='#vers'> Versionamento </a> </li>
            <li> <a href='#execucao'> Execução</a> </li>
            <li> <a href='#execucao'> Tools</a> </li>
        </ul>
</ul>
<ul>
    <li> 
        <a href='dev'>Análise</a>
        <ul>
            <li> <a href='#estrutura'> Estrutura Repositório </a> </li>
            <li> <a href='#vers'> Versionamento </a> </li>
            <li> <a href='#execucao'> Execução</a> </li>
            <li> <a href='#execucao'> Tools</a> </li>
        </ul>
</ul>

<hr>

<br>

<h2 id='info'> Informações Gerais  </h2>
<p>
    Aqui estão as informações básicas para compreender melhor o escopo deste projeto.
</p>

<hr>
<h3 id='objetivo'> Contexto </h3>
<p> 
Este case visa avaliar suas habilidades técnicas com foco em quatro aspectos:
</p>
    <li> 
    <a href=''> Documentação </a>: balblalba
    </li>
    <li> 
    <a href=''> Versionamento de Código </a>: balblalba
    </li>
    <li>
    <a href=''> Análise de Dados </a>: scrips
    </li>
    <li>
    <a href='https://app.powerbi.com/view?r=eyJrIjoiOWM2MzI1YmMtZmQ4Ny00NGY4LWIwOGQtMzM4ZDI4ZTY1MDIzIiwidCI6ImNlMzdmYjc4LWE2OTUtNDNjOS05ZTkwLTFmNzkzYWIwOTQ3MyJ9'> Storytelling/ Visualização </a>: Link para o dashboard
    </li>
<hr>
<p>
    Com base nesses aspectos, você precisará criar um repositório público no Github contendo todos os arquivos que serão necessários para a realização. Nesse repositório, é imprescindível que contenha o .readme com a estrutura dos arquivos. 
</p>
<p>
    Além disso, queremos analisar sua capacidade e pensamento estrutural, portanto comente todas as suas alterações em suas pushs dentro desse repositório. 
Após criar seu repositório, você deverá pegar a base de dados que estamos disponibilizando em anexo neste e-mail, retrato da base abaixo:
</p>
<p>
    Para fins informativos, esta base não tem dados reais, está em formato .CSV e com informações sobre áreas de Recursos Humanos (ponto, folha, admissão, recrutamento e treinamento). 
</p>
<p>
    O que você deve entregar obrigatoriamente?
</p>
<ul>
    <li>    
        1)	Estude a base e crie um glossário de cada coluna, identificando os tipos de dados, tratando erros e normalizando a tabela. Salve esse arquivo no seu repositório com o nome de “glossário”. 
    </li>
    <li>    
        2)	Após ter o glossário, divida a base em várias tabelas com alguma classificação padrão que você julgue necessário e/ou pertinente. Salve os arquivos dessas transformações nesse padrão: “tabela_nome”. Fique à vontade para usar qualquer conceito (estrutura medalhão, fato/dimensão etc.).
    </li>
    <li>    
        3)	Crie um dashboard no Power BI consumindo as tabelas que você criou, salve esse arquivo no repositório no formato .pbix com o nome de “dashboard_rh”.
    </li>
    <li>    
       4)	Crie uma documentação sobre seu projeto, de modo claro e sucinto, contendo a explicação de todos os arquivos criados anteriormente. Suba a documentação no repositório com o nome de “documentação”.
    </li>
    <li>    
       5)	Por fim, crie uma apresentação em Power Point (ou outro software/aplicativo que você esteja mais confortável em apresentar) com um foco de demonstrar seus resultados, análises e insights durante o processo. Suba a apresentação no repositório com o nome de “apresentação”.
    </li>

<hr>
</ul>
<h2 id='dev'>Desenvolvimento </h2>

<h3 id='#estrutura'>Estrutura do Projeto</h3>

<ul>
  <li><strong><a href="data/">data/</a></strong>
    <ul>
      <li><strong><a href="data/raw/">raw/</a></strong>
        <ul>
          <li><a href="data/raw/base_headcount.csv">base_headcount.csv</a>: base oririnal</li>
        </ul>
      </li>
      <li><strong><a href="data/treated/">treated/</a></strong>
        <ul>
          <li><a href="data/treated/base_corrigida.csv">base_corrigida.csv</a>: base com todos os tratamentos realizados</li>
          <li><a href="data/treated/tabela_dColaborador.csv">tabela_dColaborador.csv</a>: base </li>
          <li><a href="data/treated/tabela_dDesempenho.csv">tabela_dDesempenho.csv</a></li>
          <li><a href="data/treated/tabela_dEstrutura.csv">tabela_dEstrutura.csv</a></li>
          <li><a href="data/treated/tabela_fJornada_trabalho.csv">tabela_fJornada_trabalho.csv</a></li>
        </ul>
      </li>
      <li><a href="data/glossario.csv">glossario.csv</a></li>
    </ul>
  </li>

  <li><strong><a href="docs/">docs/</a></strong>
    <ul>
      <li><a href="docs/Apresentação.pptx">Apresentação.pptx</a></li>
    </ul>
  </li>

  <li><strong><a href="powerbi/">powerbi/</a></strong>
    <ul>
      <li><a href="powerbi/dashboard_rh.pbix">dashboard_rh.pbix</a></li>
    </ul>
  </li>

  <li><strong><a href="scripts/">scripts/</a></strong>
    <ul>
      <li><strong><a href="scripts/01_exploracao_glossario/">01_exploracao_glossario/</a></strong>
        <ul>
          <li>Exploração dos dados e criação do glossário</li>
        </ul>
      </li>
      <li><strong><a href="scripts/02_divisao_tabelas/">02_divisao_tabelas/</a></strong>
        <ul>
          <li>Tratamento dos dados e criação das tabelas divididas:
            <ul>
              <li>tabela_dColaborador.csv</li>
              <li>tabela_dDesempenho.csv</li>
              <li>tabela_dEstrutura.csv</li>
              <li>tabela_fJornada_trabalho.csv</li>
            </ul>
          </li>
        </ul>
      </li>
      <li><strong><a href="scripts/03_analise_de_dados/">03_analise_de_dados/</a></strong>
        <ul>
          <li>Tratamento dos dados e análises</li>
        </ul>
      </li>
    </ul>
  </li>

  <li><a href="README.md">README.md</a></li>
  <li><a href="INSTRUCOES.md">INSTRUCOES.md</a></li>
</ul>
<hr>
<h3 id='#vers'>Versionamento</h3>
<ol>
  <li>
    <strong>Criação do Repositório no GitHub</strong>
    <ol>
      <li>Criado repositório remoto → <a href="https://github.com/pela-andrea/people-analytics-case" target="_blank">people-analytics-case</a></li>
      <li>Definida a branch principal como <code>main</code></li>
      <li>Branch de trabalho <code>develop</code></li>
    </ol>
  </li>

  <li>
    <strong>Criação do Repositório Local</strong>
    <ol>
      <li>Definida a branch principal local como <code>main</code></li>
      <li>Branch de trabalho <code>develop</code></li>
    </ol>
  </li>

  <li>
    <strong>Definição das Branches de trabalho</strong>
    <ol>
      <li><strong>Branch principal</strong> → <code>main</code></li>
      <li><strong>Branch de desenvolvimento</strong> → <code>develop</code>: usada para integração contínua</li>
      <li>
        <code>chore/estrutura-inicial</code>: estrutura inicial do projeto com organização de pastas e arquivos.
      </li>
      <li>
        <code>feat/exploracao-glossario</code>: scripts para exploração inicial e criação do glossário de dados.
      </li>
      <li>
        <code>feat/divisao-tabelas</code>: separação da base original em tabelas fato e dimensão.
      </li>
      <li>
        <code>feat/analise-dados</code>: realização das análises e geração de insights com base na base tratada.
      </li>
      <li>
        <code>fix/ajuste-script-glossario</code>: correções pontuais no script de criação do glossário.
      </li>
      <li>
        <code>docs/readme-documentacao</code>: edição e melhoria dos arquivos <code>README.md</code> e <code>documentacao.md</code>.
      </li>
    </ol>
  </li>
</ol>

<h3 id='#execucao'>Como executar?</h3>

<p>Siga os passos abaixo para rodar o projeto localmente:</p>

<ol>
  <li>
    <strong>Clone o repositório:</strong>
    <pre><code>git clone https://github.com/pela-andrea/people-analytics-case.git
cd people-analytics-case</code></pre>
  </li>

  <li>
    <strong>(Opcional) Crie um ambiente virtual:</strong>
    <pre><code>python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows</code></pre>
  </li>

  <li>
    <strong>Instale as dependências:</strong>
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>

  <li>
    <strong>Execute os notebooks na ordem:</strong>
    <ul>
      <li><code>01_exploracao_glossario.ipynb</code> – Exploração e criação do glossário</li>
      <li><code>02_divisao_tabelas.ipynb</code> – Tratamento e separação das tabelas</li>
      <li><code>03_analise_de_dados.ipynb</code> – Análises e geração de insights</li>
    </ul>
  </li>
</ol>
<hr>
<h3 id='#tools'>Ferramentas utilizadas</h3>
<ul>
  <li><strong>Python</strong> (versão 3.10 ou superior)</li>
  <ul>
    <li>Pandas (v1.5+)</li>
    <li>NumPy (v1.23+)</li>
    <li>Matplotlib (v3.7+)</li>
    <li>Seaborn (v0.12+)</li>
  </ul>
  <li><strong>Google Colab</strong> – ambiente utilizado para exploração, análise e visualização de dados</li>
  <li><strong>Power BI</strong> – construção de dashboard final</li>
  <li><strong>Git & GitHub</strong> – versionamento e controle de código-fonte</li>
</ul>


## Autor

Andrea Pela  
[LinkedIn](https://www.linkedin.com/in/pela-andrea/)  
