Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO referência ao tema computação em nuvem.

Diferença de entre computação on-premisse, em nuvem e híbrida:
- On-premisse: são dos datacenters tradicionais que empresas possuem em seus locais designados, tendo que comprar, instalar (ambos CAPEX) e administrar seus servidores (OPEX).
- Em numvem: serviço público onde é possível criar e alocar recursos dinâmicamente, pagando-se um custo por utilização (OPEX).
- Híbrido: quando é utilizado os dos modos acima.

Conceito de CAPEX (custo de investimento) e OPEX (custo de manutenção/operacional).

Como criar uma conta gratuita na Azure e navegar e seus menus.

É importante entender qual deve ser o SLA (service level agreement) antes de começar a criar as máquinas virtuais. Para um período de desenvolvimento e testes, o SLA pode ser 99%, no entanto em produção, deve ser maior que isso caso o sistema não posso ficar offline por muito tempo. Quanto maior o SLA (99,99%), maior o custo envolvido, então é importante conhecer bem as necessidades antes de implantá-lo.

Tipos de serviço em nuvem:
- Iaas: Infraestrutura como serviço, inclui servidores, armazenamento, firewalls, segurança da rede, planta/prédio físico do datacenter. Responsabilidade do provedor: hosts fisicos, rede física e datacenter físico. Serviço de nuvem mais flexível;
- Pass: Plataforma como serviço, oferece adicionalmente o sistema operacional e ferramentas para desenvolvimento e/ou banco de dados. Responsabilidado do provedor: sistema operacional. Responsabilidade compartilhada: controle de rede, aplicativos e infraestrutura de identidade e diretório. Focado no desenvolvimento de aplicativos e o gerenciamento é realizados pelo provedor de nuvem;
- Saas: Software como serviço, oferece adicionalmente o uso de aplicativos, como por exemplo o Microsoft 365 (Teams por exemplo).Responsabilidade do provedor: controle de rede, aplicativos e resposabilidade compartilhada de infraestrutura de identidade e diretório. Modelo de preço de pagamento conforme o uso e os usuários pagam pelo software que utilizam em um modelo de assinatura.
