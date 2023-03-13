# Atributos de Qualidade

Com a seção de visão geral funcional resumindo a funcionalidade, também vale a pena incluir uma seção separada para resumir os atributos de qualidade /requisitos não Funcionais.

### Intenção

Esta seção resume os principais atributos de qualidade e deve responder aos seguintes tipos de perguntas:

- Existe uma compreensão clara dos atributos de qualidade que a arquitetura deve satisfazer?
- Os atributos de qualidade são SMART (específicos, mensuráveis, alcançáveis, relevantes e oportunos)?
- Os atributos de qualidade que geralmente são considerados garantidos foram explicitamente marcados como fora do escopo se não forem necessários? (por exemplo, "os elementos da interface do usuário serão apresentados apenas em inglês" para indicar que o suporte multilíngue não é explicitamente atendido)
- Algum dos atributos de qualidade não é realista? (por exemplo, a disponibilidade real 24 horas por dia, 7 dias por semana costuma ser muito cara para implementar *dentro* de muitas organizações)

Além disso, se algum dos atributos de qualidade for considerado "arquitetonicamente significativo" e, portanto, influenciar a arquitetura, por que não anotá-los para que você possa consultá-los posteriormente no documento.

### Estrutura

Simplesmente listar cada um dos atributos de qualidade é um bom ponto de partida. Exemplos incluem:

- Desempenho (por exemplo, latência e taxa de transferência)
- Escalabilidade (por exemplo, dados e volumes de tráfego)
- Disponibilidade (por exemplo, tempo de atividade, tempo de inatividade, manutenção programada, 24 horas por dia, 7 dias por semana, 99,9%, etc.)
- Segurança (por exemplo, autenticação, autorização, confidencialidade de dados, etc.)
- Extensibilidade
- Flexibilidade
- Auditoria
- Monitoramento e gerenciamento
-   Confiabilidade
- Alvos de recuperação de falhas/desastres (por exemplo, manual x automático, quanto tempo isso levará?)
- Continuidade do negócio
- Interoperabilidade
- Requisitos legais, de conformidade e regulamentares (por exemplo, lei de proteção de dados)
- Internacionalização (i18n) e localização (L10n)
- Acessibilidade
- Usabilidade
- ...

Cada atributo de qualidade deve ser preciso, não deixando nenhuma interpretação para o leitor. Exemplos onde este não é o caso incluem:

- "o pedido deve ser atendido rapidamente"
- "não deve haver sobrecarga"
-   "o mais rápido possível"
- "o menor possível"
- "tantos clientes quanto possível"
- ...

### Motivação

Se você é um bom cidadão da arquitetura de software e considerou proativamente os atributos de qualidade, por que não escrevê-los também? Normalmente, os atributos de qualidade não são dados a você em um prato e uma quantidade de exploração e refinamento geralmente é necessária para criar uma lista deles. Simplificando, anotar os atributos de qualidade remove qualquer ambiguidade agora e durante o trabalho de manutenção/aprimoramento no futuro.

### Público

Como os atributos de qualidade são principalmente de natureza técnica, esta seção é realmente voltada para pessoas técnicas da equipe de desenvolvimento de software.

### Obrigatório

Sim, todos os guias de software devem incluir um resumo dos atributos de qualidade/requisitos não funcionais, pois eles geralmente moldam a arquitetura de software resultante de alguma forma.