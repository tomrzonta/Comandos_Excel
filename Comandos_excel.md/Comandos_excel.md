# Comandos_Excel

Trancamento: referência absoluta
Arquivo: aula-trancamento.xlsx

1. O símbolo $ serve para "trancar" a coluna e/ou linha da referência a uma célula
    1. Uma referência trancada não varia ao ser copiada
    2. Para incluir o $ na referência, pode-se digitar manualmente ou então basta teclar F4

# Aula-imagens-formas.xlsx

Tópicos:
1. Todas Colunas de mesmo tamanho: Página Inicial / Formatar / Largura Padrão
2. Inserção de formas: Inserir / Formas
3. Inserção de imagens: Inserir /Imagens
4. As formas aceitam textos que podem ser formatados como um texto normal (fonte, cor e tamanho).
5. Guia Formatar: aparece assim que uma forma ou imagem é selecionada.
6. Alinhamento de formar e imagens:
    1. Selecione as formas e/ou imagens a alinhar (pressione a tecla SHIFT e clique nas formas);
    2. Formatar / Alinhar
7. Selecionar objetos: Página inicial / Localizar e Selecionar / Selecionar objetos
8. Transformar a figura em “JPG” ou “PNG”: recortar e colar especial

# Aula-hiperlink.xlsx

Tópicos:
1. É possível inserir hiperlinks em: FORMAS, IMAGENS, CÉLULAS
2. Para criação dos links (ou hiperlinks):
    1. Clicar na forma que receberá o hiperlink e pressionar CTRL+K (ou então na Faixa de Opções Inserir / Link).
    2. Selecionar a opção “Colocar neste documento”.
    3. Selecionar a planilha pertinente.
3.  Dica: Ao copiar uma célula com link para outra célula, o link também é copiado.

# Aula-autopreenchimento.xlsx

Tópicos:
1.  Preenchimento usando a combinação Mouse + Teclado (mais rápido):
    1. Data: digitar a primeira data e arrastar até o mês final desejado (vertical ou horizontalmente).
    2. Valor sequencial: digitar o primeiro número, pressionar a tecla “CTRL” e arrastar até o final desejado.
    3. Valor incremental: digitar o primeiro número, digitar o segundo número, selecionar os dois e arrastar até o final desejado (exemplos de incrementos possíveis: 1,3,....11 ou 2,4,...10).
2.  Preenchimento usando a Faixa de Opções: Página Inicial / Preencher / Série é ideal quando se quer preencher um grande intervalo no qual o “arraste” do mouse fica mais trabalhoso. Exemplos:
    1. Série de números de registros entre 1 e 200
    2.  Diário entre 01/01/2018 e 30/12/2018 (interessante: "Dia da semana")
    3. Crescimento (fator multiplicador: bom para progressão geométrica)
3.  Listas personalizadas: Arquivo / Opções / Avançado / Geral / Editar Listas Personalizadas

# Aaula-formatação-condicional.xlsx

Tópicos:
1.  Acesso: Página Inicial / Formatação Condicional / Gerenciar Regras
2.  Formatação condicional de cores:
    1. Selecionar a célula (ou intervalo de células que receberão a formatação condicional).
    2. Acessar Página Inicial / Formatação Condicional / Gerenciar Regras / Nova Regra.
    3. Selecionar a regra “Formatar apenas células que contenham”.
    4. Escolher uma das regras: valor da célula, texto específico, datas que ocorrem etc.
    5. Criar a regra: no exemplo a regra será “valor da célula” é <= 100.
    6. Editar as formatações desejadas: fonte (cor, tamanho, negrito, itálico etc.), borda e preenchimento.
    7. Para criar nova regra na mesma célula ou intervalo de células deve-se proceder conforme os passos
