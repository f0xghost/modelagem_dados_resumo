A seguir, estão todos os exercícios "Faça valer a pena" das fontes, com as alternativas corretas e as justificativas detalhadas.

### Unidade 1 | Seção 1.1 - Introdução a Sistemas Gerenciadores de Bancos de Dados (SGDB)

**1. Leia a sentença abaixo sobre o Sistema Gerenciador de Banco de Dados:**
Um Sistema Gerenciador de Banco de dados ou simplesmente SGBD é um **[conjunto]** de softwares que possuem o objetivo de **[gerenciar]** as informações armazenadas em um banco de dados (também conhecida como base de dados). Devem **[organizar]**, acessar, **[controlar]** e dar **[proteção]** às informações contidas no banco de dados.
Com base na sentença, assinale a alternativa que apresenta as palavras que completam a frase corretamente.
a) banco – gerenciar – processar – controlar – sustentação.
b) conjunto – agrupar – reformar – inviabilizar – proteção.
c) sistema – agrupar – processar – marcar – finalização.
**d) conjunto – gerenciar – organizar – controlar – proteção.**
e) banco – capturar – compreender – sistematizar – finalização.

**Resposta Correta: d)**
**Justificativa:** Um SGBD é um **conjunto** de programas para acesso a dados. Tem a finalidade de **gerenciar** as informações, e também deve **organizar**, **controlar** e **proteger** as informações contidas no BD. A sentença completa corretamente o conceito de SGBD com as ações que ele deve realizar.

**2. Um Sistema Gerenciador de Banco de Dados é um software que possui muitas funcionalidades, entre elas podemos destacar:**
I. Permitem aos seus usuários pesquisas para encontrar uma determinada informação.
II. Podem gerar relatórios com diversas informações da base de dados.
III. Protegem e recuperam os dados em caso de falha de software ou de hardware.
IV. Permitem o compartilhamento de dados e o controle da redundância.
Analise cada item e marque a alternativa correta referente às funcionalidades de um SGBD:
a) Somente as opções I e IV estão corretas, as outras estão incorretas.
b) Somente a opção III está incorreta.
c) Somente as opções I e III estão corretas, as outras estão incorretas.
d) Todas as opções estão incorretas.
**e) Todas as opções estão corretas.**

**Resposta Correta: e)**
**Justificativa:** Todas as opções listadas são funcionalidades do SGBD. Ele permite pesquisa e recuperação de informação, alteração e geração de relatórios, proteção e recuperação de dados após problemas de hardware ou software, além de permitir o compartilhamento de dados e a administração da redundância e restrição de integridade.

**3. Conforme Guimarães (2003), o conjunto de requisitos de um SGBD recebe o nome de ACID ou, respectivamente, Atomicidade, Consistência, Isolamento e Durabilidade. É fundamental verificar se o SGBD escolhido possui esses quatro fatores. Sobre o conceito de Atomicidade, podemos afirmar que:**
I. É a garantia que todas as informações sejam corretamente cadastradas, inviabilizando dados cadastrados erroneamente, no momento em que o usuário final utiliza o software de aplicação.
**II. É a garantia de que todas as transações sejam realizadas com sucesso. Caso contrário, tudo o que foi alterado deverá voltar ao seu estado original antes de a transação ser executada.**
III. É a certeza de que, a cada exclusão realizada no banco de dados, um arquivo reserva mantenha o item apagado por tempo indeterminado.
IV. É a certeza de que, a cada inclusão nova no banco de dados, uma nova cópia seja criada como backup provisório da inclusão realizada.
Analise atentamente as afirmativas e marque a opção correta referente ao conceito de Atomicidade de um SGBD.
a) Somente as alternativas II e IV estão corretas, as demais estão incorretas.
**b) Somente a alternativa II está correta.**
c) Somente as alternativas I e II estão incorretas, as demais estão corretas.
d) Somente a alternativa III está correta.
e) Todas as alternativas estão corretas.

**Resposta Correta: b)**
**Justificativa:** A Atomicidade garante que **nenhuma ou a totalidade** das operações da transação sejam realizadas com sucesso. Se houver algum problema, o SGBD reestabelece os dados antigos, voltando ao estado inicial. A afirmativa I descreve a Consistência ou Integridade. As afirmativas III e IV descrevem práticas de backup ou log de transação, não Atomicidade.

### Unidade 1 | Seção 1.2 - Banco de Dados Relacional

**1. A modelagem de dados relacional baseia-se na ideia de que as informações em uma base de dados são representadas em tabelas (ou entidades). Desta forma, podemos considerar:**
I. Atributos são as linhas de uma tabela.
II. Todas as linhas de uma tabela também são conhecidas como categoria.
**III. Cada informação cadastrada em um banco de dados é conhecida como tupla.**
IV. Um campo ou atributo é a coluna de uma tabela, conhecida também como categoria.
**V. Um registro é um conjunto lógico de campos que são conhecidos como tuplas.**
Analise cada item e marque a alternativa correta que demonstra os conceitos corretos referentes às partes integrantes da tabela (entidade):
a) Somente as assertivas I e III estão corretas.
b) Somente as assertivas II e IV estão corretas.
c) Somente as assertivas III e V estão corretas.
d) Somente as assertivas II e III estão corretas.
**e) Somente as assertivas IV e V estão corretas.**

