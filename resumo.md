Este resumo aborda os principais tópicos e conceitos essenciais de Modelagem de Dados apresentados nas fontes, organizados por Unidade e Seção, da maneira mais sucinta possível.

### UNIDADE 1: Fundamentos de Bancos de Dados

#### Seção 1.1 - Introdução a Sistemas Gerenciadores de Bancos de Dados (SGBD)
Um **Banco de Dados (BD)** é um conjunto de dados ou informações inter-relacionados. Um **SGBD** é um software que gerencia, organiza, acessa, controla e protege as informações contidas em um BD (ou base de dados). O SGBD visa facilitar a vida do programador e garantir que as informações estejam seguras.

O conjunto de requisitos essenciais de um SGBD é conhecido como **ACID** (Atomicidade, Consistência, Isolamento e Durabilidade):
*   **Atomicidade:** Garante que todas ou nenhuma das operações de uma transação sejam realizadas. Em caso de falha, os dados voltam ao estado inicial.
*   **Consistência:** Preserva as regras impostas no BD, garantindo que os dados estejam íntegros ao finalizar uma transação.
*   **Isolamento:** Garante que uma transação não interfira no trabalho de outra que esteja ocorrendo simultaneamente.
*   **Durabilidade:** Certeza de que, após o sucesso da transação, os resultados são gravados e persistentes no BD.

Exemplos de SGBDs atuais incluem Oracle, SQL Server, MySQL e Postgree.

#### Seção 1.2 - Banco de Dados Relacional
O **Modelo de Dados Relacional**, proposto na década de 70, baseia-se na teoria de conjuntos da álgebra relacional. As informações são representadas em **tabelas** (coleções de relações).

Os aspectos básicos do modelo relacional são:
*   **Estrutural:** Dados vistos como tabelas.
*   **De integridade:** Tabelas satisfazem restrições de integridade.
*   **Manipulador:** Operações permitidas nas tabelas (juntar, selecionar, excluir).

O processo de **modelagem** começa com o **levantamento e análise dos requisitos** do cliente, resultando em um documento de especificação. O processo envolve as etapas de concepção, elicitação, elaboração e negociação.

Os elementos que compõem um BD são: **dados**, **hardware**, **software** (SGBD) e **usuários**.

*   **Entidades:** Objetos ou indivíduos do mundo real que podem ter existência física (pessoa, carro) ou conceitual (projeto, departamento) e cujas características se deseja registrar.
*   **Atributos (Campos/Colunas):** As informações específicas armazenadas em tabelas (ex: nome, data de nascimento). Um conjunto lógico de atributos forma um **registro** (linha/tupla).
*   **DBA (Administrador do Banco de Dados):** Profissional com controle total sobre o sistema, responsável pela instalação, configuração, manutenção e definição de regras de acesso e segurança.

#### Seção 1.3 - Dados como Apoio à Tomada de Decisão
Sistemas de apoio à decisão ajudam gestores a analisar informações e tomar decisões estratégicas, prevendo problemas futuros.
*   **OLTP (On-line Transaction Processing):** Processamento de Transações em Tempo Real. Representa operações do dia a dia da empresa (consultas, alterações, exclusões) e não armazena histórico de consultas.
*   **Data Warehouse (Depósito de Dados):** Repositório de informações obtidas de várias origens, armazenado em um único local com esquema unificado, usado para apoiar a decisão.
*   **OLAP (Online Analytical Processing):** Processamento Analítico On-line. Cria, gerencia e analisa relatórios sobre dados (geralmente coletados do OLTP) em uma tabela multidimensional para análise de algoritmos.
*   **Data Mining (Mineração de Dados):** Processo de analisar grandes BDs de forma semiautomática para descobrir padrões, anomalias e associações relevantes, usando estatísticas e inteligência artificial.

A **redundância** (repetição de dados) pode levar à **inconsistência** (dados errôneos). Um SGBD deve permitir a **redundância controlada**. A segurança do BD envolve autenticação do usuário e estabelecimento de políticas de permissões e acessos (privilégios).

### UNIDADE 2: Modelos de Banco de Dados

#### Seção 2.1 - Modelos de Banco de Dados
O projeto de BD segue uma sequência de atividades:
1.  **Análise dos Requisitos:** Levantamento das necessidades.
2.  **Modelo Conceitual:** Representação de alto nível e macro da estrutura do BD (o *que* precisa ser feito), independente de hardware ou software.
3.  **Modelo Lógico:** Mapeamento do conceito, descrevendo as estruturas (tabelas, relacionamentos, tipos de dados) de acordo com a abordagem da modelagem.
4.  **Modelo Físico:** Detalhamento ao nível do SGBD escolhido, utilizando a linguagem SQL para a criação dos componentes e implementação das regras de segurança.

#### Seção 2.2 - Modelagem de Dados Através do Modelo Entidade-Relacionamento
O **Modelo de Entidade-Relacionamentos (MER)** é utilizado para aperfeiçoar o projeto de BD e permite a especificação do modelo conceitual.

As entidades podem ser classificadas como:
*   **Entidades Fortes:** Tabelas autônomas, não dependem de outras para existir (ex: Aluno).
*   **Entidades Fracas ou Dependentes:** Tabelas que necessitam de outra entidade forte para existir.
*   **Entidades Associativas:** Criadas em razão do tipo de relacionamento, geralmente a partir de um relacionamento N para N.

