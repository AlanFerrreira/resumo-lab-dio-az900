# Resumo – Conceitos Básicos de Cloud (AZ-900)

📘 **Curso:** Introdução aos Conceitos Básicos de Cloud – AZ-900  
👩‍🏫 **Instrutora:** Valéria Baptista  
🎯 **Objetivo:** Consolidar os principais conceitos de computação em nuvem, serviços e arquitetura do Microsoft Azure, com foco na certificação **AZ-900**.

---

## ☁️ Conceitos de Computação em Nuvem

A **computação em nuvem** é o fornecimento de serviços de computação pela internet, permitindo acesso rápido a recursos, maior flexibilidade, escalabilidade sob demanda e economias de escala, sem a necessidade de grandes investimentos em infraestrutura física.

---

## 🏗️ Modelos de Nuvem

### 🔒 Nuvem Privada
- Criada no **datacenter da própria organização**
- Total responsabilidade sobre **operação, manutenção e segurança**
- Não oferece acesso a usuários externos

### 🌍 Nuvem Pública
- Pertence a um **provedor de serviços de nuvem (hosting)**
- Recursos compartilhados entre várias organizações
- Acessada por meio de **conexão segura à internet**

### 🔄 Nuvem Híbrida
- Combina **nuvem pública e privada**
- Permite executar aplicações no ambiente mais adequado

---

## ⚖️ Comparação entre Modelos de Nuvem

### Nuvem Pública
- Não exige investimento inicial (**CAPEX**)
- Recursos podem ser **provisionados e desprovisionados rapidamente**
- Pagamento conforme o uso (**Pay-as-you-Go / OPEX**)

### Nuvem Privada
- Controle total sobre recursos e segurança
- Responsabilidade por **manutenção e atualização de hardware**

### Nuvem Híbrida
- Flexibilidade para definir onde executar aplicações
- Controle sobre **segurança, conformidade e requisitos legais**

---

## 💰 CAPEX vs OPEX

### CAPEX (Despesas de Capital)
- Investimento inicial em **infraestrutura física**
- Alto custo inicial
- Ativos se depreciam ao longo do tempo

### OPEX (Despesas Operacionais)
- Pagamento conforme o uso
- Cobrança imediata
- Modelo padrão da computação em nuvem

---

## 📊 Modelo Baseado em Consumo

Os provedores de nuvem operam com um **modelo baseado em consumo**, no qual os usuários pagam apenas pelos recursos utilizados.

**Benefícios:**
- Melhor previsibilidade de custos
- Preços definidos por serviço
- Cobrança baseada no uso real

---

## 🌟 Benefícios da Nuvem

### Alta Disponibilidade
- Baseada em **SLA (Service Level Agreement)**
- Define o nível de disponibilidade garantido pelo Azure

### Escalabilidade
- Capacidade de aumentar ou reduzir recursos conforme a demanda
- Pagamento apenas pelo que é utilizado

### Elasticidade
- Expansão ou redução automática ou manual de recursos
- Exemplo: adição ou remoção de **VMs ou containers**

### Confiabilidade
- Infraestrutura descentralizada e resiliente
- Recursos distribuídos em várias regiões
- Continuidade mesmo em falhas regionais

### Previsibilidade
- Previsibilidade de custo e desempenho
- Baseada no **Azure Well-Architected Framework**

### Segurança
- Ferramentas de segurança fornecidas pelo Azure
- Parte da configuração é responsabilidade do cliente
- PaaS e SaaS reduzem a necessidade de manutenção

### Governança
- Mantém o ambiente organizado, seguro e em conformidade
- Deve ser implementada desde o início

### Gerenciabilidade
- Gerenciamento via:
  - Portal Web
  - CLI
  - APIs
  - PowerShell
- Automação de implantações e escalabilidade

---

## ☁️ Tipos de Serviço de Nuvem

### IaaS (Infrastructure as a Service)
- Infraestrutura sob demanda
- Exemplo:
  - Máquinas virtuais
  - Redes
  - Armazenamento
  - Firewalls

### PaaS (Platform as a Service)
- Ambiente para desenvolvimento e implantação de aplicações
- Provedor gerencia a infraestrutura
- Exemplo:
  - Sistemas operacionais
  - Bancos de dados
  - Ferramentas de desenvolvimento

### SaaS (Software as a Service)
- Aplicações acessadas pela internet
- Modelo de assinatura
- Exemplo:
  - Microsoft 365
  - Email
  - Calendários

---

## 🏛️ Arquitetura e Serviços do Azure

### Regiões
- Presença global
- Compostas por um ou mais datacenters próximos
- Reduzem latência
- Garantem conformidade e residência dos dados

### Zonas de Disponibilidade
- Proteção contra falhas de datacenter
- Datacenters fisicamente separados
- Energia, rede e resfriamento independentes

### Pares de Regiões
- Separação mínima de 300 milhas
- Replicação automática para alguns serviços
- Atualizações sequenciais para reduzir downtime

### Regiões Soberanas
- Serviços governamentais (EUA e China)
- Infraestrutura isolada
- Operadas por parceiros específicos (ex: 21Vianet)

---

## 🧩 Recursos do Azure

### Grupos de Recursos
- Contêiner lógico para agrupar recursos
- Cada recurso pertence a apenas um grupo

### Assinaturas
- Controlam acesso, cobrança e limites
- Permitem separar custos e permissões

### Grupos de Gerenciamento
- Agrupam várias assinaturas
- Aplicam políticas de forma hierárquica

---

## 🖥️ Computação e Rede no Azure

### Serviços de Computação
- Máquinas Virtuais
- App Services
- Azure Container Instances
- Azure Kubernetes Service (AKS)
- Azure Virtual Desktop

### Máquinas Virtuais
- Emulações de computadores físicos
- Oferta de **IaaS**
- Controle total do sistema operacional

### Conjuntos de Dimensionamento (VM Scale Sets)
- Escalabilidade automática
- Balanceamento de carga

### Conjuntos de Disponibilidade
- Proteção contra falhas físicas
- Uso de domínios de falha

### Azure Virtual Desktop
- Ambiente completo de desktop virtual
- Suporte a múltiplas sessões

---

## 📦 Containers e Serverless

### Serviços de Containers
- Ambiente leve e escalável
- Sem gerenciamento do sistema operacional

- **Azure Container Instances** → PaaS para containers
- **Azure App Containers** → Escala automática
- **AKS** → Orquestração de containers

### Azure Functions
- Computação sem servidor (Serverless)
- Código executado sob demanda
- Pagamento apenas pelo tempo de execução

---

## 🌐 Serviços de Rede

### Rede Virtual (VNet)
- Comunicação entre recursos
- Suporte a endpoints públicos e privados
- Sub-redes e emparelhamento de redes

### Gateway de VPN
- Comunicação criptografada entre Azure e ambiente local

### ExpressRoute
- Conexão privada entre datacenter local e Azure

### Azure DNS
- Alta disponibilidade e desempenho
- Suporte a domínios públicos e privados
- Integração com RBAC e monitoramento

---

## 🔧 Git e GitHub – Conceitos Básicos

### Comandos Git
- `git clone <url>` → Clona repositório
- `git init` → Inicializa repositório
- `mkdir` → Cria diretórios

### Salvando Credenciais (Token)
- `git config credential.helper cache` → Temporário
- `git config credential.helper store` → Permanente

---

## ✅ Conclusão

Este repositório reúne os principais conceitos de computação em nuvem e Microsoft Azure, servindo como material de apoio para estudos e preparação para a certificação **Azure Fundamentals (AZ-900)**.
