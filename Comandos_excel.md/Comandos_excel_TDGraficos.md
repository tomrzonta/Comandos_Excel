# Aula-tabela-dinamica.xlsx

Discussão inicial sobre tabela dinâmica:

1. Aplicabilidade:
    1. Permite manipular bases de dados para se extrair informações que sejam gerencialmente
    interessantes.
    2. É uma forma para gerar relatórios de forma automática e mais fácil que com fórmulas complexas.
2. É possível gerar tabela dinâmica a partir de intervalo de dados, mas é melhor fazer a partir de uma tabela, pois é possível atualizar a tabela dinâmica automaticamente de forma mais fácil.
3. Podem ser criadas diversas tabelas dinâmicas para uma mesma base de dados.

Relatório para esta aula: Valor de vendas agrupado por loja, gênero e categoria

Checklist:

1. Inserir -> Tabela
    1. Renomear a tabela: TBVendas
2. Inserir -> Tabela Dinâmica
    1. Fonte de dados: TBVendas
    2. Onde será colocada: Nova Planilha
3. Estrutura desejada:
    1. Linha: LOJA, GENERO
    2. Coluna: CATEGORIA
    3. Valores: Soma de VALOR
    4. Filtros: CATEGORIA, LOJA, FORMA DE PAGAMENTO
4. Design -> Escolher estilo
5. Analisar -> Atualizar

# Aula-tabela-dinamica-criada.xlsx

Checklist:

1. Incluir um título
2. Analisar -> Inserir Segmentação de Dados
    1. LOJA (2 colunas)
    2. CATEGORIA (2 colunas)
    3. FORMA DE PAGAMENTO
3. Formatar largura de colunas:
    1. Colocar as colunas de valores com mesma largura
    2. Analisar -> Tabela dinâmica -> Opções -> Ajustar automaticamente a largura... (DESMARCAR)

# Aula-tabela-dinamica-criada.xlsx

Checklist:

1. Design -> Totais gerais
2. Para mostrar novamente a lista de campos para edição: Analisar -> Mostrar
3. Botão direito em um valor -> Configuração do Campo de Valor -> Formato do Número
4. Botão direito em um valor -> Configuração do Campo de Valor -> Resumir valores por...
5. Botão direito em um valor -> Configuração do Campo de Valor -> Mostrar valores como...
    1. Exemplo: % do Total de Linhas / % do Total de Colunas
    2. Nota: observe a linha de totais

# Aula-tabela-dinamica-criada.xlsx

Relatório para esta aula: Valor e volume de vendas agrupados por categoria, loja e gênero

Checklist:

1. Estrutura desejada:
    1. Linha: CATEGORIA / LOJA
    2. Coluna: GÊNERO
    3. Valores: Soma de VALOR / Soma de VOLUME
2. Design -> Escolher estilo
3. Renomear os rótulos de colunas: VENDAS (UNIDADES) e VENDAS (R$)
4. Análise -> Campos, Itens e Conjuntos -> Campo calculado
    1. Nome: MÉDIA (R$ / UNIDADES)
    2. Fórmula: = VALOR / VOLUME
5. Nota: repare nas conclusões que podem ser tiradas. Exemplo: As vendas da categoria X possui maior valor
agregado para homens ou para mulheres?

# Aula-grafico-dinamico.xlsx

Checklist:

1. Criar tabela dinâmica:
    1. Linha: ANO, MES
    2. Coluna: VENDEDOR
    3. Valores: VALOR VENDIDO
    4. Analisar -> Tabela dinâmica -> Nome: TDVendas
2. Criar gráfico dinâmico. Tipo LINHA
    1. Retirar botões de filtro do gráfico: Analisar -> Botões de Campos
    2. Retirar contorno do gráfico
3. Inserir Segmentação de Dados:
    1. Vendedor
    2. Ano

# aula-grafico-dinamico2.xlsx

Checklist:

1. Criar tabela dinâmica:
    1. Linha: ANO
    2. Coluna: VENDEDOR
    3. Valores: Negócios Perdidos (calculado): Clientes visitados - Negócios fechados
    4. Analisar -> Tabela dinâmica -> Nome: TDVendasPerdidas
2. Criar gráfico dinâmico. Tipo BARRA
    1. Retirar botões de filtro do gráfico: Analisar -> Botões de Campos
    2. Retirar contorno e preenchimento do gráfico
    3. Design -> Adicionar Elemento de Gráfico -> Rótulo de dados -> Extremidade externa
3. Referenciar a nova tabela na segmentação de dados:
    1. Botão direito -> Conexões de relatório

# aula-grafico-dinamico3.xlsx

Checklist:

1. Criar tabela dinâmica:
    1. Linha: ANO
    2. Coluna: VENDEDOR
    3. Valores: Valor médio (calculado): Valor vendido / Negócios fechados
    4. Analisar -> Tabela dinâmica -> Nome: TDValorMedio
2. Criar gráfico dinâmico. Tipo COLUNA
    1. Retirar botões de filtro do gráfico: Analisar -> Botões de Campos
    2. Retirar contorno e preenchimento do gráfico
    3. Design -> Adicionar Elemento de Gráfico -> Rótulo de dados -> Extremidade externa
3. Referenciar a nova tabela na segmentação de dados:
    1. Botão direito -> Conexões de relatório