**Resposta Correta: e)**
**Justificativa:** Um **campo ou atributo** é a coluna da tabela (Assertiva IV: correta). Um **registro** é um conjunto lógico de campos, também chamado de **tupla** ou linha (Assertiva V: correta). A assertiva I está incorreta, pois atributos são colunas. A assertiva II está incorreta, pois linhas são tuplas/registros. A assertiva III está imprecisa ou incorreta, pois a informação cadastrada é um valor dentro de um campo de uma tupla.

**2. O levantamento dos requisitos é o primeiro item a ser realizado em um novo projeto e, para atingir esse objetivo, são necessárias entrevistas para entender e documentar as necessidades solicitadas pelos usuários, conseguindo desta forma começar a elaborar o desenvolvimento do software desejado.**
Analise atentamente as alternativas e marque a correta que demonstra o conceito sobre os requisitos de um projeto de banco de dados.
a) Um requisito é um único item que, após ser diagnosticado, acaba se transformando em uma tabela associativa.
b) Um requisito é a descrição detalhada de cada item e componente de cada tabela, estabelecendo os tipos de dados que serão inseridos na base de dados.
**c) Um requisito é uma condição ou capacidade que um software deverá possuir. É um levantamento e uma análise das necessidades às quais o sistema precisa atender.**
d) Um requisito é criação da tupla de uma tabela, definindo os campos que a compõem.
e) Um requisito é a criação da base de dados no SGBD.

**Resposta Correta: c)**
**Justificativa:** Monteiro (2014) afirma que um **requisito é uma condição ou uma capacidade que um software deverá possuir**. Requisito é um levantamento e análise das necessidades que o sistema precisa atender. As demais opções descrevem fases posteriores (modelagem/implementação) ou conceitos errados.

**3. O Administrador de Banco de Dados ou simplesmente DBA é um profissional muito valorizado no mercado de trabalho, justificando, desta forma, a sua constante atualização profissional. As atribuições do DBA são fundamentais para as organizações, pois a funcionalidade do banco de dados depende deste profissional.**
Considerando as atribuições de um DBA, marque a alternativa correta referente às funções de um Administrador de Banco de Dados.
a) Realiza somente a instalação do banco de dados.
b) Projeta a modelagem do banco de dados e não participa da manutenção do banco de dados.
c) Faz a manutenção do banco de dados, mas não tem permissão para instalá-lo.
**d) Instala, configura, monitora e realiza manutenção preventiva e corretiva do banco de dados.**
e) Realiza a manutenção do banco somente quando o computador trava, afetando os negócios da empresa.

**Resposta Correta: d)**
**Justificativa:** O DBA (Administrador do Banco de Dados) possui diversas funções que envolvem a **instalação, a configuração e a manutenção do SGBD**. Ele também precisa estabelecer regras de acesso aos dados, **monitorar o banco** e realizar **manutenções preventivas e corretivas**.

### Unidade 1 | Seção 1.3 - Dados como apoio a tomada de decisão

**1. Conforme Date (2003), sistemas de apoio à decisão são sistemas que ajudam na análise de informação do negócio. Com a constante concorrência entre as empresas, atualmente os administradores utilizam esta tecnologia para diversas finalidades em suas companhias.**
Assinale a alternativa correta referente aos objetivos do uso dos sistemas de apoio à decisão:
a) Ajudar os gestores a tomarem decisões, porém não é possível prever nenhum tipo de problema com a análise dos dados da empresa.
b) Aumentar a lucratividade das empresas e a sua consequente valorização no mercado de ações.
**c) Ajudar os gestores a tomarem decisões e a apontarem existentes e até futuros problemas que possam ocorrer.**
d) Encontrar erros no SGBD e estabelecer uma rápida correção para evitar problemas entre entidades fundamentais na estrutura do banco de dados.
e) Definir a política de segurança do banco de dados e criar uma política de backup do SGBD.

**Resposta Correta: c)**
**Justificativa:** Sistemas de apoio à decisão ajudam na análise de informação do negócio. A meta é **auxiliar os gestores a tomarem decisões e a apontarem problemas existentes e até futuros que possam ocorrer**.

**2. Um Sistema Gerenciador de Banco de Dados é um software que possui muitas funcionalidades, sendo uma delas a questão de segurança. Caso ocorra uma falha de hardware ou software, a integridade do banco é mantida. A empresa que mantém um banco de dados precisa ficar atenta e também tomar muitas precauções em relação à segurança do banco de dados, por isso, precisa ter uma política de backup.**
Analise com cuidado cada alternativa e escolha a opção correta referente à política de backup que a empresa deve possuir para preservar a integridade de seu banco de dados.
a) É uma formalidade que às vezes deve ser seguida pela equipe responsável pelo SGBD.
b) Ela deve determinar o diretor ou gerente administrativo da empresa que deverá realizar o backup diariamente.
c) Ela deve definir um único local para armazenar as cópias do banco de dados, preferencialmente ao lado do servidor para facilitar o acesso, caso haja um problema no banco de dados.
d) É estabelecida somente para grandes corporações, pois somente grandes volumes de dados podem ocasionar problemas no banco de dados.
**e) São regras que devem ser estabelecidas para preservar o banco de dados, pois, caso seja necessário recuperar as informações, elas estarão em lugar seguro.**

