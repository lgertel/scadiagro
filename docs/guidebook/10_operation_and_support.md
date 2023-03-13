# Operação e Suporte

A seção de operações e suporte permite que você descreva como as pessoas executarão, monitorarão e gerenciarão seu software.

### Intenção

A maioria dos sistemas estará sujeita a requisitos operacionais e de suporte, particularmente sobre como eles são monitorados, gerenciados e administrados. A inclusão de uma seção dedicada no guia do software permite que você seja explícito sobre como seu software suportará ou suporta esses requisitos. Esta seção deve abordar os seguintes tipos de perguntas:

- Está claro como o software permite que as equipes de operação/suporte monitorem e gerenciem o sistema?
- Como isso é alcançado em todas as camadas da arquitetura?
- Como o pessoal operacional pode diagnosticar problemas?
- Onde são registrados os erros e informações? (por exemplo, arquivos de log, log de eventos do Windows, SMNP, JMX, WMI, diagnósticos personalizados, etc.)
- As alterações de configuração requerem uma reinicialização?
- Existem tarefas manuais de limpeza que precisam ser executadas regularmente?
- Os dados antigos precisam ser arquivados periodicamente?

### Estrutura

Esta seção geralmente é bastante narrativa por natureza, com um cabeçalho para cada conjunto de informações relacionadas (por exemplo, monitoramento, diagnóstico, configuração, etc.).

### Motivação

Já realizei auditorias de sistemas de software existentes no passado e tivemos que gastar tempo procurando informações básicas, como localizações de arquivos de log. Os tempos mudam e os membros da equipe seguem em frente, portanto, registrar essas informações pode ajudar a evitar situações futuras em que ninguém entenderá como operar o software.

### Público

O público desta seção é predominantemente o pessoal técnico da equipe de desenvolvimento de software junto com outros que podem ajudar a implantar, dar suporte e operar o sistema de software.

### Obrigatório

Sim, uma seção de operações e suporte deve ser incluída em todos os guias de software, a menos que você goste de jogar software em um buraco negro e esperar pelo melhor!