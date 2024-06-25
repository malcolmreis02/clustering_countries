## Resumo

O objetivo deste projeto é dividir os países conforme seu nível de interação econômica, utilizando dados de importação e exportação. Através da clusterização hierárquica e do método do cotovelo (Elbow Method), foi possível identificar seis grupos distintos de países. Os resultados são apresentados através de dendrogramas e gráficos de dispersão, permitindo uma visualização clara das relações econômicas entre os países analisados.

## Ferramentas Utilizadas

- **R**: Linguagem de programação utilizada para todo o processamento e análise dos dados.
- **readr**: Biblioteca para leitura de arquivos CSV.
- **dplyr**: Biblioteca para manipulação e transformação dos dados.
- **knitr**: Biblioteca para formatação de tabelas e relatórios.
- **ggplot2**: Biblioteca para criação de gráficos.
- **magrittr**: Biblioteca para uso de pipes (%>%).
- **ggdendro**: Biblioteca para criação de dendrogramas.
- **GGally**: Biblioteca para criação de gráficos de pares (ggpairs).
- **tidyr**: Biblioteca para manipulação de dados faltantes.

### Tabelas e Gráficos

- **Gráfico de Pares**: Visualização das variáveis de importação e exportação.
- **Gráfico Elbow**: Ajuda a determinar o número ideal de clusters.
- **Dendrograma**: Visualiza a hierarquia dos clusters.
- **Gráfico de Dispersão dos Dados Agrupados**: Mostra os dados de importação e exportação agrupados conforme o modelo escolhido.

### Referências

1. Dados econômicos dos países: "Country-data.csv"
2. Dicionário de dados: "data-dictionary.csv"