**Resposta Correta: e)**
**Justificativa:** A política de backup é um conjunto de regras estabelecido para preservar a integridade do banco de dados. O objetivo principal é garantir que, em caso de falhas, as informações possam ser recuperadas porque estão em local seguro.

**3. As duas siglas OLTP e OLAP são bastante usadas no mundo de Business Intelligence e pode-se afirmar que as duas são importantes e se complementam. Com isso, é possível dizer que:**
**I. OLTP é voltado para o sistema de transações, regras de negócios aplicadas no sistema do dia a dia da empresa.**
**II. OLAP é voltado para a análise das informações, ou seja, cálculos mais complexos, um sistema de modelagem voltado para sistemas de apoio à decisão.**
III. OLTP é voltado para sistemas de grandes proporções e usados para tomar decisões complexas no mercado financeiro.
IV. OLAP é voltado para a análise de pequenas informações do dia a dia de uma empresa, sendo que empregados operacionais podem fazer essas consultas.
Analise atentamente cada assertiva e marque o item correto, referente às finalidades do OLTP e OLAP.
a) Somente a assertiva I está correta.
b) Somente a assertiva II está correta.
**c) Somente as assertivas I e II estão corretas.**
d) Somente as assertivas III e IV estão corretas.
e) Somente as assertivas II e III estão corretas.

**Resposta Correta: c)**
**Justificativa:** **OLTP** é o Processamento de Transações em Tempo Real, representando as operações realizadas no SGBD de forma repetitiva e a nível operacional e administrativo (dia a dia). **OLAP** é o Processamento Analítico On-line, focado em criar, gerenciar, analisar e gerar relatórios sobre os dados para sistemas de apoio à decisão (análise complexa).

### Unidade 2 | Seção 2.1 - Modelos de banco de dados

**1. Segundo Coronel e Rob (2011), o modelo conceitual simula uma visão global do banco de dados, disponibilizando uma visão geral de como o banco de dados é na realidade, sendo representado por meio de um esquema do banco. É uma das ferramentas de comunicação entre o pessoal de desenvolvimento do software e o cliente.**
Marque a alternativa que demonstra o nome do modelo que deve ser realizado após a criação do modelo conceitual:
a) Modelo físico.
b) Modelo de entidades.
c) Modelo de requisitos.
**d) Modelo lógico.**
e) Modelo particional.

**Resposta Correta: d)**
**Justificativa:** A sequência do processo de modelagem de dados é: Análise de Requisitos, **Modelo Conceitual**, **Modelo Lógico** e, por fim, Modelo Físico. O Modelo Lógico é a etapa que mapeia o conceito para a criação do banco de dados, transformando o modelo abstrato em um modelo com detalhes de implementação.

**2. Korth, Silberschatz e Sudarshan (2012) descrevem que, na [modelagem física], é utilizada a linguagem Structured Query Language, ou Linguagem de Consulta Estruturada (SQL), que tem como principal objetivo a manipulação dos bancos de dados relacionais e é utilizada para interagir com o usuário e o [SGBD], permitindo inserir, consultar, gerenciar, controlar transações, entre outras opções.**
Analise os itens atentamente e marque a opção correta e que complete a sentença respectivamente:
a) entidade – SGBD.
b) classe – software.
**c) modelagem física – SGBD.**
d) modelagem conceitual – software.
e) modelagem lógica – programa de aplicação.

**Resposta Correta: c)**
**Justificativa:** A linguagem SQL é utilizada na **modelagem física**, que é a última fase do projeto de BD. O SQL manipula bancos de dados relacionais e interage com o usuário e o **SGBD**.

**3. O sucesso de um banco de dados começa muito antes do desenvolvimento do software. Várias etapas devem ser realizadas para atender às expectativas e necessidades do cliente. Uma etapa principal é entender o domínio do problema antes de efetivamente desenvolver o software.**
Analise cuidadosamente os itens e marque a alternativa correta que demonstra o objetivo de “entender o domínio do problema”.
a) Ajuda a equipe de usuários a criar novos atributos para as entidades.
**b) Ajuda a equipe de desenvolvimento a compreender questões relacionadas com a construção do sistema.**
c) É utilizado em último recurso, caso haja problemas no desenvolvimento do software.
d) É utilizado diretamente na modelagem física do banco de dados, com auxílio do SGBD.
e) Serve para estabelecer as restrições de acesso físico ao banco de dados.

**Resposta Correta: b)**
**Justificativa:** O processo de inicialização de um banco de dados de sucesso começa no levantamento e análise de requisitos, onde se deve **estudar o domínio do problema** que o banco de dados deverá solucionar. Entender o domínio do problema é crucial para identificar e criar as regras de negócio e **compreender questões relacionadas com a construção do sistema**.

### Unidade 2 | Seção 2.2 - Modelagem de dados através do modelo entidade-relacionamento

**1. Considerando o conceito de entidade, marque a alternativa correta referente à classificação das entidades em um modelo relacional.**
a) Entidade aguda, entidade inerte, entidade disjuntiva.
b) Entidade firme, entidade fraca, entidade cooperativa.
c) Entidade forte, entidade simples, entidade conjuntiva.
**d) Entidade forte, entidade fraca, entidade associativa.**
e) Entidade composta, entidade simples, entidade subjuntiva.

