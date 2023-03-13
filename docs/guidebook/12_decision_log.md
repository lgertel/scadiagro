# Registro de Decisão

A última coisa que você pode considerar em incluir em um guia de software é um registro das decisões que foram tomadas durante o desenvolvimento do sistema de software.

### Intenção

O objetivo desta seção é simplesmente registrar as principais decisões que foram tomadas, incluindo as escolhas de tecnologia (por exemplo, produtos, estruturas etc.) e a arquitetura geral (por exemplo, a estrutura do software, estilo arquitetônico, decomposição, padrões etc. ). Por exemplo:

- Por que você escolheu a tecnologia ou estrutura "X" em vez de "Y" e "Z"?
-   Como você fez isso? Avaliação do produto ou prova de conceito?
- Você foi forçado a tomar uma decisão sobre "X" com base na política corporativa ou nas estratégias de arquitetura corporativa?
- Por que você escolheu a arquitetura de software selecionada? Que outras opções você considerou?
- Como você sabe que a solução atende aos principais requisitos não funcionais?
- etc

### Estrutura

Novamente, mantenha-o simples, com um parágrafo curto ou [registro de decisão de arquitetura](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions) descrevendo cada decisão que você deseja registrar. Consulte outros recursos, como prova de conceitos, resultados de testes de desempenho ou avaliações de produtos, se os tiver.

### Motivação

A motivação para registrar as decisões significativas é que esta seção pode servir como ponto de referência no futuro. Todas as decisões são tomadas em um contexto específico e geralmente têm trade-offs. Geralmente, nunca há uma solução perfeita para um determinado problema. Articular o processo de tomada de decisão após o evento costuma ser complexo, principalmente se você estiver explicando a decisão para pessoas que estão entrando na equipe ou se estiver em um ambiente em que o contexto muda regularmente.

Embora "ninguém nunca seja demitido por comprar a IBM", talvez anotar o fato de que a política corporativa forçou você a usar o IBM WebSphere em vez do Apache Tomcat o salvará de algumas conversas complicadas no futuro.

### Público

O público desta seção é predominantemente o pessoal técnico da equipe de desenvolvimento de software junto com outros que podem ajudar a implantar, dar suporte e operar o sistema de software.

### Obrigatório

Não, mas geralmente incluo esta seção se nós (a equipe) passamos mais do que alguns minutos pensando em algo significativo, como uma escolha de tecnologia ou um estilo arquitetônico. Em caso de dúvida, gaste alguns minutos anotando, especialmente se você trabalha para uma organização de consultoria que está construindo um sistema de software sob um contrato de terceirização para um cliente.