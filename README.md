# Resumo – Conceitos Básicos de Cloud (AZ-900)

📘 **Curso:** Introdução aos Conceitos Básicos de Cloud – AZ-900  
👩‍🏫 **Instrutora:** Valéria Baptista  
🎯 **Objetivo:** Consolidar os principais conceitos de computação em nuvem, arquitetura e serviços do Azure, com foco na certificação **AZ-900**.

---

## ☁️ Conceitos de Computação em Nuvem

A **computação em nuvem** é o fornecimento de serviços de computação pela internet, permitindo acesso rápido a recursos, maior flexibilidade, escalabilidade sob demanda e economias de escala.

---

## 🏗️ Modelos de Nuvem

### 🔒 Nuvem Privada
- Criada no **datacenter da própria organização**
- Total responsabilidade sobre **operação, manutenção e segurança**
- Não oferece acesso a usuários externos

### 🌍 Nuvem Pública
- Pertence a um **provedor de serviços em nuvem (hosting)**
- Fornece recursos para várias organizações e usuários
- Acessada por meio de **conexão segura à internet**

### 🔄 Nuvem Híbrida
- Combina **nuvem pública e privada**
- Permite executar aplicações no ambiente mais adequado

---

## ⚖️ Comparação entre Modelos de Nuvem

### Nuvem Pública
- Sem despesas de capital (**CAPEX**)
- Recursos podem ser **provisionados e desprovisionados rapidamente**
- Pagamento apenas pelo uso (**Pay-as-you-Go / OPEX**)

### Nuvem Privada
- Controle total de recursos e segurança
- Responsabilidade total por **manutenção e atualização de hardware**

### Nuvem Híbrida
- Liberdade para decidir onde executar aplicações
- Controle sobre **segurança, conformidade e requisitos legais**
- Maior flexibilidade

---

## 💰 CAPEX vs OPEX

### CAPEX (Despesas de Capital)
- Gasto inicial em **infraestrutura física**
- Alto custo inicial
- O valor se reduz com o tempo (depreciação)

### OPEX (Despesas Operacionais)
- Pagamento conforme o uso de produtos e serviços
- Cobrança imediata
- Modelo padrão da computação em nuvem

---

## 📊 Modelo Baseado em Consumo

Os provedores de nuvem utilizam um **modelo baseado em consumo**, onde os usuários pagam apenas pelos recursos utilizados.

**Benefícios:**
- Melhor previsibilidade de custos
- Preços definidos por recurso e serviço
- Cobrança baseada no uso real

---

## 🌟 Benefícios da Nuvem

### Alta Disponibilidade
- Baseada em **SLA (Service Level Agreement)**
- Define o nível de disponibilidade garantido pelo Azure

### Escalabilidade
- Capacidade de aumentar ou reduzir recursos conforme a demanda
- Pagamento apenas pelo que é utilizado
- Redução de custos quando a demanda diminui

### Elasticidade
- Expansão ou redução automática ou manual de recursos
- Exemplo: adicionar ou remover **máquinas virtuais ou containers**

### Confiabilidade
- Infraestrutura descentralizada e resiliente
- Recursos distribuídos em várias regiões do mundo
- Continuidade mesmo em falhas regionais

### Previsibilidade
- Previsibilidade de desempenho e custos
- Baseada no **Microsoft Azure Well-Architected Framework**

### Segurança
- Ferramentas de segurança fornecidas pela nuvem
- Algumas configurações são responsabilidade do cliente
- PaaS e SaaS reduzem a carga de manutenção e aplicação de patches

### Governança
- Mantém o ambiente em nuvem organizado, seguro e em conformidade
- Importante implementar desde o início

### Gerenciabilidade
- Gerenciamento por:
  - Portal Web
  - Linha de comando (CLI)
  - APIs
  - PowerShell
- Automação de implantação e escalabilidade
- Uso de modelos pré-configurados

---

## ☁️ Tipos de Serviço de Nuvem

### IaaS (Infrastructure as a Service)
- Infraestrutura de TI sob demanda
- Exemplos:
  - Máquinas virtuais
  - Armazenamento
  - Redes
  - Firewalls
- Cliente gerencia sistema operacional e aplicativos

### PaaS (Platform as a Service)
- Ambiente para criação, teste e implantação de aplicações
- Provedor gerencia a infraestrutura
- Exemplos:
  - Sistemas operacionais
  - Bancos de dados
  - Ferramentas de desenvolvimento

### SaaS (Software as a Service)
- Aplicações acessadas pela internet
- Modelo de assinatura
- Exemplos:
  - Microsoft 365
  - Email
  - Calendários
  - Aplicações hospedadas

---

## 🔍 Comparação dos Serviços de Nuvem

### PaaS
- Foco no desenvolvimento de aplicações
- Gerenciamento da plataforma feito pelo provedor

### SaaS
- Pagamento conforme o uso
- Usuário utiliza apenas o software

---

## 🏛️ Arquitetura e Serviços do Azure

### Regiões
- Presença global
- Compostas por um ou mais datacenters próximos
- Reduzem latência
- Garantem residência e conformidade dos dados

### Zonas de Disponibilidade
- Proteção contra falhas de datacenter
- Datacenters fisicamente separados
- Energia, rede e resfriamento independentes
- Conectados por redes privadas de fibra óptica

### Pares de Regiões
- Separação mínima de 300 milhas
- Replicação automática para alguns serviços
- Atualizações distribuídas sequencialmente

### Regiões Soberanas
- Serviços governamentais (EUA e China)
- Infraestrutura fisicamente separada
- Operadas por parceiros específicos (ex: 21Vianet)

---

## 🧩 Recursos do Azure

### Grupo de Recursos
- Contêiner lógico para agrupar recursos
- Cada recurso pertence a apenas um grupo
- Aplicações podem usar vários grupos

### Assinaturas do Azure
- Fornecem acesso autenticado ao Azure
- Permitem controle de:
  - Cobrança
  - Acesso
  - Provisionamento de recursos

### Grupos de Gerenciamento
- Agrupam várias assinaturas
- As assinaturas herdam políticas e regras do grupo

---

## 🔧 Git e GitHub – Conceitos Básicos

### Comandos Git
- `git clone <url>` → Clona um repositório remoto
- `git init` → Inicializa um repositório Git
- `mkdir` → Cria diretórios

### Salvando Credenciais (Token)
- `git config credential.helper cache` → Salva credencial temporariamente
- `git config credential.helper store` → Salva credencial permanentemente

---

## ✅ Conclusão

Este repositório reúne os principais conceitos introdutórios de computação em nuvem, arquitetura e serviços do Azure, servindo como material de apoio para estudos e preparação para a certificação **Microsoft Azure Fundamentals (AZ-900)**.