**Resposta Correta: d)**
**Justificativa:** As fontes citam e definem: **Entidades Fortes** (autônomas), **Entidades Fracas ou Dependentes** (necessitam de outras para existir) e **Entidades Associativas** (existem devido ao tipo de relacionamento).

**2. Segundo Korth, Silberschatz e Sudarshan (2012), um banco de dados é uma coleção de dados inter-relacionados, representando informações sobre um domínio específico. Um banco de dados possui diversos componentes, entre eles podemos citar:**
**I. As tabelas, que são compostas de diversos registros.**
**II. Os registros, que são compostos de diversos campos.**
**III. Os campos, que podem ser classificados como categorias de informação.**
**IV. Os dados, que são os itens armazenados no banco de dados.**
Analise as afirmativas e marque a alternativa correta referente ao banco de dados:
a) Somente a assertiva IV está correta.
b) Somente as assertivas I e III estão corretas.
c) Somente as assertivas II e IV estão corretas.
d) Somente as assertivas II, III e IV estão corretas.
**e) Todas as assertivas estão corretas.**

**Resposta Correta: e)**
**Justificativa:** O BD usa tabelas (entidades). Uma tabela é composta de registros (linhas/tuplas) (I: correta). Registros são formados por campos (atributos/colunas) (II: correta). Campos representam categorias de informação (III: correta). Dados são os valores únicos inseridos na intersecção entre linha e coluna (IV: correta).

**3. A relação entre tabelas se dá através da cardinalidade. A cardinalidade é um número que expressa o comportamento (número de ocorrências) de determinada entidade associada a uma ocorrência da entidade em questão por meio do relacionamento.**
Sobre os relacionamentos entre tabelas, é correto afirmar que:
a) Todo relacionamento entre tabelas é sempre “N para N”.
b) Todo relacionamento entre tabelas é sempre “1 para 1”.
**c) Cada relacionamento deve ser analisado para que seja possível determinar a sua cardinalidade.**
d) Somente o usuário final do banco de dados pode determinar o relacionamento entre uma tabela.
e) Não há diferenças entre os relacionamentos “1 para N” ou “N para N” e, como não há consequências no banco de dados, é melhor sempre deixar N para N.

**Resposta Correta: c)**
**Justificativa:** A cardinalidade pode ser 1:1, 1:N, N:1 ou N:N. O relacionamento deve ser analisado e as repostas dependem do problema a ser modelado.

### Unidade 2 | Seção 2.3 - Diagrama de Entidade-Relacionamento (DER)

**1. Segundo Navathe e Ramez (2005), o objeto básico de um Modelo de Entidade-Relacionamento é uma entidade (ou tabela) que representa alguma coisa do mundo real e que possa ter informações para serem armazenadas. As informações, por sua vez, podem ser classificadas por categorias, sendo esses os campos da entidade ou tabela. Podemos apontar um dos campos como um campo chave da tabela.**
Marque a alternativa correta, que apresenta os principais tipos de chave encontrados em um Modelo de Entidade-Relacionamento.
a) Chave primária e chave composta.
b) Chave composta e chave estrangeira.
c) Chave única e chave mestra.
**d) Chave primária e chave estrangeira.**
e) Chave simplificada e chave composta.

**Resposta Correta: d)**
**Justificativa:** Os tipos de chaves incluem Chave Primária (PK), Chave Concatenada ou Composta, Chave Substituta, Chave Secundária ou Chave Estrangeira (FK). As mais fundamentais e principais para o relacionamento entre tabelas são a **Chave Primária** (identifica o registro) e a **Chave Estrangeira** (relaciona com outra tabela).

**2. A integridade [referencial] em um banco de dados relacional é, na verdade, uma [restrição] para que dados [incorretos] não entrem no banco de dados.**
Marque a alternativa que preenche corretamente as lacunas da afirmativa.
a) substancial – obrigação - imperfeitos.
b) comportamental – alternativa – armazenados.
**c) referencial – restrição - incorretos.**
d) estrutural – migração – incompatíveis.
e) relacional – facilidade – destorcidos.

**Resposta Correta: c)**
**Justificativa:** A **integridade referencial** é uma exigência ou **restrição** que garante que dados **incorretos** (por exemplo, uma cidade inexistente) não entrem no BD, pois a chave estrangeira (FK) deve coincidir com a chave primária (PK) na outra tabela.

**3. Conforme Coronel e Rob (2011), uma chave consiste em um ou mais atributos que determinam outros atributos, ou seja, é um campo que pode identificar outros campos. Existem diversos tipos de chaves.**
Considerando o contexto, avalie as afirmativas a seguir e marque V (Verdadeiro) ou F (Falso):
( **F** ) Uma chave primária é obrigatória nas tabelas, mas existe a possibilidade de deixar o seu valor como nulo, inserindo o valor da chave somente nos momentos de pesquisas no banco de dados.
( **F** ) Uma chave secundária tem como objetivo o conjunto de várias chaves primárias, que juntas poderão formar uma única chave primária.
( **V** ) Uma chave estrangeira é uma chave que, obrigatoriamente, é uma chave primária em outra tabela e deverá se relacionar com a tabela que possui a chave estrangeira.
a) V – F – V.
b) V – V – F.
c) F – V – V.
**d) F – F – V.**
e) F – V – F.

