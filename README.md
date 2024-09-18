**Roteiro:**  Me parece razoável partir do pressuposto de que o baixo interesse (por que? estudar sobre a origem/passado do curso no país) pelo curso bacharelado em estatística no Brasil leve a outros agravantes como o número limitado de faculdades/universidades que oferecem o curso tanto pública e privada (mas mais rara em instituições privadas o que indica que pela baixa demanda de alunos gere baixa oferta de cursos justo nas particulares onde não seria rentável?).

O que por sua vez não explica a facilidade de se entrar no curso quando comparada com outros cursos similares (ou explica?).

A multidisciplinaridade poderia ser um dos fatores que contribui para a baixa adesão já que o curso é bem "genérico" no sentido de que não possui ou pelo menos não possuia um direcionamento claro (apesar de que com o passar dos anos o curso vem aos poucos virando sinônimo de data science) fazendo com que não atraia atenção nem das grandes mídias nem das crianças e adolescentes.

por exemplo, um advogado estuda direito, ele precisa fazer a prova da OAB para atuar, a possibilidade de focar em concursos na área é também uma possibilidade que é de certa forma de senso comum entre as pessoas.  

agora, e um estatístico? você saberia responder onde dormem, o que estudam ou para quê servem?

(fazer paralelo com análise e desenvolvimento de sistemas (ADS) que parece ter explodido em popularidade nos últimos anos; possíveis motivos são alta divulgação por influenciadores pela área da programação e junto a isso a grande oferta de vagas em diversas faculdades públicas e privadas (mas principalmente privadas) e não só baixo custo e portanto facilidade de ingressar mas também pela possibilidade de tecnólogo o que diminui de 4 (duração média de um curso tradicional) para 2 anos para concluir o curso, ou seja, vemos que as pessoas querem maior rapidez para apanhar o canudo e creem que quanto mais rápido melhor pois irão se inserir logo no mercado de trabalho porém isso não é verdade(né?).

Poderia ser pela dificuldade do curso? A princípio... não já que outros cursos muito mais populares como ciência da computação possui nível muito similar de dificuldade.

Bom, temos que o número de faculdades que oferecem o curso são baixas e sabemos também que as notas de corte são menores que de outros cursos correlatos. O que me leva a crer que seja simplesmente um problema de baixa procura pelo curso. Mas então, por que isso acontece?

---
Para acessar os dados sobre concluintes de cursos de graduação, como o bacharelado em Estatística, pelo site do *INEP*, siga os passos abaixo:

## Passo 1: Acessar o site do INEP
* Vá até o site oficial do INEP: www.gov.br/inep.

## Passo 2: Navegar até o Censo da Educação Superior
1. No topo da página, passe o cursor sobre a aba "**Estatísticas**".
2. No menu suspenso, clique em "**Censo da Educação Superior**".

## Passo 3: Acessar as Bases de Dados e Relatórios
1. Dentro da página do **Censo da Educação Superior**, você verá a opção de acessar "**Microdados**" ou "**Relatórios e Sinopses Estatísticas**".

Para uma análise mais detalhada e customizada, os **microdados** serão mais úteis, pois contêm informações detalhadas sobre os concluintes de todos os cursos. Se preferir um relatório já formatado, as **Sinopses Estatísticas** podem te atender, mas elas não vão oferecer detalhamento por curso específico.

2. Para obter os **microdados**:
   * Clique na aba de **Microdados**.
   * Baixe o arquivo do ano mais recente do **Censo da Educação Superior**.
  
## Passo 4: Extrair Informações dos Microdados
1. O arquivo de microdados geralmente vem em formato .*csv* ou similar, compactado em .*zip*. Descompacte o arquivo.
2. Os microdados incluem diferentes categorias, como "matrículas", "concluintes", "cursos", entre outros. Você vai querer focar nos arquivos que contêm dados sobre **concluintes**.

## Passo 5: Filtrar pelos Dados de Concluintes do Curso de Estatística
1. Após baixar os dados, abra o arquivo referente a **concluintes** em uma planilha (como Excel) ou em softwares estatísticos (como R, Power BI).
2. Aplique filtros para encontrar o **curso de Estatística** (o nome oficial do curso pode variar, mas geralmente é "Bacharelado em Estatística").
3. Selecione o ano desejado e extraia os números de concluintes.

## Exemplos de Dados
Os microdados costumam fornecer informações como:
   * Quantidade de concluintes por ano.
   * Distribuição por região, instituição, sexo, idade, entre outros fatores.

Isso permitirá que você faça uma análise aprofundada sobre a baixa taxa de concluintes no curso de Estatística, identificando possíveis tendências e fatores regionais.

---
Para descobrir quantas universidades públicas e privadas oferecem o curso de Bacharelado em Estatística no Brasil, você pode seguir os passos abaixo:

## Opção 1: Utilizar o Sistema e-MEC
O **e-MEC** é o sistema de regulação e supervisão do Ministério da Educação (MEC), e permite consultar todas as instituições de ensino superior credenciadas e os cursos que oferecem.

**Passo a Passo:**
1. Acesse o site do e-MEC: *sistema e-MEC*.
2. No menu, clique em **Consulta Avançada**.
3. Em "Curso", digite "**Estatística**".
4. No campo "Modalidade", selecione "**Presencial**" (ou deixe em branco, se também quiser incluir cursos a distância).
5. Em "Grau Acadêmico", selecione "**Bacharelado**".
6. Para filtrar por **instituições públicas ou privadas**, no campo "Categoria Administrativa", escolha entre:
   * **Pública Federal**, **Pública Estadual**, ou **Pública Municipal** para instituições públicas.
   * **Privada** para as instituições particulares.
7. Clique em **Pesquisar**.

O sistema exibirá uma lista de todas as universidades e faculdades que oferecem o curso de Bacharelado em Estatística no Brasil, com suas respectivas modalidades (presencial ou a distância) e categorias administrativas (pública ou privada).

## Opção 2: Usar os Microdados do Censo da Educação Superior (INEP)
Além de consultar diretamente no e-MEC, outra abordagem seria usar os **microdados** do **Censo da Educação Superior** (disponíveis no INEP, como mencionado anteriormente). Dentro desses microdados, há tabelas com informações sobre os cursos e as instituições que os oferecem.

**Passo a Passo:**
1. Baixe os **microdados do Censo da Educação Superior** no site do INEP, conforme expliquei anteriormente.
2. Dentro dos arquivos de microdados, procure o arquivo que contém informações sobre cursos.
3. Filtre o curso "**Bacharelado em Estatística**".
4. A partir desses dados, você poderá contar quantas instituições de ensino (sejam públicas ou privadas) oferecem o curso no Brasil.

Essa abordagem permite identificar todas as instituições com detalhes mais granulares, como sua distribuição geográfica.

Essas duas ferramentas são excelentes para encontrar e organizar as informações sobre as universidades que oferecem o curso de Estatística.
