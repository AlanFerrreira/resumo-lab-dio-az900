# 📘 Resumo AZ-900 – Fundamentos de Cloud Computing e Microsoft Azure

Este repositório contém um resumo completo e organizado dos principais conceitos cobrados na certificação **Microsoft Azure Fundamentals (AZ-900)**. O material foi elaborado com foco em **estudo, revisão e fixação**, mantendo uma linguagem clara e alinhada aos conteúdos oficiais da Microsoft.

---

## ☁️ Conceitos Básicos de Computação em Nuvem

### O que é Computação em Nuvem

A computação em nuvem é o fornecimento de serviços de computação pela internet, permitindo acesso rápido a recursos flexíveis, escaláveis e com economia de custos, sem a necessidade de manter infraestrutura física local.

---

## 🌐 Modelos de Nuvem

### Nuvem Privada

* Ambiente de nuvem criado e mantido no datacenter da própria organização
* Total responsabilidade da organização sobre operação, manutenção e segurança
* Não oferece acesso a usuários externos

### Nuvem Pública

* Pertence a provedores de nuvem ou hosting (ex: Microsoft Azure)
* Fornece recursos para múltiplas organizações e usuários
* Acessada por meio de conexão segura via internet

### Nuvem Híbrida

* Combina nuvem pública e privada
* Permite executar aplicações no ambiente mais adequado
* Oferece maior flexibilidade e controle

---

## 🔁 Comparação dos Modelos de Nuvem

### Nuvem Pública

* Não exige investimento inicial em infraestrutura (CapEx)
* Recursos podem ser provisionados e desprovisionados rapidamente
* Modelo de pagamento conforme o uso (Pay as You Go)

### Nuvem Privada

* Maior controle sobre recursos e segurança
* Organização é responsável por manutenção e atualização do hardware

### Nuvem Híbrida

* Define onde cada aplicação será executada
* Controle de segurança, conformidade e requisitos legais
* Alta flexibilidade

---

## 💰 CapEx x OpEx

### CapEx (Despesas de Capital)

* Gasto inicial com infraestrutura física
* Valor do investimento se deprecia ao longo do tempo

### OpEx (Despesas Operacionais)

* Pagamento conforme o uso de produtos e serviços
* Custos cobrados imediatamente

### Modelo Baseado em Consumo

* Usuários pagam apenas pelos recursos utilizados
* Melhor previsibilidade de custos
* Cobrança baseada no uso real

---

## ✅ Benefícios da Nuvem

### Alta Disponibilidade

* Garantida por meio de SLA (Service Level Agreement)
* Define nível de disponibilidade e desempenho dos serviços

### Escalabilidade

* Capacidade de aumentar ou reduzir recursos conforme a demanda
* Evita pagamento por recursos não utilizados

### Elasticidade

* Ajuste rápido de recursos diante de picos ou quedas de demanda
* Pode ocorrer de forma automática ou manual

### Confiabilidade

* Arquitetura descentralizada e distribuída globalmente
* Recursos podem ser implantados em múltiplas regiões

### Previsibilidade

* Melhor controle de custos e desempenho
* Baseada no Azure Well-Architected Framework

### Segurança

* Ferramentas avançadas de proteção
* Parte da configuração de segurança é responsabilidade do cliente

### Governança

* Permite manter o ambiente seguro, controlado e conforme políticas

### Gerenciabilidade

* Gerenciamento via Portal Web, CLI, APIs ou PowerShell
* Automação e padronização de implantações

---

## 🧱 Tipos de Serviço de Nuvem

### IaaS – Infrastructure as a Service

* Infraestrutura sob demanda
* Inclui servidores, VMs, armazenamento, redes e SO

### PaaS – Platform as a Service

* Ambiente para desenvolvimento, teste e implantação de aplicações
* Provedor gerencia a infraestrutura subjacente

### SaaS – Software as a Service

* Aplicações acessadas via internet
* Modelo de assinatura (ex: Microsoft 365)

---

## 🏗️ Arquitetura do Azure

### Regiões

* Presença global
* Formadas por um ou mais datacenters
* Redução de latência e conformidade com residência de dados

### Zonas de Disponibilidade

