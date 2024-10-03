# 📚 Resumo da Aula: Primeiros Passos com Governança e Conformidade na Azure

Este resumo aborda os principais conceitos e ferramentas para garantir a governança e a conformidade no Azure, incluindo o uso de Blueprints, políticas, e bloqueios de recursos.

---

## 🛠️ Blueprints, Políticas e Bloqueios de Recurso

### **Azure Blueprints**
- **Descrição:** Ferramenta para definir e padronizar a configuração de ambientes no Azure. Permite a implantação de políticas, templates e permissões de forma automatizada e consistente.
- **Aplicações:** Usado para automatizar a criação de ambientes em conformidade com as políticas da empresa, incluindo regras de segurança e padrões operacionais.

### **Azure Policy**
- **Descrição:** Serviço que permite a criação e aplicação de políticas que garantem o cumprimento de regras e requisitos dentro de recursos no Azure.
- **Aplicações:** Restringir tipos de recursos que podem ser criados, garantir o uso de regiões específicas, ou verificar se os recursos estão em conformidade com políticas estabelecidas.

### **Resource Locks (Bloqueios de Recurso)**
- **Descrição:** Bloqueios que impedem a exclusão ou modificação acidental de recursos importantes.
- **Tipos de Bloqueio:**
  - **Read-only:** Impede que o recurso seja modificado.
  - **Delete:** Impede a exclusão de recursos.

---

## 🔒 Gerenciando Bloqueios de Recursos

- **Objetivo:** Proteger recursos críticos contra alterações acidentais ou não autorizadas.
- **Exemplo:** Utilizar o bloqueio "Delete" para garantir que uma VM ou um grupo de recursos importante não seja excluído por engano.

---

## 🔎 Revisando a Governança e Conformidade

### **Governança no Azure**
- **Descrição:** A governança envolve a criação de um ambiente gerenciável e seguro, garantindo que todas as políticas de TI e regulatórias sejam seguidas.
- **Ferramentas:** Azure Blueprints, Azure Policy e Resource Locks são componentes essenciais para manter a governança dos recursos.

### **Conformidade**
- **Descrição:** Conformidade é o processo de garantir que os recursos no Azure estejam de acordo com os requisitos legais, regulamentares e organizacionais.
- **Monitoramento Contínuo:** Use as ferramentas de conformidade do Azure para verificar continuamente o status dos recursos e garantir que estejam em conformidade.

---

> **Nota:** Este resumo visa reforçar os conceitos aprendidos na aula sobre governança e conformidade no Azure, ajudando a consolidar o conhecimento adquirido.

---
