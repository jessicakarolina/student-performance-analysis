# Análise do Desempenho de Estudantes

**Objetivo: Descobrir o que realmente importa para o sucesso acadêmico**

Esse projeto investiga uma questão fundamental para estudantes de tecnologia: *quais hábitos realmente fazem diferença nas notas?* Através de uma análise estatística detalhada de dados de 909 estudantes, busco entender o que separa os alunos de alto desempenho dos demais.

##  A pergunta que guiou a análise

Com tanto para estudar e tantas distrações disponíveis, como os estudantes de tecnologia podem organizar sua rotina para terem melhor desempenho? Será que é preciso abandonar o lazer? Ou será que alguns fatores que consideramos importantes não são tão determinantes assim?

##  O que fiz

Analisei dados de 909 estudantes de cursos como Ciência da Computação e Engenharia da Computação, focando em:

- **Desempenho:** As notas dos exames
- **Hábitos de estudo:** Horas dedicadas por dia
- **Bem-estar:** Saúde mental e atividade física
- **Lazer:** Tempo em redes sociais e streaming
- **Contexto:** Educação dos pais, trabalho, presença nas aulas

Usei estatística como uma ferramenta para encontrar padrões reais no comportamento dos estudantes.

## Ferramentas que usei

- **Google Colab** para executar toda a análise
- **Pandas** para organizar e limpar os dados
- **Matplotlib e Seaborn** para criar visualizações claras
- **Estatística descritiva** para entender a distribuição das notas
- **Correlação** para medir relações entre diferentes fatores

## O que descobri

### O fator mais importante (e talvez óbvio)
**Tempo de estudo** tem uma correlação muito forte com as notas (+0.82). Os alunos do topo estudam em média **5 horas por dia**, enquanto os com notas mais baixas estudam menos de **2 horas**.

###   Insights

1. **Saúde mental importa** (+0.32 de correlação)
   - Alunos que se sentem bem mentalmente tendem a ter notas melhores
   - Não é apenas "estudar até cansar"

2. **Atividade física faz diferença**
   - 41% dos alunos com alto desempenho se exercitam 5-6 vezes por semana
   - 39% dos alunos com baixo desempenho quase não se exercitam

3. **O lazer não é vilão**
   - Redes sociais e Netflix têm correlação fraca (-0.17)
   - O problema não é ter lazer, mas não priorizar o estudo

###  O que **não** faz diferença
- Educação dos pais
- Ter emprego de meio período
- Apenas comparecer às aulas
- Qualidade específica da dieta

## Como acessar o  projeto:

### Para ver a análise completa:
1. **Ler o PDF** - Arquivo PDF para entender toda a análise de forma organizada
2. **Explore o Notebook** - Abra o arquivo `.ipynb` para ver o código e gráficos interativos

### ou:
1. Baixe o notebook `.ipynb`
2. Abra no Google Colab (gratuito) ou Jupyter Notebook
3. O código está pronto para executar

##  Reflexões 

Esta análise me mostrou que o sucesso nos estudos de tecnologia vem mais de **autogestão** do que de fatores externos. Não se trata de ser um gênio ou ter vantagens familiares, mas de:

1. **Priorizar** o estudo diário
2. **Cuidar** da saúde mental e física
3. **Equilibrar** estudo e lazer, não eliminar um pelo outro