**Resposta Correta: d)**
**Justificativa:**
*   A PK é o identificador único e não pode ser nula (Falso).
*   A chave secundária é usada para fins de recuperação de informação/busca, não para formar a PK (Falso).
*   A FK é sempre uma PK de outra tabela, usada para estabelecer o relacionamento, e seus valores deverão coincidir com a PK correspondente (Verdadeiro).

### Unidade 3 | Seção 3.1 - Modelagem de dados através do modelo entidade-relacionamento usando DER

**1. Conforme afirmam Coronel e Rob (2011), há duas abordagens clássicas tradicionais que podem ser adotadas como estratégia de modelagem em um diagrama de entidade-relacionamentos: top-down (que se inicializa identificando os conjuntos de dados e, então, são definidos os elementos de cada um desses conjuntos) e bottom-up (são identificados os elementos de dados ou seja, os itens, que são agrupados em conjuntos de dados).**
Marque a alternativa correta que identifica o meio termo entre as estratégias de modelagem top-down e bottom-down.
a) middle-down.
b) middleware.
**c) middle-up-down.**
d) up-down-safe.
e) safe-up-down.

**Resposta Correta: c)**
**Justificativa:** As abordagens top-down e bottom-up podem se complementar, e essa abordagem mista é denominada **middle-up-down**.

**2. O ciclo de vida de um software descreve as atividades desde sua concepção até sua última fase, que é a manutenção ou extinção. Em um projeto de banco de dados também há um ciclo de vida que vai determinar o projeto do começo ao fim (neste caso, a manutenção ou a evolução). Destacam-se as seguintes fases do ciclo de vida de um banco de dados:**
I. Estudo dos requisitos do problema e suas restrições, definição dos objetivos, escopo e fronteiras do banco de dados.
II. Criação do projeto conceitual, escolha do SGBD que deverá ser usado, criação do projeto lógico e físico do banco de dados.
III. Instalação do SGBD, criação do banco de dados, carregamento ou conversão dos dados que serão armazenados no banco.
IV. Realização de testes na base de dados para encontrar possíveis erros.
Analisando cuidadosamente as afirmativas apresentadas, é correto o que se afirma em:
a) Apenas as afirmativas II, III e IV estão corretas.
b) Apenas as afirmativas I, III e IV estão corretas.
c) Apenas as afirmativas I, II e III estão corretas.
d) Apenas as afirmativas I, II e IV estão corretas.
**e) As afirmativas I, II, III e IV estão corretas.**

**Resposta Correta: e)**
**Justificativa:** O ciclo de vida de um BD, conforme Coronel e Rob (2011), possui seis fases: **Estudo Inicial** (I), **Projeto do BD** (II), **Implementação e Carga** (III), **Teste e Avaliação** (IV), Operação e Manutenção/Evolução. Portanto, todas as afirmativas listadas estão corretas.

**3. Utilizamos os requisitos para criar os modelos de banco de dados. Geralmente as tabelas são encontradas através dos [substantivos], os campos são as [características] e o relacionamentos são os [verbos] que ligam uma tabela a outra.**
Assinale a alternativa que completa as lacunas corretamente:
a) verbos – alternativas – meios.
b) substantivos – alternativas – tipos.
c) meios – chaves – tipos.
**d) substantivos – características – verbos.**
e) verbos – chaves – substantivos.

**Resposta Correta: d)**
**Justificativa:** Para criar um modelo lógico, são necessárias revisões buscando por: **Tabelas** em **substantivos** (objetos reais); **Campos** em **características** específicas ou adjetivos; e **Relacionamentos** em **verbos** que "ligam" uma tabela a outra.

### Unidade 3 | Seção 3.2 - Modelagem de dados através do modelo entidade-relacionamento usando UML

**1. A Linguagem de Modelagem Unificada ou UML (Unified Modeling Language) é uma ferramenta que auxilia na modelagem de sistemas orientados a objetos.**
Marque a afirmativa correta sobre a UML:
a) Serve para a programação somente de banco de dados.
b) É utilizada como um SGBD pelo fato de permitir a orientação a objetos.
**c) Permite padronizar projetos de sistemas orientados a objetos e de banco de dados.**
d) É uma linguagem de programação orientada a objetos reutilizável.
e) É utilizada somente para a criação do modelo lógico de banco de dados de um SGBD.

**Resposta Correta: c)**
**Justificativa:** A UML tem a finalidade de proporcionar uma **padronização nos projetos de sistemas**, abrangendo tanto aspectos conceituais (regras de negócios) quanto artefatos concretos (como classes e esquemas de banco de dados).

**2. Os atributos ou campos são características de determinadas classes ou entidades. Eles devem ter nomes apropriados ao sentido do que vão armazenar e um tipo de dados que deverá ser declarado, podendo ser: inteiro, caractere, decimal, entre outros.**
Assinale a alternativa correta referente à diferença entre classes e entidades.
a) Uma classe é somente um conjunto de campos, exatamente igual as entidades dos modelos conceituais de banco de dados.
**b) Uma das vantagens da classe é possuir métodos que podem manipular os seus atributos, já as entidades possuem o objetivo de armazenar as informações em seus atributos.**
c) As classes e as entidades possuem métodos que permitem, de forma moderada, a alteração de seus atributos.
d) Uma entidade possui a vantagem de ter métodos que podem ser utilizados para modificar os atributos da própria tabela, algo que em classe ainda não é permitido.
e) Uma vez criados os atributos em classes ou em entidades, não é possível alterar o conteúdo armazenado, isto é, assim que o atributo for criado, recebe um valor e não pode mais ser alterado.

