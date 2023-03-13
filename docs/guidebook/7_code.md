# Código

Embora outras seções do guia de software descrevam a arquitetura geral do software, muitas vezes você desejará apresentar detalhes de nível inferior para explicar como as coisas funcionam. É para isso que serve a seção de código. Alguns modelos de documentação de arquitetura de software chamam isso de "visão de implementação" ou "visão de desenvolvimento".

### Intenção

O objetivo da seção de código é descrever os detalhes de implementação de partes do sistema de software que são importantes, complexas, significativas, etc. Por exemplo, escrevi sobre o seguinte para projetos de software em que estive envolvido:

- Gerando/renderizando HTML: uma breve descrição de um framework interno que foi criado para gerar HTML, incluindo as principais classes e conceitos.
- Vinculação de dados: nossa abordagem para atualizar objetos de negócios como resultado de solicitações HTTP POST.
- Coleta de dados de várias páginas: uma breve descrição de uma estrutura interna que usamos para criar formulários que abrangem várias páginas da web.
- Web MVC: um exemplo de uso do framework web MVC que estava sendo utilizado.
- Segurança: nossa abordagem para usar o Windows Identity Foundation (WIF) para autenticação e autorização.
- Modelo de domínio: uma visão geral das partes importantes do modelo de domínio.
- Component framework: uma breve descrição do framework que construímos para permitir que os componentes sejam reconfigurados em tempo de execução.
- Configuração: uma breve descrição do mecanismo de configuração do componente padrão em uso na base de código.
- Camadas arquitetônicas: uma visão geral da estratégia de camadas e os padrões usados para implementá-la.
- Exceções e registro: um resumo de nossa abordagem para tratamento de exceção e registro em várias camadas arquitetônicas.
- Padrões e princípios: uma explicação de como padrões e princípios são implementados.
- etc

### Estrutura

Mantenha-o simples, com uma seção curta para cada elemento que você deseja descrever e inclua diagramas se eles ajudarem o leitor. Por exemplo, uma classe UML de alto nível e/ou diagrama de sequência pode ser útil para ajudar a explicar como funciona uma estrutura interna sob medida. Resista à tentação de incluir todos os detalhes e não sinta que seus diagramas precisam mostrar tudo. Prefiro gastar alguns minutos esboçando um diagrama de classe UML de alto nível que mostre atributos e métodos selecionados (importantes) em vez de usar os diagramas complexos que podem ser gerados automaticamente a partir de sua base de código com ferramentas UML ou plug-ins IDE. Manter os diagramas com alto nível de detalhamento significa que eles são menos voláteis e permanecem atualizados por mais tempo porque podem tolerar pequenas alterações no código e, ainda assim, permanecer válidos.

### Motivação

A motivação para escrever esta seção é garantir que todos entendam como as partes importantes/significativas/complexas do sistema de software funcionam para que possam mantê-las, aprimorá-las e ampliá-las de maneira consistente e coerente. Esta seção também ajuda os novos membros da equipe a se familiarizarem rapidamente.

### Público
O público desta seção é predominantemente o pessoal técnico da equipe de desenvolvimento de software.

### Obrigatório
Não, mas geralmente incluo esta seção para qualquer coisa que não seja um sistema de software trivial.