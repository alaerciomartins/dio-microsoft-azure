# 🖥️ Lab: Criação de Máquinas Virtuais na Microsoft Azure

Este documento descreve o processo de criação de máquinas virtuais (VMs) na plataforma Microsoft Azure, abordando as principais etapas, configurações e recursos envolvidos.

![Azure](https://img.shields.io/badge/Azure-VM-blue?style=flat-square&logo=microsoft-azure) ![Virtual Machine](https://img.shields.io/badge/Virtual%20Machine-Setup-green?style=flat-square&logo=windows-terminal)

---

## 📋 Passos para Criar uma Máquina Virtual no Azure

### 1. Acessar o Portal do Azure
- Acesse o [Portal do Azure](https://portal.azure.com) com suas credenciais.

### 2. Criar um Grupo de Recursos
- **Grupo de Recursos:** Um contêiner que armazena recursos relacionados. É recomendado criar um novo grupo para organizar a VM e seus componentes.
- Navegue até "Grupos de Recursos" e clique em **Criar**.

### 3. Iniciar o Processo de Criação da VM
- Vá até **Máquinas Virtuais** no painel lateral.
- Clique em **Adicionar** para iniciar a configuração de uma nova VM.

### 4. Configurações Básicas
- **Assinatura:** Selecione a assinatura ativa.
- **Grupo de Recursos:** Escolha o grupo criado anteriormente.
- **Nome da VM:** Defina um nome amigável (ex: `SRV-LAB-AZ900`).
- **Região:** Escolha a localização mais próxima ou adequada para seus recursos.

### 5. Escolher a Imagem e o Tamanho da VM
- **Imagem:** Selecione a imagem do sistema operacional desejado, como `Windows Server` ou `Ubuntu`.
- **Tamanho:** Escolha o tamanho da VM conforme suas necessidades de CPU, memória e disco.

### 6. Configurar as Opções de Rede
- **Rede Virtual (VNet):** Configure ou crie uma nova VNet para gerenciar o tráfego de rede da VM.
- **Endereço IP Público:** Opcional, necessário para acesso externo.
- **Grupo de Segurança de Rede (NSG):** Configure as regras de entrada e saída para controlar o tráfego.

### 7. Revisar e Criar
- Revise todas as configurações e clique em **Criar** para iniciar a implementação da VM.

![image](https://github.com/user-attachments/assets/4c5b1744-9b18-47c5-8766-4144cc82bf16)


---

## 📝 Exemplos de Recursos Criados

- **VM:** SRV-LAB-AZ900
- **Interface de Rede:** srv-lab-az900742
- **Endereço IP Público:** SRV-LAB-AZ900-ip
- **Rede Virtual (VNet):** SRV-LAB-AZ900-vnet
- **Grupo de Segurança (NSG):** SRV-LAB-AZ900-nsg
- **Agendamento de Desligamento:** shutdown-computevm-SRV-LAB-AZ900

---

## 📈 Benefícios da Criação de VMs no Azure
- **Flexibilidade:** Escolha de várias configurações de hardware e software.
- **Escalabilidade:** Ajuste de recursos de acordo com a demanda.
- **Segurança:** Integração com ferramentas de segurança avançadas da Microsoft.

---

> **Dica:** Após a criação, é recomendável configurar o **Encerramento Automático** para evitar custos adicionais quando a VM não estiver em uso.

📌 **Links Úteis:**
- [Portal do Azure](https://portal.azure.com)
- [Documentação do Azure](https://docs.microsoft.com/azure)

---

⚙️ **Lab concluído com sucesso!** Mantenha suas VMs otimizadas e seguras, e continue explorando as funcionalidades do Azure para aprimorar seus ambientes virtuais.
