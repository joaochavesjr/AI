## Laboratório DIO
### Análise de Sentimentos com Language Studio no Azure AI
---
1 - Inicialmente foi criado novo recurso de AI Language Service do tipo Microsoft Cognitive Service, no portal do Azure.

<img src="/TextAnalysis/deploy_1.png" alt="Deploy 1">

2 - Finalmente foi criado o recurso idiomakanguage (sim só vi o erro de digitação depois do recurso pronto).

<img src="/TextAnalysis/deploy_2.png" alt="Deploy 2">

3 - Após criar este recurso na Azure, efetuamos o acesso ao Language Studio Portal (language.cognitive.azure.com), para a criação de um novo projeto.

<img src="/TextAnalysis/language_studio.png" alt="LS">

4 - Selecionamos a opção Sentiment and opinion mining tryout, definimos a língua e selecionamos o recurso criado no Azure (idiomakanguage), e finalmente também incluimos o texto para ser analisado.

<img src="/TextAnalysis/text_sentiment.png" alt="TS">

5 - Após a execução da analise, podemos examinar o resultado passo a passo de cada sentença:

<img src="/TextAnalysis/sentence_1.png" alt="s1">

<img src="/TextAnalysis/sentence_2.png" alt="s2">

<img src="/TextAnalysis/sentence_3.png" alt="s3">

- Para cada sentença é apresentado um percentual da analise de sentimento como positiva, neutra ou negativa.
- No texto também são destacados os principais trechos analisados e suas avaliações, também com percentual.

6 - No final é ainda possível observar algumas possibilidades como ver como instalar o SDK e utilizar o recurso, visualizar o código para possibilitar integração com desenvolvimento de aplicações, preços, entre outros.

<img src="/TextAnalysis/resource.png" alt="resource">

<img src="/TextAnalysis/run_the_code.png" alt="run_the_code">

<img src="/TextAnalysis/next_steps.png" alt="next_steps">




