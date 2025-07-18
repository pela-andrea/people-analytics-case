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
            <li> <a href='#notebooks'> Notebooks</a> </li>
            <li> <a href='#tabelas'> Tabelas</a> </li>
            <li> <a href='#execucao'> Execução</a> </li>
            <li> <a href='#tools'> Ferramentas</a> </li>
        </ul>
</ul>
<ul>
    <li> 
        <a href='analise'>Análise</a>
        <ul>
            <li> <a href='#insights'> Principais Insights </a> </li>
            <li> <a href='#dash'> Dashboard</a> </li>
            <li> <a href='#doc'> Documentação</a> </li>
            <li> <a href='#autor'> Autor</a> </li>
        </ul>
</ul>

<hr>

<br>

<h3 id='info'> Informações Gerais  </h3>
<p>
    Aqui estão as informações básicas para compreender melhor o escopo deste projeto.
</p>

<hr>
<h2 id='objetivo'>Objetivo</h2>
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
<h2 id='intrucoes'> Instruções</h2>

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

<h3 id='estrutura'>Estrutura do Projeto</h3>

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
<h3 id='vers'>Versionamento</h3>
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
<h2 id='notebooks'>Notebooks</h2>

<h2> Notebook 01 - Exploração e Glossário</h2>
<p><a href="https://github.com/pela-andrea/people-analytics-case/blob/docs/readme-documentacao/scripts/01_exploracao_glossario.ipynb" target="_blank">
  Acesse o notebook no GitHub
</a></p>

<p>Este notebook contempla as etapas iniciais de exploração da base de dados. São abordados:</p>

<ul>
  <li>Leitura da base original</li>
  <li>Entendimento e descrição das colunas</li>
  <li>Identificação e tratamento de dados inconsistentes ou faltantes</li>
  <li>Inferência e conversão de tipos de dados</li>
  <li>Criação do glossário contendo:</li>
  <ul>
    <li>Nome da coluna original</li>
    <li>Nome amigável</li>
    <li>Tipo de dado</li>
    <li>Observações relevantes</li>
  </ul>
  <li>Salvamento do glossário em formato <code>.csv</code> ou <code>.md</code></li>
</ul>

<h2>Notebook 02 - Divisão de Tabelas</h2>
<p>
  <a href="https://github.com/pela-andrea/people-analytics-case/blob/docs/readme-documentacao/scripts/02_divisao_tabelas.ipynb" target="_blank">
    Acesse o notebook no GitHub
  </a>
</p>

<p>
  Neste notebook, daremos continuidade ao processo de preparação dos dados para análise, realizando a classificação e segmentação da base original em múltiplas tabelas organizadas segundo critérios específicos. O objetivo é estruturar os dados de forma mais eficiente para análises futuras e uso no Power BI, aplicando conceitos de modelagem como fato e dimensão, quando pertinente.
</p>

<p>As principais etapas deste notebook incluem:</p>
<ul>
  <li>Aplicar classificações relevantes para separar as informações em grupos lógicos</li>
  <li>Dividir a base de dados original em diversas tabelas e nomear os arquivos gerados seguindo o padrão <code>tabela_nome.csv</code>, garantindo organização</li>
  <li>Salvar as tabelas finais para utilização no Power BI</li>
</ul>

<h2>Notebook 03 - Análise de Dados</h2>
<p>
  <a href="https://github.com/pela-andrea/people-analytics-case/blob/docs/readme-documentacao/scripts/03_analise_de_dados.ipynb" target="_blank">
    Acesse o notebook no GitHub
  </a>
</p>

<p>
  Neste notebook daremos início à análise de dados para explorar a base de dados de RH, buscando identificar padrões, inconsistências e potenciais insights que possam apoiar a tomada de decisão.
</p>

<p>Principais abordagens exploradas:</p>
<ul>
  <li>Análise de rotatividade (admissões, demissões e saldo)</li>
  <li>Distribuição de salário e bônus</li>
  <li>Correlação entre desempenho e atrasos, faltas ou promoções</li>
  <li>Comparações por departamento, gestor e turno</li>
  <li>Criação de visualizações para apoiar os achados</li>
</ul>


<h2 id='tabelas'>Tabelas</h2>
<h>
<ul>
    <li><a href='#glossario'>Glossário</a></li>
    <li><a href='#dcolab'>Tabela dColaborador</a></li>
    <li><a href='#dcolab'>Tabela dColaborador</a></li>
    <li><a href='#dcolab'>Tabela dColaborador</a></li>
    <li><a href='#dcolab'>Tabela dColaborador</a></li>
    <li><a href='#dcolab'>Tabela dColaborador</a></li>
    <li><a href='#dcolab'>Tabela dColaborador</a></li>
        
