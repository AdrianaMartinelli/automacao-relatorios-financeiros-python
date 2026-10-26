# Automação de Relatórios Financeiros com Python e Excel

Projeto demonstrativo de automação de processos e análise de dados com **Python, Pandas e OpenPyXL**.

## Objetivo
Transformar lançamentos financeiros de uma planilha CSV em um relatório Excel organizado, com indicadores mensais, totais por categoria e gráfico de receitas e despesas.

## Funcionalidades
- Importação e validação de dados
- Remoção de duplicidades e registros inválidos
- Consolidação de receitas, despesas e saldo mensal
- Análise por categoria
- Exportação de relatório Excel com gráfico

## Como executar
```bash
pip install -r requirements.txt
python src/gerar_relatorio.py
```

**Entrada:** `dados/lancamentos.csv`  
**Saída:** `saida/relatorio_financeiro.xlsx`

## Estrutura
- `dados/`: dados fictícios para demonstração
- `src/`: código de automação
- `saida/`: relatório gerado

## Observação
Os dados são totalmente fictícios. Projeto desenvolvido para demonstração de competências em análise de dados e automação de processos.
