# Arquitetura de Software

A seção de arquitetura de software é sua visão geral e permite que você apresente a estrutura do software. Os documentos tradicionais de arquitetura de software geralmente se referem a isso como uma "visão conceitual" ou "visão lógica", e muitas vezes há confusão sobre se tais visões devem se referir a detalhes de implementação, como escolhas de tecnologia.

### Intenção

O objetivo desta seção é resumir a arquitetura de software do seu sistema de software para que as seguintes perguntas possam ser respondidas:

- Como é o "quadro geral"?
- Existe uma estrutura clara?
- Está claro como o sistema funciona a partir da "visão de 30.000 pés"?
- Mostra os principais contêineres e opções de tecnologia?
- Mostra os principais componentes e suas interações?
- Quais são as principais interfaces internas? (por exemplo, um serviço da web entre suas camadas da web e de negócios)

### Estrutura

Eu uso o container e componente diagramas como o foco principal desta seção, acompanhados por uma breve narrativa explicando o que o diagrama está mostrando, além de um resumo de cada contêiner/componente.

Às vezes, diagramas de sequência ou colaboração UML mostrando interações de componentes podem ser uma maneira útil de ilustrar como o software satisfaz os principais casos de uso/histórias de usuários/etc. Só faça isso se agregar valor e resista à tentação de descrever como *cada* caso de uso/história de usuário funciona!

### Motivação

A motivação para escrever esta seção é que ela fornece os mapas que as pessoas podem usar para obter uma visão geral do software e ajudar os desenvolvedores a navegar na base de código.

### Público

O público desta seção é predominantemente o pessoal técnico da equipe de desenvolvimento de software.

### Obrigatório

Sim, todos os guias de software devem incluir uma seção de arquitetura de software porque é essencial que a estrutura geral do software seja bem compreendida por todos na equipe de desenvolvimento.