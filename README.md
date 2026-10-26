# 📊 Automação de Relatórios Financeiros com Python e Excel

## 📌 Sobre o projeto

Este projeto apresenta uma solução de automação de relatórios financeiros utilizando Python, Pandas e Excel.

O objetivo é automatizar atividades repetitivas de tratamento, organização e consolidação de dados financeiros, reduzindo a necessidade de processamento manual de planilhas.

A solução utiliza dados fictícios para demonstrar um processo de automação aplicável a diferentes cenários empresariais.

## 🎯 Objetivos

- Automatizar a leitura de dados financeiros.
- Organizar e tratar informações provenientes de arquivos CSV.
- Consolidar receitas e despesas.
- Gerar relatórios financeiros em Excel.
- Facilitar a análise de indicadores financeiros.
- Demonstrar a aplicação de Python na automação de processos.

## 🛠️ Tecnologias utilizadas

- **Python:** desenvolvimento da automação.
- **Pandas:** manipulação e análise de dados.
- **OpenPyXL:** geração e formatação de arquivos Excel.
- **Excel:** visualização dos relatórios.
- **GitHub:** versionamento e documentação do projeto.

## ⚙️ Funcionamento da automação

O processo é dividido em três etapas:

**1. Entrada de dados**

Leitura do arquivo `lancamentos.csv`, contendo informações financeiras fictícias.

**2. Processamento**

O Python realiza o tratamento e a consolidação dos dados financeiros.

**3. Geração do relatório**

A automação gera o arquivo `relatorio_financeiro.xlsx`, disponibilizando as informações para análise.

### Fluxo do processo

```text
Arquivo CSV
    |
    v
Leitura dos dados com Python
    |
    v
Tratamento e organização com Pandas
    |
    v
Consolidação das informações
    |
    v
Geração do relatório Excel
```

## 📂 Estrutura do projeto

```text
automacao-relatorios-financeiros-python/
|
|-- dados/
|   |-- lancamentos.csv
|
|-- src/
|   |-- gerar_relatorio.py
|
|-- saida/
|   |-- relatorio_financeiro.xlsx
|
|-- README.md
|-- requirements.txt
```

## ▶️ Como executar

**1. Clone o repositório:**

```bash
git clone https://github.com/AdrianaMartinelli/automacao-relatorios-financeiros-python.git
```

**2. Acesse a pasta do projeto:**

```bash
cd automacao-relatorios-financeiros-python
```

**3. Instale as dependências:**

```bash
pip install -r requirements.txt
```

**4. Execute a automação:**

```bash
python src/gerar_relatorio.py
```

**5. Consulte o resultado:**

Abra o arquivo `saida/relatorio_financeiro.xlsx`.

## 💼 Competências demonstradas

- Automação de processos com Python.
- Manipulação e tratamento de dados.
- Leitura e geração de arquivos CSV e Excel.
- Consolidação de informações financeiras.
- Organização e documentação de projetos.
- Aplicação de soluções para otimização de rotinas operacionais.

## 🚀 Possíveis melhorias

- Desenvolvimento de dashboards em Power BI.
- Integração com bancos de dados SQL.
- Importação de dados por APIs.
- Agendamento automático da execução.
- Envio automatizado de relatórios por e-mail.

## 📌 Sobre o portfólio

Projeto demonstrativo desenvolvido para apresentar conhecimentos em Análise de Dados, Business Intelligence e Automação de Processos utilizando Python e Excel.
