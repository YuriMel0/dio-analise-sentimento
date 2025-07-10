# Relatório de Atividade: Análise de Sentimento com Azure Speech Service

## Introdução

Durante o bootcamp de Ciência de Dados, utilizamos a ferramenta [Azure Speech Service](https://speech.microsoft.com/portal) da Microsoft para realizar uma análise de sentimento a partir de arquivos de áudio. A proposta da atividade foi explorar como tecnologias de reconhecimento de fala podem ser aplicadas em tarefas de Processamento de Linguagem Natural (PLN), como a análise de sentimentos.

## Metodologia

A ferramenta permite o upload de arquivos de áudio, os quais são convertidos automaticamente em texto por meio da transcrição de fala. Em seguida, é possível aplicar serviços cognitivos para obter insights, como a identificação de emoções e sentimentos expressos nas falas.

O processo seguiu as seguintes etapas:
1. Gravação ou upload de um arquivo de áudio.
2. Transcrição automática da fala.
3. Análise do conteúdo textual transcrito para inferência do sentimento (positivo, neutro ou negativo).
4. Visualização dos resultados fornecidos pela interface da ferramenta.

## Observações

Apesar de ser uma demonstração interessante, a experiência foi bastante **manual**:
- É necessário fazer o upload individual de cada áudio.
- Os resultados não são exportáveis de forma estruturada para análise em escala.
- Não há possibilidade de customizar os modelos ou treinar com dados próprios.

Por outro lado, a ferramenta mostra o potencial de integração com outras soluções da Microsoft via API, o que pode permitir automações mais complexas fora do ambiente web demonstrado.

## Conclusão

A utilização do Azure Speech Service no contexto do bootcamp permitiu um primeiro contato com aplicações reais de análise de sentimento baseada em fala. No entanto, para uso em projetos mais robustos ou em produção, seria necessário integrar a API em pipelines próprios, garantindo maior controle, automação e escalabilidade.

## Sugestões

- Utilizar a API diretamente via Python para automatizar o envio de dados e coleta dos resultados.
- Combinar os resultados da análise de sentimento com outras variáveis (como tempo de fala, entonação, etc.) para insights mais completos.
- Comparar com outras ferramentas de análise de sentimento (como o `VADER` ou `TextBlob` para texto) para entender vantagens e limitações.

