<!--
# COUGHVID
Projeto que faz parte da disciplina da UNICAMP de Ciência e Visualização de Dados em Saúde.
-->
<!--
#  Análise de condições clínicas respiratórias com base em anotações médicas e áudios de tosse 
-->
<!--
# Projeto - Primeira Entrega
-->
<!--
O objetivo geral do projeto final desta disciplina é realizar a análise de dados relacionados à saúde, para usá-los em uma das seguintes possíveis tarefas: recomendação, estudo de associações, validação de hipóteses, análise exploratória, análise visual, análise comparativa e predição.
-->
<!--
Na primeira entrega do projeto, seu grupo deverá:
-->
<!--
 - Criar um repositório GitHub ou GitLab **público** que será usado ao longo de todo o projeto (o link deverá ser submetido na atividade correspondente no Google Classroom da disciplina);
 - Organizar o repositório segundo a estrutura de diretórios proposta abaixo;
 - Editar arquivo README.md do repositório com a proposta inicial do projeto, segundo modelo descrito a seguir;
 - Disponibilizar vídeo de duração máxima de 3 minutos de apresentação da proposta do projeto. Não é necessário que todos os membros da equipe apareçam ou participem do vídeo.
 -->
<!--
Após a primeira entrega, será agendada (em horário de aula) uma data de arguição da proposta de projeto. É obrigatória a participação de todos os membros durante o momento da arguição da proposta. Durante a arguição, os professores fornecerão feedbacks sobre a proposta e seu grupo poderá tirar dǘvidas sobre o encaminhamento do projeto. 
-->
<!--
# Estrutura do Repositório
-->
<!--
A fim de uniformizar os repositórios de projetos da disciplina, os diretórios de seu repositório deverão ser nomeados e utilizados segundo a estrutura sugerida em [Home - Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/), na seção "Directory structure".
-->
<!--
Note que nem todos os diretórios ou arquivos serão necessários para todos os projetos. Foque em seguir o padrão para os diretórios que forem necessários. Não crie diretórios que não serão utilizados.
-->
<!--
Seu repositório deverá obrigatoriamente conter o arquivo README.md, arquivo de documentação Markdown, que deverá conter a descrição do projeto conforme orientações a seguir.
-->
<!--
# Editando Arquivo README.md
-->
<!--
	
