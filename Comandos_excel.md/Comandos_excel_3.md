# Aula-filtros.xlsx
1. Usos do filtro (ver arquivo): Criar RELATÓRIOS GERENCIAIS conforme a necessidade do tomador de decisão
a partir de uma base extensa de dados, economizando tempo de preparação.
2. Dica: No Excel, intervalo de dados é diferente de tabela de dados, pois essa última tem mais recursos (como será visto em aula específica nesse capítulo).
3. Para criar um filtro a partir de um intervalo de dados basta selecionar qualquer célula nesse intervalo de dados e clicar em “Filtro” disponível na Página “Dados”
4. Também pode-se usar as teclas de atalho CTRL+SHIFT+L para criar um filtro.
5. Com o filtro acionado é possível selecionar “partes” do intervalo de dados de acordo com critérios como:
    1. Datas (dias, meses ou anos) por meio de filtros tais como: “Antes de...”, “Depois de...” ou “Está entre...”.
    2. Texto por meio de filtros tais como: “É igual a...”, “Começa com...” ou “Contém...”.
    3. Número por meio de filtros tais como: “É maior do que...”, “É menor do que...” ou “É diferente de...”.
    4. Cor por meio de filtros que considerem as cores da fonte ou de preenchimento das células.

# Aula-classificação.xlsx
1. Para acionar a classificação clicar no comando “Classificar” disponível na faixa de opções “Dados”.
2. Nessa faixa de opções há três comandos de classificação: “do maior para o menor” e “do menor para o maior” que ordenam automaticamente e “classificar” que abre caixa de diálogo.
3. É possível classificar o intervalo de dados que possui filtro.
4. É possível efetuar mais de uma classificação simultaneamente (mais de uma coluna de dados) denominada nível de classificação.

# Aula-filtro-avançado.xlsx
1. Principal vantagem de usar o filtro avançado: está relacionada a ação de colar o resultado, pois permite trabalhar com esses dados sem alterar os dados de origem.
2. Para acionar o filtro avançado: Dados -> Avançado
3. Antes de iniciar o filtro avançado é necessário criar em qualquer parte da mesma planilha (ou de outra planilha) um intervalo com no mínimo duas linhas, sendo a primeira o cabeçalho com texto idêntico ao do cabeçalho do intervalo de dados (pode ser parte do cabeçalho, mas o texto de cada parte deve ser idêntico).
4. Para colar o resultado da filtragem na própria planilha:
    1. Intervalo da lista: ao iniciar o filtro avançado se qualquer célula do intervalo de dados que representa a lista estiver selecionada esse campo já estará preenchido.
    2. Intervalo de critérios: selecionar o intervalo criado na mesma planilha para servir de critérios.
    3. Marcar a opção “Copiar para outro local”.
    4. Copiar para: informar uma célula na mesma planilha que receberá o resultado da filtragem.
5. Para colar o resultado da filtragem em outra planilha:
    1. Ativar a planilha que receberá o resultado da filtragem: o comando filtro avançado será executado a partir dela.
    2. Intervalo da lista: acessar a planilha que contém o intervalo de dados (lista) e selecioná-lo totalmente (use
    3. conjunto de teclas de atalho  selecione a 1ª célula da lista e pressione ctrl + shift + ↓ e em seguida →).
    4. Intervalo de critérios: selecionar o intervalo criado na planilha que receberá o resultado da filtragem para servir de critérios.
    5. Marcar a opção “Copiar para outro local”.
    6. Copiar para: informar uma célula na planilha que receberá o resultado da filtragem.
6. Nas células que servem de critério de filtragem podem ser usados caracteres especiais de filtragem:
    1. O asterisco (*) permite a busca genérica. Por exemplo: um campo cujo cabeçalho seja o nome do
empregado ao se digitar “Pe*” o filtro avançado retornará todo empregado cujo nome começa com “Pe”.
    2. Os sinais de comparação (<, >, >=, <=, <>) podem ser usados para filtragem de números.
7. Se houver mais de uma linha abaixo do cabeçalho do intervalo de critérios terá o efeito do operador “Ou” (UNIÃO) na filtragem.
8.  Se houver duas vezes a mesma coluna do cabeçalho do intervalo de critérios terá o efeito do operador “E” (INTERSECÇÃO) na filtragem.

# Aula-tabela.xlsx
1. Vantagem da tabela: automatização de fórmulas e inserção de dados
2. Para transformar um intervalo de dados em uma tabela:
    1. Selecione qualquer célula dentro do intervalo de dados.
    2. Clique na Faixa de Opções “Inserir” e depois clique em “Tabela” ou basta pressionar CTRL + Alt + T.
3. Aba DESIGN:
    1. Mostrar/ocultar a linha de cabeçalho.
    2. Inserir e retirar as cores alternadas (tiras) nas linhas e nas colunas.
    3. Inserir ou ocultar linhas de Totais: posicionada ao final da tabela permite cálculos por coluna tais como máximo, mínimo, média e soma.
    4. Renomear a tabela (é importante dar um nome significativo).
    5. Remover registros duplicados. Cuidado! Dependendo da tabela haverá registros duplicados que serão
necessários. A exclusão de registros pode ser desfeita logo em seguida à exclusão acidental, pressionando
CTRL + Z (desfazer).
   6. Para que a tabela volte a ser um intervalo de dados basta clicar em “Converter em intervalo”.

4. Inserção de informações:
    1. Para inserir um novo registro na tabela basta posicionar o cursor na última coluna do último registro e pressionar a tecla “Tab”. Também é possível incorporar um novo registro bastando digitar na primeira coluna da primeira linha após o último registro.
    2. Para inserir vários registros apontar o mouse na última coluna do último registro, o cursor muda de formato: clicar e arrastar a quantidade de linhas (ou colunas) desejada.
    3. A inserção de fórmula em um registro de tabela “propaga” essa fórmula para todos os registros da tabela automaticamente, inclusive quando novos registros são inseridos.
5. Referência aos dados da tabela:
    1. Exemplo de referência à coluna inteira: =MEDIA(TabelaVendas[VALOR])
    2. Exemplo de referência ao valor do registro (na mesma linha): =[@VALOR]/[@VOLUME]