# Informações#

Este documento deve orientar a elaboração e execução de um experimento numérico que visa atender requerimentos da disciplina de Dinâmica dos Fluidos. O objetivo do relatório é realizar a aplicação de instrumentos básicos de gestão de projetos para a elaboração, planejamento, preparação e execução de um projeto de Dinâmica dos Fluidos Computacional. 

Esse documento não pretende esgotar todas as questões relativas à atividade. Complementações podem ser feitas além do requerimento mínimo de conteúdo. Mas os itens mínimos devem ser preenchidos. 

Este trabalho deverá ser feito **individualmente**. Quaisquer indícios de cópias e plágio receberão **nota zero**.

Abaixo segue guias para colocar equações e imagens no arquivo README:


Exemplo para anexar uma imagem (A imagem deve ser enviada para a pasta do grupo via *upload*):

![Teste de legenda de imagem](thrust.jpg)


Para escrever as equações usando o formato do LateX use [este link](https://www.codecogs.com/latex/eqneditor.php). A equação deverá ser gerada no site, salva em formato .gif e enviada para o repositório para ser anexada como imagem, conforme exemplo abaixo:

![Teste de legenda de imagem 2](CodeCogsEqn.gif)

Os problemas propostos para o projeto são:

**Problema 1:** Uma instalação de bombeamento tem apresentado problemas em uma seção de tubulação de 1 metro de comprimento e 40 mm de diâmetro. A perda de carga foi medida usando sensores de pressão, e mensurou-se uma queda de pressão de 2 Pa. A bomba que supre esta tubulação com água está operando em potência máxima. Também mediu-se a vazão deste escoamento, obtendo um valor de 0,0001 metro cúbico por segundo na saída do tubo. O projeto de CFD deve:

- Determinar se estes valores de vazão e perda de carga estão coerentes ou não, e o motivo para isto.
- Apresentar possibilidades de problemas em caso dos valores colocados acima não estarem coerentes.
- Usando a simulação apresentada, realizar um estudo paramétrico para avaliar se o cenário acima é normal ou não para esta instalação.

Sugere-se usar o tutorial de escoamento em dutos de seção circular feito anteriormente. A variável objeto do estudo paramétrico será divulgada para cada aluno individualmente.

**Problema 2:** Deseja-se otimizar o processo de lubrificação de um mancal que é componente de um dado sistema mecânico de um eixo girante. Como todo o memorial de cálculo do mancal se perdeu, não há informações quantitativas de rotação, torque ou do óleo lubrificante usado, apenas que o eixo possui 60 mm e a folga entre o eixo e o mancal é de 2 mm. O projeto de CFD deve:

- Determinar um valor de rotação e torque de operação padrão para este mancal.
- Determinar se existe a possibilidade de outros valores de operação suportados por este mancal.
- Usando a simulação apresentada, realizar um estudo paramétrico para determinar cenários de funcionamento do mancal.

Sugere-se usar o tutorial de escoamento 2D em círculos concêntricos feito anteriormente. A variável objeto do estudo paramétrico será divulgada para cada aluno individualmente.


O projeto em ambos os problemas consistirá de três etapas, onde cada etapa está dividida em subetapas e valem 1/3 da nota. O prazo para entrega de cada etapa é de **1 semana, onde as análises, cálculos, imagens e figuras obtidas deverão ser feitas no GitHub**. Estas etapas são:

### 1. Modelagem: 

A primeira etapa deverá conter as respostas para as seguintes perguntas:

- Qual é o objetivo do projeto?
- Quais são seus requisitos de solução?
- Qual é a finalidade do projeto?
- Que hipóteses de simplificação podem ser adotadas?
- Que hipóteses de simplificação devem ser adotadas?
- Qual é a precisão requerida nos resultados do projeto?
- Qual é o prazo de entrega do projeto?
- Há outra metodologia mais adequada do que CFD?

O projeto deverá conter nesta etapa:

- Desenhos CAD mostrando a geometria do problema.
- Desenho esquemático da modelagem do problema.

### 2.	Pré-Processamento:

A segunda etapa deverá conter as respostas para as seguintes perguntas:

- Quanto detalhado o domínio de cálculo precisa ser?
- A geometria está adequada?
- Que tipo de malha e método usar? Estruturada ou não-estruturada? Volumes Finitos ou Elementos Finitos?
- Quais são as informações de entrada (Input) do problema?
- Que escolhas devem ser feitas em relação ao processamento da solução?
- Quais são os prazos e disponibilidade de capacidade computacional para a análise em questão? 

O projeto deverá conter nesta etapa:

- Descrição do pré-processamento feito no ANSYS.
- Imagens da malha de cálculo do problema.

### 3.	Processamento e Pós-Processamento:

A terceira etapa deverá conter as respostas para as seguintes perguntas:

- O histórico de convergência do cálculo está adequado?
- Quanto tempo a simulação está levando para ser processada?
- Os resíduos estão em valores aceitáveis?
- A simulação fornece resultados qualitativos?
- É possível calcular resultados quantitativos e qualitativos com o que a simulação calculou?
- Os resultados estão de acordo com a realidade física do escoamento?

O projeto deverá conter nesta etapa:

- Análise dos resultados obtidos.
- Comparação dos resultados numéricos com os resultados analíticos de cada problema.
- Imagens de visualização do escoamento.
- Análise dos resultados obtidos pelo estudo paramétrico.

