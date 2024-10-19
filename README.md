[\[English\]](READMEE.md) [\[Português\]](README.md)

# Modelos de Serviço em Computação em Nuvem: IaaS, PaaS e SaaS

## 1. IaaS (Infrastructure as a Service)

### Definição
IaaS é um modelo de serviço em nuvem que fornece infraestrutura de TI sob demanda, como servidores, armazenamento, redes e sistemas operacionais, de forma virtualizada. As empresas utilizam esse modelo para criar e gerenciar seus próprios ambientes de TI sem a necessidade de adquirir ou manter hardware físico.

### Exemplos
- **AWS EC2**
- **Microsoft Azure Virtual Machines**
- **Google Cloud Compute Engine**

### Responsabilidade do Usuário
O usuário é responsável por gerenciar o sistema operacional, middleware, aplicativos e dados, enquanto o provedor cuida da infraestrutura subjacente (hardware, redes, armazenamento).

### Caso Prático
**Empresa de E-commerce usando IaaS**
Uma empresa de e-commerce decide expandir suas operações para um mercado internacional. Para lidar com o aumento de tráfego, ela escolhe a AWS EC2 para hospedar seus servidores de aplicação e banco de dados. A equipe de TI configura as máquinas virtuais, instala o sistema operacional e gerencia a escalabilidade da aplicação. Esse modelo permite que a empresa escale rapidamente seus recursos computacionais conforme necessário, sem a necessidade de investir em novos servidores físicos.

---

## 2. PaaS (Platform as a Service)

### Definição
PaaS fornece uma plataforma pronta para desenvolvimento, testes e implantação de aplicativos, sem a necessidade de gerenciar a infraestrutura subjacente. O objetivo é facilitar o trabalho de desenvolvimento, oferecendo um ambiente controlado com todas as ferramentas necessárias.

### Exemplos
- **Google App Engine**
- **Microsoft Azure App Service**
- **Heroku**

### Responsabilidade do Usuário
O usuário gerencia apenas os aplicativos e dados, enquanto o provedor cuida da infraestrutura, sistema operacional e runtime.

### Caso Prático
**Startup de Desenvolvimento de Aplicativos usando PaaS**
Uma startup que desenvolve um aplicativo móvel para gerenciamento de finanças pessoais usa o Heroku como plataforma para lançar seu produto no mercado rapidamente. Os desenvolvedores criam a aplicação, configuram a plataforma e a integram com ferramentas de banco de dados e análise. O Heroku cuida da infraestrutura, balanceamento de carga e escalabilidade automática, permitindo que a equipe de desenvolvimento foque apenas em melhorar o aplicativo sem se preocupar com questões operacionais.

---

## 3. SaaS (Software as a Service)

### Definição
SaaS oferece software pronto para uso diretamente pela internet, sem necessidade de instalação, configuração ou gerenciamento pelo usuário. As soluções SaaS são acessíveis via navegador, proporcionando uma experiência simples e integrada.

### Exemplos
- **Google Workspace**
- **Microsoft 365**
- **Salesforce**

### Responsabilidade do Usuário
O usuário apenas utiliza o software, sem se preocupar com manutenção, atualizações ou infraestrutura.

### Caso Prático
**Empresa de Marketing usando SaaS**
Uma empresa de marketing decide adotar o **Salesforce** para gerenciar seu relacionamento com clientes (CRM). Com o Salesforce, a equipe de vendas pode acompanhar o progresso das negociações, automatizar tarefas e acessar relatórios em tempo real. A empresa não precisa se preocupar com a configuração do sistema ou manutenção do software, já que o provedor cuida de tudo, desde as atualizações até a segurança.

---

## Resumo de Responsabilidades

| Modelo  | Responsabilidade do Provedor                | Responsabilidade do Usuário             |
|---------|---------------------------------------------|-----------------------------------------|
| **IaaS**| Infraestrutura (hardware, rede, storage)     | Sistema operacional, middleware, dados e aplicações |
| **PaaS**| Infraestrutura e plataforma (runtime, OS)    | Aplicações e dados                      |
| **SaaS**| Tudo (software, plataforma, infraestrutura)  | Uso do software                        |

