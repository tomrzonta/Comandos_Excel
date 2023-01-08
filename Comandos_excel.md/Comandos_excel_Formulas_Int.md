# Aula-cont-se.xlsx

1. Aplicabilidade: determinar a quantidade de valores que atendem a um critério
2. Disponíveis na Guia “Fórmulas”, item “Mais Funções”, opção “Estatística”.
3. CONT.SE: um único critério é avaliado.
4. CONT.SE(intervalo;critério)
## EXEMPLO:
=CONT.SE(TBEstoque[GRUPO];CONT.SE!A6)

# Aula-cont-se.xlsx

1. Aplicabilidade: determinar a quantidade de valores que atendem a um ou mais critérios
2. Disponíveis na Guia “Fórmulas”, item “Mais Funções”, opção “Estatística”.
3. CONT.SES: dois ou mais critérios são avaliados simultaneamente.
4. CONT.SES(intervalo_critérios1;critérios1;intervalo_critérios2;critérios2...)
5. CONT.SES aceita até 127 critérios simultâneos.
## EXEMPLO:
=CONT.SES(TBEstoque[GRUPO];E6;TBEstoque[QTDE.];"<"&F6)

# Aula-soma-se.xlsx
1. Aplicabilidade: obter a soma dos valores de uma fonte de dados, baseada em uma condição aplicada a outra fonte de dados equivalente
2. Disponíveis na Guia “Fórmulas”, item “Matemática e Trigonometria”.
3. SOMASE(intervalo;critérios;intervalo_soma)
## EXEMPLO:
=SOMASE(tbvendas[LOJA];B7;tbvendas[VOLUME])


# Aula-soma-ses.xlsx
1. Aplicabilidade: similar ao SOMASE, porém podendo ter mais de um critério
2. Disponíveis na Guia “Fórmulas”, item “Matemática e Trigonometria”.
3. SOMASES(intervalo_soma;intervalo_critério1;critério1;intervalo_critério2;critério2;...)
4. SOMASES aceita até 127 critérios simultâneos.
## EXEMPLO:
=SOMASES(tbvendas[VALOR];tbvendas[LOJA];B7;tbvendas[CATEGORIA];$C$12;tbvendas[GÊNERO];$C$13)

