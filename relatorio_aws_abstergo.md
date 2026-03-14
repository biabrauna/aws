# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
### Redução de Custos Operacionais — Adoção de Nuvem

---

| Campo | Informação |
|---|---|
| **Data de Início** | 14 de março de 2025 |
| **Empresa** | Abstergo Industries |
| **Responsável** | Ana Beatriz Dutton da Silva Braúna |
| **Setor** | Farmacêutico / Operações de TI |
| **Classificação** | Confidencial |

---

## 1. Introdução

Este relatório apresenta o processo de implementação de serviços de computação em nuvem na Abstergo Industries, conduzido por Ana Beatriz Dutton da Silva Braúna. O objetivo central do projeto foi identificar e implantar três serviços da Amazon Web Services (AWS), selecionados estrategicamente para promover a redução imediata de custos operacionais de TI, sem comprometer a segurança, a conformidade regulatória e a disponibilidade dos sistemas críticos do setor farmacêutico.

A migração para a nuvem representa uma mudança de paradigma na gestão de infraestrutura da empresa. Em vez de manter hardware físico subutilizado, a Abstergo Industries passa a consumir recursos de TI sob demanda, com escalabilidade controlada e previsibilidade de custos.

---

## 2. Descrição do Projeto

O projeto foi estruturado em três etapas independentes, cada uma voltada a um domínio específico de otimização. As ferramentas foram selecionadas com base em critérios de impacto financeiro imediato, facilidade de adoção e relevância para o contexto farmacêutico.

---

### Etapa 1 — Amazon EC2 (Elastic Compute Cloud)

| Campo | Descrição |
|---|---|
| **Foco** | Virtualização de servidores e redução de infraestrutura física |
| **Caso de Uso** | Migração dos servidores de aplicação utilizados no ERP farmacêutico e nos sistemas de controle de estoque de medicamentos para instâncias EC2 com Auto Scaling. Com uso de instâncias reservadas e Spot Instances para cargas não críticas, a empresa elimina custos de manutenção de hardware físico, reduz despesas com data center próprio (energia, refrigeração, espaço físico) e paga apenas pelo poder computacional consumido. Estimativa de redução de até 40% nos custos de infraestrutura no primeiro ano. |

---

### Etapa 2 — Amazon S3 (Simple Storage Service)

| Campo | Descrição |
|---|---|
| **Foco** | Armazenamento de dados regulatórios e documentação técnica |
| **Caso de Uso** | Substituição dos servidores de arquivos locais pelo Amazon S3 para armazenamento de documentação técnica, laudos laboratoriais, registros de lotes e arquivos de conformidade da ANVISA. O S3 oferece durabilidade de 99,999999999%, controle de versionamento para rastreabilidade de documentos regulatórios e políticas de ciclo de vida que migram automaticamente arquivos menos acessados para classes de armazenamento mais baratas (S3 Glacier), reduzindo os custos de armazenamento em até 60% em comparação ao NAS físico. |

---

### Etapa 3 — Amazon RDS (Relational Database Service)

| Campo | Descrição |
|---|---|
| **Foco** | Gerenciamento de banco de dados com alta disponibilidade e zero custo de DBA operacional |
| **Caso de Uso** | Migração dos bancos de dados relacionais (controle de produção, gestão de supply chain farmacêutica e dados de P&D) para o Amazon RDS com MySQL ou PostgreSQL. O RDS automatiza tarefas antes executadas manualmente por DBAs — backups, aplicação de patches, replicação Multi-AZ e failover automático — reduzindo custos com pessoal especializado e licenças de banco de dados proprietários. A alta disponibilidade garante SLA de 99,95%, essencial para sistemas críticos 24/7 do setor farmacêutico. |

---

## 3. Conclusão

A implementação das três ferramentas AWS na Abstergo Industries tem como resultado esperado uma redução significativa de custos operacionais de TI, com estimativas entre 35% e 55% nos gastos com infraestrutura, armazenamento e banco de dados no primeiro ano. Além da economia financeira direta, a empresa se beneficia de maior escalabilidade, alta disponibilidade dos sistemas críticos, conformidade facilitada com regulamentações farmacêuticas e redução da dependência de hardware físico sujeito a obsolescência.

Recomenda-se a continuidade da utilização das ferramentas implementadas, com monitoramento contínuo de custos via AWS Cost Explorer, e a avaliação de novos serviços que possam ampliar ainda mais os ganhos de eficiência operacional, tais como AWS Lambda (computação serverless) e Amazon CloudWatch (monitoramento centralizado).

### Benefícios Consolidados

- Redução de até 55% nos custos de infraestrutura de TI no primeiro ano
- Eliminação de gastos com aquisição e manutenção de hardware físico
- Alta disponibilidade e continuidade dos negócios com SLA garantido por contrato
- Conformidade com regulamentações da ANVISA facilitada por controles de auditoria nativos da AWS
- Escalabilidade sob demanda para períodos de pico de produção e pesquisa
- Redução de riscos operacionais com backups automatizados e disaster recovery

---

## 4. Assinatura e Aprovação

O presente relatório foi elaborado com base em análise técnica e financeira dos sistemas de TI da Abstergo Industries e aprovado pelo responsável abaixo identificado.

---

**Ana Beatriz Dutton da Silva Braúna**
Responsável pelo Projeto
Abstergo Industries
*14 de março de 2025*

---

## 5. Anexos

- **Anexo A** — Comparativo de custos: infraestrutura física vs. AWS (planilha)
- **Anexo B** — Arquitetura de rede proposta na AWS (diagrama técnico)
- **Anexo C** — Plano de migração de dados e cronograma de implantação
- **Anexo D** — Política de segurança e conformidade regulatória (ANVISA / LGPD)
- **Anexo E** — Manual de uso do AWS Cost Explorer para monitoramento contínuo
- **Anexo F** — Termos do contrato de SLA com a Amazon Web Services
