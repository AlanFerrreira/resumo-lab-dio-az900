# ☁️ Conceitos Básicos de Cloud – AZ-900

Resumo dos conceitos fundamentais de **Computação em Nuvem e Microsoft Azure**, com base no curso **AZ-900 – Microsoft Azure Fundamentals**, ministrado por **Valéria Baptista**.

---

## 📘 Conceitos de Nuvem

### Computação em Nuvem
A computação em nuvem é o fornecimento de serviços de computação pela internet, permitindo:
- Inovação mais rápida  
- Recursos flexíveis  
- Economia de escala  

---

## ☁️ Modelos de Nuvem

### 🔒 Nuvem Privada
- Criada no datacenter da própria organização  
- A organização é responsável por operar e manter os serviços  
- Não oferece acesso a usuários externos  

### 🌐 Nuvem Pública
- Pertence a um provedor de nuvem ou hosting  
- Recursos compartilhados entre várias organizações e usuários  
- Acesso via conexão de rede segura  

### 🔀 Nuvem Híbrida
- Combina nuvens públicas e privadas  
- Permite executar aplicações no ambiente mais adequado  

---

## 📊 Comparação dos Modelos de Nuvem

### Nuvem Pública
- Nenhuma despesa de capital (CapEx)
- Provisionamento e desprovisionamento rápidos
- Pagamento apenas pelo que é utilizado (Pay as You Go – OpEx)

### Nuvem Privada
- Controle total de recursos e segurança
- Responsabilidade por manutenção e atualização do hardware

### Nuvem Híbrida
- Flexibilidade para decidir onde executar aplicações
- Controle de segurança, conformidade e requisitos legais

---

## 💰 CapEx vs OpEx

### CapEx (Capital Expenditure)
- Gasto inicial com infraestrutura física
- Valor reduz ao longo do tempo (depreciação)

### OpEx (Operational Expenditure)
- Pagamento conforme o uso
- Cobrança imediata

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
- Pagamento apenas pelo que é utilizado

### Elasticidade
- Expansão ou redução automática ou manual de recursos
- Exemplo: adicionar ou remover VMs e containers

### Confiabilidade
- Infraestrutura distribuída globalmente
- Continuidade mesmo em falhas regionais

### Previsibilidade
- Previsibilidade de desempenho e custos
- Baseada no Azure Well-Architected Framework

### Segurança
- Ferramentas de segurança robustas
- Parte da implementação é responsabilidade do cliente

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
- Firewalls e segurança de rede
- Datacenter físico

### PaaS – Platform as a Service
- Ambiente para desenvolvimento, teste e deploy
- Sem gerenciamento da infraestrutura
- Sistemas operacionais e ferramentas de desenvolvimento

### SaaS – Software as a Service
- Aplicações prontas via internet
- Exemplo: Microsoft 365, e-mail e calendários

---

## 🏗️ Arquitetura do Azure

### Regiões
- Presença global
- Baixa latência
- Conformidade de dados

### Zonas de Disponibilidade
- Datacenters fisicamente separados
- Energia, refrigeração e rede independentes
- Conectados por fibra óptica privada

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
- Contêiner lógico para gerenciamento de recursos
- Um recurso pertence a apenas um grupo

### Assinaturas
- Controle de cobrança
- Controle de acesso

### Grupos de Gerenciamento
- Agrupam várias assinaturas
- Herança de políticas

---

## 🖥️ Computação no Azure

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

### Conta de Armazenamento
- Nome globalmente exclusivo
- Acesso via internet
- Definição de redundância

### Redundância
- LRS: 11 noves
- ZRS: 12 noves

### Serviços
- Blob Storage
- Disk Storage
- File Storage
- Queue Storage
- Table Storage
- Data Lake Storage Gen2

---

## 🔄 Migração para o Azure

- Azure Migrate
- Azure Data Box (até 80 TB)
- AzCopy
- Storage Explorer
- Azure File Sync

---

## 🔐 Identidade e Acesso

### Microsoft Entra ID
- Autenticação
- Single Sign-On (SSO)
- Gerenciamento de dispositivos
- B2B

### Autenticação vs Autorização
- Autenticação: quem é
- Autorização: o que pode fazer

### MFA
- Autenticação multifator para maior segurança

### RBAC
- Controle de acesso baseado em função
- Princípio do menor privilégio

---

## 🛡️ Segurança e Governança

- Zero Trust
- Microsoft Defender for Cloud
- Azure Policy
- Resource Locks
- Microsoft Purview
- Azure Arc

---

## 💸 Gerenciamento de Custos

- Azure Cost Management
- Calculadora de Preços
- Calculadora TCO
- Orçamentos e Alertas
- Tags para organização de custos

---

## ⚙️ Infraestrutura como Código

### Azure Resource Manager (ARM)
- Camada de gerenciamento do Azure
- Criação, atualização e exclusão de recursos

### Templates ARM
- Arquivos JSON declarativos
- Recursos reutilizáveis e modulares
- Validação integrada

### Bicep
- Linguagem de infraestrutura da Microsoft
- Sintaxe simplificada em relação ao ARM JSON