</ul>
<h2 id='glossario'>Glossário</h2>
<table border="1" cellpadding="6" cellspacing="0" style="border-collapse: collapse; width: 100%;">
  <thead style="background-color: #f2f2f2;">
    <tr>
      <th>Coluna Original</th>
      <th>Coluna Corrigida</th>
      <th>Tipo de Dado</th>
      <th>Observações</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>employee_id</td><td>ID do Colaborador</td><td>object</td><td>Identificação do colaborador. Ex: EMP_00001, ...</td></tr>
    <tr><td>job_title</td><td>Cargo</td><td>object</td><td>Gerente de RH, Engenheiro de Dados, Desenvolvedor Python, etc.</td></tr>
    <tr><td>department</td><td>Departamento</td><td>object</td><td>Financeiro, Marketing, Operações, RH, Jurídico, TI, Vendas</td></tr>
    <tr><td>location</td><td>Localização</td><td>object</td><td>Salvador, BH, POA, Curitiba, SP, Fortaleza, RJ</td></tr>
    <tr><td>salary</td><td>Salário</td><td>float64</td><td>Valor contínuo em reais</td></tr>
    <tr><td>hire_date</td><td>Data de Admissão</td><td>datetime64[ns]</td><td>Convertido para datetime</td></tr>
    <tr><td>termination_date</td><td>Data de Demissão</td><td>datetime64[ns]</td><td>---</td></tr>
    <tr><td>is_active</td><td>Está Ativo</td><td>object</td><td>'Sim' indica ativo, 'Não' indica desligado</td></tr>
    <tr><td>absence_days</td><td>Dias de Falta</td><td>int64</td><td>Faltas injustificadas e justificadas</td></tr>
    <tr><td>sick_days</td><td>Dias de Licença Médica</td><td>int64</td><td>---</td></tr>
    <tr><td>vacation_days_taken</td><td>Dias de Férias Usufruídos</td><td>int64</td><td>---</td></tr>
    <tr><td>bank_hours</td><td>Banco de Horas</td><td>int64</td><td>Pode conter valores negativos (uso ou dívida)</td></tr>
    <tr><td>overtime_hours</td><td>Horas Extras</td><td>int64</td><td>Horas extras acumuladas</td></tr>
    <tr><td>tardiness_count</td><td>Quantidade de Atrasos</td><td>int64</td><td>Contagem de atrasos registrados</td></tr>
    <tr><td>gender</td><td>Gênero</td><td>object</td><td>Feminino, Masculino, Outro</td></tr>
    <tr><td>marital_status</td><td>Estado Civil</td><td>object</td><td>Viúvo(a), Casado(a), Divorciado(a), Solteiro(a)</td></tr>
    <tr><td>number_of_dependents</td><td>Número de Dependentes</td><td>int64</td><td>Número inteiro</td></tr>
    <tr><td>education_level</td><td>Nível de Escolaridade</td><td>object</td><td>Graduação, Mestrado, Ensino Médio, Doutorado</td></tr>
    <tr><td>performance_rating</td><td>Avaliação de Desempenho</td><td>int64</td><td>Nota de 1 a 5</td></tr>
    <tr><td>bonus_percentage</td><td>Percentual de Bônus</td><td>float64</td><td>Percentual de bônus - contínuo</td></tr>
    <tr><td>shift</td><td>Turno</td><td>object</td><td>Manhã, Tarde, Noite</td></tr>
    <tr><td>contract_type</td><td>Tipo de Contrato</td><td>object</td><td>Permanente, Temporário</td></tr>
    <tr><td>cost_center</td><td>Centro de Custo</td><td>object</td><td>Código de centro de custo</td></tr>
    <tr><td>compliance_status</td><td>Status de Conformidade</td><td>object</td><td>Status de conformidade</td></tr>
    <tr><td>health_plan</td><td>Plano de Saúde</td><td>object</td><td>Premium, Básico, Padrão</td></tr>
    <tr><td>email</td><td>Email</td><td>object</td><td>Formato padrão de e-mail</td></tr>
    <tr><td>tenure_years</td><td>Tempo de Empresa (anos)</td><td>float64</td><td>Anos de empresa (float)</td></tr>
    <tr><td>probation_completed</td><td>Período de Experiência Concluído</td><td>object</td><td>Sim, Não</td></tr>
    <tr><td>manager_id</td><td>ID do Gestor</td><td>object</td><td>ID do gestor (Chave Gestor)</td></tr>
    <tr><td>last_promotion_date</td><td>Data da Última Promoção</td><td>datetime64[ns]</td><td>Nulos indicam sem promoção registrada</td></tr>
    <tr><td>last_training_date</td><td>Data do Último Treinamento</td><td>datetime64[ns]</td><td>Nulos indicam ausência de treinamentos recentes</td></tr>
    <tr><td>-</td><td>Flag: Promoção após Demissão</td><td>object</td><td>Indica registros em que a data da última promoção é posterior à demissão</td></tr>
    <tr><td>-</td><td>Flag: Demissão antes da Admissão</td><td>object</td><td>Identifica casos onde a data de demissão anterior à admissão</td></tr>
    <tr><td>-</td><td>Flag: Treinamento antes da Admissão</td><td>object</td><td>Aponta registros em que a data do último treinamento anterior à admissão</td></tr>
  </tbody>
