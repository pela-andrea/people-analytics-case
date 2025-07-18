# Documentação do projeto: People Analytics Case

## Estrutura de pasta e arquivos

- `data/`
  - `raw/`: dados originais fornecidos para a análise
    - `base_headcount.csv`
  - `treated/`: arquivos tratados e prontos para análise
    - `base_corrigida.csv`
    - `tabela_dColaborador.csv`
    - `tabela_dDesempenho.csv`
    - `tabela_dEstrutura.csv`
    - `tabela_fJornada_trabalho.csv`
  - `glossario.csv`: dicionário de dados com colunas, tipos e observações

- `docs/`
  - `Apresentação.pptx`: apresentação final do projeto
  - `documentacao.md`: detalhamento técnico, descrição de tabelas e glossário

- `scripts/`: notebooks com os principais scripts de dados
  - `01_exploracao_glossario.ipynb`
  - `02_divisao_tabelas.ipynb`
  - `03_analise_de_dados.ipynb`

- `powerbi/`: dashboard final desenvolvido no Power BI
  - [Dashboard RH - Power BI](https://app.powerbi.com/view?r=eyJrIjoiOWM2MzI1YmMtZmQ4Ny00NGY4LWIwOGQtMzM4ZDI4ZTY1MDIzIiwidCI6ImNlMzdmYjc4LWE2OTUtNDNjOS05ZTkwLTFmNzkzYWIwOTQ3MyJ9)
  - [Acesse a documentação completa aqui](https://pela-andrea.notion.site/Case-People-Analytics-23433c70ce978084b664d2388dd9c257)

- `README.md`: resumo do projeto, instruções e tecnologias
- `INSTRUCOES.md`: instruções do projeto 


---

## Scripts

### 01_exploracao_glossario.ipynb

- Leitura da base original  
- Entendimento e descrição das colunas  
- Tratamento de dados inconsistentes ou faltantes  
- Conversão de tipos  
- Criação do glossário com nome original, nome amigável, tipo e observações  
- Salvamento do glossário  

📄 [Acessar notebook](https://github.com/pela-andrea/people-analytics-case/blob/docs/readme-documentacao/scripts/01_exploracao_glossario.ipynb)

### 02_divisao_tabelas.ipynb

- Classificação e segmentação da base  
- Criação de tabelas fato e dimensão  
- Salvamento dos arquivos tratados  

📄 [Acessar notebook](https://github.com/pela-andrea/people-analytics-case/blob/docs/readme-documentacao/scripts/02_divisao_tabelas.ipynb)

### 03_analise_de_dados.ipynb

- Análise exploratória e visual dos dados  
- Correlações, distribuições e insights para tomada de decisão  

📄 [Acessar notebook](https://github.com/pela-andrea/people-analytics-case/blob/docs/readme-documentacao/scripts/03_analise_de_dados.ipynb)

---

## Tabelas criadas

### tabela_dColaborador.csv

Identificação e dados pessoais do colaborador:

- ID do Colaborador  
- Localização  
- Data de Admissão  
- Data de Demissão  
- Está Ativo  
- Gênero  
- Estado Civil  
- Número de Dependentes  
- Nível de Escolaridade  
- Email  
- Flag: Promoção após Demissão  
- Flag: Demissão antes da Admissão  

### tabela_dEstrutura.csv

Informações organizacionais:

- ID do Colaborador  
- Cargo  
- Departamento  
- Salário  
- Data de Admissão  
- Data de Demissão  
- Turno  
- Centro de Custo  
- Tipo de Contrato  
- Plano de Saúde  
- ID do Gestor  

### tabela_dDesempenho.csv

Remuneração, benefícios e avaliação de performance:

- ID do Colaborador  
- Cargo  
- Salário  
- Avaliação de Desempenho  
- Percentual de Bônus  
- Tempo de Empresa (anos)  
- Data da Última Promoção  
- Data do Último Treinamento  
- Flag: Treinamento antes da Admissão  

### tabela_fJornada_trabalho.csv

Eventos temporais da jornada de trabalho:

- ID do Colaborador  
- Dias de Falta  
- Dias de Licença Médica  
- Dias de Férias Usufruídos  
- Banco de Horas  
- Horas Extras  
- Quantidade de Atrasos  

---

## Tecnologias e bibliotecas

- Python (pandas, seaborn, matplotlib, numpy)
- Google Colab
- Power BI
- Git e GitHub

---

## Autor

Andrea Pelá  
[LinkedIn](https://www.linkedin.com/in/andrea-pela/)
