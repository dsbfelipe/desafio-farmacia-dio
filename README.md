### RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data**: 02/08/2025

**Empresa**: Abstergo Industries

**Responsável**: Felipe dos Santos Bento

### Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Felipe dos Santos Bento. O objetivo do projeto foi elencar 3 serviços da Amazon Web Services (AWS) com foco na redução de custos, aumento da disponibilidade e melhoria da segurança, atendendo às necessidades estratégicas da infraestrutura de TI da organização.

### Descrição do Projeto

O projeto foi dividido em 3 etapas, cada uma voltada para resolver um gargalo identificado na estrutura tecnológica da Abstergo Industries, especialmente no que tange ao armazenamento de dados clínicos, execução de rotinas analíticas e controle de acessos internos.

**Etapa 1**: Amazon S3 (Simple Storage Service)

**Foco**: Armazenamento Escalável e Seguro

**Descrição de caso de uso**:

Antes da migração, a Abstergo armazenava grandes volumes de dados de pesquisas clínicas e documentos regulamentares em servidores locais, com backups manuais e infraestrutura de armazenamento limitada. Isso gerava custos elevados de manutenção e riscos quanto à integridade dos dados.

Com a adoção do Amazon S3, foi possível migrar todo o acervo digital para um armazenamento altamente durável e escalável, com versionamento de arquivos, replicação entre regiões e políticas de ciclo de vida automatizadas. Isso resultou em redução de custos operacionais, eliminação de backups manuais e maior segurança dos dados.

**Etapa 2**: Amazon EC2 (Elastic Compute Cloud)

**Foco**: Processamento e Execução de Aplicações

**Descrição de caso de uso**:

A Abstergo utilizava servidores físicos para executar aplicações laboratoriais que realizam análise de dados genéticos. Com o crescimento da base de dados, os servidores não comportavam a demanda, causando lentidão e indisponibilidade.

A migração dessas cargas para instâncias EC2 otimizadas permitiu a execução sob demanda, com escalabilidade horizontal e balanceamento de carga. Além disso, foi implantado Auto Scaling para manter o desempenho sob picos de uso. Como resultado, houve melhoria significativa na performance, redução no tempo de processamento e diminuição do custo total de propriedade (TCO).

**Etapa 3**: AWS IAM (Identity and Access Management)

**Foco**: Segurança e Controle de Acessos

**Descrição de caso de uso**:

O controle de acesso aos sistemas era feito de forma descentralizada e manual, dificultando auditorias e expondo a empresa a riscos de compliance.

Com a implementação do AWS IAM, foi possível definir políticas de acesso baseadas em papéis (RBAC), com autenticação multifator (MFA) e logs de auditoria via AWS CloudTrail. Essa mudança trouxe centralização no controle de identidades, mais segurança nos acessos aos serviços e conformidade com normas regulatórias do setor farmacêutico, como a HIPAA e ANVISA.

### Conclusão

A implementação dos serviços AWS na Abstergo Industries resultou em benefícios estratégicos e operacionais importantes, incluindo:

- ✅ Redução de custos com infraestrutura física e manutenção;

- ✅ Aumento da disponibilidade das aplicações críticas da empresa;

- ✅ Melhoria significativa na segurança e rastreabilidade dos acessos;

- ✅ Automação de rotinas de backup, escalabilidade e gestão de identidades;

- ✅ Adequação a normas internacionais de proteção de dados sensíveis.

Essa transformação digital marca o início de uma nova fase para a Abstergo Industries, mais resiliente, segura e preparada para escalar seus serviços com base em dados e tecnologia de ponta.
