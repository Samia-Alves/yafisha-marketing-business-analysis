# Y.Afisha | Análise de Marketing e Rentabilidade

**Projeto de portefólio em Análise de Dados · TripleTen · Sprint 8**

## Problema de negócio

A Y.Afisha pretende otimizar o investimento em marketing. O objetivo deste estudo é compreender como os utilizadores interagem com a plataforma, quando se tornam compradores e quais as origens de aquisição com melhor desempenho económico.

O estudo utiliza registos de visitas, encomendas e custos de publicidade disponibilizados no contexto da formação, relativos ao período de análise do projeto.

## Ferramentas e competências

- **Python e Jupyter Notebook** para preparação, exploração e visualização de dados;
- **pandas, NumPy, Matplotlib e Seaborn** para cálculos, agregações e gráficos;
- **Análise de coortes** para retenção e evolução do valor dos clientes;
- **Métricas de negócio:** DAU, WAU, MAU, conversão, valor médio por encomenda, LTV, CAC e ROMI.

## Metodologia

1. Carregamento, limpeza e validação dos dados de visitas, encomendas e despesas.
2. Análise de utilização do produto: utilizadores ativos, sessões, duração e retenção.
3. Análise de vendas: tempo até à primeira compra, encomendas, valor médio e LTV por coorte.
4. Análise de marketing: despesas por origem, CAC por **comprador** e comparação de retorno através do ROMI.
5. Interpretação dos resultados e recomendações de alocação de orçamento.

## Principais resultados

| Indicador | Resultado |
| --- | ---: |
| Utilizadores ativos por dia (média) | ~908 |
| Utilizadores ativos por semana (média) | ~5.716 |
| Utilizadores ativos por mês (média) | ~23.228 |
| Duração média de sessão | ~644 segundos |
| Tempo médio até à primeira compra | ~16,73 dias |
| Valor médio de encomenda | ~5,00 unidades monetárias |
| Investimento total em marketing | 329.131,62 unidades monetárias |

**Desempenho das origens de aquisição (ROMI):**

| Origem | ROMI reportado |
| --- | ---: |
| 10 | 1,55 |
| 9 | 1,40 |
| 4 | 1,13 |
| 1 | 0,98 |
| 5 | 0,95 |
| 2 | 0,56 |
| 3 | 0,51 |

> O ROMI apresentado no notebook corresponde à razão entre LTV e CAC. Um valor superior a 1 indica que o LTV estimado supera o custo de aquisição, **não** necessariamente lucro líquido contabilístico.

### Principal descoberta

A **origem 3** concentrou aproximadamente **141.321 unidades monetárias** de investimento, o maior montante entre as origens analisadas, mas registou o menor ROMI (**0,51**). Este contraste indica uma oportunidade prioritária para rever o orçamento de aquisição.

## Recomendações

- **Reavaliar o investimento na origem 3**, tendo em conta o seu elevado custo e o retorno estimado mais baixo.
- **Testar uma redistribuição gradual do orçamento** para as origens 10, 9 e 4, acompanhando CAC, conversão e retorno ao longo do tempo.
- **Acompanhar a retenção por coorte**, dado o declínio expressivo de utilizadores após o primeiro mês.
- **Validar o LTV diretamente por origem de aquisição** antes de tomar decisões definitivas: o cálculo atual atribui aos compradores o LTV da respetiva coorte temporal, pelo que a comparação entre origens deve ser interpretada com cautela.

## Limitações

Este é um **projeto académico**, desenvolvido com dados fornecidos no curso. As conclusões representam os resultados do notebook, não uma avaliação financeira auditada. A análise de LTV por origem pode ser aprofundada com a receita efetiva dos compradores atribuídos a cada canal.

## Consultar a análise

📓 [Abrir o notebook completo](YAfisha_Analise_Marketing.ipynb)

**Autora:** Samia Alves · [GitHub](https://github.com/Samia-Alves) · [LinkedIn](https://www.linkedin.com/in/samia-alves-a8baa51b0)
