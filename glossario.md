Git -> Serviço de versionamento

#Sistemas de Informação (o que é e para que servem): 
Definição: Componentes interligados que fazem a coleta, armazenamento, processamento e distribuição de dados para 
auxiliar na tomada de decisões e controle dentro de empresas e organizações.

- Categorias de Sistemas de Informação (exemplos):

*Sistemas de Processamento de Transações (TPS): Sistema projetado para processamento e coleta de dados de transações comerciais
Exemplo: Sistema de pagamento de contas, sistema de caixa

*Sistemas de Apoio à Decisão (DSS): Sistema projetado para auxiliar na tomada de decisões dentro de uma empresa, oferecendo ferramentas interativas e acesso a analise de dados.
Exemplo: Planilhas eletrônicas, sistema de analise de estatísticas

*Sistemas de Informação Gerencial (MIS): Sistemas projetados para compilar dados de diversas fontes afim de facilitar na tomada de decisões, no controle e no planejamento.
Exemplo: ERP (Sistema de planejamento de recursos empresarial), SCM (Sistema de gerenciamento de linha de produção)

*Sistemas de Informação Executiva (EIS): Sistemas projetados para facilitar o acesso de informações estratégicas para administradores.

#Integração de Sistemas:
Definição: Trata-se da união de diferentes softwares e sistemas dentro de uma empresa através de um sistema de integração
Uso: Pode ser efetuado através de formas como:
Integração banco a banco: Onde um mesmo banco de dados é compartilhado entres diferentes sistemas através de um software que extrai dados
Troca de dados eletrônicos: Transfere dados de um sistema a outro através de um software "tradutor" que traduz os dados a serem transferidos
Integração por API: A API serve de ponte que conecta sistemas e transfere dados entre estes com agilidade e segurança

# Modelos de Negocio:
Software as a Service - (SaaS):
- É uma forma pela que pode-se disponibilizar aplicações e softwares em nuvem para usuários por meio da internet como um serviço.
+Vantagem -> não é necessário instalar nenhum software extra/não há necessidade de instalar um programa localmente. Reduz custos relacionados a infraestrutura, pode ser utilizado em qualquer local com acesso a internet.
*Exemplos: E-Mail, Calendário (aplicativo), Pacote Office (Office 365)

Platform as a Service - (PaaS):
- Serviços em nuvem que oferecem toda a plataforma (software, hardware) necessária para desenvolvimento de aplicações, disponibilizando ferramentas e ambientes para programação.
+Vantagem -> Simplificação do desenvolvimento de software, eliminação de preocupação de requerimentos em infraestrutura.
*Exemplos: Microsoft Azure

Infrastructure as a Service - (IaaS):
- Tipo de modelo de computação que oferece recursos de computação, armazenamento, servidores e rede sob demanda ou com pagamento conforme o uso.
+Vantagem -> Recursos (softwares, hardware) adquiridos conforme o uso (Flexibilidade);
*Exemplos: AWS EC2, Google Cloud Compute Engine

Anything as a Service - (XaaS):
- Modelo de todo o serviço entregue através da internet, inclui os próprios SaaS, PaaS, IaaS além de incluir serviço de segurança, backup e até IA como serviço.
+Vantagem -> Abrangente e personalizada, integra múltiplos serviços.
*Exemplos: Desktop-as-a-Service (DaaS); Ai-as-a-Service.

#Integração:
MicroServiços:
- Estilo de arquitetura de desenvolvimento de aplicações onde uma aplicação é separada em partes independentes. Estas partes chamadas de microsserviços comunicam-se umas a outras através de APIs, com estes microsserviços tendo própria logica de negocio e banco de dados.
+Vantagem -> Facilita a integração de novas tecnologias, sendo mais flexível.
-Desvantagem -> Pode dificultar na resolução de problemas devido a essa separação.

#Diferença de Bibliotecas, Pacotes, Frameworks e APIs:
Bibliotecas:
- Definem-se como o conjunto de funções ou classes pré-definidas, podendo ser chamadas e utilizadas em projetos de software.
*Exemplo: Bibliotecas do Java
Pacotes:
- São o agrupamento de Bibliotecas trabalhando juntas, servindo como uma "ferramenta" completa.
*Exemplo: Pacote requests do Python (utilizado para efetuar requisições de HTTP)
Frameworks:
- Encapsulam Pacotes de Bibliotecas, são estruturas ou plataformas utilizadas no desenvolvimento de aplicações que possuem um conjunto de regras e ferramentas definidas que auxiliam o desenvolvedor.
*Exemplo: Plataforma Django (Auxilia no desenvolvimento Web através do Python, podendo fazer conexões com banco de dados)
APIs:
- Interfaces que funcionam como pontes para permitir a comunicação entre diferentes sistemas e aplicações.
*Exemplo: Google Maps

CRM -> (Customer Relationship Management) Sistema de software completo que gerencia o relacionamento com o cliente, é composto das estratégias, praticas e tecnologias que as empresas utilizam para efetuar o gerenciamento e analise de suas interações com seus clientes. Seu objetivo é melhorar o relacionamento do cliente para com a empresa, buscando aumentar sua satisfação e subsequentemente gerar o aumento nas vendas.

Conceitos:
Pipeline ->  Auxilio visual sobre as oportunidades existentes nas diferentes etapas do processo de venda.
Ticket -> Solicitações de suporte, reportagem de problemas, dúvidas e incidentes de clientes. 
Kanban -> Ferramenta de controle e otimização de fluxos de trabalho, utiliza cartões para demonstrar isso visualmente.
Leads -> Clientes em potencial

ERP -> Sistema gerencial que auxilia o acesso e integração de dados em uma empresa, com foco na gestão interna de recursos e processos dentro da empresa.

**
Qual o Sistema de Informação?
Cenário 1:
Medicos e dentistas -> consultorio -> agendamento
-> atendimento (consulta)
    -> prontuario
-> atendimento/retorno -> sem custos
-> financeiro
R: SaaS, o cliente é a clinica

Cenário 2:
Cliente SaaS -> clinicas (gestão de clinicas)
-> Banco de dados
-> Contrato
    -> obrigações, deveres
    -> financeiro
R: IaaS ou SaaS
**
