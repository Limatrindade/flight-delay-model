# flight_delay_model

![Status do Projeto](https://img.shields.io/badge/status-concluído-brightgreen)
![Version](https://img.shields.io/badge/version-1.0.0-blue)

## Descrição

Você já teve algum voo atrasado ou perdeu alguma conexão devido a atraso? Esses contratempos podem ocorrer por diversas razões, incluindo condições climáticas adversas, a necessidade de um avião se deslocar de um local para outro, ou imprevistos no momento do embarque dos passageiros que dificultam o embarque na hora prevista. Esses atrasos não só afetam a experiência dos passageiros, mas também geram custos tanto para as empresas aéreas quanto para os passageiros.

Para enfrentar esses desafios, nosso objetivo é otimizar a gestão aeroportuária com o propósito de definir de forma mais eficiente onde cada avião deve estacionar, criando planos de estacionamento mais adequados, rápidos e otimizados.

Mas qual o objetivo desse projeto?

Vamos desenvolver um modelo preditivo para prever os atrasos nos voos e ajustar os planos de estacionamento de acordo com essas previsões. Com essa abordagem, esperamos alcançar duas metas principais:

1. Reduzir o Tempo de Espera dos Passageiros: Ao prever e ajustar com antecedência os atrasos nos voos, podemos minimizar o tempo que os passageiros passam esperando e melhorar a sua experiência geral.

2. Otimizar as Operações do Aeroporto: Melhorar a alocação dos espaços de estacionamento e os processos de embarque com base nas previsões de atraso pode levar a uma operação mais eficiente e menos caótica no aeroporto.

Mas qual foi a Metodologia aplicada?

Nossa primeira missão consiste em desenvolver um modelo de machine learning, mais especificamente um modelo de regressão. Este modelo será responsável por prever os atrasos nos voos com base em suas características. As previsões geradas por este modelo serão fundamentais, pois servirão como entrada para outros processos de otimização, ajudando a definir estratégias eficazes para a alocação de espaço e a gestão do fluxo de passageiros.

Ao construir e aplicar este modelo, buscamos não apenas prever os atrasos de forma precisa, mas também fornecer uma base sólida para a implementação de melhorias operacionais no aeroporto.

Ao final do projeto, espera-se:

- Um Modelo de Previsão Precisão: Desenvolver um modelo preditivo preciso e confiável que possa prever atrasos nos voos com base nas variáveis disponíveis.
- Redução de Atrasos e Melhoria Operacional: Utilizar as previsões para ajustar os planos de estacionamento e melhorar a gestão operacional do aeroporto, resultando em uma redução significativa dos tempos de espera e maior eficiência operacional.
- Insights Valiosos: Fornecer insights valiosos sobre os fatores que mais influenciam os atrasos, ajudando a informar futuras decisões e estratégias no gerenciamento de aeroportos.

## Sumário

- [Descrição](#descrição)
- [Sumário](#sumário)
- [Instalação](#instalação)
- [Tecnologias](#tecnologias)
- [Uso](#uso)
- [Resultados](#resultados)
- [Contribuição](#contribuição)
- [Contato](#contato)

## Instalação

Para configurar o ambiente e iniciar o projeto, siga as etapas de instalação abaixo. Estas instruções garantem que todas as dependências necessárias sejam instaladas e que você possa executar o projeto localmente sem problemas.

**Exemplo:**

```bash
# Clone este repositório
git clone https://github.com/Limatrindade/flight-delay-model.git

# Entre no diretório do projeto
cd nome-do-projeto

# Acesse o notebook de sua preferência
Jupyter notebook
Google colabory
VScode com Jupyter notebook
Pycharm
Outros
```

## Tecnologias

Tecnologias e bibliotecas utilizadas no projeto.

**Exemplo:**

- **Linguagem**: Python 3.10
- **Análise de Dados**: Pandas, Numpy
- **Machine Learning**: Scikit-learn
- **Visualização de Dados**: Matplotlib, Seaborn, Plotly
- **Ambiente de Desenvolvimento**: Jupyter Notebook, VSCode
- **Versionamento de Código**: Git, GitHub
- **Outras**: Statsmodels

## Uso

Para começar a utilizar este projeto, siga as instruções abaixo. Elas irão guiá-lo desde a configuração do ambiente até a execução do código. Se você estiver interessado em explorar as funcionalidades ou adaptar o projeto para suas necessidades, os exemplos fornecidos ajudarão a facilitar o processo.

```bash
# Abra o Jupyter Notebook
jupyter notebook

# Navegue até o arquivo principal
```

## Resultados

Os resultados obtidos mostram o impacto significativo das análises realizadas, destacando insights valiosos e métricas de desempenho robustas que demonstram a eficácia das soluções propostas. Veja abaixo os principais resultados e conclusões.

**Exemplo:**

- Ao analisar a relação entre as companhias aéreas e os atrasos, observamos que a Companhia MM apresenta o maior atraso médio em comparação com as demais. No entanto, é importante notar que essa companhia não tem o maior número total de voos. Isso indica que o atraso médio não está diretamente correlacionado com o volume total de voos operados por uma companhia aérea. Em outras palavras, uma companhia pode ter um alto atraso médio mesmo com um número relativamente baixo de voos, sugerindo que fatores específicos a afetam mais intensamente do que a quantidade total de operações. Essa discrepância pode apontar para variáveis adicionais que impactam os atrasos, como a eficiência operacional, condições de manutenção da frota ou questões específicas relacionadas aos aeroportos de origem e destino.

- Outra observação relevante é a diferença no atraso médio entre os tipos de voo, especificamente voos Schengen e não-Schengen. Os voos não-Schengen apresentam um atraso médio superior em comparação aos voos Schengen. No entanto, é importante notar que o volume de voos não-Schengen é menor do que o volume de voos Schengen. Esse dado sugere que, embora os voos não-Schengen enfrentem atrasos maiores em média, sua menor quantidade pode influenciar menos a percepção geral dos atrasos do que a maior quantidade de voos Schengen. Isso pode indicar que os voos não-Schengen enfrentam desafios adicionais que impactam sua pontualidade, possivelmente relacionados a processos de controle de segurança mais rigorosos ou logística internacional complexa.

- Outra observação importante é que os atrasos médios em feriados são, em média, quatro vezes maiores do que em dias normais. Isso sugere que os feriados podem trazer desafios adicionais para a operação dos voos, como um aumento na demanda, maior volume de passageiros, ou possíveis interrupções nas operações aeroportuárias e de controle de tráfego aéreo. Esse aumento significativo nos atrasos durante feriados destaca a necessidade de estratégias de gestão e planejamento mais eficazes para lidar com o fluxo adicional e minimizar os impactos na pontualidade dos voos.

- Um dado interessante é que, ao comparar o número de voos por tipo de aeronave, o modelo Airbus A320 se destaca com quase o dobro de voos em relação ao segundo colocado na lista. Entre os seis modelos de aeronaves com o maior número de voos, três são modelos menores destinados a voos regionais, enquanto os outros três são aeronaves maiores para voos internacionais. Esse padrão sugere que a distinção entre voos regionais e internacionais não parece ter um impacto significativo no atraso médio dos voos. Em outras palavras, o tipo de voo—se regional ou internacional—não é um fator determinante para o atraso médio, indicando que outros fatores, possivelmente relacionados à operação ou ao gerenciamento de cada tipo de aeronave, podem estar influenciando os atrasos de forma mais significativa.

- Ao calcular as métricas de regressão para o DummyRegressor, observamos os seguintes resultados: Raiz do Erro Quadrático Médio (RMSE): 23.2241, Erro Absoluto Médio (MAE): 18.6127, R² Score: -0.0
- Esses resultados indicam que o DummyRegressor, que utiliza uma estratégia simplista de previsão, apresenta um desempenho relativamente insatisfatório. O RMSE e o MAE elevados sugerem que o modelo tem uma alta margem de erro em suas previsões. Além disso, o R² Score de -0.0 indica que o modelo não consegue capturar nenhuma variação significativa nos dados e que, na verdade, pode estar se saindo pior do que um modelo que simplesmente prevê a média dos valores. Esses resultados evidenciam a necessidade de utilizar modelos de regressão mais sofisticados e ajustados para melhorar a precisão das previsões e fornecer insights mais valiosos.

- Ao avaliar as métricas de regressão para o RandomForestRegressor, obtivemos os seguintes resultados: Raiz do Erro Quadrático Médio (RMSE): 13.7318, Erro Absoluto Médio (MAE): 11.0198, R² Score: 0.6504
- Esses resultados indicam que o RandomForestRegressor oferece uma performance significativamente melhor em comparação com o DummyRegressor. A redução no RMSE e no MAE demonstra que o modelo está fazendo previsões mais precisas, com menor erro médio. O R² Score de 0.6504 sugere que aproximadamente 65% da variabilidade nos dados pode ser explicada pelo modelo, o que é um indicativo positivo de sua capacidade de capturar padrões e relações importantes. Esses resultados destacam a eficácia do RandomForestRegressor em relação à regressão simplista, indicando que ele é uma escolha robusta para prever os atrasos nos voos e melhorar a precisão das nossas análises.

- Durante a validação cruzada, os valores obtidos foram:
```bash
Erro Absoluto Médio (MAE):

Scores Individuais: -11.086, -11.319, -11.064, -11.155, -11.185
MAE Média: -11.162
Desvio Padrão (Std): 0.090

Raiz do Erro Quadrático Médio (RMSE):

Scores Individuais: -13.775, -14.061, -13.798, -13.879, -13.932
RMSE Média: -13.889
Desvio Padrão (Std): 0.103

R² Score:

Scores Individuais: 0.646, 0.624, 0.645, 0.641, 0.635
R² Média: 0.638
Desvio Padrão (Std): 0.008
```

- Esses resultados indicam que o modelo apresenta um desempenho consistente e robusto através das diferentes iterações da validação cruzada. A média do MAE de -11.162 e a média do RMSE de -13.889, com baixos desvios padrão, sugerem que o modelo tem uma precisão confiável e estável nas previsões dos atrasos. O R² Score médio de 0.638 confirma que o modelo é capaz de explicar cerca de 64% da variabilidade dos dados, com uma variabilidade mínima entre as diferentes divisões dos dados. Esses resultados indicam que o modelo está bem ajustado e é eficaz na previsão dos atrasos, proporcionando uma base sólida para aplicações práticas e análises adicionais.

- Ao analisar as importâncias das características no modelo RandomForestRegressor, observamos quais variáveis têm o maior impacto nas previsões. Os resultados mostram as seguintes importâncias para cada característica:

1. airline_BZ: 0.5290
2. is_holiday: 0.1479
3. aircraft_type_Airbus A320: 0.1008
4. aircraft_type_Airbus A330: 0.0583
5. aircraft_type_Embraer E175: 0.0457
6. arrival_time: 0.0392
7. aircraft_type_Boeing 787: 0.0291
8. origin_TCY: 0.0177
9. origin_CSF: 0.0128
10. origin_PUA: 0.0106

- Os dados indicam que a variável airline_BZ é a mais influente, com uma importância de 0.5290, o que sugere que ela tem o maior impacto nas previsões do modelo. Em seguida, is_holiday também tem uma contribuição significativa, com uma importância de 0.1479. Outras variáveis como aircraft_type_Airbus A320 e aircraft_type_Airbus A330 também têm importâncias notáveis, embora menores, indicando que o tipo de aeronave desempenha um papel relevante nas previsões. As variáveis relacionadas ao horário de chegada e às origens têm importâncias menores, mas ainda contribuem para a performance geral do modelo. Esses resultados ajudam a entender quais variáveis são mais relevantes para a previsão de atrasos, oferecendo insights valiosos para melhorar a estratégia de otimização e foco na gestão dos fatores que mais influenciam as previsões.

## Contribuição

Achou o projeto interessante e quer contribuir, melhorar, ou simplesmente criar a sua própria versão? Ótimo! Siga os passos abaixo.

Exemplo:

```bash
1. Faça um fork deste repositório

2. Crie uma branch para sua feature (git checkout -b feature/nova-feature)

3. Faça commit das suas alterações (git commit -m 'Adiciona nova feature')

4. Envie para a branch original (git push origin feature/nova-feature)

5. Abra um Pull Request
```

## Contato

Gostou do que viu? Entre em contato comigo para saber mais ou discutir colaborações!

**Exemplo:**

- **Email**: [teulima20@hotmail.com](mailto:teulima20@hotmail.com)
- **LinkedIn**: [Matheus Lima](https://www.linkedin.com/in/matheus-lima-809407191/)
- **GitHub**: [Meu GitHub](https://github.com/Limatrindade)

