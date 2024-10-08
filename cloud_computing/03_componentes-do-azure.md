# Principais componentes arquitetônicos do Azure

## Regiões

Regiões são a parte física do Azure.

O Azure oferece mais regiões globais do que qualquer outro provedor de nuvem, com mais de 60 regiões representando mais de 140 países.

As regiões são compostas de um ou mais datacenters muito próximos.

Eles fornecem flexibilidade e escala para reduzir a latência do cliente.

As regiões preservam a residência dos dados com uma oferta abrangente de conformidade.

### Pares de Regiões

- São regiões que possuem no mínimo 300 milhas de separação.
- Replicação automática de alguns serviços.
- Recuperação de região priorizada em caso de interrupção.

Cada região possui uma região par, é possível usar a região par para evitar indisponibilidade

### Regiões Soberanas do Azure

As regiões soberanas não estão disponíveis para os clientes.

#### Serviços Governamentais dos EUA

- Atende às necessidades de segurança (Exército) e conformidade das agências federais, governos estaduais e locais dos EUA e seus provedores de soluções.
- Fisicamente isolada de implantações que não sejam do governo dos EUA.
- Acessível somente a pessoal verificado e autorizado.

#### Azure China

- A Microsoft é o primeiro provedor estrangeiro de serviços de nuvem pública da China, em conformidade com as regulamentações governamentais.
- Instância fisicamente separada dos serviços de nuvem do Azure operados pela 21Vianet.
- Todos os dados permanecem dentro da China para garantir a conformidade.

## Recursos do Azure

Os recursos do Azure são componentes que estão disponíveis para criar soluções de nuvem como:

- Contas de Armazenamento
- Máquinas virtuais
- Redes Virtuais
- Serviços de Aplicativos
- Bancos de dados SQL
- Funções

### Grupos de Recursos

É uma maneira de organizar os recursos, onde os recursos que você usa para uma determinada solução
são agrupados e apresentados num painel que os agrupa.

Por exemplo é possível ter um grupo de recursos que atende web e banco de dados outro para máquinas virtuais, ou para armazenamento, entre outros.

O agrupamento pode ser por regiões, por recursos ou por solução. Os recursos podem existir em apenas um grupo de recursos. Os recursos podem existir em diferentes regiões.
Os recursos podem ser movidos para diferentes grupos de recursos (mas não é possível renomeá-los).
Os aplicativos podem utilizar vários grupos de recursos.

Resumo: Um grupo de recursos é um contêiner que você usa para gerenciar e agregar recursos em uma única unidade.

Regras poderão ser aplicadas a um grupo de recursos.

RESUMO:

- Os grupos de recursos podem conter apenas recursos de uma mesma região.

## Assinaturas do Azure

Conta Azure

- Assinatura do desenvolvimento
- Assinatura de teste
- Assinatura de produção

## Hierarquia de grupos de recursos, assinaturas e grupos de gerenciamento



# Exercícios anotados porque não estavam na matéria

1. As zonas de disponibilidade permitem que clientes executem aplicativos essenciais com quais benefícios?

- Alta disponibilidade e Replicação de baixa latência

2. Qual objeto do Microsoft Azure contém **múltiplos datacenters** que são **conectados** por uma **rede de baixa latência**?

- Uma geografia
- **Uma região** (CORRETA)
- Um conjunto de disponibilidade
- Um par

3. Os **conjuntos de disponibilidade** são compostos por quais dos itens a seguir?

- Domínios de atualização
- Uma geografia
- Pares de regiões
- **Domínios de atualização e domínios de falha** (CORRETA)

4. As **zonas de disponibilidade** permitem que clientes executem aplicativos essenciais com quais **benefícios**?

- **Alta disponibilidade e Replicação de baixa latência** (CORRETA)
- Backup externo e Camadas de segurança da rede
- Migração ao vivo
- Segurança de blob

5. É um contêiner que você usa para gerenciar e agregar recursos em uma única unidade. ​

- Zona de Disponibilidade
- Datacenter
- Região
- Grupo de Recursos (CORRETA)
