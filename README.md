# Coffee Bucks Finances 🍵

## Cenário e objetivo

Este projeto de Business Intelligence (BI) tem como objetivo analisar a saúde financeira da cafeteria Coffee Bucks, utilizando dados para identificar oportunidades de melhoria e apoiar a tomada de decisão.
O objetivo
- Avaliar receitas, despesas e lucros.
- Analisar custos fixos e variáveis.
- Detectar possíveis gargalos financeiros.
- Gerar recomendações para melhorar a performance financeira.

## Sobre o negócio

A Coffee Bucks é uma empresa especializada na venda de cafés premium em grãos selecionados de diversas regiões, com operações em São Paulo, Florianópolis e Rio de Janeiro. Além de atender diretamente os **consumidores finais**, a Coffee Bucks também busca expandir seus serviços para o setor **corporativo**. Para isso, a empresa deverá utilizar os insights obtidos a partir dos dados financeiros, permitindo a personalização de soluções corporativas e uma **melhor alocação de recursos** para melhor direcionamento do negócio.

Para auxiliar a empresa a entender como seus recursos estão sendo utilizados, foi desenvolvido um relatório utilizando Power BI que monitora indicadores, como, receita, margem de contribuição, despesas e resultado líquido, além de comparar com os valores planejados e orçados. Com ajuda de elementos visuais, é possível identificar rapidamente quais áreas necessitam de atenção, melhorando a rapidez para ação, além de ir no **ponto crucial do processo**.

Para ver o painel acesse o link: [Link do Painel](https://app.powerbi.com/view?r=eyJrIjoiMTNjMWE4YzUtZTdhZC00MTEzLTk2NTMtY2Y3M2NiNjAzNWU0IiwidCI6ImIzYWUzNDliLThjZTktNDc2Yi05ZWJlLTY1Y2NhNzdlZDA4ZiJ9)

## Ferramentas Utilizadas

- Power BI ➡️ Conexão com a fonte de dados, tratamentos e visualização
- Fonte de dados: Arquivos.csv

## Principais Indicadores

- Comparativo entre períodos (Realizado Vs Mês anterior, Realizado vs Ano Anterior)
- Evolução do realizado vs Orçado/Previsto Mensal
- Análise de custos operacionais ( Planos de contas detalhados )

## Análises e Recomendações

![Principais Despesas](TopDespesas.png)

Como um ambiente corporativo é dinâmico e de rápidas mudanças, o foco aqui é no último período disponível, visto que são análises de performance financeira operacional.

O primeiro ponto de atenção aqui são as despesas `Depreciação e Amortização` e `Despesas Operacionais`. Como pode-se ver na imagem, quando ordenamos pela variação do Orçado (`(∆)%,`) essas são as 2 com a maior distância do realizado x Orçado.

Apesar disso, baseado na receita bruta e valor dessas dívidas, as `Despesas Operacionais` são as que, em valor absoluto (R$), geram a maior despesa, e dessa forma corrigir isso (se possível) gerará um impacto financeiro maior. Com isso em mente, vamos detalhar mais a conta de `Despesas Operacionais`.

![alt text](DespesasOperacionaisDetalhadas.png)

Dentre as despesas operacionais mais especificamente `Publicidade`dentro de `Despesas Comerciais`e `Horas Extras`dentro de `Despesas Administrativas`, juntas acumularam **R$ 22.660** de dividas não esperadas.

**Recomendações**: 

#### Publicidade: 

Se olharmos para o histórico desta conta específica ao longo dos meses nesse ano (imagem abaixo), vemos que em todos os meses houve uma discordância entre o realizado e o orçado para essa área de `Publicidade`, o que pode indicar uma necessidade de melhoria do processo de aprovação de cada campanha, ou ainda que deveria haver 

![alt text](EvoluçãoPublicidade.png)