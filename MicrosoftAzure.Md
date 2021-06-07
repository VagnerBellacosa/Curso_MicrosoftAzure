# Microsoft Azure

## O que é o Azure?

A plataforma de nuvem do Azure consiste em mais de 200 produtos e serviços de nuvem projetados para ajudar você a dar vida às novas soluções para resolver os desafios atuais e criar o futuro. Crie, execute e gerencie aplicativos em várias nuvens, locais e na borda, com as ferramentas e as estruturas de sua escolha.

## Guia de introdução para desenvolvedores do Azure

### O que é o Azure?

O Azure é uma plataforma de nuvem completa que pode hospedar seus aplicativos existentes e simplificar o desenvolvimento de novos aplicativos. O Azure pode até mesmo aprimorar os aplicativos locais. O Azure integra os serviços de nuvem necessários para desenvolver, testar, implantar e gerenciar seus aplicativos aproveitando as eficiências da computação em nuvem.

Ao hospedar seus aplicativos no Azure, você pode começar por algo pequeno e facilmente escalar seu aplicativo à medida que aumenta a demanda do cliente. O Azure também oferece a confiabilidade necessária para aplicativos de alta disponibilidade, incluindo failover entre diferentes regiões. O portal do Azure permite que você gerencie facilmente todos os serviços do Azure. Além disso, também é possível gerenciar seus serviços programaticamente, utilizando modelos e APIs e específicos do serviço.

Este guia é uma introdução à plataforma Azure para desenvolvedores de aplicativos. Este guia fornece diretrizes e direção necessárias para começar a criar novos aplicativos no Azure ou migrar aplicativos existentes para o Azure.

#### Por onde começo?

Com todos os serviços que o Azure oferece, pode ser uma tarefa assustadora descobrir quais serviços são necessários para suportar a arquitetura da solução. Esta seção destaca os serviços do Azure que normalmente são utilizados pelos desenvolvedores. Para obter uma lista de todos os serviços do Azure, consulte a Documentação do Azure.

Primeiro, você deve decidir como hospedar o aplicativo no Azure. É necessário gerenciar toda a infraestrutura como uma máquina virtual (VM)? É possível utilizar as instalações de gerenciamento da plataforma que o Azure fornece? Você precisa de uma estrutura sem servidor para hospedar a execução de código somente?

Seu aplicativo precisa de armazenamento em nuvem para qual o Azure oferece várias opções. Você pode usufruir da autenticação empresarial do Azure. Além disso, há ferramentas para monitoramento e desenvolvimento baseado em nuvem e a maioria dos serviços de hospedagem oferece integração DevOps.

Agora, vejamos alguns dos serviços específicos que recomendamos investigar para suas aplicações.

### Hospedagem de aplicativos

O Azure fornece várias ofertas de computação baseada em nuvem para executar seu aplicativo, de modo que você não precise se preocupar com os detalhes da infraestrutura. Você pode facilmente escalar verticalmente ou escalar horizontalmente seus recursos à medida que o uso do aplicativo aumenta.

O Azure oferece serviços que dão suporte ao desenvolvimento de aplicativos e necessidades de hospedagem. O Azure fornece IaaS (Infraestrutura como Serviço) para oferecer-lhe controle total sobre a hospedagem do aplicativo. As ofertas de Plataforma como Serviço (PaaS) do Azure fornecem os serviços totalmente gerenciados necessários para potencializar seus aplicativos. Há, inclusive, verdadeira hospedagem sem servidor no Azure, onde tudo o que você precisa fazer é escrever seu código.

####  Opções de hospedagem de aplicativo do Azure

- Customer-managed (IaaS)
- Platform-managed (PaaS)
- Code-only (serveless)

#### Serviço de aplicativo do Azure

Ao buscar o caminho mais rápido para publicar seus projetos baseados na web, considere o Serviço de Aplicativo do Azure. O Serviço de Aplicativo facilita a extensão de seus aplicativos Web para oferecer suporte aos clientes móveis e publicar facilmente as APIs REST consumidas. Essa plataforma fornece autenticação utilizando provedores sociais, dimensionamento automático baseado em tráfego, teste em produção e implantações baseadas em contêiner e contínuas.

