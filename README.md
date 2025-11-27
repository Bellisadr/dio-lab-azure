# Desafio DIO - Azure: Implementação e Documentação de Máquina Virtual Azure (IaaS)

## 1. Contexto e Objetivos

Este projeto prático foi realizado para consolidar os conhecimentos adquiridos no módulo de Cloud Computing, com foco na criação e gerenciamento de Máquinas Virtuais (VMs) na plataforma Microsoft Azure.

**O objetivo principal foi:**

* Demonstrar a aplicação do modelo **IaaS (Infrastructure as a Service)**.
* Documentar de forma clara cada etapa da criação de um recurso na nuvem.
* Entender a transição de **CapEx** (custo fixo) para **OpEx** (custo variável).

## 4. Conclusão do Desafio

O desafio consistiu em documentar conceitualmente o processo de criar uma máquina virtual (VM) no Azure. O objetivo foi entender a aplicação do modelo IaaS (Infraestrutura como Serviço). Para iniciar a criação de um servidor, precisamos passar por seis decisões críticas no portal do Azure: 1. A primeira etapa é criar um Grupo de Recursos (Resource Group), que funciona como um contêiner lógico para todos os itens da VM (disco, IP, rede). Isso ajuda na organização e na cobrança. 2. Em seguida, definimos os detalhes da instância, dando um nome e escolhendo a região do Data Center. 3. A parte mais importante é a escolha do Sistema Operacional (como o Windows Server), que define o tipo de servidor que estamos alugando. 4. Depois, escolhemos o Tamanho da VM (CPU e RAM), que é a decisão que mais impacta o custo (o nosso OpEx). 5. Na parte de segurança, definimos um nome de usuário e uma senha (ou chave SSH) para a Autenticação, garantindo que só nós possamos nos conectar. 6. O passo final é a Rede, onde confirmamos as regras de firewall e, crucialmente, habilitamos o acesso remoto (como a porta RDP no Windows) para garantir que conseguiremos nos conectar ao nosso novo servidor. O processo finalizado garante que estamos prontos para a etapa de implantação, tendo o controle total sobre o S.O. e os dados.