</table>
<h>
<h2 id='dcolab'>Tabela dColaborador</h2>
<p>Contém informações cadastrais e demográficas dos colaboradores, com foco na identificação individual, dados pessoais e flags de integridade temporal.</p>

<ul>
  <li><strong>ID do Colaborador</strong>: Identificador único do colaborador (ex: EMP_00001)</li>
  <li><strong>Localização</strong>: Cidade-base do colaborador</li>
  <li><strong>Data de Admissão</strong>: Data de entrada na empresa</li>
  <li><strong>Data de Demissão</strong>: Data de desligamento, se aplicável</li>
  <li><strong>Está Ativo</strong>: Indica se o colaborador está ativo na empresa (Sim/Não)</li>
  <li><strong>Gênero</strong>: Masculino, Feminino ou Outro</li>
  <li><strong>Estado Civil</strong>: Estado civil do colaborador (Casado(a), Solteiro(a), etc.)</li>
  <li><strong>Número de Dependentes</strong>: Quantidade de dependentes cadastrados</li>
  <li><strong>Nível de Escolaridade</strong>: Grau de formação (Ex: Graduação, Mestrado)</li>
  <li><strong>Email</strong>: Endereço de e-mail corporativo</li>
  <li><strong>Flag: Promoção após Demissão</strong>: Sinaliza se houve promoção após o desligamento (verificação de inconsistência)</li>
  <li><strong>Flag: Demissão antes de Admissão</strong>: Sinaliza se há data de demissão anterior à de admissão (erro temporal)</li>
</ul>

    
</h>
<h>
<h2 id='dcolab'>Tabela dEstrutura</h2>
<p>Reúne dados organizacionais relacionados à posição e vínculo do colaborador dentro da empresa.</p>

<ul>
  <li><strong>ID do Colaborador</strong>: Identificador único do colaborador</li>
  <li><strong>Cargo</strong>: Função ou título exercido (ex: Analista de Dados, Gerente de RH)</li>
  <li><strong>Departamento</strong>: Área ou setor de atuação (ex: TI, Marketing)</li>
  <li><strong>Salário</strong>: Remuneração mensal em reais</li>
  <li><strong>Data de Admissão</strong>: Data em que o colaborador ingressou na empresa</li>
  <li><strong>Data de Demissão</strong>: Data de saída, caso o colaborador tenha sido desligado</li>
  <li><strong>Turno</strong>: Período de trabalho (Manhã, Tarde, Noite)</li>
  <li><strong>Centro de Custo</strong>: Código do centro de custo vinculado</li>
  <li><strong>Tipo de Contrato</strong>: Tipo de vínculo empregatício (Permanente, Temporário)</li>
  <li><strong>Plano de Saúde</strong>: Categoria do plano de saúde corporativo</li>
  <li><strong>ID do Gestor</strong>: Identificador do gestor responsável pelo colaborador</li>
</ul>

    
</h>
<h>
<h2 id='dcolab'>Tabela dDesempenho</h2>
<p>Contém informações sobre remuneração, benefícios e desempenho dos colaboradores.</p>

<ul>
  <li><strong>ID do Colaborador</strong>: Identificador único do colaborador</li>
  <li><strong>Cargo</strong>: Cargo atual do colaborador</li>
  <li><strong>Salário</strong>: Remuneração mensal em reais</li>
  <li><strong>Avaliação de Desempenho</strong>: Nota atribuída ao desempenho do colaborador (escala de 1 a 5)</li>
  <li><strong>Percentual de Bônus</strong>: Percentual recebido a título de bônus</li>
  <li><strong>Tempo de Empresa (anos)</strong>: Tempo total de permanência na empresa</li>
  <li><strong>Data da Última Promoção</strong>: Última data registrada de promoção</li>
  <li><strong>Data do Último Treinamento</strong>: Data mais recente de participação em treinamento</li>
  <li><strong>Flag: Treinamento antes da Admissão</strong>: Indica se houve treinamento antes da data de admissão</li>
</ul>
</h>
<h>
<h2 id='dcolab'>Tabela fJornada_trabalho</h2>

<p>Registra eventos temporais relacionados à jornada de trabalho dos colaboradores.</p>