Você pode criar aplicativos Web, back-ends de aplicativos móveis e aplicativos de API.

Como todos os três tipos de aplicativos compartilham o runtime do Serviço de Aplicativo, é possível hospedar um site, oferecer suporte a clientes móveis e expor suas APIs no Azure, tudo a partir do mesmo projeto ou solução. Para saber mais sobre o Serviço de Aplicativo, consulte O que são Aplicativos Web do Azure.

O Serviço de Aplicativo foi projetado com o DevOps em mente. Ela dá suporte a várias ferramentas de publicação e implantações contínuas de integração. Essas ferramentas incluem WebHooks do GitHub, Jenkins, Azure DevOps, TeamCity e outros.

É possível migrar seus aplicativos existentes para o Serviço de Aplicativo, utilizando a ferramenta de migração online.

Quando utilizar: utilize o Serviço de Aplicativo ao migrar aplicativos Web existentes para o Azure e quando precisar de uma plataforma de hospedagem totalmente gerenciada para seus aplicativos Web. Al´me disso, é possível utilizar o Serviço de Aplicativo quando precisar dar suporte a clientes móveis ou expor APIs REST com seu aplicativo.

Introdução: O Serviço de Aplicativo facilita a criação e implantação de seu primeiro aplicativo Web, aplicativo móvel ou aplicativo de API.

Experimente agora: o Serviço de Aplicativo permite que você forneça um aplicativo de curta duração para experimentar a plataforma sem precisar inscrever-se em uma conta do Azure. Experimente a plataforma e crie seu aplicativo do Serviço de Aplicativo do Azure.

### Máquinas Virtuais do Azure

Como um provedor da IaaS (Infraestrutura como Serviço), o Azure permite implantar ou migrar seu aplicativo para VMs Linux ou Windows. Juntamente com a Rede Virtual do Azure, as Máquinas Virtuais do Azure dão suporte para a implantação de VMs Linux ou Windows para o Azure. Com VMs, você tem total controle sobre a configuração da máquina. Ao utilizar VMs, você será responsável por toda a instalação de software para servidores, configuração, manutenção e patches do sistema operacional.

Devido ao nível de controle que você possui com VMs, será possível executar uma ampla gama de cargas de trabalho do servidor no Azure que não se ajustam em um modelo de PaaS. Essas cargas de trabalho incluem servidores de banco de dados, Windows Server Active Directory e Microsoft SharePoint. Para obter mais informações, consulte a documentação sobre Máquinas Virtuais para Linux ou Windows.

Quando utilizar: utilize Máquinas Virtuais quando quiser ter um controle total sobre a infraestrutura do aplicativo ou migrar cargas de trabalho do aplicativo local para o Azure sem precisar fazer alterações.

 Introdução: Criar uma VM Linux ou VM Windows a partir do portal do Azure.

#### Azure Functions (sem servidor)

Em vez de se preocupar em criar e gerenciar um aplicativo inteiro ou a infraestrutura para executar seu código, e se você pudesse apenas escrever seu código e executá-lo em resposta a eventos ou agendar? Azure Functions é uma oferta de estilo "sem servidor" que permite escrever apenas o código que você precisa. Com o Functions, a execução do código é disparada por solicitações HTTP, webhooks, eventos de serviço de nuvem ou em um agendamento. É possível codificar em sua linguagem de desenvolvimento de preferência, como C#, F#, Node.js, Python ou PHP. Com a cobrança baseada no consumo, você paga apenas pelo tempo que seu código é executado, e escalas do Azure, conforme necessário.

Quando utilizar: utilize o Azure Functions quando tiver um código disparado por outros serviços do Azure, por eventos baseados na Web ou em um agendamento. Também é possível utilizar o Azure Functions quando não há necessidade de sobrecarga de um projeto hospedado completo ou quando você somente quer pagar o tempo que o código é executado. Para saber mais, consulte Visão Geral do Azure Functions.

Introdução: Seguir o tutorial de iniciação rápida do Azure Functions para criar sua primeira função a partir do portal.

