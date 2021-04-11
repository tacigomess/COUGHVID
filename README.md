# COUGHVID
Projeto que faz parte da disciplina da UNICAMP de Ciência e Visualização de Dados em Saúde.
<!--
# Diagnóstico de COVID-19 baseado em características da tosse 
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
# Projeto - Diagnóstico de COVID-19 baseado em características da tosse
# Project - COVID-19 Diagnosis based on cough characteristics


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

 
> Link para vídeo de apresentação da proposta do projeto (máximo 3 minutos).

# Perguntas de Pesquisa
1. É possível realizar o diagnóstico de COVID-19 através da análise de gravações de áudio com características da tosse de uma pessoa? 
2. Existem padrões de sinal de tosse que podem ser reconhecidos e caracterizar uma condição clínica de COVID-19?
3. Quais são as diferenças no áudio da tosse de uma pessoa com COVID-19 em comparação com outra pessoa sem essa condição clínica? 

* Hipótese nula: As características do áudio de tosse de uma pessoa com COVID-19 e sem COVID-19 são os mesmos.
* Hipótese alternativa: As características do áudio de tosse de uma pessoa com COVID-19 e sem COVID-19 são diferentes. 


# Bases de Dados
Com as perguntas de pesquisa levantadas, procuramos algumas bases de dados candidatas a serem usadas no projeto. Encontramos duas bases candidatas:
* [Coughvid](https://zenodo.org/record/4048312#.YGzbTD9v-Uk)
* [Virufy COVID-19](https://github.com/virufy/virufy-data)

Dentre essas duas bases, acreditamos que a base Coughvid é a melhor, já que tem mais amostras (20.000 áudios vs. 17 áudios da Virufy COVID-19), além de possuir 3.000 dados verificados por especialistas. Outro ponto positivo para a base Coughvid é que a base possui informações adicionais por paciente, como por exemplo se apresentou febre ou dor no corpo e se possuia alguma condição respiratória (estes dados foram relatados pelos próprios pacientes).
<!-- 
> Elencar bases de dados candidatas a serem utilizadas no projeto. 
-->

# Metodologia
Para realizar a atividade proposta, seguiremos a abordagem do *Knowledgment Discovery in Databases* (KDD):
1. Seleção da base de dados
2. Limpeza e pré-processamento dos dados
3. Análise exploratória, análise estatística e visualização dos dados
4. Mineração de dados
	* Utilização de algoritmos de aprendizado de máquina
5. Interpretação e análise dos resultados

Na segunda etapa, considerando que a base que utilizaremos será a Coughvid, iremos verificar se existem dados faltantes e faremos o pré-processamento dos áudios (inicialmente, pensamos em transformar os áudios em imagens e trabalhar com algoritmos que lidam com esse tipo de dados).

Na terceira etapa, iremos análisar possíveis padrões nos dados, tanto nos dados coletados quanto nas imagens geradas.

Na quarta etapa, iremos utilizar classificadores de aprendizado de máquina para fazer a classificação das imagens.

Na quinta etapa, iremos avaliar os resultados obtidos pelos classificadores da quarta etapa. Caso seja necessário, podemos retornar às etapas anteriores (segunda, terceira ou quarta etapa).
<!--
> Proposta de metodologia incluindo especificação de quais técnicas pretende-se explorar, tais como: aprendizagem de máquina, análise de redes, análise estatística, ou integração de uma ou mais técnicas. Para a primeira entrega, descreva de maneira mais genérica que tipo de abordagem seu grupo pretende realizar.
-->

# Ferramentas
 Pretendemos utilizar inicialmente o ambiente de notebooks Google Colab junto com a linguagem Python durante o projeto. Para complementar as análises exploratórias e estatísticas, usaramos também a ferramenta SPSS.

# Cronograma
<!--
> Proposta de cronograma. Procure estimar quantas semanas serão gastas para cada etapa do projeto.
-->
Tomando como base a metodologia do KDD, dividimos o cronograma em cada uma de suas etapas abaixo em quinzenas:

 |Entregas| Descrição  | Abril - Q1 | Abril - Q2 | Maio - Q1 | Maio - Q2 | Junho - Q1 | Junho - Q2 |
 |--|--|--|--|--|--|--|--|
 | **Entrega 1 - 13/04**|Elaboração do plano de projeto | X ||||||
 | **Entrega 2 - 11/05**|Seleção dos dados || X |||||
 | |Pré-processamento dos dados || X | X ||||
 | |Análise exploratória e estatística || X | X ||||
 | **Entrega 3 - 24/06**|Mineração dos dados |||| X | X ||
 | |Interpretação e conclusão |||| X | X ||
 | **Apresentações**|Apresentação do projeto |||||| X |

# Referências

1- https://www.nature.com/articles/s41467-020-18685-1

2- https://ieeexplore.ieee.org/document/9208795

3- https://www.nature.com/articles/s41746-020-00372-6
