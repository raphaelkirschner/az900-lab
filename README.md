# Resumo do aprendizado
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab da Formação Microsoft AZ-900 Certification na DIO

# Conceito de nuvem

## Modelos de Nuvem
Computação em nuvem é o fornecimento de serviços de computação na internet, habilitando inovações mais rápidas, recursos mais flexíveis e economias de escala. Os modelos de nuvem pode ser: Privada, Pública e Híbrida.

### Nuvem Privada
O ambiente fica em um datacenter próprio da empresa e as empresas são responsáveis por operar os serviços, sem acesso para usuários de fora da organização. Aqui as empresas tem total controle sobre os recursos e segurança, também são totalmente responsáveis pela manutenção do hardware e software.

### Nuvem Pública
São fornecidas por empresas provedoras de hosting ou serviços em nuvem. Elas fornecem para várias organizações ou usuários, que podem acessar os recursos através de conexões seguras pela internet. Neste modelo a empresa que contrata o serviço não precisa de despesa de capital grande inicialmente, pois paga conforme a utilização. Pode provisionar e desprovisionar aplicativos e serviços rapidamente, facilitando escala.

### Nuvem Hibrida
Quando uma empresa combina os modelos Privado e Público para permitir que suas aplicações sejam executadas no local mais adequado.

## Despesas CapEx e OpEx

### CapEx
Está relacionado ao custo com infraestrutura física inicial necessário. As despesas desse tipo reduzem com o tempo.

### OpEx
Despesas com produtos e serviços ocorre conforme o necessário, o pagamento é conforme o uso.

## Modelo baseado em consumo
É a forma como os provedores de serviços em nuvem operam, as empresas e usuários pagam conforme a utilização de recursos. São fornecidos preços para cada recurso e serviço, dessa forma se tem maior previsisão de custos e a cobrança é feita com base no uso real.

## Benefícios da Nuvem

### Alta Disponibilidade
Garantir a disponibilidade máxima, independente de interrupções ou eventos que possam ocorrer. Garantir serviço funcionando sempre que necessário, de acordo com seu SLA (Contrato de Nível de Serviço). Se não for entregue a disponibilidade acordada, a organização recebe um crédito pela indisponibilidade excedida.

### Escalabilidade
Capacidade de alterar recursos para atender à demanda. Você pode aumentar recursos para lidar com o aumento de demanda (ajustar espaço em disco, memória, CPUs, etc). Você não paga nada além do necessário, somente pelo uso. Se a demanda cair, você pode reduzir custos. É uma escala vertical, se você está desenvolvendo um app e precisa de mais processamento, pode aumentar CPU e RAM à máquina virtual.

### Elasticidade
Exemplo: Black Friday.
Se você tem um saldo acentuado e repentido de demanda, sem previsibilidade, seus recursos podem ser expandidos (automaticamente ou manualmente).
Pode ser adicionadas máquinas virtuais ou contêineres por meio da expansão. Da mesma forma, se reduzir a demanda, os recursos podem ser reduzidos horizontalmente (automático ou manual). Se tiver X% de requisição expande ou x% de requisição reduz.

COMPLETAR COM BENEFICIOS

## Tipos de serviço de nuvem

<img width="1874" height="1060" alt="image" src="https://github.com/user-attachments/assets/7dd74998-0faf-4aaf-85c2-d590e4774503" />

### IaaS - Infraestrutura como serviço
Exemplos de recursos: Servidores e armazenamento; Firewalls/segurança de rede; Planta física/edifício do datacenter

Crie uma infraestrutura de TI de pagamento conforme o uso alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem.

São recursos onde tem maior envolvimento em configurações, acessos, personalização dos recursos. Exemplo: criar um servidor, instalar e configurar Visual Studio, SQL Server

### PaaS - Plataforma como serviço
Exemplos de recursos: além dos recursos de infraestrutura, englobam Sistemas operacionas; Ferramentas para desenvolvedores, análise de negócios de gerenciamento de database

Fornece um ambiente para a criação, o teste e a implantação de aplicativos de software, sem focar no gerenciamento da infraestrutura subjacente. 

Não quero me envolver com questões de infra, como qual é a máquina, servidor, configurações. Me preocupo apenas com a aplicação. Exemplo: quero um banco de dados, não importa o servidor.

### SaaS - Sistema como serviço
Exemplos de recursos: além dos recursos de infraestrutura e plataforma, englobam Aplicativos/apps hospedados.

Os usuários se conectam e usam aplicativos com base em nuvem pela Internet: por exemplo, Microsoft Office 365, email, calendários.

Sistemas, aplicativos e softwares acessados na nuvem conforme modelo de licenças. Aplicação já existe, o que determina o que será acessado é o licenciamento. Exemplo: Microsoft Teams, M365

## Modelo de responsabilidade compartilhada
A responsabilidade vai diminuindo conforme o tipo de serviço

  <img width="1488" height="992" alt="image" src="https://github.com/user-attachments/assets/0637ad00-8457-487e-9b7b-c790f1fdbd16" />

### IaaS
- Serviço de nuvem mais flexível;
- Você cofigura e gerencia o hardware para seu aplicativo;

### PaaS
- Focado no desenvolvimento de aplicativos;
- O gerenciamento de platagorma é realizado pelo provedor de nuvem;

### SaaS
- Modelo de preço de pagamento conforme o uso;
- Os usuários pagam pelo software que utilizam em um modelo de assinatura;

* Para a prova o que mais importa é entender o nível de gestão de cada tipo de serviço de nuvem
