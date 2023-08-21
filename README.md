# Pipeline de ETL em Python

Este repositório contém um exemplo de um pipeline de ETL (Extração, Transformação e Carga) em Python para processar dados de um arquivo CSV e gerar sugestões de filmes com base na área de atuação das pessoas.

## Funcionalidades

- **Extract**: Os dados são extraídos de um arquivo CSV chamado "pessoas.csv" usando a biblioteca pandas.
- **Transform**: Para cada pessoa, são geradas sugestões de filmes relacionados à sua área de atuação. Os filmes são armazenados em um dicionário e posteriormente associados a cada pessoa.
- **Load**: Os dados transformados são carregados de volta em um DataFrame e as sugestões de filmes são adicionadas como uma coluna.

## Sugestões de Filmes por Área de Atuação

- Desenvolvimento de Software: "The Social Network", "Hackers", "Jobs"
- Marketing: "Mad Men", "The Greatest Movie Ever Sold", "The Founder"
- Design Gráfico: "Helvetica", "Objectified", "Art & Copy"
- Engenharia Civil: "Bridge of Spies", "The Bridge on the River Kwai", "The Towering Inferno"
- Medicina: "Patch Adams", "Contagion", "Awakenings"
- Psicologia: "A Beautiful Mind", "Good Will Hunting", "Eternal Sunshine of the Spotless Mind"
- Arquitetura: "My Architect", "The Fountainhead", "Sketches of Frank Gehry"
- Gastronomia: "Julie & Julia", "Chef", "Ratatouille"
- Economia: "The Big Short", "Inside Job", "Margin Call"
- Data Science: "Moneyball", "Her", "Ex Machina"
