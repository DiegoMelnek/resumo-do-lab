## Resumo do Laboratório – Portal do Azure

Neste laboratório foi apresentada uma visão geral do portal do Microsoft Azure e de como ele é organizado.

Foram mostradas as principais abas do portal:
- **Computação**: utilizada para criar e gerenciar máquinas virtuais.
- **Rede**: usada para configurar a comunicação entre os serviços.
- **Armazenamento**: responsável por armazenar dados na nuvem.
- **Análises**: utilizada para analisar dados, gerar relatórios e obter informações a partir dos dados armazenados.

O laboratório ajudou a entender o funcionamento básico do portal do Azure e a função de cada área.

## Experiência prática

Durante o laboratório, tive a oportunidade de explorar o portal do Azure de forma prática. Ao criar uma máquina virtual, percebi como cada configuração impacta diretamente no desempenho e na disponibilidade do serviço. Experimentei selecionar o tipo e o tamanho da VM, configurar o sistema operacional e o armazenamento, além de ajustar a rede e os grupos de segurança.

### Seleção do sistema operacional

No processo de criação da máquina virtual, foi possível selecionar o sistema operacional por meio das imagens disponibilizadas pelo Azure. O portal oferece diversas opções, como Windows Server e diferentes distribuições Linux, permitindo escolher a imagem mais adequada de acordo com o objetivo da aplicação. Essa escolha influencia diretamente na compatibilidade, segurança e gerenciamento do ambiente.

Também explorei as opções de **SLA (Service Level Agreement)** e **zonas de disponibilidade**, entendendo que a escolha da zona pode aumentar significativamente a resiliência do serviço, garantindo maior uptime em caso de falhas. Foi interessante ver como pequenas decisões, como o tipo de disco ou a distribuição em zonas, podem afetar a performance, segurança e confiabilidade da VM.

### Criação de banco de dados SQL

Outro ponto importante do laboratório foi a criação de um banco de dados SQL no Azure. Durante esse processo, aprendi que é necessário primeiro criar um servidor SQL, definindo configurações como nome do servidor, região, autenticação e nível de desempenho.

Foi possível analisar os diferentes níveis de SLA, entendendo como eles impactam na disponibilidade, desempenho e custo do banco de dados. Essa etapa reforçou a importância de planejar corretamente os requisitos da aplicação antes de escolher a configuração do serviço.

Durante a criação de uma conta de armazenamento, aprendi a importância de escolher o tipo de redundância adequado (**LRS, ZRS, GRS**) para garantir segurança e disponibilidade dos dados.

### Tipos de serviços em nuvem

Durante o laboratório, também foi apresentado um breve resumo sobre os **modelos de serviços em nuvem**, que definem o nível de responsabilidade entre o provedor de nuvem e o usuário:

- **IaaS (Infrastructure as a Service)**: fornece a infraestrutura básica, como máquinas virtuais, redes e armazenamento. O usuário é responsável por gerenciar o sistema operacional, aplicações e configurações. (A Microsoft é responsável pela infraestrutura física e virtual básica, enquanto o cliente é responsável pelo sistema operacional e tudo acima dele.)

- **PaaS (Platform as a Service)**: oferece uma plataforma pronta para desenvolvimento, teste e implantação de aplicações, sem a necessidade de gerenciar a infraestrutura subjacente. O provedor cuida do sistema operacional e do ambiente, enquanto o usuário foca no código. (O gerenciamento de plataforma é realizado pelo provedor de nuvem)

- **SaaS (Software as a Service)**: disponibiliza aplicações completas acessadas via internet, sem necessidade de instalação ou gerenciamento por parte do usuário. Toda a infraestrutura e manutenção são responsabilidade do provedor. (Os usuários pagam pelo software que utilizam em um modelo de assinatura)

Esse conteúdo ajudou a compreender como escolher o modelo de serviço mais adequado de acordo com o nível de controle, responsabilidade e facilidade desejados.

