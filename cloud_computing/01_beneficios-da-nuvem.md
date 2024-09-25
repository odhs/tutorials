# Nuvem

AZ-900: Introdução so Conceitos Básicos do Microsoft Azure

## Benefícios da Nuvem

- Alta disponibilidade e Escalabilidade.
- Confiabilidade e Previsibilidade.
- Segurança e Governança.
- Capacidade de gerenciamento.

### Alta disponibilidade

A alta disponibilidade se concentra em garantir a disponibilidade máxima, independente de interrupções ou eventos que possam ocorrer.

É um sistema com recursos disponíveis sempre que necessário.
Há um contrato chamado de SLA - _Service Level Agreement_ que determina o tempo de disponibilidade permitido. Por exemplo, para o SLA de 99% corresponde a 7h20min no mês.
Caso o provedor de serviço não entregue o serviço contrato fornecerá ao usuário um voucher de crédito para ser usado no próprio Microsoft Azure.

Há um website que informa o que está acontecendo no sistema caso o próprio sistema de painel de controle caia.

### Escalabilidade

ADICIONA HARDWARE

A escalabilidade refere-se a capacidade de ajustar recursos para atender a demanda,
adicionando recursos para lidar melhor com o aumento da demanda.

Você paga apenas pelo o que consome. Se a demanda cair você reduzir os recursos, reduzindo o custo.

Escalabilidade é vertical, é hardware, você aumenta memória RAM e número de processadores.

### Elasticidade

ADICIONA SOFTWARE

Com a elasticidade você expande seus recursos horizontalmente, isto é, você pode adicionar máquinas virtuais ou containers por meio da expansão, de maneira automática ou manual.

### Confiabilidade

Devido ao design decentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente, ela permite que você tenha recursos implantados em várias regiões do mundo.

Se ocorrer um evento catastrófico em uma região as outras regiões ainda estarão funcionando.

### Previsibilidade

A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo.
Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework.

### Segurança

A nuvem oferece muitas ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.

**Se você quiser o controle máximo da segurança**, a _infraestrutura como serviço_ fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção.

Se você quiser que a aplicação de patches e a manutenção sejam automáticas então você vai utilizar o _software como serviço_.

### Governança

A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus **padrões corporativos** e fornece estratégias de mitigação.
Dependendo do seu modelo operacional, patches de segurança e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.

Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

A segurança pode criar as regras e a governança implementar, porém sempre haverá uma linha tênue entre quem faz o que, dependendo do modelo que a empresa implementou.

### Gerenciabilidade

Facilita o gerenciamento dos recursos em nuvem.
Há dois tipos de capacidade de gerenciamento para computação em nuvem:

1) Escalar automaticamente a implantação de recursos com base na necessidade.

Implantar recursos com base em um modelo pré configurado, removendo a necessidade de configuração manual.
É possível criar:

- Usando API
- Usando o PowerShell
