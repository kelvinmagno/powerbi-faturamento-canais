# Análise de Faturamento por Canal

Dashboard de estudo desenvolvido por **Kelvin Magno** no **Power BI**, com visualizações de faturamento por período, canal de vendas e vendedor.

## Objetivo

Praticar a organização de indicadores comerciais em uma página, explorando a evolução do faturamento, a participação dos canais e o detalhamento dos resultados.

## Contexto e fonte dos dados

Projeto de caráter educacional. A referência do exercício e a origem detalhada da base ainda estão em confirmação.

## Perguntas exploradas

- Como o faturamento varia ao longo do período apresentado?
- Qual é a participação de cada canal no faturamento?
- Como detalhar o faturamento por canal e vendedor?
- Quais valores de faturamento e itens vendidos são apresentados por ano?

## Visualização

**[Visualizar o dashboard em PDF](./Constru%C3%A7%C3%A3o%20de%20um%20dashboard.pdf)**

O PDF apresenta o painel completo em uma página. É uma exportação estática: as interações e a expansão das hierarquias dependem do relatório original.

O arquivo `.pbix` e o link para a versão interativa ainda não foram disponibilizados.

## Indicadores e recursos

- Série temporal de faturamento, com hierarquia indicada de ano, trimestre, mês e dia.
- Gráfico de participação do faturamento por canal.
- Árvore de decomposição com canal e vendedor.
- Matriz analítica com faturamento e total de itens vendidos por ano.

## Resultados exibidos

| Indicador | Valor na exportação |
| --- | ---: |
| Faturamento total | 17.500.591,74 |
| Total de itens vendidos | 4.213.827 |

### Faturamento por canal

| Canal | Faturamento | Participação exibida |
| --- | ---: | ---: |
| Varejo | 7.419.260,71 | 42,39% |
| Parceiros | 5.305.003,18 | 30,31% |
| On-line | 4.776.327,85 | 27,29% |

Os percentuais exibidos podem não somar exatamente 100% devido ao arredondamento.

## Principais observações

- **Varejo** apresenta a maior participação no faturamento do recorte exportado.
- **Parceiros** aparece em segundo lugar, seguido de **On-line**.
- A tabela separa os resultados de **2021 e 2022**.
- A árvore de decomposição apresenta o detalhamento por canal e, no ramo expandido de Varejo, por vendedor.

O gráfico sugere cobertura parcial de 2022. Sem confirmar as datas de início e fim da base, os totais anuais não devem ser utilizados para concluir crescimento ou queda entre períodos equivalentes.

## Ferramenta e práticas

**Power BI**, com prática de:

- Visualização de séries temporais.
- Comparação da participação de categorias.
- Construção de árvore de decomposição.
- Apresentação de resultados em matriz com hierarquia.
- Organização visual do relatório em uma página.

## Limitações da documentação

A análise foi feita a partir do PDF. As fórmulas, o modelo de dados, a unidade monetária e as interações não foram verificados no arquivo original.

## Créditos

- **Desenvolvido por:** Kelvin Magno.
- **Referência do exercício e fonte detalhada dos dados:** em confirmação.

## Autor

[Kelvin Magno](https://github.com/kelvinmagno) — Analista de Prevenção à Fraude, desenvolvendo habilidades em Power BI, Excel e SQL.