**Relacionamento** descreve uma associação entre entidades. O **Grau de Relacionamento (Cardinalidade)** define o número de ocorrências de uma entidade associada a ocorrências de outra:
*   **Um para Um (1:1)**
*   **Um para Muitos (1:N)** ou **Muitos para Um (N:1)**
*   **Muitos para Muitos (N:N):** Sempre deve ser "quebrado" e gera uma tabela associativa.

#### Seção 2.3 - Diagrama de Entidade-Relacionamento (DER)
O DER é a representação gráfica do modelo lógico.

**Chaves:** Um ou mais atributos que determinam a existência de outros atributos e são usados para estabelecer relacionamentos. Tipos principais:
*   **Chave Primária (PK):** Campo único que identifica um registro na tabela. Não pode ser repetido. Pode ser composta/concatenada (formada por dois ou mais campos).
*   **Chave Estrangeira (FK):** Uma chave primária de outra tabela. É fundamental para estabelecer relacionamentos e garantir a **Integridade Referencial** (garantir que a FK foi cadastrada antes como PK em outra tabela).

Os relacionamentos 1 para N são estabelecidos pelo uso da Chave Estrangeira, que fica na tabela do lado N.

### UNIDADE 3: Abordagem Entidade-Relacionamento

#### Seção 3.1 - Modelagem de Dados Através do Modelo Entidade-Relacionamento Usando DER
**Estratégias de Modelagem:**
*   **Top-down:** Começa identificando os conjuntos de dados (tabelas) e depois seus elementos (atributos). Usada em BDs maiores.
*   **Bottom-up:** Começa identificando os elementos de dados (atributos) e depois os agrupa em conjuntos (tabelas). Usada em BDs pequenos.
*   **Mista (middle-up-down):** Complementa as duas anteriores.

**Dicionário de Dados:** Documento que contém **metadados** (detalhes dos dados) e é essencial para a padronização e documentação. Deve descrever nome das tabelas/atributos, tipos de dados, tamanhos e chaves.

#### Seção 3.2 - Modelagem de Dados Através do Modelo Entidade-Relacionamento Usando UML
**UML (Unified Modeling Language):** Linguagem de Modelagem Unificada, usada para padronizar projetos de sistemas orientados a objetos.
*   Um **Objeto** tem informações e funcionalidades.
*   Uma **Classe** agrupa informações comuns de um objeto (nome, atributos e métodos).

A modelagem de dados utiliza o conceito de **Herança** da orientação a objetos através de **Generalização** (agrupar entidades em uma única entidade genérica) e **Especialização** (criar novas entidades filhas com atributos específicos). Pode ser **Parcial** (nem toda ocorrência da generalizada tem uma especializada) ou **Total** (toda ocorrência tem uma especializada correspondente).

#### Seção 3.3 - Ferramentas CASE’s de Modelagem do DER
**Ferramentas CASEs (Computer Aided Software Engeneering):** Ferramentas que auxiliam e automatizam tarefas no desenvolvimento de software e modelagem, estabelecendo padrões.
Características das ferramentas CASE para BD:
*   Suporte à criação de diagramas gráficos com notações (ex: Peter Chen, Pé de Galinha).
*   **Geração de scripts SQL**.
*   **Forward Engineer:** Cria o modelo físico (BD) automaticamente a partir do DER (modelo gráfico).
*   **Reverse Engineer:** Gera o modelo gráfico (DER) a partir do modelo físico (BD).
*   **Geração automática de documentação** (dicionário de dados).

### UNIDADE 4: Normalização de Dados

#### Seção 4.1 - Normalização de Dados na Computação
**Normalização:** Técnica para avaliar e corrigir estruturas de tabelas para minimizar redundâncias e inconsistências. O objetivo é reduzir a repetição de dados, aumentar a performance e facilitar a manutenção.

**Dependência Funcional:** Restrição entre dois ou mais conjuntos de atributos, onde o valor de um conjunto (X) determina o valor de outro (Y). Pode ser:
*   **Transitiva ou Indireta:** Um campo depende de outro campo que não é a chave primária.
*   **Total ou Completa:** Um atributo não-chave depende de *todos* os atributos da chave primária (ocorre em chaves concatenadas).
*   **Parcial:** Um atributo não-chave depende apenas de *parte* da chave primária.

#### Seção 4.2 - Transformação 1FN - 2FN
**Primeira Forma Normal (1FN):** Uma tabela está em 1FN se, e somente se, todos os seus atributos forem **atômicos** (não divisíveis) e não possuírem grupos repetitivos ou colunas multivaloradas.

**Segunda Forma Normal (2FN):** Uma tabela está em 2FN se, e somente se, estiver na 1FN **e** todas as suas colunas que não são chaves dependam **exclusivamente** de toda a chave primária. Se houver dependência parcial em chaves concatenadas, a 2FN não é satisfeita, sendo necessário remover o campo e criar uma nova tabela.

#### Seção 4.3 - Transformação 3FN - 4FN
**Terceira Forma Normal (3FN):** Uma tabela está em 3FN se, e somente se, estiver na 2FN **e** todos os campos forem independentes (eliminar dependências transitivas). O campo deve depender unicamente da chave primária e não de outro campo não-chave dentro da mesma tabela.

**Quarta Forma Normal (4FN):** Uma tabela está em 4FN se, e somente se, estiver na 3FN **e** não existir **dependência multivalorada**. Campos multivalorados (que causam repetição de informações na mesma tabela) devem ser removidos e divididos em novas tabelas.