Experimente agora: o Azure Functions permite que você execute seu código sem precisar inscrever-se em uma conta do Azure. Experimente agora em e crie sua primeira função do Azure.

### Azure Service Fabric

O Azure Service Fabric é uma plataforma de sistemas distribuídos. Essa plataforma faz com que seja fácil compilar, empacotar, implantar e gerenciar microsserviços escalonáveis e confiáveis. Ela também fornece recursos abrangentes de gerenciamento de aplicativos, como:

- Provisionamento
- Implantando
- Monitoramento
- Atualização/aplicação de patch
- Excluindo

Os aplicativos executados em um pool compartilhado de máquinas podem começar pequenos e escalar para centenas ou milhares de máquinas, conforme necessário.

O Service Fabric dá suporte para WebAPI com Open Web Interface para .NET (OWIN) e ASP.NET Core. Ele fornece SDKs para a construção de serviços no Linux em tanto em .NET Core como Java. Para saber mais sobre o Service Fabric, consulte a documentação do Service Fabric.

Quando utilizar: o Service Fabric é uma boa escolha quando você está criando um aplicativo ou reescrevendo um aplicativo existente para utilizar uma arquitetura de microsserviço. Utilize o Service Fabric quando precisar de mais controle ou acesso direto à infraestrutura subjacente.

Introdução: Criar seu primeiro aplicativo Azure Service Fabric.

### Azure Spring Cloud

O Azure Spring Cloud é uma plataforma de microsserviço sem servidor que permite compilar, implantar, dimensionar e monitorar seus aplicativos na nuvem. Use o Spring Cloud para trazer padrões de microatendimento modernos para aplicativos Spring Boot, eliminando o código clichê para criar rapidamente aplicativos Java robustos.

- Aproveite as versões gerenciadas do servidor de descoberta e configuração do Spring Cloud Service, enquanto garantimos que esses componentes críticos estejam sendo executados em condições ideais.

- Concentre-se na criação de sua lógica de negócios e cuidaremos do tempo de execução de seu serviço com patches de segurança, padrões de conformidade e alta disponibilidade.

- Gerencie o ciclo de vida do aplicativo (por exemplo: implantar, iniciar, parar, dimensionar) na parte superior do Serviço de Kubernetes do Azure.

- Associe facilmente as conexões entre seus aplicativos e os serviços do Azure, como o Banco de Dados do Azure para MySQL e o Cache do Azure para Redis.

- Monitore e solucione problemas de microsserviços e aplicativos usando ferramentas de monitoramento unificado de nível empresarial que oferecem informações aprofundadas sobre dependências de aplicativos e telemetria operacional.

Quando usar: como um serviço totalmente gerenciado, o Azure Spring Cloud é uma boa opção quando você está minimizando os custos operacionais que executam microsserviços baseados em Spring Boot/Spring Cloud no Azure.

Guia de início rápido Implantar o seu primeiro aplicativo Azure Spring Cloud.

## Aprimore seus aplicativos com os serviços do Azure

Junto com a hospedagem de aplicativos, o Azure fornece ofertas de serviço que podem aprimorar a funcionalidade. O Azure também pode melhorar o desenvolvimento e a manutenção dos seus aplicativos, tanto na nuvem quando no local.

### Armazenamento hospedado e acesso a dados

A maioria dos aplicativos deve armazenar dados, portanto, independentemente de como você decidir hospedar o aplicativo no Azure, considere um ou mais dos seguintes serviços de dados e armazenamento.

- Azure Cosmos DB um serviço de banco de dados multimodelo globalmente distribuído. Ele é projetado para se dimensionar de modo elástico e independente o armazenamento e a taxa de transferência em quaisquer regiões geográficas com um SLA abrangente.

Quando usar: quando seu aplicativo precisa de bancos de dados de documento, de tabela ou de grafo, incluindo bancos de dados MongoDB, com vários modelos de consistência bem definidos.

Introdução: compilar um aplicativo Web do Azure Cosmos DB. Se você for um desenvolvedor do MongoDB, consulte Compilar um aplicativo Web do MongoDB com o Azure Cosmos DB.