**Resposta Correta: b)**
**Justificativa:** Uma **classe** é dividida em nome, atributos (dados) e **métodos (comportamentos/funções que manipulam os atributos)**. As **entidades** (tabelas) em BD relacional têm como objetivo principal o **armazenamento** e a estrutura dos dados (atributos/campos).

**3. Um exemplo prático da utilização de UML em um diagrama de entidade-relacionamentos é a aplicação da generalização e especialização, que nada mais é do que usar o conceito de herança no modelo lógico do banco de dados.**
Assinale a alternativa correta que mostra os tipos de generalização e especialização.
a) Duplo e Simples.
b) Composto e Unitário.
c) Duplo e Isolado.
**d) Total e Parcial.**
e) Composto e Simples.

**Resposta Correta: d)**
**Justificativa:** Uma estrutura de generalização e especialização pode ser classificada em **Parcial** (quando nem toda ocorrência da entidade generalizada possui uma entidade especializada correspondente) ou **Total** (quando toda ocorrência da entidade generalizada possui uma entidade especializada correspondente).

### Unidade 3 | Seção 3.3 - Ferramentas CASE’s de modelagem do DER

**1. Uma das vantagens de utilizar uma ferramenta CASE para a modelagem de banco de dados é a possibilidade da criação automática de scripts. Este procedimento acelera o trabalho de administrador do banco de dados, e os comandos dos scripts são executados todos juntos, criando tabelas e relacionamentos, além de poderem inserir dados no banco de dados.**
Assinale a alternativa correta sobre a finalidade dos scripts em uma ferramenta CASE para banco de dados.
a) Os scripts são os desenhos das tabelas em uma ferramenta CASE.
b) Os scripts servem exclusivamente para a definição automática das chaves primárias e estrangeiras de uma tabela.
c) O script é a linguagem de programação do SGBD utilizada para criar graficamente o modelo físico do banco de dados.
d) O script é a versão orientada a objetos que pode ou não ser utilizada como alternativa de modelagem de um banco de dados.
**e) Os scripts geram todos os comandos em SQL de criação de tabelas, campos e chaves.**

**Resposta Correta: e)**
**Justificativa:** A geração de códigos automáticos das ferramentas CASEs para banco de dados são conhecidas como **scripts**, que geram **todos os comandos em SQL de criação de tabelas, campos e chaves**, auxiliando na criação física do BD no SGBD.

**2. Utilizar ferramentas CASEs para a modelagem gráfica de banco de dados é muito importante no processo de desenvolvimento de qualquer software. Esta ferramenta permite que os diagramas criados tenham um padrão, o que ajuda no processo de comunicação e na qualidade final do projeto de banco de dados.**
Assinale a alternativa correta que aponta como a ferramenta CASE pode ajudar no processo de modelagem de um banco de dados.
a) Ajuda na programação dos relatórios do banco de dados.
b) Pode ajudar na criação gráfica das páginas HTML que vão apresentar o banco de dados.
c) Deixa disponíveis todas as informações que o usuário armazenará no banco de dados.
**d) Pode ajudar na padronização da modelagem do banco de dados.**
e) Ajuda no processo de coleta de informação, acelerando o mecanismo de acesso aos dados dos clientes.

**Resposta Correta: d)**
**Justificativa:** As ferramentas CASEs auxiliam no desenvolvimento de software e minimizam o tempo. Elas são essenciais para **estabelecer padrões de desenvolvimento** para que todos os envolvidos modelem da mesma forma, ajudando na **padronização da modelagem**.

**3. As ferramentas CASEs (Computer Aided Software Engeneering ou Engenharia de Software Auxiliada por Computador) apresentam uma série de serviços que auxiliam no desenvolvimento de software e podem minimizar o tempo de desenvolvimento do software modelado.**
Assinale a alternativa correta referente às ferramentas CASE’s para modelagem de banco de dados.
a) Todas a ferramentas CASEs são freeware, o principal motivo de ter sido usado nos processos de modelagem de banco de dados.
b) A ferramenta MySQL Workbench, por pertencer à empresa Oracle, é proprietária e não permite a criação de modelagens grátis, além de seus scripts serem exclusivos para o SGBD ORACLE.
**c) Existe a versão freeware, como o MySQL Workbench, e diversas ferramentas online que podem ou não ser freeware, mas a maioria permite a criação de pequenos projetos para a utilização da ferramenta.**
d) As ferramentas online possuem a desvantagem de não gerar scripts, fator que está dificultando o uso destas ferramentas nas modelagens de banco de dados.
e) Todas as ferramentas CASEs são pagas e somente empresas podem utilizar (após cadastro realizado e aprovado), o que dificulta o acesso e o uso deste tipo de ferramenta por parte dos desenvolvedores de software.

**Resposta Correta: c)**
**Justificativa:** Existem ferramentas CASEs gratuitas (**freeware**), como o MySQL Workbench, e também ferramentas online como Draw.IO ou Lucidchart, que geralmente oferecem versões gratuitas com limitações, ideais para pequenos diagramas. A opção (d) é incorreta, pois Lucidchart, por exemplo, gera scripts SQL.

### Unidade 4 | Seção 4.1 - Normalização de dados na computação

