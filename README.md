# Análise de Sentimentos com Azure AI Language Studio

Este repositório contém um exemplo de análise de sentimentos usando o Azure AI Language Studio. Abaixo estão os detalhes do processo e insights obtidos.

## Estrutura do Repositório
- **inputs/sentencas.txt**: Contém as sentenças utilizadas para análise.
- **README.md**: Documentação do projeto.

## Processo
1. Criei um recurso no Azure AI Language Studio.
2. Utilizei o modelo pré-treinado para análise de sentimentos.
3. Inseri as sentenças do arquivo `sentencas.txt` no Language Studio.
4. Obtenha os resultados de sentimentos (positivo, negativo, neutro) e pontuações de confiança.

## Insights
- O modelo identificou corretamente as sentenças positivas e negativas.
- Sentenças ambíguas, como "A entrega foi rápida, mas o produto não era o que eu esperava", foram classificadas como neutras.
- A pontuação de confiança ajuda a entender a certeza do modelo em cada análise.

## Possibilidades
- Integrar o modelo em aplicações para feedback automático de clientes.
- Analisar grandes volumes de dados de redes sociais para tendências de sentimentos.
- Melhorar o modelo com dados específicos do domínio para maior precisão.

## Prints do Processo
