# Tipos de Serviço de Nuvem
## IaaS - Infraestrutura como serviço
  Permite maior liberdade para o cliente, a configuração é de responsabilidade do cliente, não da nuvem. O fornecedor disponibiliza serviços de infraestrutura (como armazenamento e virtualização), de acordo com a necessidade, pela nuvem ou internet. <br>
  O cliente é quem fornece o SO, dados, aplicações, componenetes de middleware (software que facilita a comunicação e o gerenciamento de dados entre componentes) e runtimes. O provedor concede os acessos necessários para o cliente, não precisando manter ou atualizar data center local. O cliente acessa a infraestrutura através de um dashboard ou API (interface de programação de aplicações. 

## PaaS - Plataforma como serviço
  Ambiente para criação, teste e implantação de aplicativos de software, sem focar no gerenciamento de infraestrutura subjacente. <br>
  Nessa modalidade o provedor hospeda componentes de hardware e software na sua própria infraestrutura, fornecendo uma plataforma que pode ser usada como solução integrada, stack de soluções ou serviço conectado via internet.

## SaaS - Software como serviço
  Os usuário se conectam e usam aplicativos com base em nuvem pela internet, sem necessidade de instalar algum software.

## Modelo de Responsabilidade Compartilhada no Microsoft Azure
| Responsabilidade                       | SaaS        | PaaS        | IaaS        | No local   |
|---------------------------------------|-------------|-------------|-------------|------------|
| Informações e dados                   | Cliente     | Cliente     | Cliente     | Cliente    |
| Dispositivos (móveis e PCs)           | Cliente     | Cliente     | Cliente     | Cliente    |
| Contas e identidades                    | Compartilhada | Compartilhada | Cliente     | Cliente    |
| Infraestrutura de identidade e diretório | Compartilhada | Compartilhada | Cliente     | Cliente    |
| Aplicativos                           | Microsoft   | Cliente     | Cliente     | Cliente    |
| Controles de rede                     | Microsoft   | Compartilhada | Cliente     | Cliente    |
| Sistema operacional                   | Microsoft   | Microsoft   | Cliente     | Cliente    |
| Hosts físicos                         | Microsoft   | Microsoft   | Microsoft   | Cliente    |
| Rede física                           | Microsoft   | Microsoft   | Microsoft   | Cliente    |
| Datacenter físico                     | Microsoft   | Microsoft   | Microsoft   | Cliente    |

As informações e dados, dispositivos e contas de identidade e diretório sempre são de responsabilidade do cliete. <br>
Em serviços de nuvem os hosts físicos, a rede física e o datacentes físico sempre é de responsabilidade da Microsoft. <br>

| Tecnologia                                    | IaaS | PaaS | SaaS |
|-----------------------------------------------|------|------|------|
| Servidores e armazenamento                    | Sim  | Sim  | Sim  |
| Firewalls/segurança de rede                   | Sim  | Sim  | Sim  |
| Planta física/edifício do datacenter         | Sim  | Sim  | Sim  |
| Sistemas operacionais                         | Não  | Sim  | Sim  |
| Ferramentas de desenvolvimento, análise de... | Não  | Sim  | Sim  |
| Aplicativos/apps hospedados                   | Não  | Não  | Sim  |
