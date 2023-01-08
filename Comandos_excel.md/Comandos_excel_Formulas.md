# Aula-fórmulas-texto.xlsx

1. Fórmulas de “Texto” atuam sobre os caracteres textuais do Excel.
2. Há diversas fórmulas de manipulação de texto disponíveis na Faixa de Opções “Fórmulas / Texto”.
3. Concatenar( ): Faz a junção de textos e/ou números localizados em células diferentes.
4. Maiúscula( ): Transforma para caixa alta todos os caracteres de um texto.
5. Minúscula( ): Transforma para caixa baixa todos os caracteres de um texto.
6. Pri.Maiúscula( ): Transforma em caixa alta o primeiro caractere de cada palavra em um texto.
7. Texto( ): Formata um texto de acordo com o código de formatação desejado. Alguns desses códigos de formatação são apresentados a seguir:
    1. O código R$#.##0,00 formata o número 1245 para R$ 1.245,00
    2. O código 0000 formata o número 234 para 0234
    3. O código 0,00% formata o número 0,283 para 28,30%
    4. Exemplos de códigos para datas: dd/mm/aaaa, dd/mm/aa, dddd, mmmm

# aula-fórmulas-data-hora.xlsx
1. Fórmulas de “Data e hora” atuam sobre o tempo no Excel.
2. Há diversas fórmulas de manipulação de texto disponíveis na Faixa de Opções “Fórmulas / Data e hora”.
3. Hoje( ): apresenta a data atual do sistema no formato “dia da semana, dd/mm/aaaa”.
4. Ano( ): extrai o ano de uma data. No exemplo Ano(“25/12/2018) = 2018.
5. Mês( ): extrai o mês de uma data. No exemplo Mês(“25/12/2018) = 12.
6. Dia( ): extrai o mês de uma data. No exemplo Dia(“25/12/2018) = 25.
7. DiaTrabalhoTotal( ): apresenta o número de dias úteis entre duas datas.

# Lógica (E, Ou; Se)

Teoria - Expressões lógicas
Expressão lógica:
CONDIÇÕES -> VERDADEIRO/FALSO
PRINCIPAIS OPERADORES LÓGICOS: "E", "OU"

1. ## Função E:
=E(condição1; condição2; ...)
2. ## Função OU:
=OU(condição1; condição2; ...)
3. ## Função SE:
=SE(teste_lógico; valor_se_verdadeiro; valor_se_falso)
=SE( ; ; SE( ; ; ))

# aula-formulas-matematica.xlsx
1. Faixas de Opções:
    1. Fórmulas / Matemática e Trigonometria
    2. Fórmulas / Mais Funções / Estatística
2. SOMA: soma os números constantes em um intervalo de células.
3. MÉDIA: calcula a média aritmética dos valores contidos nas células de um intervalo (se uma célula do intervalo
estiver vazia, não é considerada no cálculo da média, mas se tiver o número 0 – zero – será considerada).
4. MÁXIMO: maior valor
5. MAIOR: k-ésimo maior valor
6. MÍNIMO: menor valor
7. MENOR: k-ésimo menor valor
8. CONT.NÚM: conta o número de células de um intervalo que possui algum valor numérico.
9. CONT.VALORES: conta o número de células de um intervalo que não estão vazias (possui texto, data, número etc.).
10. CONTAR.VAZIO: conta o número de células de um intervalo que estão vazias