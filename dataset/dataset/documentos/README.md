# Documentação do Projeto
**Projeto:** Processando e Transformando Dados com Power BI (DIO)  
**Autor:** Lavine Bezerra Sena  
**Repositório:** processando-transformando-dados-powerbi

---

## 1. Resumo
Breve descrição do objetivo do projeto: transformar, modelar e apresentar os dados fornecidos no desafio da DIO utilizando Power BI e Power Query. O projeto demonstra etapas de ETL, modelagem dimensional e criação de visualizações e medidas em DAX.

---

## 2. Arquivos do repositório (pasta `documentos`)
- `01_Instrucoes_Desafio.docx` — instruções originais do desafio.
- `02_Slides_Desafio.pptx` — slides com enunciado e orientações.
- `03_DOCUMENTACAO_DO_PROJETO.md` — esta documentação.
- (Opcional) `04_CHANGES.md` — histórico de alterações.

---

## 3. Arquivos de dados (pasta `dataset`)
Liste aqui os arquivos de dados que você usou (ex.: `vendas.csv`, `clientes.xlsx`, `fato_vendas.pbix`), com breve descrição de cada um.

---

## 4. Passos realizados (ETL / Power Query)
Descreva passo a passo o que foi feito no Power Query, por exemplo:
- Importei `vendas.csv` e `clientes.xlsx`.
- Removi colunas irrelevantes: `coluna_x`, `coluna_y`.
- Corrigi tipos de dados (ex.: data, inteiro, decimal).
- Tratei valores nulos com preenchimento/default.
- Separei colunas (ex.: `endereco` → `rua`, `numero`).
- Agrupei/compactei dados quando necessário.
- Adicionei colunas calculadas (ex.: `Ano`, `Mês`, `Receita`).

*(Se possível, liste as transformações na ordem em que foram aplicadas.)*

---

## 5. Modelagem (Power BI)
- Tipo de modelagem adotada: **Star Schema** / **Snowflake** (escolha o que você fez).
- Tabelas de fato: `Fato_Vendas` (lista de métricas: `Quantidade`, `Valor`, `Desconto`).
- Tabelas de dimensão: `Dim_Produto`, `Dim_Cliente`, `Dim_Tempo`, etc.
- Relacionamentos: explicar chaves (PK e FK). Se puder, adicione um print do diagrama em `imagens/`.

---

## 6. Medidas DAX criadas
Liste as medidas principais, exemplo:
- `Total Receita = SUM(Fato_Vendas[Valor_Venda])`
- `Quantidade Total = SUM(Fato_Vendas[Quantidade])`
- `Ticket Médio = [Total Receita] / [Quantidade Total]`

---

## 7. Visualizações e relatório
Descreva as páginas do relatório (ex.: Página 1 — Visão Geral com KPIs; Página 2 — Análise por Região; Página 3 — Vendas por Produto) e quais visualizações principais foram usadas (cartões, colunas, linhas, matriz).

---

## 8. Evidências (pasta `imagens`)
- Inclua prints do Power Query, do modelo de dados, das medidas e do relatório final.
- Nomeie as imagens, ex.: `01_powerquery_transformacoes.png`, `02_modelo_dados.png`, `03_dashboard.png`.

---

## 9. Como abrir / reproduzir o relatório
1. Baixe o arquivo `.pbix` da pasta raiz (se presente).  
2. Abra com Power BI Desktop (versão recomendada: xx.x.x).  
3. Caso faltem fontes de dados, aponte para os arquivos da pasta `dataset`.  
4. Atualize (refresh) para carregar os dados transformados.

---

## 10. Conclusão e melhorias futuras
- Resumo dos principais achados (ex.: clientes com maior receita, produtos com maior venda).
- Sugestões de melhorias: automatizar atualizações no Power BI Service; criar indicadores avançados; aplicar controle de qualidade de dados etc.

---

## 11. Contato
**E-mail:** laviniasenaramos@gmail.com