* Proteção contra falhas de datacenter
* Datacenters fisicamente separados
* Energia, rede e resfriamento independentes

### Pares de Regiões

* Separação mínima de 300 milhas
* Replicação automática para alguns serviços
* Atualizações sequenciais

### Regiões Soberanas

* Atendem requisitos governamentais específicos
* Exemplo: Azure Government e Azure China (21Vianet)

---

## 📦 Organização de Recursos no Azure

### Grupo de Recursos

* Contêiner lógico de recursos
* Um recurso pertence a apenas um grupo

### Assinaturas do Azure

* Unidade de faturamento e controle de acesso
* Permite relatórios e limites de custo

### Grupos de Gerenciamento

* Agrupam múltiplas assinaturas
* Permitem aplicação de políticas em escala

---

## 🖥️ Computação no Azure

### Máquinas Virtuais

* Emulações de computadores físicos
* Oferta de IaaS com controle total

### Conjuntos de Dimensionamento (Scale Sets)

* Escalonamento automático e balanceamento de carga

### Conjuntos de Disponibilidade

* Distribuem VMs em domínios de falha

### Azure Virtual Desktop

* Área de trabalho Windows baseada em nuvem
* Suporte a múltiplos usuários simultâneos

### Containers

* Ambiente leve e portátil
* Execução de microsserviços

### AKS – Azure Kubernetes Service

* Orquestração de containers em larga escala

### Azure Functions

* Computação sem servidor (serverless)
* Executa código sob demanda baseado em eventos

---

## 🌐 Serviços de Rede

### VNet – Rede Virtual

* Comunicação entre recursos, internet e redes locais

### VPN Gateway

* Conexão criptografada entre Azure e ambiente local

### ExpressRoute

* Conexão privada dedicada com o Azure

### Azure DNS

* Serviço DNS global, seguro e altamente disponível

---

## 💾 Armazenamento no Azure

### Conta de Armazenamento

* Nome globalmente exclusivo
* Define serviços e redundância

### Redundância

* LRS: redundância local (11 noves)
* ZRS: redundância entre zonas (12 noves)

### Serviços de Armazenamento

* Blob: dados não estruturados
* File: compartilhamento de arquivos
* Queue: mensagens
* Table: dados NoSQL
* Data Lake Gen2: big data e analytics

---

## 🚚 Migração para o Azure

### Azure Migrate

* Avaliação e migração de workloads

### Azure Data Box

* Migração física de grandes volumes de dados

### Ferramentas

* AzCopy
* Storage Explorer
* Azure File Sync

---

## 🔐 Identidade, Acesso e Segurança

### Microsoft Entra ID

* Gerenciamento de identidades e acessos
* SSO, MFA, B2B, dispositivos

### Autenticação x Autorização

* Autenticação: quem é você
* Autorização: o que você pode fazer

### RBAC

* Controle de acesso baseado em função

### Zero Trust

* Modelo de segurança em camadas

### Microsoft Defender para Nuvem

* Monitoramento e recomendações de segurança
* Proteção contra ameaças

---

## 💸 Gerenciamento de Custos

### Fatores de Custo

* Tipo de recurso
* Consumo
* Região
* Tráfego de rede

### Ferramentas

* Calculadora de Preços
* Calculadora TCO
* Orçamentos e alertas
* Tags (marcas)

---

## 📜 Governança e Conformidade

### Azure Policy

* Impõe padrões e avalia conformidade

### Bloqueios de Recursos

* Evitam exclusões ou alterações acidentais

### Microsoft Purview

* Governança e conformidade de dados

---

## ⚙️ Gerenciamento e Monitoramento

### Azure Resource Manager (ARM)

* Camada de gerenciamento de recursos

### Infraestrutura como Código

* Padronização e automação

### ARM Templates

* Arquivos JSON declarativos

### Bicep

* Linguagem moderna para IaC

### Azure Advisor

* Recomendações de custo, segurança, desempenho e confiabilidade

### Azure Monitor

* Coleta e análise de métricas e logs

### Service Health

* Status geral e incidentes do Azure

### Resource Health

* Integridade dos recursos individuais

---

📌 **Este material pode ser utilizado como base de estudo, revisão rápida ou documentação de aprendizado para projetos e certificação AZ-900.**
