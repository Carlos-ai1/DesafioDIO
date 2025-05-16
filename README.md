# DesafioDIO

Desafio proposto é a criação de um repositório contendo resumos, anotações e dicas sobre o uso da Azure


🌐 Resumo sobre o Microsoft Azure
Microsoft Azure é uma plataforma de computação em nuvem desenvolvida pela Microsoft que oferece mais de 200 produtos e serviços em nuvem. Ela permite criar, gerenciar e implantar aplicativos em uma rede global de data centers. É amplamente usada para hospedagem de sites, inteligência artificial, análise de dados, armazenamento, desenvolvimento de aplicativos, e muito mais.

Principais categorias de serviços:
Computação: Máquinas virtuais (VMs), Azure Kubernetes Service (AKS), App Services

Armazenamento: Blobs, Files, Tables, Queues

Banco de Dados: Azure SQL, Cosmos DB, MySQL/PostgreSQL gerenciados

Rede: Azure Virtual Network, Load Balancer, VPN Gateway, Azure DNS

Segurança e identidade: Azure Active Directory, Key Vault, Azure Defender

DevOps: Azure DevOps, GitHub Actions

IA e Machine Learning: Azure AI Services, Azure Machine Learning Studio

Ferramentas de gerenciamento: Azure Monitor, Azure Cost Management, Resource Manager

📝 Anotações importantes
1. Recursos (Resources)
Cada serviço na Azure é um recurso.

Os recursos são agrupados em Resource Groups, que ajudam na organização e no gerenciamento de acesso.

2. Regiões e Zonas
Os serviços são implantados em regiões (ex: "East US", "Brazil South").

Algumas regiões têm múltiplas zonas de disponibilidade (AZs) para maior tolerância a falhas.

3. Modelos de Implantação
Pay-as-you-go: Pagamento conforme o uso.

Reserva de instâncias: Economias ao se comprometer com uso por 1 ou 3 anos.

Free tier: Azure oferece uma camada gratuita com serviços limitados.

4. CLI e Portal
Azure Portal: Interface web gráfica.

Azure CLI: Linha de comando para automação e scripts.

PowerShell: Suporte para automatização com scripts em PowerShell.

💡 Dicas de uso da Azure
Para Iniciantes
Comece pelo Azure Portal – É mais visual e facilita o aprendizado.

Use o Azure Learn (https://learn.microsoft.com/azure/) – Cursos gratuitos e interativos.

Teste com a conta gratuita – Você ganha crédito inicial e acesso ao plano gratuito.

Explore o App Services – Rápido para hospedar apps web com escalabilidade integrada.

Para Usuários Intermediários
Use templates do ARM ou Bicep – Para implantar infraestrutura como código (IaC).

Implemente boas práticas de segurança – Como gerenciamento de identidade via Azure AD.

Monitore com Azure Monitor e Log Analytics – Para insights detalhados e alertas.

Automatize com Azure DevOps ou GitHub Actions – Para CI/CD integrado à nuvem.

Segurança e Governança
Sempre configure tags nos recursos para organização e faturamento.

Use o Azure Policy para forçar conformidades (ex: impedir VMs sem criptografia).

Monitore e limite os custos com orçamentos e alertas no Cost Management.