- Armazenamento do Azure: oferece armazenamento durável e altamente disponível para blobs, filas, arquivos e outros tipos de dados não relacionais. O armazenamento fornece a base de armazenamento para VMs.

Quando utilizar: quando seu aplicativo armazena dados não relacionais, como pares chave-valor (tabelas), blobs, compartilhamentos de arquivos ou mensagens (filas).

Introdução: escolher entre um desses tipos de armazenamento: blobs, tabelas, filas ou arquivos.

- Banco de Dados SQL do Azure: uma versão baseada no Azure do mecanismo do Microsoft SQL Server para armazenar dados tabulares relacionais na nuvem. O Banco de Dados SQL fornece desempenho previsível, escalabilidade sem tempo de inatividade, continuidade dos negócios e proteção de dados.

Quando utilizar: quando seu aplicativo requer armazenamento de dados com integridade referencial, suporte transacional e suporte para consultas TSQL.

Introdução: criar um banco de dados no Banco de Dados SQL do Azure em minutos utilizando o portal do Azure.

É possível utilizar o Azure Data Factory para mover dados locais existentes para o Azure. Caso não esteja pronto para mover dados para a nuvem, as Conexões Híbridas no Serviço de Aplicativo do Azure permitem que você conecte o Serviço de Aplicativo hospedado aos recursos locais. Além disso, é possível conectar-se aos dados do Azure e aos serviços de armazenamento a partir de seus aplicativos locais.

## Suporte ao Docker

Os contêineres do Docker, uma forma de virtualização de SO, permitem implantar aplicativos de forma mais eficiente e previsível. Um aplicativo em contêineres funciona em produção da mesma maneira que em seus sistemas de desenvolvimento e teste. É possível gerenciar contêineres utilizando ferramentas do Docker padrão. Você pode utilizar suas ferramentas de software livre populares e habilidades existentes para implantar e gerenciar aplicativos baseados em contêineres no Azure.

O Azure fornece várias maneiras de utilizar contêineres em seus aplicativos.

- Serviço de Kubernetes do Azure: permite criar, configurar e gerenciar um cluster de máquinas virtuais pré-configuradas para executar aplicativos em contêineres. Para saber mais sobre o Serviço de Kubernetes do Azure, consulte introdução ao Serviço de Kubernetes do Azure.

Quando utilizar: quando for necessário criar ambientes escalonáveis prontos para produção que fornecem ferramentas de gerenciamento e agendamento adicionais ou, quando estiver implantando um cluster Docker Swarm.

Introdução: : implantar um cluster do Serviço de Kubernetes.

- Máquina do Docker: permite instalar e gerenciar um Mecanismo de Docker em hosts virtuais utilizando comandos docker-machine.

Quando utilizar: quando for necessário desenvolver rapidamente protótipo de um aplicativo criando um host do Docker único.

- Imagem de Docker personalizada para Serviço de Aplicativo: permite utilizar contêineres do Docker de um registro de contêiner ou um contêiner de cliente ao implantar um aplicativo Web no Linux.

Quando utilizar: ao implantar um aplicativo Web no Linux para uma imagem de Docker.

Introdução: Utilizar uma imagem de Docker personalizada para Serviço de Aplicativo no Linux.

## Autenticação

É crucial não apenas saber quem está utilizando seus aplicativos, como também impedir o acesso não autorizado aos seus recursos. O Azure fornece várias maneiras de autenticar os clientes do aplicativo.

- Azure AD (Azure Active Directory): o serviço de gerenciamento de acesso e identidade baseado em nuvem multilocatário da Microsoft. É possível adicionar SSO (login único) aos seus aplicativos integrando com o Azure AD. É possível acessar as propriedades do diretório utilizando diretamente a API do Graph do Azure AD ou a API do Microsoft Graph. É possível integrar com o suporte do Azure AD para a estrutura de autorização OAuth2.0 e Open ID Connect, utilizando os pontos de extremidade HTTP/REST nativos e as bibliotecas multiplataformas de autenticação do Azure AD.