anteriores.
2. Formatação condicional de ícones ou barras:
    1. Selecionar a célula (ou intervalo de células que receberão a formatação condicional).
    2. Acessar Página Inicial / Formatação Condicional / Gerenciar Regras / Nova Regra.
    3. Selecionar Estilo de Formatação “Conjunto de Ícones”.
    4. Selecionar o “Estilo do Ícone” (conforme a necessidade de informação que o ícone deve transmitir).
    5. Marcar a opção “Mostrar Somente Ícone” (melhora a estética).
    6. Marcar a opção “Ordem Inversa de Ícones” (usada no exemplo, pois nesse caso, quanto maior a média de estoque “pior” será – sinal vermelho).
    7. Editar as regras: as regras são construídas conforme o valor digitado que pode ser número, percentagem ou ainda uma formula.

# Aula-comentários.xlsx
1. Para inserir um comentário:
    1. Acessar a Faixa de Opções “Revisão” e clicar “Novo Comentário”.
    2. Esses comentários são acionados somente quando o mouse “passa/está” sobre a célula.
    3. Quando a célula está selecionada o comentário não é acionado.
2. Para inserir uma mensagem de informação tipo comentário quando a célula é selecionada:
    1. Selecione a célula onde se deseja inserir a mensagem.
    2. Acessar a Faixa de Opções “Dados” e clicar no comando “Validação de Dados”.
    3. Selecionar a aba “Mensagem de Entrada”.
    4. Marcar a opção “Mostrar mensagem de entrada ao selecionar a célula”.
    5. Digitar a mensagem no campo “Mensagem de Entrada”.
    6. Esse recurso de validação será melhor estudado na próxima aula.

# Aula-validação.xlsx
1.  Para inserir uma validação acessar Faixa de Opções “Dados / Validação de Dados”.
2.  Os critérios de validação de uma célula (ou intervalo de células) podem ser baseados em:
    1. Números inteiros e decimais.
    2. Listas com nomes (digitado na própria caixa de diálogo ou obtido a partir de outro intervalo de células.
    3. Comprimento de texto (número de caracteres).
    4. Data e hora.
    5. Personalizado, usando fórmulas (tópico avançado).
3. Quando o usuário inserir dado que não observa o critério de validação é emitido um alerta de erro que pode ser de três tipos (Estilos):
    1. Parar: avisa e impede a inserção do dado incorreto.
    2. Aviso: avisa e permite que o usuário escolha continuar com a inserção do dado incorreto.
    3. Informações: apenas avisa, mas mantém a inserção do dado incorreto.

# Aula-congelamento-proteção.xlsx
1. Para congelar um painel acessar Faixa de Opções “Exibir / Congelar Painéis”.
2. Há três opções de congelamento de painéis:
    1. Congelar Painéis: congela o que está à esquerda e acima do cursor.
    2. Congelar Linha Superior: congela a 1ª linha.
    3. Congelar Primeira Coluna: congela a 1ª coluna.

# Aula-congelamento-proteção.xlsx
1. Para proteger uma planilha (ou células):
    1. Selecionar as células que não serão bloqueadas/protegidas (por padrão todas as células de uma planilha são bloqueadas).
    2. Acessar a Faixa de Opções: Página Inicial / Formatar / Formatar Células / Proteção
2.  Desmarcar a opção “Bloqueadas”.
    1. Acessar a Faixa de Opções “Revisão / Proteger”.
    2. Se desejar senha inserir uma senha.
    3. Se desejar que apenas as células desbloqueadas sejam selecionadas, desmarcar a opção "Selecionar
    células bloqueadas".

# Aula-impressão.xlsx
1. Para visualizar a impressão: Arquivo / Imprimir
    1. Dica: repare na linha pontilhada que aparece na planilha
2. Para selecionar a área de impressão:
    1. Selecione as células desejadas
    2. Faixa de opções: Layout de Página / Área de impressão / Definir área de impressão
3. Para ajustar a área de impressão à página:
    1. Arquivo / Imprimir / (opções de dimensionamento)
4. Configurações de página:
    1. Personalizar cabeçalho / rodapé
    2. Incluir data, número de página, etc.
5. Outras opções:
    1. Orientação
    2. Tipo de papel
    3. Margens
    4. Propriedades da impressora

