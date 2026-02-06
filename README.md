# Fundamentos de Cloud Computing – AZ-900

> Resumo completo dos conceitos fundamentais de Cloud Computing e Microsoft Azure  
> Conteúdo baseado no curso **AZ-900 – Microsoft Azure Fundamentals**  
> Instrutora: **Valéria Baptista**

---

## ☁️ Conceitos de Nuvem

### Computação em Nuvem
A computação em nuvem é o fornecimento de serviços de computação pela internet, permitindo maior agilidade, recursos flexíveis e economia de escala.

---

## 🌐 Modelos de Nuvem

### Nuvem Privada
- Ambiente em nuvem criado no datacenter da própria organização  
- A organização é responsável por operar e manter os serviços  
- Não oferece acesso a usuários externos  

### Nuvem Pública
- Pertence a um provedor de serviços de nuvem (hosting)  
- Fornece recursos e serviços para várias organizações e usuários  
- Acessada por meio de conexão de rede segura  

### Nuvem Híbrida
- Combina nuvens públicas e privadas  
- Permite executar aplicações no ambiente mais adequado  

---

## 🔍 Comparação dos Modelos de Nuvem

### Nuvem Pública
- Nenhuma despesa de capital (CapEx) para escalar  
- Provisionamento e desprovisionamento rápidos  
- Pagamento conforme o uso (*Pay as You Go*)  

### Nuvem Privada
- Controle total sobre recursos e segurança  
- Responsabilidade pela manutenção e atualização do hardware  

### Nuvem Híbrida
- Flexibilidade para definir onde executar aplicações  
- Controle sobre segurança, conformidade e requisitos legais  

---

## 💰 CapEx e OpEx

### CapEx (Capital Expenditure)
- Gasto inicial com infraestrutura física  
- O valor do investimento se reduz ao longo do tempo  

### OpEx (Operational Expenditure)
- Pagamento conforme o uso de produtos e serviços  
- Cobrança imediata  

### Modelo Baseado em Consumo
- Pagamento apenas pelos recursos utilizados  
- Melhor previsibilidade de custos  
- Cobrança baseada no uso real  

---

## 🚀 Benefícios da Nuvem

### Alta Disponibilidade
- Definida por SLA (*Service Level Agreement*)  
- Garante níveis de disponibilidade e desempenho dos serviços Azure  

### Escalabilidade
- Ajuste de recursos conforme a demanda  
- Evita custos desnecessários  

### Elasticidade
- Expansão ou redução automática/manual de recursos  
- Ideal para picos ou quedas repentinas de demanda  

### Confiabilidade
- Arquitetura descentralizada e resiliente  
- Recursos distribuídos globalmente  

### Previsibilidade
- Previsibilidade de desempenho e custos  
- Baseada no Azure Well-Architected Framework  

### Segurança
- Ferramentas de segurança fornecidas pelo Azure  
- Parte da implementação é responsabilidade do cliente  

### Governança
- Controle e padronização do ambiente de nuvem  
- Garante conformidade e boas práticas  

### Gerenciabilidade
- Gerenciamento via:
  - Portal Web  
  - CLI  
  - APIs  
  - PowerShell  

---

## 🧩 Tipos de Serviço de Nuvem

### IaaS – Infraestrutura como Serviço
- Servidores virtuais  
- Armazenamento e redes  
- Sistemas operacionais  
- Firewalls e segurança  

### PaaS – Plataforma como Serviço
- Ambiente para desenvolvimento, teste e deploy  
- Sistemas operacionais e ferramentas de desenvolvimento  
- Gerenciamento de banco de dados  

### SaaS – Software como Serviço
- Aplicações acessadas via internet  
- Exemplo: Microsoft 365, e-mail e calendários  

---

## 🏗️ Arquitetura e Serviços do Azure

### Regiões
- Presença global  
- Compostos por um ou mais datacenters  
- Reduzem latência e garantem conformidade  

### Zonas de Disponibilidade
- Proteção contra falhas de datacenter  
- Infraestrutura independente por zona  

### Pares de Regiões
- Separação mínima de 300 milhas  
- Replicação automática e recuperação priorizada  

### Regiões Soberanas
- Ambientes isolados para governos  
- Operadas separadamente do Azure público  

---

## 📦 Recursos do Azure

### Grupo de Recursos
- Contêiner lógico para gerenciar recursos  
- Um recurso pertence a apenas um grupo  

### Assinaturas
- Controle de acesso e cobrança  
- Relatórios e limites separados  

### Grupos de Gerenciamento
- Organização de múltiplas assinaturas  
- Herança de políticas e controles  

---

## 🖥️ Computação no Azure

- Máquinas Virtuais (VMs)  
- Azure App Services  
- Azure Container Instances  
- Azure Kubernetes Service (AKS)  
- Azure Virtual Desktop  

### Máquinas Virtuais
- Emulação de computadores físicos  
- Oferta de IaaS com controle total  

### Containers
- Ambiente leve e escalável  
- Ideal para microsserviços  

### Azure Functions
- Computação sem servidor (Serverless)  
- Execução baseada em eventos  

---

## 🌐 Serviços de Rede

- Azure Virtual Network (VNet)  
- VPN Gateway  
- ExpressRoute  
- Azure DNS  

---

## 💾 Armazenamento no Azure

### Conta de Armazenamento
- Nome globalmente exclusivo  
- Define serviços e redundância  

### Redundância
- **LRS**: redundância local (11 noves)  
- **ZRS**: redundância por zona (12 noves)  

### Serviços
- Blob Storage  
- Azure Files  
- Queue Storage  
- Table Storage  
- Azure Disks  

---

## 🔄 Migração para o Azure

### Azure Data Box
- Transferência de até 80 TB  
- Ideal para locais com conectividade limitada  

### Ferramentas
- AzCopy  
- Azure Storage Explorer  
- Azure File Sync  

---

## 🔐 Identidade, Acesso e Segurança

### Microsoft Entra ID
- Gerenciamento de identidades e acessos  
- Autenticação, SSO, B2B e gerenciamento de dispositivos  

### Autenticação vs Autorização
- **Autenticação**: valida identidade  
- **Autorização**: define permissões  

### MFA – Autenticação Multifator
- Exige dois ou mais fatores de autenticação  

### Controle de Acesso Baseado em Função (RBAC)
- Permissões granulares  
- Acesso mínimo necessário  

### Confiança Zero
- Segurança em camadas  
- Nenhuma confiança implícita  

### Microsoft Defender para Nuvem
- Monitoramento de segurança  
- Detecção de ameaças e malware  
- Recomendações de segurança  

---

## 🧠 Git e GitHub

### Comandos Básicos
```bash
git clone <url-do-repositorio>
git init
mkdir <nome-do-diretorio>