Quando utilizar: quando quiser fornecer uma experiência de SSO, trabalhe com dados baseados em grafo ou autentique usuários baseados em domínio.

Introdução: Para saber mais, consulte o Guia do desenvolvedor do Azure Active Directory.

- Autenticação do Serviço de Aplicativo: ao escolher o Serviço de Aplicativo para hospedar seu aplicativo, você também obterá suporte de autenticação interna para o Azure AD, juntamente com provedores de identidade social — incluindo Facebook, Google, Microsoft e Twitter.

Quando utilizar: quando quiser habilitar a autenticação em um aplicativo do Serviço de Aplicativo utilizando o Azure AD, os provedores de identidade social ou ambos.

Introdução: Para saber mais sobre a autenticação no Serviço de Aplicativo, consulte Autenticação e autorização no Serviço de Aplicativo do Azure.

Para saber mais sobre as melhores práticas de segurança no Azure, consulte Padrões e melhores práticas de segurança do Azure.

## Monitoramento

Com seu aplicativo instalado e executando no Azure será necessário monitorar o desempenho, inspecionar problemas e observar como os clientes estão utilizando seu aplicativo. O Azure fornece várias opções de monitoramento.

- Application Insights: um serviço de análise extensível hospedado no Azure que se integra com o Visual Studio para monitorar seus aplicativos Web em tempo real. Ele fornece os dados necessários para melhorar o desempenho e a usabilidade de seus aplicativos continuamente. Essa melhoria ocorre se você hospeda seus aplicativos no Azure ou não.

Introdução: Seguir o tutorial do Application Insights.

- Azure Monitor: um serviço que ajuda a visualizar, consultar, rotear, arquivar e atuar nas métricas e logs que são gerados pelos recursos e pela infraestrutura do Azure. O Monitor fornece as exibições de dados que são visualizadas no portal do Azure e é uma fonte única para monitorar os recursos do Azure.

Introdução: Introdução ao Azure Monitor.

## Integração de DevOps

Quer seja provisionando VMs ou publicando seus aplicativos Web com integração contínua, o Azure se integra com a maioria das ferramentas de DevOps populares. Você pode trabalhar com as ferramentas que você já tem e maximizar sua experiência existente com suporte para ferramentas como:

- Jenkins
- GitHub
- Puppet
- Chef
- TeamCity
- Ansible
- Azure DevOps

Introdução: Para consultar as opções de DevOps para um aplicativo do Serviço de Aplicativo, consulte Implantação contínua para Serviço de Aplicativo do Azure.

Experimente agora: Experimente várias das integrações DevOps.

## Regiões do Azure

O Azure é uma plataforma de nuvem global que geralmente está disponível em muitas regiões em todo o mundo. Quando você provisiona um serviço, aplicativo ou VM no Azure, é solicitado que você selecione uma região. Essa região representa um datacenter específico em que seu aplicativo é executado ou onde os dados estão armazenados. Essas regiões correspondem a locais específicos, os quais são publicados na página Regiões do Azure.

### Escolha a melhor região para seu aplicativo e dados

Um dos benefícios de utilizar o Azure é que você pode implantar seus aplicativos em vários datacenters em todo o mundo. A região que você escolher poderá afetar o desempenho do aplicativo. Por exemplo, é melhor escolher uma região que esteja mais próxima da maioria dos seus clientes para reduzir a latência nas solicitações de rede. Talvez você queira selecionar sua região para cumprir os requisitos legais para distribuir seu aplicativo em determinados países/regiões. Sempre a melhor prática será armazenar os dados do aplicativo no mesmo datacenter ou em um datacenter o mais próximo possível do datacenter que hospeda o aplicativo.

### Aplicativos de várias regiões
Embora seja improvável, não é impossível que todo um datacenter fique offline devido a um evento como um desastre natural ou uma falha na internet. Uma prática recomendada é hospedar aplicativos de negócios vitais em mais de um datacenter para fornecer a máxima disponibilidade. Utilizar várias regiões também pode reduzir a latência para usuários globais e oferecer oportunidades adicionais de flexibilidade ao atualizar aplicativos.

