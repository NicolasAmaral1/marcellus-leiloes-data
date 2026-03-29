# Marcellus Leiloes — Base de Imoveis em Leilao Judicial

43 imoveis do leiloeiro **Nakakogue Leiloes** (Curitiba/PR) analisados automaticamente.

Valor total avaliado: **R$ 142,6 milhoes** | 14 cidades do Parana + 1 SP

---

## Estrutura

```
analysis/
  consolidated.md          ← Ranking geral dos 43 imoveis
  legal/                   ← Analise juridica por imovel (risco de nulidade, CPC)
  investment/              ← Analise de investimento (custo total, score)

guides/                    ← Guia completo por imovel (11 secoes)

markdown/editais/          ← Editais convertidos de PDF para Markdown

editais-pdf/               ← PDFs originais dos editais

property-registry.json     ← Base de dados completa (todos os campos)
```

## O que tem em cada guia

Cada arquivo em `guides/` contem:

1. **Identificacao** — ID, leiloeiro, leilao, lote, processo, matricula, link direto
2. **Localizacao** — endereco, bairro, cidade/UF, comarca
3. **Descricao** — tipo, areas, quartos, vagas, fotos
4. **Valores** — avaliacao, lance minimo, desconto %, preco/m2
5. **Leilao** — datas 1a/2a praca, comissao, pagamento
6. **Judicial** — vara, tribunal, tipo execucao, credor, devedor
7. **Onus** — IPTU, condominio, penhoras, indisponibilidades
8. **Ocupacao** — status, dificuldade de desocupacao
9. **Risco de nulidade** — 8 dimensoes com base legal (CPC art. 879-903)
10. **Investimento** — custo total, score de atratividade, recomendacao
11. **Documentos** — links para o site, edital PDF e Markdown

## Top 5 oportunidades

| # | ID | Tipo | Cidade | Lance Min | Desconto | Risco | Score |
|---|---|---|---|---|---|---|---|
| 1 | MRC-137449-3601 | casa | Santo Antonio | R$ 125k | 50% | 34 | 85 |
| 2 | MRC-137449-3602 | casa | Ibaiti | R$ 2.792k | 50% | 34 | 85 |
| 3 | MRC-137449-3603 | casa | Joaquim Tavora | R$ 213k | 50% | 34 | 85 |
| 4 | MRC-137439-601 | terreno | Curitiba | R$ 1.428k | 49% | 28 | 82 |
| 5 | MRC-137450-3001 | apto | Curitiba | R$ 1.253k | 49% | 31 | 78 |

## Por tipo de imovel

| Tipo | Qtd |
|------|-----|
| Terreno | 16 |
| Casa | 10 |
| Apartamento | 9 |
| Fazenda | 4 |
| Chacara | 2 |
| Garagem | 1 |
| Cobertura | 1 |

## Fonte

Dados extraidos de [nakakogueleiloes.com.br](https://www.nakakogueleiloes.com.br) em 28/03/2026.

---

*Gerado por Marcellus Leiloes v0.1.0*
