# Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX

## Objetivo: 
A partir da base "financials", que a Microsoft fornece como base de exemplos, fazer uma modelagem que adeque ao 
modelo estrela.
### Etapas:
A primeira etapa foi duplicar a tabela principal e tratar para que fosse dado formato as dimenções.

![Dimensões](https://github.com/jemersonsoares/Modelando-um-Dashboard-de-E-commerce-com-Power-BI-Utilizando-F-rmulas-DAX/blob/main/duplicando.png)
 
Em seguida, com as devidas transformações e adequações, obtivemos o modelo abaixo que, devido as ligações, se asemelha ao modelo floco de neve (snowflake)

![Dimensões](https://github.com/jemersonsoares/Modelando-um-Dashboard-de-E-commerce-com-Power-BI-Utilizando-F-rmulas-DAX/blob/main/Modelando%20um%20Dashboard%20de%20E-commerce%20com%20Power%20BI%20Utilizando%20F%C3%B3rmulas%20DAX.png)


Particularmente, não vejo necessidade de termos na dimensão dProduto as tabelas descontos e detalhes de produtos. Prefiro deixar os descontos na tabela fato e complementar os detalhes dos produtos diretamente
na dProduto, deixando o esquema estrela.

Quando a dimensão dCalendário, prefetir abordar uma criação dinâmica, ou seja, enquanto ocorrer entradas de dados, o proprio power query se encarregará de extrair a data mínima  e e máxima para compor o modelo de datas.

![Dimensões](https://github.com/jemersonsoares/Modelando-um-Dashboard-de-E-commerce-com-Power-BI-Utilizando-F-rmulas-DAX/blob/main/dCalendario.png)



Para mais detalhes, execute o projeto e se ocorrer dúvidas, por gentileza, me contate pelas redes.
