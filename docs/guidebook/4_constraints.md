# Restrições

O software vive dentro do contexto do mundo real, e o mundo real tem restrições. Esta seção permite que você declare essas restrições para que fique claro que você está trabalhando dentro delas e como elas afetam suas decisões de arquitetura.

### Intenção

Restrições são normalmente impostas a você, mas não são necessariamente "ruins", pois a redução do número de opções disponíveis geralmente torna seu trabalho de design de software mais fácil. Esta seção permite resumir explicitamente as restrições com as quais você está trabalhando e as decisões que já foram tomadas para você.

### Estrutura

Assim como os atributos de qualidade basta listar as restrições conhecidas e resumi-las brevemente. Exemplos de restrições incluem:

- Tempo, orçamento e recursos.
- Listas de tecnologias aprovadas e restrições tecnológicas.
- Plataforma de implantação alvo.
- Sistemas existentes e padrões de integração.
- Padrões locais (por exemplo, desenvolvimento, codificação, etc.).
- Padrões públicos (por exemplo, HTTP, SOAP, XML, XML Schema, WSDL, etc).
- Protocolos padrão.
- Formatos de mensagem padrão.
- Tamanho da equipe de desenvolvimento de software.
- Perfil de competências da equipe de desenvolvimento de software.
- Natureza do software que está sendo construído (por exemplo, tático ou estratégico).
- Condicionantes políticos.
- Uso de propriedade intelectual interna.
- etc

Se as restrições tiverem um impacto, vale a pena resumi-las (por exemplo, o que são, por que estão sendo impostas e quem as está impondo) e declarar como elas são significativas para sua arquitetura.

### Motivação

As restrições têm o poder de influenciar maciçamente a arquitetura, principalmente se limitarem a tecnologia que pode ser usada para construir a solução. Documentá-los evita que você tenha que responder a perguntas no futuro sobre por que aparentemente tomou algumas decisões estranhas.

### Público

O público desta seção inclui todos os envolvidos com o processo de desenvolvimento de software, já que algumas restrições são técnicas e outras não.

### Obrigatório

Sim, todos os guias de software devem incluir um resumo das restrições, pois geralmente moldam a arquitetura de software resultante de alguma forma. Vale a pena tornar essas restrições explícitas o tempo todo, mesmo em ambientes que possuem um conjunto de restrições muito conhecido (por exemplo, "todo o nosso software é ASP.NET em um banco de dados SQL Server") porque as restrições têm o hábito de mudar com o tempo.