Alguns serviços, como Máquina Virtual e Serviços de Aplicativos utilizam o Gerenciador de Tráfego do Azure para habilitar o suporte de várias regiões com failover entre regiões para suportar aplicativos empresariais de alta disponibilidade. Por exemplo, consulte Arquitetura de referência do Azure: executar um aplicativo Web em várias regiões.

Quando utilizar: quando você tiver aplicativos empresariais de alta disponibilidade que beneficiam-se de failover e replicação.

## Como fazer para gerenciar meus aplicativos e projetos?

O Azure fornece um avançado conjunto de experiências para você criar e gerenciar seus projetos, aplicativos e recursos do Azure — tanto programaticamente, quanto no portal do Azure.

### Interfaces de linha de comando e PowerShell

O Azure fornece duas maneiras de gerenciar seus aplicativos e serviços na linha de comando. Você pode usar ferramentas como Bash, Terminal, o prompt de comando ou sua ferramenta de linha de comando de sua escolha. Normalmente, é possível executar as mesmas tarefas a partir da linha de comando do portal do Azure — como criar e configurar máquinas virtuais, redes virtuais, aplicativos Web e outros serviços.

CLI do Azure: permite conectar-se a uma assinatura do Azure e programar várias tarefas em relação aos recursos do Azure a partir da linha de comando.

Azure PowerShell: fornece um conjunto de módulos com cmdlets que permitem gerenciar recursos do Azure utilizando o Windows PowerShell.

#### Portal do Azure

O portal do Azure é um aplicativo baseado na Web. Você pode usar o portal do Azure para criar, gerenciar e remover recursos e serviços do Azure. Ele inclui:

- Um painel configurável
- Gerenciamento de recursos do Azure
- Acesso a configurações de assinatura e informações de cobrança. Para obter mais informações, consulte a Visão geral do portal do Azure.

### APIs REST

O Azure é desenvolvido em um conjunto de APIs REST que suportam a interface do usuário do Portal do Azure. A maioria dessas APIs REST também é suportada para permitir que você programa e gerencie seus recursos e aplicativos do Azure a partir de qualquer dispositivo habilitado para Internet. Para o conjunto completo da documentação de API REST, consulte a Referência de SDK do REST do Azure.

#### APIs

Além das APIs REST, muitos serviços do Azure também permitem que você gerencie recursos de seus aplicativos utilizando SDKs do Azure específicos da plataforma, incluindo SDKs para as seguintes plataformas de desenvolvimento:

- .NET
- Node.js
- Java
- PHP
- Python
- Ruby
- Go

Serviços como Aplicativos Móveis e Serviços de Mídia do Azure fornecem SDKs do lado do cliente para permitir que você acesse serviços dos aplicativos Web e clientes móveis.

### Azure Resource Manager

Executar seu aplicativo no Azure provavelmente envolve trabalhar com vários serviços do Azure. Esses serviços seguem o mesmo ciclo de vida e podem ser pensados como uma unidade lógica. Por exemplo, um aplicativo Web pode usar Aplicativos Web, Banco de Dados SQL, Armazenamento, Cache Redis do Azure e serviços de Rede de Distribuição de Conteúdo do Azure. O Azure Resource Manager permite que você trabalhe com os recursos em seu aplicativo como um grupo. É possível implantar, atualizar ou excluir todos os recursos em uma operação coordenada única.

Além de agrupar e gerenciar logicamente recursos relacionados, o Azure Resource Manager inclui capacidades de implantação que permitem personalizar a implantação e configuração de recursos relacionados. Por exemplo, você pode usar o Resource Manager para implantar e configurar um aplicativo. Esse aplicativo pode consistir em várias máquinas virtuais, um balanceador de carga e um banco de dados no Banco de Dados SQL do Azure como uma única unidade.

