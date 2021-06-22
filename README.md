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
Diante de uma situação pandêmica onde várias linhas de frente estão atuando para  descoberta e elaboração de testes de COVID-19 [1] [2] [3] mais rápidos e acessíveis para toda a população, com o objetivo de um maior controle contra a propagação do vírus. Decidimos trabalhar com uma proposta de teste rápido, não invasivo e em tempo real para o diagnóstico do COVID-19 baseando-nos tanto no áudio como nas características da tosse do paciente.

A rápida detecção de uma pessoa com COVID-19 favorece a diminuição dos níveis de surtos locais, além da possibilidade do resguardo de vidas pela detecção da doença através de um sintoma que pode ser manifestado nos estágios iniciais, levando a pessoa a procurar ajuda mais rápido.

Seria inviável tanto no quesito da logística quanto financeiro a construção de testes físicos para toda população de um país utilizar diariamente ou sempre que for ter contato com outra pessoa. Com esse objetivo, estudos estão sendo feitos com o uso da Inteligência Artificial para tornar viável os testes rápidos, não invasivos e diários para a população. Assumindo assim um controle maior da situação durante a pandemia.

Para tanto, utilizaremos dados que são compostos de 20.000 registros de áudio de pacientes apresentando uma variedade de idade, gêneros, localização geográfica, e se o paciente está ou não infectado com o COVID-19, dentre eles 2000 registros contém anotações médicas extras. 

# Vídeos do Projeto
## Vídeo da Proposta
Link para vídeo de apresentação da proposta do projeto : https://drive.google.com/file/d/1DRkbzs9tnc_VRzRQwNYXgOeBPn6Aj942/view?usp=sharing

## Vídeo da Apresentação final

# Slides do Projeto
## Slides da Proposta

## Slides da Apresentação Final

# Introdução e Referenciais de Teóricos

# Perguntas de Pesquisa
1.	É possível identificar condições clínicas respiratórias através de anotações médicas e padrões de áudios de tosse?  
2.	Há associação entre o diagnóstico do especialista e a classificação do áudio de acordo com uma análise particular do indivíduo?
3.	Quais são as condições clínicas do sistema respiratório que podem ser associadas com o diagnóstico de COVID-19? 

Hipótese nula: Não há associação entre uma determinada condição clínica respiratória e o padrão de tosse do indivíduo. 

Hipótese alternativa: Há associação entre uma determinada condição clínica respiratória e o padrão de tosse do indivíduo. 

# Objetivos do Projeto

# Metodologia
Para realizar a atividade proposta, seguiremos a abordagem do *Knowledgment Discovery in Databases* (KDD):
1. Seleção da base de dados
2. Limpeza e pré-processamento dos dados
3. Análise exploratória, análise estatística e visualização dos dados
4. Mineração de dados
	* Utilização de algoritmos de aprendizado de máquina
5. Interpretação e análise dos resultados

Na segunda etapa, considerando que a base que utilizaremos será a Coughvid, iremos verificar se existem dados faltantes e faremos o pré-processamento dos áudios (inicialmente, pensamos em transformar os áudios em imagens e trabalhar com algoritmos que lidam com esse tipo de dados).

Na terceira etapa, analisaremos possíveis padrões nos dados, tanto nos dados coletados quanto nas imagens geradas.

Na quarta etapa, utilizaremos classificadores de aprendizado de máquina para fazer a classificação das imagens.

Na quinta etapa, avaliaremos os resultados obtidos pelos classificadores da quarta etapa. Caso seja necessário, podemos retornar às etapas anteriores (segunda, terceira ou quarta etapa).
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
|Virufy COVID-19|https://github.com/virufy/virufy-data | A base de dados contém anotações de 16 pacientes, indicando o resultado do teste PCR, o áudio da tosse, a idade, gênero, se é fumante, o histórico médico e os sintomas reportados |

A análise de dados da base Virufy pode ser encontrada [aqui](https://github.com/tacigomess/COUGHVID/blob/main/assets/pdf/VirufyCOVID-19/Analise%20Virufy%20COVID-19.pdf).

Escolhemos não adotar esta base de dados devido a pouca quantidade de amostras, comparado com a base Coughvid. Além disso, a base não possui a verificação da tosse por especialistas (por exemplo, se a tosse é seca ou carregada).

## Base Estudada e Adotada
|Base de Dados|Endereço na Web|Resumo Descritivo|
|-|-|-|
|Coughvid|https://zenodo.org/record/4048312#.YGzbTD9v-Uk | A base de dados contém anotações de mais de 20.000 pacientes, possuindo o áudio da tosse, informações de idade e gênero, se possui condição respiratória e dores musculares ou febre. Além disso, existem mais de 2.000 áudios verificados por especialistas, indicando diversas características dos áudios de tosse, como o tipo de tosse, se é uma tosse seca ou carregada e a qualidade do áudio|

A análise de dados da base Coughvid pode ser encontrada [aqui](https://github.com/tacigomess/COUGHVID/blob/main/assets/pdf/Coughvid/Analise%20Coughvid.pdf).

Dentre essas duas bases, acreditamos que a base Coughvid é a melhor, já que tem mais amostras (20.000 áudios vs. 16 áudios da Virufy COVID-19), além de possuir mais de 2.000 dados verificados por especialistas. Outro ponto positivo para a base Coughvid é que a base possui informações adicionais por paciente, como por exemplo se apresentou febre ou dor no corpo e se possuia alguma condição respiratória (estes dados foram relatados pelos próprios pacientes).
<!-- 
> Elencar bases de dados candidatas a serem utilizadas no projeto. 
-->

# Análises Realizadas

## Ferramentas
 Pretendemos utilizar inicialmente o ambiente de notebooks Google Colab junto com a linguagem Python durante o projeto. Para complementar as análises exploratórias e estatísticas, usaremos também as ferramentas Orange e SPSS.
 
# Resultados 
<!--
Os resultados inciais estão [aqui](https://github.com/tacigomess/COUGHVID/blob/main/assets/pdf/Coughvid/Resultados.pdf).

A tabela abaixo sumariza os resultados até agora

| Rede | Experimento | Acurácia balanceada na validação (%)|
|--|--|--|
| InceptionResNetv2 | Com apenas dados de especialistas | 42,63 |
| MobileNet | Com dados adicionais | 42,50 |
-->

# Discussão

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

# Trabalhos Futuros

# Referências

[1] Jin, C., Chen, W., Cao, Y. et al. Development and evaluation of an artificial intelligence system for COVID-19 diagnosis. Nat Commun **11**, 5088 (2020).

[2] Laguarta, J., Hueto, F. and B. Subirana. COVID-19 Artificial Intelligence Diagnosis Using Only Cough Recordings. IEEE Open Journal of Engineering in Medicine and Biology, vol. 1, pp. 275-281, 2020.

[3] Zoabi, Y., Deri-Rozov, S. & Shomron, N. Machine learning-based prediction of COVID-19 diagnosis based on symptoms. npj Digit. Med. **4**, 3 (2021). 

[4] Orlandic, L., Teijeiro, T., and Atienza, D. The COUGHVID crowdsourcing dataset: A corpus for the study of large-scale cough analysis algorithms. ArXiv, pp. 1-11, 2020.

[5] Fakhry, A., Jiang, X., Xiao, J. et al. Virufy: A Multi-Branch Deep Learning Network for Automated Detection of COVID-19. ArXiv, pp. 1-9, 2021.
<!--
1- https://www.nature.com/articles/s41467-020-18685-1

2- https://ieeexplore.ieee.org/document/9208795

3- https://www.nature.com/articles/s41746-020-00372-6
-->
