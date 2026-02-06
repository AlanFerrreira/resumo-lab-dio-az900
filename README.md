# 📘 Resumo – Fundamentos de Cloud Computing (AZ-900)

> Conteúdo baseado nas aulas de **Valéria Baptista**, organizado e revisado para fins de estudo e portfólio no GitHub.

---

## ☁️ Conceitos de Nuvem

### Computação em Nuvem

Computação em nuvem é o fornecimento de serviços de computação pela internet, permitindo maior agilidade, recursos flexíveis e economia de escala.

---

## 🌐 Modelos de Nuvem

### Nuvem Privada

* Ambiente em nuvem criado no datacenter da própria organização
* Total responsabilidade da empresa pela operação e manutenção
* Não oferece acesso a usuários externos

### Nuvem Pública

* Pertence a provedores de nuvem ou hosting
* Fornece recursos para múltiplas organizações e usuários
* Acessada por meio de conexão segura via internet

### Nuvem Híbrida

* Combina nuvem pública e privada
* Permite executar aplicações no ambiente mais adequado

---

## 🔍 Comparação dos Modelos de Nuvem

### Nuvem Pública

* Sem despesa inicial de capital (CapEx)
* Provisionamento e desprovisionamento rápido
* Pagamento conforme o uso (Pay as You Go)

### Nuvem Privada

* Controle total sobre recursos e segurança
* Responsabilidade total pela manutenção e atualização do hardware

### Nuvem Híbrida

* Flexibilidade para escolher onde executar aplicações
* Controle de segurança, conformidade e requisitos legais

---

## 💰 CapEx vs OpEx

### CapEx (Despesas de Capital)

* Investimento inicial em infraestrutura física
* Valor depreciado ao longo do tempo

### OpEx (Despesas Operacionais)

* Pagamento conforme uso
* Custos cobrados imediatamente

### Modelo Baseado em Consumo

* Pagamento apenas pelos recursos utilizados
* Melhor previsibilidade de custos
* Cobrança baseada no uso real

---

## 🚀 Benefícios da Nuvem

### Alta Disponibilidade

* Definida por SLA (Service Level Agreement)
* Garante níveis de disponibilidade e desempenho

### Escalabilidade

* Capacidade de aumentar ou reduzir recursos conforme demanda
* Evita gastos desnecessários

### Elasticidade

* Ajuste automático ou manual de recursos em picos ou quedas de demanda

### Confiabilidade

* Arquitetura descentralizada e resiliente
* Recursos distribuídos globalmente

### Previsibilidade

* Planejamento confiável de desempenho e custos
* Baseado no Azure Well-Architected Framework

### Segurança

* Ferramentas robustas de segurança
* Parte da configuração é responsabilidade do cliente

### Governança

* Mantém o ambiente seguro, organizado e em conformidade

### Gerenciabilidade

* Gerenciamento via Portal Web, CLI, APIs e PowerShell
* Automação e uso de modelos pré-configurados

---

## 🧱 Tipos de Serviço em Nuvem

### IaaS – Infrastructure as a Service

* Infraestrutura sob demanda
* Servidores, VMs, redes e armazenamento

### PaaS – Platform as a Service

* Ambiente para desenvolvimento e implantação
* Sem gerenciamento da infraestrutura subjacente

### SaaS – Software as a Service

* Aplicações acessadas via internet
* Ex: Microsoft 365, e-mail e calendários

---

## 🏗️ Arquitetura do Azure

### Regiões

* Abrangência global
* Um ou mais datacenters próximos
* Redução de latência e conformidade de dados

### Zonas de Disponibilidade

* Proteção contra falhas de datacenter
* Datacenters fisicamente separados

### Pares de Regiões

* Separação mínima de 300 milhas
* Replicação automática e recuperação priorizada

### Regiões Soberanas

* Serviços governamentais (EUA e China)
* Instâncias fisicamente isoladas

---

## 📦 Recursos do Azure

### Grupo de Recursos

* Contêiner lógico para gerenciamento de recursos

### Assinaturas

* Controle de cobrança e acesso

### Grupos de Gerenciamento

* Organização hierárquica de múltiplas assinaturas

---

## 🖥️ Computação no Azure

### Máquinas Virtuais (VMs)

* Emulação de computadores físicos
* Oferta de IaaS com controle total

### Conjuntos de Dimensionamento

* Escalonamento automático com balanceamento de carga

### Área de Trabalho Virtual

* Ambiente virtual completo
* Suporte a múltiplas sessões

### Containers

* Ambientes leves e escaláveis
* AKS para orquestração de containers

### Azure Functions

* Computação sem servidor (Serverless)
* Execução baseada em eventos

---

## 🌐 Serviços de Rede

* Azure Virtual Network (VNet)
* VPN Gateway
* ExpressRoute
* Azure DNS

---

## 💾 Armazenamento no Azure

### Conta de Armazenamento

* Nome globalmente exclusivo
* Define redundância e serviços disponíveis

### Redundância

* LRS: redundância local (11 noves)
* ZRS: redundância entre zonas (12 noves)

### Serviços

* Blob Storage
* Disk Storage
* Queue Storage
* File Storage
* Table Storage

---

## 🔐 Identidade e Segurança

### Microsoft Entra ID

* Gerenciamento de identidades e acessos
* SSO, MFA, B2B e gerenciamento de dispositivos

### Autenticação vs Autorização

* Autenticação: quem é o usuário
* Autorização: o que ele pode acessar

### MFA

* Camada adicional de segurança

### Controle de Acesso (RBAC)

* Acesso granular baseado em funções

### Confiança Zero

* Segurança em camadas

### Microsoft Defender for Cloud

* Monitoramento e proteção contra ameaças

---

## 💸 Gerenciamento de Custos

### Fatores que Afetam Custos

* Tipo de recurso
* Consumo
* Região
* Tráfego de rede

### Ferramentas

* Calculadora de Preços
* Calculadora TCO
* Orçamentos e Alertas

### Tags

* Organização e controle de custos
* Metadados no formato chave-valor

---

📌 **Este repositório tem como objetivo consolidar os principais conceitos cobrados na certificação AZ-900, servindo como material de estudo e portfólio técnico.**