Essas implantações são desenvolvidas utilizando um modelo do Azure Resource Manager, que é um documento no formato JSON. Os modelos permitem que você defina uma implantação e gerencie seus aplicativos utilizando modelos declarativos, em vez de scripts. Seus modelos podem funcionar para diferentes ambientes, como teste, de preparo e produção. Por exemplo,você pode utilizar modelos para adicionar um botão a um repositório GitHub que implanta o código no repositório para um conjunto de serviços do Azure com um único clique.

Quando utilizar: utilize modelos do Resource Manager quando quiser uma implantação baseada em modelo para seu aplicativo, de modo que você possa gerenciar programaticamente utilizando APIs REST, a CLI do Azure e o Azure PowerShell.

Introdução: Para a introdução ao modelo, consulte Criando modelos do Azure Resource Manager.

## Compreendendo contas, assinaturas e cobrança

Como desenvolvedores, gostamos de mergulhar diretamente no código e tentar começar o mais rápido possível, fazendo com que nossos aplicativos sejam executados. Nós, certamente, queremos incentivá-lo a começar a trabalhar no Azure da maneira mais fácil possível. Para torná-lo mais fácil, o Azure oferece uma avaliação gratuita. Alguns serviços ainda possuem uma funcionalidade "Experimente gratuitamente", como o Serviço de Aplicativo do Azure que não exige a criação de uma conta. Mesmo que seja divertido mergulhar na codificação e implantação do seu aplicativo no Azure,também é importante dispor de algum tempo para compreender como o Azure funciona. Principalmente, você deve entender como ele funciona do ponto de vista de contas de usuário, assinaturas e cobrança.

### O que é uma conta do Azure?

Para poder criar ou trabalhar com uma assinatura do Azure é necessário ter uma conta do Azure. Uma conta do Azure é simplesmente uma identidade no Azure AD ou em um diretório, como uma organização corporativa ou de estudante em que o Azure AD confia. Caso não pertença a essa organização, sempre será possível criar uma assinatura utilizando sua Conta da Microsoft, que é confiável pelo Azure AD. Para saber mais sobre como integrar o Windows Server Active Directory local com o Azure AD, consulte Integração de suas identidades locais com o Azure Active Directory.

Cada assinatura do Azure tem uma relação de confiança com uma instância do Azure AD. Isso significa que ela confia que esse diretório autentique usuários, serviços e dispositivos. Várias assinaturas podem confiar no mesmo diretório, mas uma única assinatura confia em apenas um diretório. Para saber mais, consulte Como as assinaturas do Azure são associadas ao Azure Active Directory.

Além de definir identidades de conta do Azure individuais, também chamadas de usuários, também é possível definir grupos no Azure AD. Criar grupos de usuários é uma boa maneira de gerenciar o acesso aos recursos em uma assinatura utilizando o controle de acesso baseado em função (RBAC). Para saber como criar grupos, consulte Criar um grupo na versão prévia do Azure Active Directory. Também é possível criar e gerenciar grupos utilizando o PowerShell.

### Gerenciar suas assinaturas

Uma assinatura é um agrupamento de serviços do Azure que está vinculada a uma conta do Azure. Uma única conta do Azure pode conter várias assinaturas. A cobrança dos serviços do Azure é feita por assinatura. Para obter uma lista das ofertas de assinatura disponíveis por tipo, consulte os Detalhes da oferta do Microsoft Azure. As assinaturas do Azure têm um administrador da conta que tem o controle total da assinatura. Eles também têm um administrador de serviços que tem controle sobre todos os serviços na assinatura. Para obter informações sobre os administradores clássicos de assinatura, confira Adicionar ou alterar administradores de assinatura do Azure. Contas individuais podem receber controle detalhado dos recursos do Azure usando o controle de acesso baseado em função do Azure (Azure RBAC).

### Grupos de recursos

Ao fornecer novos serviços do Azure, isso é feito em uma determinada assinatura. Os serviços do Azure individuais, que também são chamados de recursos, são criados no contexto de um grupo de recursos. Os grupos de recursos facilitam a implantação e o gerenciamento dos recursos de seu aplicativo. Um grupo de recursos deve conter todos os recursos para o aplicativo que você quer trabalhar como uma unidade. É possível mover recursos entre grupos de recursos e até diferentes assinaturas. Para saber mais sobre como mover recursos, consulte Mover recursos para o novo grupo de recursos ou assinatura.

