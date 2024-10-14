# Bootcamp_custos_azure
Este repositório fala um pouco sobre o que aprendi durante o modulo Custos no Azure do Bootcamp Microsoft Azure Essentials da Dio.

# Quais são os fatores que Podem Afetar os Custos no Azure



## Fatores que Influenciam os Custos

- **Tipo de Serviço**: Diferentes serviços, como máquinas virtuais (VMs), bancos de dados e armazenamento, têm estruturas de preço variadas. VMs de maior desempenho ou bancos de dados com alta disponibilidade têm custos mais elevados.
  
- **Tamanho da Instância**: As VMs são cobradas com base no tamanho, recursos de CPU, memória e armazenamento. Instâncias maiores resultam em custos maiores.

- **Localização (Região)**: Os preços variam entre diferentes regiões do Azure devido a fatores como demanda e infraestrutura local. Escolher a região correta pode ajudar a reduzir os custos.

- **Utilização de Recursos**: O tempo que os recursos ficam ativos afeta diretamente o custo. Manter uma VM ligada 24/7 custará mais do que desativá-la quando não estiver em uso.

- **Opções de Licenciamento**: O Azure oferece diferentes modelos de licenciamento, como "pay-as-you-go", instâncias reservadas (RI) ou a opção de usar licenças existentes via **Azure Hybrid Benefit**.

- **Transferência de Dados**: A movimentação de dados entre regiões ou fora do Azure pode gerar custos significativos, especialmente se grandes volumes de dados forem transferidos com frequência.

##  Calculadora de Preços vs. TCO

### **Calculadora de Preços**
A **Calculadora de Preços do Azure** permite estimar os custos mensais dos recursos que você pretende utilizar, fornecendo uma visão detalhada do custo de serviços individuais.

### **TCO (Total Cost of Ownership)**
A ferramenta **TCO** ajuda a comparar os custos do Azure em relação à manutenção de uma infraestrutura local. Ela leva em consideração despesas como hardware, energia e suporte para demonstrar como a migração para a nuvem pode gerar economia.


##  Ferramenta de Gerenciamento de Custos do Azure

A **Ferramenta de Gerenciamento de Custos** permite monitorar e otimizar seus gastos no Azure, oferecendo insights sobre o uso dos serviços e ajudando a prever custos futuros.

### Funcionalidades:
- **Relatórios Detalhados**: Mostra o consumo de recursos e os custos acumulados.
- **Alertas de Orçamento**: Permite definir alertas quando os gastos atingem um limite predefinido.
- **Recomendações de Otimização**: Sugere ajustes para reduzir o consumo de recursos e, consequentemente, o custo.

## Tags

**Marcas ou Tags** no Azure são usadas para organizar e categorizar os recursos, atribuindo chaves e valores aos recursos. Isso ajuda a identificar facilmente o propósito de cada recurso, como um projeto específico, departamento ou ambiente (produção, desenvolvimento, etc.).

### Vantagens das Marcas:
- **Gerenciamento de Custos**: Com o uso de tags, é possível filtrar relatórios de custos com base em categorias específicas, facilitando a atribuição de despesas.
- **Organização**: Facilita a organização e a busca de recursos em ambientes complexos.
- **Governança**: Garante que as políticas de governança da organização sejam aplicadas corretamente a todos os recursos.

---

# Vejamos na prática:

###  Acessando a **Calculadora de Preços**
- Vá para o site da [Calculadora de Preços do Azure](https://azure.microsoft.com/pt-br/pricing/calculator/).
- Adicione os serviços que você planeja utilizar ao clicar em "Adicionar item".
- Configure os detalhes de cada serviço, como região, tipo de instância, e tempo de utilização.
- A calculadora gerará uma estimativa de custo baseada nas suas escolhas. Você pode salvar, exportar ou compartilhar a estimativa.

###  Acessando a **Calculadora de TCO**
- Acesse a ferramenta [TCO Calculator](https://azure.microsoft.com/en-us/pricing/tco/calculator/).
- Insira os detalhes da sua infraestrutura local atual, incluindo servidores, armazenamento, rede, licenciamento e custos de energia.
- A ferramenta comparará os custos de manter essa infraestrutura localmente versus migrá-la para o Azure.
- Visualize a economia potencial com a migração para a nuvem.

###  Utilizando o **Gerenciamento de Custos no Azure Portal**
- No **Portal do Azure**, vá para a opção de **Gerenciamento de Custos**:
- No menu esquerdo, selecione **Gerenciamento de Custos + Faturamento**.
- **Visualize Relatórios**:
  - Acesse os relatórios de custo e consumo para analisar os gastos mensais.
- **Defina Orçamentos**:
  - No painel de gerenciamento de custos, crie um orçamento e defina limites para ser notificado quando os gastos atingirem um valor específico.
- **Otimize seus Recursos**:
  - A ferramenta fornecerá recomendações de economia baseadas no uso atual dos recursos.

---

