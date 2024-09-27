# Tipos de Serviços de Nuvem na Azure

Para descobrir qual tipo de serviço atende vamos conhecer cada tipo de serviço.

## Tipos

### IaaS - Infraestrutura como Serviço (Nível de Licença 1)

Um dos serviços mais utilizados é o IaaS.
Ela engloba os servidores de armazenamento, _firewalls_ e segurança da rede e
a planta/prédio físico do _datacenter_.

A IaaS tende a ser recursos e serviço onde os clientes se envolvem mais, como _backup_,
sistemas operacionais, ferramentas para desenvolvedores, análise de negócios.
O cliente é responsável pelos recursos e usar somente a infraestrutura em rede.

Resumo:

- É so serviço de nuvem mais flexível.
- Você configura e gerencia o hardware para o seu aplicativo.

### PaaS - Plataforma como Serviço (Nível de Licença 2)

A Plataforma como Serviço engloba além da infraestrutura os sistemas operacionais e
as ferramentas para desenvolvedores, análise de negócios, gerenciamento de banco de dados.

A preocupação é somente com a aplicação. A PaaS fornece um ambiente para a criação, o teste e a
implantação de aplicativos de software, sem focar no gerenciamento da infraestrutura subjacente.

Resumo:

- É Focado no desenvolvimento de aplicativos.
- O gerenciamento de plataforma é realizado pelo provedor de nuvem.

### SaaS - Software como Serviço (Nível de Licença 3)

Aqui a responsabilidade de configuração e monitoração dos serviços anteriores NÃO são responsabilidades do cliente.

Os usuários se conectam e usam aplicativos com base em nuvem pela Internet.
Por exemplo: _Microsoft Office 365_, _Google Docs_, _Gmail_, e calendários como o _Google Calendar_.

Resumo:

- Modelo de preço de pagamento conforme o uso.
- Os usuários pagam pelo software que utilizam em um modelo de assinatura.

## Modelo de Responsabilidade Compartilhada

A responsabilidade é sempre retida pelo **cliente**

- Informações e dados
- Dispositivos (Móveis e PC)
- Contas e identidades

A responsabilidade varia conforme o tipo

- Infraestrutura de identidade e diretório (Compartilhada entre Cliente e Nuvem)
- Aplicativos (SaaS ou Compartilhada entre Cliente e Nuvem PaaS)
- Controle de Rede (SaaS ou Compartilhada entre Cliente e Nuvem PaaS)
- Sistema Operacional (SaaS e PaaS)

Transferência de responsabilidade para provedores de nuvem

- Hosts Físicos (Responsabilidade da nuvem)
- Rede Física (Responsabilidade da nuvem)
- Data Center Físico (Responsabilidade da nuvem)

Quando tudo for local a responsabilidade para tudo isso é do Cliente.
