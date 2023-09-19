# Proj Capacidade Produtiva Etapa-II - O atual momento de escassez orçamentária/financeira e de pessoal em que se encontra o o mercado, vem exigindo esforços pela busca de métodos de planejamento que otimizem o uso dos recursos, priorizem demandas, aumentem a produtividade e o impacto das ações de supervisão de mercado. O sistema utiliza basicamente três variáveis para estabelecerem suas metas nos Planos de Planejamento Técnico: histórico de execução, quantitativo de pessoal técnico capacitado e disponibilidade financeira.
No entanto, estas variáveis vem se mostrando insuficientes, para produzir um plano de planejamento Técnico que considere o melhor potencial de produtividade, com maior cobertura e impacto nos setores econômicos e nas áreas geográficas que mais necessitam acompanhamento.

Preparação do ambiente de programação
A linguagem escolhida para trabalhar a estrutura de dados “BDCP”, na organização, parametrização, categorização e analise de dados, foi o “R” que é muito utilizada em áreas de Data-Science.

a) Linguagem R - R é uma linguagem de programação multi-paradigma orientada a objetos, programação funcional, dinâmica, fracamente tipada, voltada à manipulação, análise e visualização de dados. O R disponibiliza uma ampla variedade de técnicas estatísticas e gráficas, incluindo modelação linear e não linear, testes estatísticos clássicos, análise de séries temporais (time-series analysis), classificação, agrupamento e outras. A R é facilmente extensível através de funções e extensões, e a comunidade R é reconhecida pelos seus contributos ativos em termos de pacotes.

b) IDE Rstudio - RStudio é um ambiente de desenvolvimento integrado (IDE) para R. Inclui um console, editor de realce de sintaxe que oferece suporte à execução direta de código, bem como ferramentas para plotagem, histórico, depuração e gerenciamento de espaço de trabalho.

c) Foi adotado para a criação dos códigos o RMarkdown que é uma linguagem pensada para a escrita de textos em que são criadas marcações para títulos, links, códigos de um modo conciso e legível. É tão legível que está hoje ao alcance de pessoas que não desenvolvem para ‘web’ como eu e você, possivelmente.

## Metodologia
Este projeto será executado em 3 fases não necessariamente subsequentes, desenvolvidas por meio de análise documental exploratória, pesquisa bibliográfica, aplicação de métodos estatísticos e sistematização em plataforma web.

## Sub-Etapas

1 - Análise Envoltória de Dados (DEA) com dados da Etapa I - Utilização de DEA entre as UF usando a Metodologia DEA (Data Envelopment Analysis) - Segundo DEA, o desempenho de uma empresa é avaliado em relação a uma fronteira eficiente, que é construída através da combinação linear das empresas existentes. O procedimento baseia-se numa formulação matemática sofisticada.

2 - Prospecção de variáveis estruturantes - Tudo aquilo que não está sob o poder de decisão dos dirigentes dessas instituições, tais como os fatores de infraestrutura, fatores regionais ou mesmo os de natureza ambiental, política ou econômica, mas que podem ser apropriados de forma positiva (oportunidades) ou negativa (ameaças) sobre o desempenho institucional [AGUIRRE et al., 2011; SUGAHARA et al. , 2018; ERASMO et al., 2018].

![image](https://user-images.githubusercontent.com/66335171/169878897-3091c940-8be9-4f83-9f54-a5f9a2891a7e.png)

3 - Definição das variáveis estruturantes - CORRELOGRAMA  - Calcula a correlação de variáveis e exibe os resultados graficamente. As funções de painel incluídas podem exibir pontos, sombreamento, elipses e valores de correlação com intervalos de confiança nos ajudam a visualizar os dados em matrizes de correlação.
![2 Correlação, variância e covariância (matrizes)](https://user-images.githubusercontent.com/66335171/169882627-d01146cf-6aa3-4198-a6a2-eefb7b88a95a.png)

4 - Preparação das variáveis estruturantes - Escala positiva e negativa

Valor BASAL
	Situação na qual o recorte regional do estudo representa, quando da comparação com outros locais, a condição menos favorável para operação de uma determinada unidade institucional (UI)
Valor FRONTEIRIÇO:  
	Refere-se à condição mais favorável para atuação de uma UI, em um determinado local de atuação.
DESIGUALDADE ESTRUTURAL OU REGIONAL
	Refere-se à variação entre os valores BASAIS e FRONTEIRIÇOS de atuação da unidades comparadas.

![image](https://user-images.githubusercontent.com/66335171/169878785-4837af58-779a-4a04-9b33-54c7fd5a1aed.png)

![image](https://user-images.githubusercontent.com/66335171/169879028-faa4ee5b-b3bc-4779-a074-dc5f2df2f4ae.png)

![image](https://user-images.githubusercontent.com/66335171/169879187-f39dca05-2423-45ee-b5bb-5a812d444afe.png)

![image](https://user-images.githubusercontent.com/66335171/169879606-960d2ca1-590b-4307-98d0-20a5ae3d1a2f.png)

5 - Análise com o PCA (Principal Component Analysis) das 03 variáveis GEO - SNB - TELECOM.

6 - Análise com o PCA para definição de pesos para criação de variável estruturante unificadora  "INFRA" - através da Técnica de Análise de Componentes Principais ou PCA (Principal Component Analysis) é uma técnica de análise multivariada que pode ser usada para analisar inter-relações entre um grande número de variáveis e explicar essas variáveis em termos de suas dimensões inerentes (Componentes).

7 - Reutilizar a DEA com a inclusão da variável de "INFRA", para verificar a eficiência das UF - A Metodologia DEA (Data Envelopment Analysis) - Segundo DEA, o desempenho de uma empresa é avaliado em relação a uma fronteira eficiente, que é construída através da combinação linear das empresas existentes. O procedimento baseia-se numa formulação matemática sofisticada.

## PRÓXIMAS ETAPAS SERÃO INSERIDAS A MEDIDA DO AVANÇAR DO PROJETO

