# Arquitetura de Infraestrutura

Embora a maior parte do guia de software seja focada no software em si, também precisamos considerar a infraestrutura porque a arquitetura de software é sobre software *e* infraestrutura.

### Intenção

Esta seção é usada para descrever o hardware físico/virtual e as redes nas quais o software será implantado. Embora, como arquiteto de software, você não esteja envolvido no projeto da infraestrutura, você precisa entender que isso é suficiente para permitir que você atinja seus objetivos. O objetivo desta seção é responder aos seguintes tipos de perguntas:

- Existe uma arquitetura física clara?
- Que hardware (virtual ou físico) isso inclui em todas as camadas?
- Atende a redundância, failover e recuperação de desastres, se aplicável?
- Está claro como os componentes de hardware escolhidos foram dimensionados e selecionados?
- Se vários servidores e sites forem usados, quais são os links de rede entre eles?
- Quem é responsável pelo suporte e manutenção da infraestrutura?
- Existem equipes centrais para cuidar da infraestrutura comum (por exemplo, bancos de dados, barramentos de mensagens, servidores de aplicativos, redes, roteadores, switches, balanceadores de carga, proxies reversos, conexões de internet, etc)?
- Quem é o dono dos recursos?
- Existem ambientes suficientes para desenvolvimento, teste, aceitação, pré-produção, produção, etc?

### Estrutura

O foco principal desta seção é geralmente um diagrama de infraestrutura/rede mostrando os vários componentes de hardware/rede e como eles se encaixam, com uma breve narrativa para acompanhar o diagrama. Se estou trabalhando em uma grande organização, geralmente há arquitetos de infraestrutura que cuidam da arquitetura de infraestrutura e criam esses diagramas para mim. Às vezes, esse não é o caso e eu mesmo os desenharei.

### Motivação

A motivação para escrever esta seção é me forçar (o arquiteto de software) a sair da minha zona de conforto e pensar sobre a arquitetura da infraestrutura. Se eu não entender, há uma chance de que a arquitetura de software que estou criando não funcione ou que a infraestrutura existente não suporte o que estou tentando fazer.

### Público

O público desta seção é predominantemente o pessoal técnico da equipe de desenvolvimento de software junto com outros que podem ajudar a implantar, dar suporte e operar o sistema de software.

### Obrigatório

Sim, uma seção de arquitetura de infraestrutura deve ser incluída em todos os guias de software porque ilustra que a infraestrutura foi compreendida e considerada.