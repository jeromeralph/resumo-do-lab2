# resumo-do-lab2
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

SLA (Service Level Agreement), ou Acordo de Nível de Serviço, é um contrato que define os níveis de serviço esperados entre um provedor de serviços (como um provedor de nuvem) e o cliente. Um dos componentes mais críticos de um SLA é a garantia de disponibilidade, que normalmente é expressa em termos percentuais, como 99%, 99.9%, 99.99%, ou 99.999%. Cada um desses valores corresponde a um tempo máximo de inatividade permitido durante um período de tempo (geralmente um ano).

Aqui está uma explicação dos diferentes níveis de SLA:

1. SLA de 99% de Disponibilidade
Tempo de inatividade permitido por ano: Aproximadamente 87,6 horas (3,65 dias).
Uso típico: Este nível de SLA é comum em serviços menos críticos onde a tolerância à interrupção é um pouco maior.
2. SLA de 99.9% (Três Noves)
Tempo de inatividade permitido por ano: Aproximadamente 8,76 horas.
Uso típico: Comum em aplicações importantes que precisam de alta disponibilidade, mas onde breves períodos de inatividade são aceitáveis.
3. SLA de 99.99% (Quatro Noves)
Tempo de inatividade permitido por ano: Aproximadamente 52,56 minutos.
Uso típico: Usado em sistemas críticos, como plataformas de e-commerce, onde cada minuto de inatividade pode ter um impacto significativo.
4. SLA de 99.999% (Cinco Noves)
Tempo de inatividade permitido por ano: Aproximadamente 5,26 minutos.
Uso típico: Este nível de SLA é usado em ambientes extremamente críticos, como sistemas financeiros ou de saúde, onde quase nenhuma interrupção é tolerável.
Considerações sobre SLA
Custo: Quanto maior a garantia de disponibilidade (mais próximos de 100%), maior o custo do serviço. Isso se deve ao fato de que garantir tempos de inatividade tão baixos exige uma infraestrutura altamente redundante e monitoramento rigoroso.

Arquitetura de Resiliência: Para alcançar SLAs elevados, os provedores de serviços geralmente utilizam técnicas como redundância, failover automático, e replicação geográfica de dados.

Penalidades: Muitos SLAs incluem cláusulas onde, se o provedor não conseguir atingir o nível de serviço acordado, o cliente poderá receber compensações, como créditos no serviço.

Ao escolher um nível de SLA, as organizações devem balancear entre o custo e a criticidade da aplicação, garantindo que o nível de disponibilidade escolhido seja adequado para as necessidades do negócio.
