# ☁️ Conceitos Básicos de Cloud – AZ-900

Resumo dos principais conceitos estudados no curso **AZ-900 – Microsoft Azure Fundamentals**, ministrado por **Valéria Baptista**.

---

## 📌 Computação em Nuvem

A computação em nuvem é o fornecimento de serviços de computação pela internet, permitindo:
- Inovação mais rápida  
- Recursos flexíveis  
- Economia de escala  

---

## ☁️ Modelos de Nuvem

### 🔒 Nuvem Privada
- Criada no datacenter da própria organização  
- Total responsabilidade sobre operação e manutenção  
- Não oferece acesso externo  

### 🌐 Nuvem Pública
- Pertence a um provedor de nuvem (ex: Microsoft Azure)  
- Recursos compartilhados entre vários clientes  
- Acesso via conexão segura pela internet  

### 🔀 Nuvem Híbrida
- Combina nuvem pública e privada  
- Permite executar aplicações no ambiente mais adequado  

---

## 📊 Comparação dos Modelos de Nuvem

### Nuvem Pública
- Sem despesas de capital (CapEx)
- Provisionamento e desprovisionamento rápidos
- Pagamento conforme o uso (Pay as You Go)

### Nuvem Privada
- Controle total de recursos e segurança
- Responsabilidade total por manutenção e atualizações

### Nuvem Híbrida
- Flexibilidade na execução das aplicações
- Controle de segurança, conformidade e requisitos legais

---

## 💰 CapEx vs OpEx

### CapEx (Capital Expenditure)
- Gasto inicial com infraestrutura física
- Valor se deprecia ao longo do tempo

### OpEx (Operational Expenditure)
- Pagamento conforme o uso
- Custos cobrados imediatamente

### Modelo Baseado em Consumo
- Pagamento apenas pelos recursos utilizados
- Melhor previsibilidade de custos
- Cobrança baseada no uso real

---

## 🚀 Benefícios da Nuvem

### Alta Disponibilidade
- Garantida por SLA (Service Level Agreement)

### Escalabilidade
- Ajuste de recursos conforme a demanda
- Redução de custos quando a demanda diminui

### Elasticidade
- Expansão ou redução automática ou manual de recursos
- Exemplo: adicionar ou remover VMs e containers

### Confiabilidade
- Infraestrutura distribuída globalmente
- Continuidade mesmo em falhas regionais

### Previsibilidade
- Controle de desempenho e custos
- Baseada no Azure Well-Architected Framework

### Segurança
- Ferramentas avançadas de proteção
- Parte da segurança é responsabilidade do cliente

### Governança
- Controle, conformidade e padronização desde o início

### Gerenciabilidade
- Portal Web
- CLI
- APIs
- PowerShell

---

## 🧩 Tipos de Serviço de Nuvem

### IaaS – Infrastructure as a Service
- Máquinas virtuais
- Armazenamento
- Redes
- Sistemas operacionais

### PaaS – Platform as a Service
- Ambiente para desenvolvimento e deploy
- Sem gerenciamento da infraestrutura
- Foco em aplicações

### SaaS – Software as a Service
- Aplicações prontas via internet
- Exemplo: Microsoft 365

---

## 🏗️ Arquitetura do Azure

### Regiões
- Presença global
- Baixa latência
- Conformidade de dados

### Zonas de Disponibilidade
- Datacenters fisicamente separados
- Alta disponibilidade e resiliência

### Pares de Região
- Separação mínima de 300 milhas
- Replicação automática
- Atualizações sequenciais

### Regiões Soberanas
- Azure Government (EUA)
- Azure China (21Vianet)

---

## 📦 Recursos do Azure

### Grupo de Recursos
- Contêiner lógico para recursos
- Um recurso pertence a apenas um grupo

### Assinaturas
- Controle de cobrança
- Controle de acesso

### Grupos de Gerenciamento
- Agrupam várias assinaturas
- Herança de políticas

---

## 🖥️ Serviços de Computação

- Máquinas Virtuais (VMs)
- App Services
- Azure Kubernetes Service (AKS)
- Containers
- Azure Virtual Desktop
- Azure Functions (Serverless)

---

## 🌐 Serviços de Rede

- Virtual Network (VNet)
- VPN Gateway
- ExpressRoute
- Azure DNS

---

## 💾 Armazenamento no Azure

### Serviços
- Blob Storage
- Disk Storage
- File Storage
- Queue Storage
- Table Storage

### Redundância
- LRS (11 noves)
- ZRS (12 noves)

---

## 🔄 Migração para o Azure

- Azure Migrate
- Azure Data Box (até 80 TB)
- AzCopy
- Storage Explorer
- File Sync

---

## 🔐 Identidade e Acesso

### Microsoft Entra ID
- Autenticação
- SSO
- Gerenciamento de dispositivos
- B2B

### Autenticação vs Autorização
- Autenticação: quem é
- Autorização: o que pode fazer

### MFA
- Segurança adicional por múltiplos fatores

### Controle de Acesso Baseado em Função (RBAC)
- Permissões granulares
- Princípio do menor privilégio

---

## 🛡️ Segurança e Governança

- Zero Trust
- Microsoft Defender for Cloud
- Azure Policy
- Resource Locks
- Microsoft Purview

---

## 💸 Gerenciamento de Custos

- Azure Cost Management
- Calculadora de Preços
- Calculadora TCO
- Orçamentos e Alertas
- Tags para organização de custos

---

📚 **Objetivo:** Consolidar os fundamentos de Cloud Computing e Microsoft Azure para certificação AZ-900 e projetos práticos.
