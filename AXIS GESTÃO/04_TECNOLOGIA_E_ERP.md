# 04 — TECNOLOGIA E ERP

## Princípio
A AXIS deve ser inicialmente **ERP-agnostic** para atender clientes que já possuem sistemas, mas precisa homologar uma stack preferencial para reduzir custo de treinamento, integração e suporte.

## Arquitetura recomendada
### Camada 1 — Produtividade e identidade
Google Workspace ou Microsoft 365.

### Camada 2 — Gestão operacional
ClickUp como orquestrador de tarefas, SLAs, implantação, POPs, clientes e projetos.

### Camada 3 — CRM
HubSpot ou Pipedrive.

### Camada 4 — ERP/Financeiro dos clientes
Operar prioritariamente no ERP do cliente. Para clientes sem solução adequada, homologar plataformas específicas para BPO.

### Camada 5 — BI
Power BI ou Looker Studio.

### Camada 6 — Automação
n8n / Make / APIs / RPA / OCR.

### Camada 7 — Assinatura
Clicksign, DocuSign ou equivalente.

### Camada 8 — Segurança
Gerenciador corporativo de senhas + MFA + menor privilégio.

### Camada 9 — Documentos
Drive/SharePoint com estrutura e políticas por cliente.

## ERP preferencial — hipótese atual
### Curto prazo
**Nibo BPO + Nibo Gestão Financeira** para padronizar a operação financeira de múltiplos clientes sem obrigar todos a adotar um ERP empresarial completo.

### Alternativa forte para clientes PME
**Conta Azul Mais / Conta Azul Pro BPO**, por possuir painel específico para parceiros BPO e acesso a múltiplas empresas.

### ERP operacional amplo
**Omie** deve ser homologado para clientes que necessitem financeiro + vendas + estoque + fiscal em um ERP brasileiro mais abrangente.

### Plataforma futura de operação integrada
**Odoo** é candidato para a própria AXIS ou para clientes de maior complexidade quando houver capacidade de implantação, porque permite multiempresa, CRM, compras, projetos, documentos e automações. Não deve ser a primeira decisão sem equipe técnica e processo validado.

## Sistema AXIS próprio
Não desenvolver ERP completo agora.

O sistema proprietário futuro deve funcionar como camada de governança:
- clientes;
- contratos;
- workflows;
- SLAs;
- documentos;
- aprovações;
- exceções;
- histórico;
- indicadores;
- automações;
- auditoria;
- portal do cliente.

A construção só se justifica após repetição comprovada dos processos.