**1. Desenvolver um software de qualidade é o objetivo de todo analista de sistemas. Existem diversas técnicas que podem auxiliar a identificar problemas no software projetado. Modelar uma banco de dados não é uma exceção. É necessário realizar refinamentos nas tabelas buscando repetições e erros que passaram despercebidos.**
Marque a alternativa correta que ajuda a melhorar a qualidade do projeto de um banco de dados.
a) Modelagem de dados.
**b) Normalização de dados.**
c) Refinamento de dados.
d) Reciclagem de dados.
e) Estabilização dos dados.

**Resposta Correta: b)**
**Justificativa:** A **normalização** é a técnica utilizada para avaliar e corrigir estruturas e tabelas, tornando mínimas as redundâncias de dados e reduzindo a chance de problemas.

**2. Korth, Silberschatz e Sudarshan (2012) afirmam que as primeiras técnicas de normalização foram criadas em 1972 por Edgar Frank Codd. Após ter dado o primeiro passo, Codd propôs junto com Raymond Boyce, um novo significado, que ficou conhecido como Forma Normal Boyce-Codd (ou FNBC). Normalizar um banco de dados é aplicar regras para todas as tabelas do banco de dados, com os objetivos, além reduzir a redundância, eliminar campos que não dizem respeito à tabela.**
Marque a alternativa correta que demonstra uma vantagem de ter nenhuma ou pouca redundância em um banco de dados.
a) Redução do número de tabelas no banco de dados.
b) Diminuição de chaves estrangeiras nas tabelas de um banco de dados.
**c) Diminuição de dados repetidos deixando o banco de dados mais compacto.**
d) Redução de campos nas tabelas, sendo substituídos por chaves primárias concatenadas.
e) Aumento da quantidade de chaves primárias e estrangeiras para conseguir diminuir a quantidade de relacionamentos entre as tabelas.

**Resposta Correta: c)**
**Justificativa:** Um dos objetivos e vantagens da normalização é a **diminuição de dados repetitivos**, deixando o banco de dados mais compacto. A redundância de dados desperdiça espaço de armazenamento.

**3. Identificar as dependências funcionais nas tabelas é o primeiro passo para saber que precisamos normalizar as tabelas em um banco de dados. A dependência funcional pode ser classificada em: transitiva ou indireta, total ou parcial.**
Assinale a alternativa correta que demonstra o conceito para uma dependência funcional.
a) Uma dependência funcional é uma nova tabela criada para estabelecer a normalização dos dados de uma tabela.
b) Uma dependência funcional é a criação de chaves concatenadas para evitar as redundâncias entre as tabelas relacionadas.
c) Uma dependência funcional é um relacionamento entre dois bancos de dados que podem interferir diretamente na performance do SGBD.
**d) Uma dependência funcional é um relacionamento entre dois ou mais atributos de forma que o valor de um atributo identifique o valor para cada um dos outros atributos, ou seja, um atributo está relacionado a outro.**
e) Uma dependência funcional é um novo campo que deve ser acrescentado na tabela para receber as informações duplicadas, dessa forma, todas as dependências são centralizas nesse novo campo criado.

**Resposta Correta: d)**
**Justificativa:** Dependência funcional é uma restrição entre dois ou mais conjuntos de atributos e ocorre se a cada valor de X estiver associado um e somente um valor de Y (X determina Y).

### Unidade 4 | Seção 4.2 - Transformação 1FN - 2FN

**1. Para realizar a normalização das tabelas, o primeiro passo é analisar os atributos ou campos como também são conhecidos. Muitas vezes um atributo pode esconder diversas informações. Um exemplo é o atributo endereço. O endereço é composto das seguintes informações: nome da rua, número da casa, complemento, bairro. É necessário verificar se essas informações serão mantidas como campos ou se podem até virar uma tabela chamada Endereço.**
O atributo que não é divisível possui um sentido único, e não pode ser dividido em dois outros campos e um conceito de:
a) Atributo monovalorado.
**b) Atributo simples ou atômico.**
c) Atributo multivalorado.
d) Atributo regular.
e) Atributo normal.

**Resposta Correta: b)**
**Justificativa:** Um **Atributo simples ou atômico** é aquele que **não é divisível** e possui um sentido único, como o RG ou CPF.

**2. A Primeira Forma Normal ou simplesmente 1FN possui a seguinte regra: uma tabela estará na Primeira Forma Norma se, e somente se, todos seus atributos forem atômicos, não possuindo grupos repetitivos ou colunas que possuam mais de um valor.**
Marque a alternativa correta que indica um dos primeiros passos para deixar uma tabela na 1FN.
a) Estabelecer os relacionamentos entre as tabelas.
b) Criar no mínimo quinze campos a mais na tabela.
**c) Identificar ou criar uma chave primária na tabela.**
d) Reduzir a quantidade de campos para que fiquem abaixo de vinte campos.
e) Dividir a tabela em no mínimo três tabelas novas.

**Resposta Correta: c)**
**Justificativa:** O primeiro passo para estar na 1FN é **identificar a chave primária da tabela**.