Este é um guia de como produzir documentação em Markdown. Para entender como criar documentos em Markdown no Github, veja o material/vídeo:
[Guia de Uso do Markdown](https://github.com/mc-unicamp/oficinas/tree/master/docs).
-->
<!--
Vide detalhes sobre o Markdown em: [Mastering Markdown](https://guides.github.com/features/mastering-markdown/).
-->
<!--
E mais especificamente sobre tabelas em: [Organizing information with tables](https://help.github.com/en/articles/organizing-information-with-tables)
-->
<!--
Segue abaixo o modelo de como deve ser apresentado e documentado o projeto. Tudo o que for indicado entre `<...>` indica algo que deve ser substituído pelo indicado. No modelo são colocados exemplos ilustrativos, que serão substituídos pelos do seu projeto.
-->
<!--
Segue abaixo o modelo de como devem ser documentadas as entregas.
> Tudo o que aparecer neste modo de citação se refere algo que deve ser substituído pelo indicado. No modelo são colocados exemplos ilustrativos, que serão substituídos pelos do seu projeto.
-->
<!--
# Modelo para Apresentação do Projeto
-->
# Projeto -  Análise de condições clínicas respiratórias com base em anotações médicas e áudios de tosse
# Project - Analysis of respiratory clinical conditions based on physician notes and cough audios 


# Apresentação

O presente projeto foi originado no contexto das atividades da disciplina de pós-graduação [*Ciência e Visualização de Dados em Saúde*](https://github.com/datasci4health/home), oferecida no primeiro semestre de 2021, na Unicamp.

 Equipe:
 |Nome  | RA | Especialização|
 |--|--|--|
 | Brunna Raphaelly Amaral da Silva   | 144566  | Saúde|
 | Carolina Vieira Campos  | 263081  | Saúde|
 | Gabriel Bianchin de Oliveira  | 230217  | Computação|
 | Taciana Alessandra Gomes Cruz  | 107132  | Computação|


# Descrição Resumida do Projeto
Diante de uma situação pandêmica de COVID-19, diversos profissionais atuam para expansão do conhecimento sobre sintomas clínicos e combate ao vírus. Muitos estudos mostraram avanço nos testes de diagnóstico para COVID-19 [1] [2] [3] mais rápidos e acessíveis para toda a população, com o objetivo de maior controle contra a propagação do vírus. Decidimos investigar uma proposta de detecção dos sintomas de COVID-19 ou outra síndrome respiratória assim como avaliação da severidade da condiçao clínica através de áudios de tosse enviados pelo próprio indivíduo ao profissional de saúde. 

A rápida detecção de uma pessoa com COVID-19 favorece a diminuição dos níveis de surtos locais, além da possibilidade do resguardo de vidas pela detecção da doença através de um sintoma que pode ser manifestado nos estágios iniciais, levando a pessoa a procurar ajuda mais rápido.

Seria inviável tanto no quesito da logística quanto financeiro a construção de testes físicos para toda população de um país utilizar diariamente ou sempre que for ter contato com outra pessoa. Com esse objetivo, estudos estão sendo feitos com o uso da Inteligência Artificial para tornar viável os testes rápidos, não invasivos e diários para a população. Assumindo assim um controle maior da situação durante a pandemia.

Para tanto, utilizaremos dados que são compostos de cerca de 2.000 registros de áudio de indivíduos apresentando uma variedade de idade, gêneros, localização geográfica, onde cada um dos dados foi avaliado por um especialista. 

# Vídeos do Projeto
## Vídeo da Proposta
Link para vídeo de apresentação da proposta do projeto: https://drive.google.com/file/d/1DRkbzs9tnc_VRzRQwNYXgOeBPn6Aj942/view?usp=sharing

## Vídeo da Apresentação final
Link para vídeo de apresentação final: https://drive.google.com/file/d/1QfmflEN0d5AT1iq2-5v3t6VoiFqsIlAZ/view?usp=sharing

# Slides do Projeto
## Slides da Proposta
Link para o power point de apresentação da proposta do projeto: https://drive.google.com/file/d/1hn-KTxZMSYJD9Qvi_0TL7rg_RykUqfDv/view?usp=sharing

## Slides da Apresentação Final
Link para o power point de apresentação final: https://drive.google.com/file/d/1pI9Lj003CHq587_1DyvBgYs_lRRV0vRb/view?usp=sharing

# Introdução e Referenciais de Teóricos

# Perguntas de Pesquisa
1.	É possível identificar condições clínicas respiratórias através de anotações médicas e padrões de áudios de tosse?  
2.	Há associação entre o diagnóstico do especialista e a classificação do áudio de acordo com uma análise particular do indivíduo?
3.	Quais são as condições clínicas do sistema respiratório que podem ser associadas com o diagnóstico de COVID-19? 

Hipótese nula: Não há associação entre uma determinada condição clínica respiratória e o padrão de tosse do indivíduo. 

Hipótese alternativa: Há associação entre uma determinada condição clínica respiratória e o padrão de tosse do indivíduo. 

# Objetivos do Projeto
Investigar padrões do sinal de áudios de tosse e anotações de especialistas sobre os áudios para o diagnóstico de indivíduos entre saudável, sintomático ou COVID-19.

# Metodologia
Para realizar a atividade proposta, seguimos a abordagem do *Knowledgment Discovery in Databases* (KDD):
1. Seleção da base de dados
2. Limpeza e pré-processamento dos dados
3. Análise exploratória, análise estatística e visualização dos dados
4. Mineração de dados
	* Utilização de algoritmos de aprendizado de máquina
5. Interpretação e análise dos resultados

Na primeira etapa, avaliamos duas bases de dados diferentes e optamos pela base de dados Coughvid.

Na segunda etapa, verificamos a existência de dados faltates e fizemos o pré-processamento dos áudios (remoção de dados que não foram avaliados por especialistas e a junção de dados de um mesmo indivíduo, caso mais de um especialista faça a análise daquele caso).

Na terceira etapa, exploramos a base de dados para encontrar possíveis padrões que possam ajudar a realizar a categorização correta de cada dado. Ainda nesta etapa, fizemos diversas visualizações dos dados.

Na quarta etapa, utilizamos classificadores baseados em imagens para fazer a classificação de áudios e classificadores baseados em dados tabulares para realizar classificação das anotações de especialistas. Em ambos os casos, o objetivo foi predizer corretamente as três possíveis classes (saudável, sintomático e COVID-19).

Na quinta etapa, avaliamos os resultados obtidos pelos classificadores da quarta etapa.
<!--
> Proposta de metodologia incluindo especificação de quais técnicas pretende-se explorar, tais como: aprendizagem de máquina, análise de redes, análise estatística, ou integração de uma ou mais técnicas. Para a primeira entrega, descreva de maneira mais genérica que tipo de abordagem seu grupo pretende realizar.
-->

# Bases de Dados
Com as perguntas de pesquisa levantadas, procuramos algumas bases de dados candidatas a serem usadas no projeto. Encontramos duas bases candidatas:
* [Coughvid](https://zenodo.org/record/4048312#.YGzbTD9v-Uk) [4]
* [Virufy COVID-19](https://github.com/virufy/virufy-data) [5]

## Base Estudada mas não Adotada
|Base de Dados|Endereço na Web|Resumo Descritivo|
|-|-|-|
|Virufy COVID-19|https://github.com/virufy/virufy-data | A base de dados contém anotações de 16 indivíduos, indicando o resultado do teste PCR, o áudio da tosse, a idade, gênero, se é fumante, o histórico médico e os sintomas reportados |

A análise de dados da base Virufy pode ser encontrada [aqui](https://github.com/tacigomess/COUGHVID/blob/main/assets/pdf/VirufyCOVID-19/Analise%20Virufy%20COVID-19.pdf).

Escolhemos não adotar esta base de dados devido a pouca quantidade de amostras, comparado com a base Coughvid. Além disso, a base não possui a verificação da tosse por especialistas (por exemplo, se a tosse é seca ou carregada).

## Base Estudada e Adotada
|Base de Dados|Endereço na Web|Resumo Descritivo|
|-|-|-|
|Coughvid|https://zenodo.org/record/4048312#.YGzbTD9v-Uk | A base de dados contém anotações de mais de 20.000 indivíduos, possuindo o áudio da tosse, informações de idade e gênero, se possui condição respiratória e dores musculares ou febre. Além disso, existem mais de 2.000 áudios verificados por especialistas, indicando diversas características dos áudios de tosse, como o tipo de tosse, se é uma tosse seca ou carregada e a qualidade do áudio|

Primeiro, realizamos a ánalise da base completa, ou seja, com todos os 20.000 indivíduos. A análise de dados da base Coughvid completa pode ser encontrada [aqui](https://github.com/tacigomess/COUGHVID/blob/main/assets/pdf/Coughvid/Analise%20base%20completa.pdf). A figura a seguir apresenta o workflow utilizado.

![Workflow](https://github.com/tacigomess/COUGHVID/blob/main/assets/photos/workflow%20base%20original.png).

Na sequência, analisamos os dados de indivíduos que tiveram os áudios analisados por especialistas. Fizemos um filtro (cough_detected > 0.50) para selecionar apenas as amostras com chance de representar áudio de tosse maior que 50%. A análise pode ser encontrada [aqui](https://github.com/tacigomess/COUGHVID/blob/main/assets/pdf/Coughvid/Analise%20base%20anotacoes%20especialistas.pdf). A figura a seguir apresenta o workflow utilizado.

![Work flow](https://github.com/tacigomess/COUGHVID/blob/main/assets/photos/WORKFLOW_ORANGE_cough_detected.jpg).

Dentre essas duas bases, acreditamos que a base Coughvid é a melhor, já que tem mais amostras (20.000 áudios vs. 16 áudios da Virufy COVID-19), além de possuir mais de 2.000 dados verificados por especialistas. <!--Outro ponto positivo para a base Coughvid é que a base possui informações adicionais por indivíduo, como por exemplo se apresentou febre ou dor no corpo e se possuia alguma condição respiratória (estes dados foram relatados pelos próprios indivíduos). Elencar bases de dados candidatas a serem utilizadas no projeto. -->

# Análises Realizadas
## Experimentos Realizados
Dividimos os experimentos em duas vertentes: predição da situação do indivíduo a partir do áudio da tosse e predição da situação do indivíduo a partir das anotações de especialistas. Em ambos os experimentos, utilizamos apenas dados que foram verificados por especialistas.

Para os experimentos para a predição da situação do indivíduo a partir do áudio da tosse, exploramos diversas variações de experimentos, sendo eles:
* Avaliação de 21 redes diferentes com pesos pré-treinados no ImageNet e com um ajuste fino para a nossa base de dados;
* Pré-processamento dos áudios com trim;
* Pré-processamento dos áudios com a segmentação de trechos que identificam a tosse no áudio;
* Vision Transformers [6];
* Stacking ensemble dos modelos;
* Aumentação dos dados, gerando novos dados a partir dos dados originais.

Para os experimentos para a predição da situação do indivíduo a partir das anotações de especialistas, exploramos diversas variações de experimentos, sendo eles:
* Avaliação de árvore de decisão, floresta aleatória e máquina de vetores de suporte;
* Grid Search dos modelos.

Os notebooks com os códigos de cada uma das etapas podem ser encontrados [aqui](https://github.com/tacigomess/COUGHVID/tree/main/notebooks).

## Ferramentas
Para o desenvolvimento do projeto, utilizamos a linguagem de programação Python, junto com algumas bibliotecas, como tensorflow, sklearn, numpy, pandas e matplotlib, e o ambiente virtual Google Colab. Além do Python, utilizamos a ferramenta Orange.
 
# Resultados 

Todos os resultados dos diversos experimentos usando áudio podem ser encontrados [aqui](https://github.com/tacigomess/COUGHVID/blob/main/assets/pdf/Coughvid/Resultados%20audios.pdf).

A tabela abaixo sumariza os melhores resultados em cada um dos experimentos no conjunto de validação em termo de acurácia balanceada. O melhor resultado foi obtido pela EfficientNetB7 para a segmentação completa, atingindo 43,18% de acurácia balanceada na validação.

| Experimento | MEL Spectrogram | MFCC|
|--|--|--|
| Transfer Learning com as redes do ImageNet | 41,34 (EfficientNetB7) | 41,42 (EfficientNetB7) |
| Trim | 42,31 (DenseNet201 - trim de 60) | 40,87 (VGG19 - trim de 90) |
| Segmentação | 42,77 (VGG19 - segmentação completa) | 43,18 (EfficientNetB7 - segmentação completa) |
| Transformers | 42,41 | 35,90 |
| Stacking Ensemble | 28,85 | 33,03 |
| Aumentação de dados | 34,73 | --- |

Com a melhor rede selecionada, fizemos a avaliação no conjunto de teste. Como resultado, obtivemos 39,75% de acurácia balanceada. A figura abaixo ilustra a matriz de confusão.

![Matriz confusão](https://github.com/tacigomess/COUGHVID/blob/main/assets/photos/matriz-confusao-audio.png)

Todos os resultados dos experimentos usando dados de especialistas podem ser encontrados [aqui](https://github.com/tacigomess/COUGHVID/blob/main/assets/pdf/Coughvid/Resultados%20anotacoes%20especialistas.pdf).

A tabela abaixo sumariza os melhores resultados no conjunto de validação em termo de acurácia balanceada. O melhor resultado foi obtido pela árvore de decisão, atingindo 36,46% de acurácia balanceada na validação.

| Classificador | Acurácia balanceada |
|--|--|
| Árvore de decisão | 36,46 |
| Floresta Aleatória | 35,60 |
| Máquina de vetores de suporte | 36,44 |

Com 0 melhor classificador selecionado, fizemos a avaliação no conjunto de teste. Como resultado, obtivemos 32,75% de acurácia balanceada. A figura abaixo ilustra a matriz de confusão.

![Matriz confusão](https://github.com/tacigomess/COUGHVID/blob/main/assets/photos/matriz-confusao-especialista.png)

<!--
Os resultados inciais estão [aqui](https://github.com/tacigomess/COUGHVID/blob/main/assets/pdf/Coughvid/Resultados.pdf).

A tabela abaixo sumariza os resultados até agora

| Rede | Experimento | Acurácia balanceada na validação (%)|
|--|--|--|
| InceptionResNetv2 | Com apenas dados de especialistas | 42,63 |
| MobileNet | Com dados adicionais | 42,50 |
-->

# Discussão
Para avaliarmos a concordância entre o melhor preditor da situação do indivíduo a partir do áudio da tosse e o melhor preditor da situação do indivíduo a partir das anotações de especialistas, utilizamos a métrica detalahada a seguir.

![metrica](https://github.com/tacigomess/COUGHVID/blob/main/assets/photos/equation.jpg)

Nesta métrica, N00 indica que tanto o o melhor preditor da situação do indivíduo a partir do áudio da tosse e o melhor preditor da situação do indivíduo a partir das anotações de especialistas erraram na avaliação, N01 indica que o melhor preditor da situação do indivíduo a partir do áudio da tosse acertou e o melhor preditor da situação do indivíduo a partir das anotações de especialistas errou na avaliação, N10 indica que o melhor preditor da situação do indivíduo a partir do áudio da tosse errou e o melhor preditor da situação do indivíduo a partir das anotações de especialistas acertou na avaliação e N11 indica que ambos acertaram. O maior valor possível é 1, indicando que os preditores se discordam, e o menor valor possível é 0, indicando que se concordam.

Para esta avaliação, utilizamos as predições no conjunto de teste. Como resultado, obtivemos o valor igual a 0,53, o que mostra que exite um meio termo, ou seja, não existe uma concordância e nem uma discondância entre os dois classificadores.


<!--
# Cronograma
> Proposta de cronograma. Procure estimar quantas semanas serão gastas para cada etapa do projeto.

Tomando como base a metodologia do KDD, dividimos o cronograma em cada uma de suas etapas abaixo em quinzenas:

 |Entregas| Descrição  | Abril - Q1 | Abril - Q2 | Maio - Q1 | Maio - Q2 | Junho - Q1 | Junho - Q2 |
 |--|--|--|--|--|--|--|--|
 | **Entrega 1 - 13/04**|Elaboração do plano de projeto | X ||||||
 | **Entrega 2 - 25/05**|Seleção dos dados || X | X ||||
 | |Pré-processamento dos dados || X | X ||||
 | |Análise exploratória e estatística || X | X ||||
 | **Entrega 3 - 24/06**|Mineração dos dados |||| X | X ||
 | |Interpretação e conclusão |||| X | X ||
 | **Apresentações**|Apresentação do projeto |||||| X |
-->
# Conclusão
A partir da análise dos dados através de ferramentas diversas, desde o Orange até redes convolucionais, pudemos observar uma discrepância entre a avaliação dos especialistas e a classificação do próprio indivíduo em relação à sua condição de saúde. Três especialistas avaliaram os áudios de tosse com base nos seguintes sintomas: falta de ar (dispneia), respiração ofegante, dificuldade para respirar (asfixia) e congestão nasal. Os resultados mostraram que foram atribuídos pesos diferentes para cada sintoma, levando a um diagnóstico final não necessariamente coincidente entre os especialistas.

Apesar de haver certa variação no diagnóstico final, é possível identificar características clínicas da saúde do indivíduo no áudio de tosse através da associação do ruído com os sintomas. No entanto, concordamos que para um diagnóstico exato e preciso, testes mais avançados de medicina são necessários.

Voltando as questões de pesquisa, podemos, agora, responde-las:
1.  É possível identificar condições clínicas respiratórias através de anotações médicas e padrões de áudios de tosse?  
- Pelos resultados obtido, podemos concluir que as condições clínicas respiratórias podem ser identificadas com maior precisão pelo áudio, já que este tipo de modelo foi capaz de atingir maior generalização. Porém, para um diagnóstico preciso, são necessários exames clínicos.

2.  Há associação entre o diagnóstico do especialista e a classificação do áudio de acordo com uma análise particular do indivíduo?
- Pelos resultados de concordância entre os classificadores de áudio e de anotações de especialista, podemos concluir que não existe uma associação clara entre as duas abordagens.

3.  Quais são as condições clínicas do sistema respiratório que podem ser associadas com o diagnóstico de COVID-19? 
- Não existe um consenso entre os três especialistas que anotaram os dados. Cada um deles indicou uma condição como a principal, a partir da análise feita com regressão logística. Para o especialista 1, a principal condição para indicar condição clínica grave foi a presentação de dispneia, enquanto para o especialista 2 foi a presenção da sensação de asfixia e para o especialista 3 foi a presença de respiração ofegante. Portanto, podemos concluir que essas são as três principais condições clínicas para indicar condição clínica grave.

# Trabalhos Futuros
Como trabalhos futuros, podemos apontar os seguintes passos:
* Aquisição de mais dados anotados por especialistas. Com isso, os modelos terão mais dados para treinar, e, eventualmente, terão maiores valores de acurácia balanceada.
* Investigação de métodos para a criação de dados de forma sintética com outras combinações de dados e de pré-processamento e de tratamento de dados. Deste modo, podemos utilizar os dados já analisados por especialistas para o treinamento do modelo.
* Investigação de outras técnicas de aprendizado de máquina, como outras opções de ensemble de redes.


# Referências

[1] Jin, C., Chen, W., Cao, Y. et al. Development and evaluation of an artificial intelligence system for COVID-19 diagnosis. Nat Commun **11**, 5088 (2020).

[2] Laguarta, J., Hueto, F. and B. Subirana. COVID-19 Artificial Intelligence Diagnosis Using Only Cough Recordings. IEEE Open Journal of Engineering in Medicine and Biology, vol. 1, pp. 275-281, 2020.

[3] Zoabi, Y., Deri-Rozov, S. & Shomron, N. Machine learning-based prediction of COVID-19 diagnosis based on symptoms. npj Digit. Med. **4**, 3 (2021). 

[4] Orlandic, L., Teijeiro, T., and Atienza, D. The COUGHVID crowdsourcing dataset: A corpus for the study of large-scale cough analysis algorithms. ArXiv, pp. 1-11, 2020.

[5] Fakhry, A., Jiang, X., Xiao, J. et al. Virufy: A Multi-Branch Deep Learning Network for Automated Detection of COVID-19. ArXiv, pp. 1-9, 2021.

[6] Dosovitskiy, A., Beyer, L., Kolesnikov, A. et al. An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale. ArXiv, pp. 1-22. 2020.
<!--
1- https://www.nature.com/articles/s41467-020-18685-1

2- https://ieeexplore.ieee.org/document/9208795

3- https://www.nature.com/articles/s41746-020-00372-6
-->
