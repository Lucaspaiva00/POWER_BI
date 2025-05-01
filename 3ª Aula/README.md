# 3ª Aula
- Link para a sala: https://meet.google.com/ggf-gboc-xsy
### Conhecimentos:
- DAX - (Calculate e Sum)

- Conteúdo passado:
- Total Vendas = SUM(base_mercearia_com_erros[TotalVenda])
- Total Quantidade = SUM(base_mercearia_com_erros[Quantidade] )
- TOTAL VENDASs = SUMX(
    base_mercearia_com_erros,
IF(base_mercearia_com_erros[TotalVenda] > 0, base_mercearia_com_erros[TotalVenda],0))