<ul>
  <li><strong>ID do Colaborador</strong>: Identificador único do colaborador</li>
  <li><strong>Dias de Falta</strong>: Quantidade total de faltas (justificadas e injustificadas)</li>
  <li><strong>Dias de Licença Médica</strong>: Total de dias afastados por motivos de saúde</li>
  <li><strong>Dias de Férias Usufruídos</strong>: Quantidade de dias de férias utilizados</li>
  <li><strong>Banco de Horas</strong>: Saldo de horas acumuladas (pode ser positivo ou negativo)</li>
  <li><strong>Horas Extras</strong>: Total de horas trabalhadas além da jornada padrão</li>
  <li><strong>Quantidade de Atrasos</strong>: Número de registros de atraso no ponto</li>
</ul>

</h>

<hr>

<h3 id='execucao'>Como executar?</h3>

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
<h3 id='tools'>Ferramentas utilizadas</h3>
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

<h3 id='analises'>Análises</h3>

<h2 id='insights'>Insights</h2>
<ul>
  <li>
    <strong>Distribuição por gênero e faixa salarial:</strong> 
    análise da proporção de colaboradores por gênero e como os salários se distribuem entre esses grupos.
    <br>
    <img src="CAMINHO/DA/IMAGEM1.png" alt="Distribuição por gênero e salário" width="600">
  </li>
  <li>
    <strong>Relação entre desempenho e promoções:</strong> 
    explorada a média de tempo até promoção por faixa de avaliação de desempenho.
    <br>
    <img src="CAMINHO/DA/IMAGEM2.png" alt="Desempenho e promoções" width="600">
  </li>
  <li>
    <strong>Atrasos por turno:</strong> 
    comparado o número médio de atrasos por colaborador em diferentes turnos (manhã, tarde, noite).
    <br>
    <img src="CAMINHO/DA/IMAGEM3.png" alt="Atrasos por turno" width="600">
  </li>
  <li>
    <strong>Rotatividade por departamento e gestor:</strong> 
    medição da proporção de demissões por gestor e análise de saldo de admissões/demissões por área.
    <br>
    <img src="CAMINHO/DA/IMAGEM4.png" alt="Rotatividade por gestor e departamento" width="600">
  </li>
  <li>
    <strong>Correlação entre horas extras e desempenho:</strong> 
    identificação visual e estatística da relação entre esforço adicional e avaliação.
    <br>
    <img src="CAMINHO/DA/IMAGEM5.png" alt="Horas extras vs desempenho" width="600">
  </li>
</ul>

<h2 id='dash'>Dashboard</h2>

<p>Visualizações desenvolvidas no Power BI com base nos dados tratados. Abaixo, estão os principais painéis do dashboard:</p>

<div style="display: flex; flex-wrap: wrap; gap: 20px; margin-top: 20px;">
  <div style="flex: 1 1 45%;">
    <img src="caminho/para/imagem1.png" alt="Dashboard 1" style="width: 100%; border: 1px solid #ccc;" />
    <p style="text-align: center;">Título do Dashboard 1</p>
  </div>
  <div style="flex: 1 1 45%;">
    <img src="caminho/para/imagem2.png" alt="Dashboard 2" style="width: 100%; border: 1px solid #ccc;" />
    <p style="text-align: center;">Título do Dashboard 2</p>
  </div>
  <div style="flex: 1 1 45%;">
    <img src="caminho/para/imagem3.png" alt="Dashboard 3" style="width: 100%; border: 1px solid #ccc;" />
    <p style="text-align: center;">Título do Dashboard 3</p>
  </div>
  <div style="flex: 1 1 45%;">
    <img src="caminho/para/imagem4.png" alt="Dashboard 4" style="width: 100%; border: 1px solid #ccc;" />
    <p style="text-align: center;">Título do Dashboard 4</p>
  </div>
</div>

<p>🔗 Link para o arquivo do dashboard no Power BI: 
<a href="https://github.com/seu-usuario/seu-repositorio/blob/main/powerbi/dashboard_rh.pbix" target="_blank">
dashboard_rh.pbix</a>
</p>

<h2 id='doc'>Documentação</h2>

<p>Para mais detalhes técnicos sobre a estrutura do projeto, métodos utilizados, glossário e dicionário de dados, consulte o arquivo abaixo:</p>

<ul>
  <li>
    <a href="https://github.com/seu-usuario/seu-repositorio/blob/main/documentacao.md" target="_blank">
      <code>documentacao.md</code> – Documentação técnica completa
    </a>
  </li>
</ul>
<hr>
<h2 id='autor'>Autor</h2>
<p>Este projeto foi desenvolvido por <strong>Andrea Pela</strong>.</p>
<ul>
  <li>
    <a href="https://www.linkedin.com/in/pela-andrea" target="_blank">🔗 LinkedIn</a>
  </li>
  <li>
    <a href="https://seu-portfolio.com" target="_blank">🌐 Portfólio</a>
  </li>
</ul>