**3. A normalização é o processo de organizar os dados em um banco de dados. Isso inclui criar tabelas e estabelecer relacionamentos entre essas tabelas de acordo com as regras criadas para proteger os dados e para tornar o banco de dados mais flexíveis, eliminando a redundância e dependência inconsistente. Existem várias formas normais, entre as principais estão: 1FN, 2FN, 3FN e a 4FN.**
Marque a alternativa correta que mostra a regra para uma tabela estar na 2FN.
a) Uma tabela está na 2FN se, e somente se, não estiver na 1FN e todas as suas colunas, que não são chaves, não dependam exclusivamente da chave primária.
b) Uma tabela está na 2FN somente se não estiver na 1FN e todas as suas chaves estrangeiras dependam exclusivamente da chave primária.
c) Uma tabela está na 2FN, automaticamente, se estiver na 1FN e não precise de nenhuma chave primária, somente das chaves estrangeiras.
d) Uma tabela está na 2FN, automaticamente, se não estiver na 1FN e não precise de nenhuma chave primária, somente de uma chave estrangeira.
**e) Uma tabela está na 2FN se, e somente se, estiver na 1FN e todas as suas colunas, que não são chaves, dependam exclusivamente da chave primária.**

**Resposta Correta: e)**
**Justificativa:** A Segunda Forma Normal (2FN) exige que a tabela esteja na 1FN **e** que todas as suas colunas que não são chaves dependam **exclusivamente da chave primária** (de toda a chave primária e não só de parte dela).

### Unidade 4 | Seção 4.3 - Transformação 3FN - 4FN

**1. Um dos primeiros passos no processo de normalização é a identificação das dependências funcionais. Uma dependência funcional é um relacionamento entre dois ou mais atributos de forma que o valor de um atributo identifique o valor para cada um dos outros atributos, ou seja, um atributo está relacionado a outro. A dependência funcional consiste em uma restrição entre dois ou mais conjuntos de atributos de uma mesma tabela ou relacionamento.**
Assinale a alternativa correta que determina quando uma tabela está na 3FN.
a) Uma tabela estará na Terceira Forma Normal somente se estiver na Segunda Forma Normal e todos os campos forem dependentes funcionais entre as chaves primárias e estrangeiras.
b) Uma tabela estará na Terceira Forma Normal somente se estiver na Quarta Forma Normal e todos os campos forem independentes da chave primária.
**c) Uma tabela estará na Terceira Forma Normal somente se estiver na Segunda Forma Normal e todos os campos forem independentes e não poderá haver dependências funcionais entre os campos.**
d) Uma tabela estará na Terceira Forma Normal somente se estiver na Primeira Forma Normal e todos os campos forem dependentes da chave primária e da chave estrangeira.
e) Uma tabela estará na Terceira Forma Normal se os campos forem dependentes das chaves estrangeiras da tabela.

**Resposta Correta: c)**
**Justificativa:** Uma tabela está na Terceira Forma Normal (3FN) se estiver na 2FN **e** todos os campos forem independentes, o que significa que **não poderá haver dependências funcionais (transitivas) entre os campos** (ou seja, os campos da tabela precisam depender unicamente da chave primária).

**2. Uma tabela somente estará na 4FN se não existir dependência multivalorada. Quando as dependências multivaloradas ocorrem, as informações inseridas nas tabelas podem ficar se repetindo e, dessa forma, produzem redundâncias na tabela.**
Assinale a alternativa correta que indica como resolver o problema da dependência multivalorada em uma tabela.
a) Para evitar esse tipo de problema é melhor juntar todos os campos, concatenando os dois campos em um único campo, isso agiliza o processo de cadastro das informações.
b) Para evitar esse tipo de problema é melhor dividir a chave primária em duas, tornando a chave numa chave composta, agilizando o armazenamento dos dados.
c) Para evitar esse tipo de problema é melhor criar um campo a mais para cada campo da tabela. Ele servirá de backup para a tabela, acelerando a sua manutenção.
d) Para evitar esse tipo de problema é melhor transformar em chave estrangeira cada campo duplicado, dessa forma, nunca mais haverá repetições na tabela.
**e) Para evitar esse tipo de problema é melhor dividir a tabela, quantas vezes for necessário, a fim de evitar esse tipo de dependência.**

**Resposta Correta: e)**
**Justificativa:** Para resolver a dependência multivalorada e satisfazer a 4FN, é necessário **dividir a tabela** em novas tabelas, uma para cada grupo multivalorado.

**3. De acordo com Navathe e Ramez (2005), para uma tabela estar na Quarta Forma Normal, além de estar na Terceira Forma Normal, precisa que todo campo da tabela seja um campo atômico. Isso permite que repetições desnecessárias sejam evitadas, diminuindo transtornos de manutenção e problemas de redundâncias nos dados inseridos no banco de dados.**
Marque a alternativa que demonstra o conceito correto de um atributo atômico.
a) É um atributo que pode ser divido em mais campos, facilitando a inserção de dados na tabela.
**b) É um atributo que não é divisível, possui um sentido único e não pode ser dividido em dois outros campos.**
c) É um atributo que “turbina” a tabela, aceitando quaisquer tipos de dados. É conhecido como um campo coringa para as tabelas.
d) É o atributo que automaticamente vira a chave primária da tabela, caso tenha dois campos atômicos, teremos duas chaves primárias na tabela.
e) É o atributo que é responsável por relacionar uma tabela com a outra tabela.

**Resposta Correta: b)**
**Justificativa:** Um atributo atômico (ou simples) é aquele que **não é divisível** e possui um sentido único. A 1FN exige que todos os atributos sejam atômicos.