O Azure Resource Explorer é uma ótima ferramenta para visualizar os recursos já criados em sua assinatura. Para saber mais, consulte Utilizar o Azure Resource Explorer para visualizar e modificar recursos.

### Conceder acesso aos recursos

Ao permitir acesso aos recursos do Azure, sempre será melhor conceder aos usuários o privilégio mínimo necessário para executar uma determinada tarefa.

- Controle de acesso baseado em função (Azure RBAC) : no Azure, é possível conceder acesso a contas de usuários (entidades) em um escopo especificado: assinatura, grupo de recursos ou recursos individuais. O Azure RBAC permite implantar um conjunto de recursos em um grupo de recursos e conceder permissões a um usuário ou grupo específico. Também permite limitar o acesso a apenas os recursos que pertencem ao grupo de recursos de destino. Além disso, é possível conceder acesso a um recurso único, como uma máquina virtual ou uma rede virtual. Para conceder acesso, você atribui uma função ao usuário, ao grupo ou à entidade de serviço. Há muitas funções predefinidas, no entanto, você também pode definir suas próprias funções personalizadas. Para saber mais, confira O que é controle de acesso baseado em função do Azure (Azure RBAC)?

Quando usar: quando você precisa de gerenciamento de acesso refinado para usuários e grupos ou quando precisa transformar um usuário em proprietário de uma assinatura.

Introdução: para mais informações, confira Atribuir funções do Azure usando o portal do Azure.

- Objetos de entidade de serviço: além de fornecer acesso a entidades de usuários e grupos, é possível conceder o mesmo acesso a uma entidade de serviço.

Quando utilizar: ao gerenciar de forma programática os recursos do Azure ou conceder acesso a aplicativos. Para obter mais informações, consulte Criar entidade de serviço e aplicativo do Active Directory.

##  Marcações
O Azure Resource Manager permite atribuir marcas personalizadas para recursos individuais. As marcas, que são pares chave-valor, podem ser úteis quando for necessário organizar recursos para cobrança ou monitoramento. As marcas fornecem uma maneira de rastrear recursos em vários grupos de recursos. Você pode atribuir marcações das seguintes maneiras:

- No portal
- No modelo do Azure Resource Manager
- Usando a API REST
- Usando a CLI do Azure
- Usando o PowerShell

Além disso, é possível atribuir várias marcas para cada recurso. Para saber mais, consulte Usando marcas para organizar os recursos do Azure.

### Cobrança

Na mudança da computação local para serviços hospedados na nuvem, acompanhar e estimar o uso do serviço e os custos relacionados são preocupações significativas. É importante poder estimar o custo dos novos recursos para serem executados mensalmente. Também é necessário projetar como a cobrança procura um determinado mês baseado nos gastos atuais.

#### Obter dados de uso do recurso

O Azure fornece um conjunto de API REST de cobrança que fornecem acesso ao consumo do recurso e informações de metadados para assinaturas do Azure. Essas APIs de cobrança fornecem-lhe a capacidade de prever melhor e gerenciar os custos do Azure. Você pode acompanhar e analisar os gastos em incrementos por hora e criar alertas de gastos. Você também pode prever a cobrança futura com base nas tendências de uso atuais.

Introdução: para saber mais sobre o uso das APIs de cobrança, consulte Visão geral do consumo de APIs do Azure

### Prever os custos futuros

Embora seja desafiador estimar os custos antecipadamente, o Azure tem ferramentas que podem ajudar. Ele tem uma calculadora de preços para ajudar a estimar o custo dos recursos implantados. Você também pode utilizar os recursos de cobrança no portal e as APIs REST de Cobrança para estimar os custos futuros baseado no consumo atual.

Introdução: consulte visão geral da [API de consumo do Azure](https://docs.microsoft.com/pt-br/azure/cost-management-billing/manage/consumption-api-overview).

[Guia de introdução para desenvolvedores do Azure](https://docs.microsoft.com/pt-br/azure/guides/developer/azure-developer-guide)