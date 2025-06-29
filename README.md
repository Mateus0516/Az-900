# Az-900
# 🛰️ Monitoramento de Máquinas Virtuais no Azure

## 📌 Descrição do Projeto

Este repositório documenta o laboratório prático realizado como parte da formação na DIO, com o objetivo de configurar e gerenciar o monitoramento de recursos no **Microsoft Azure**, com foco em **máquinas virtuais (VMs)**. O propósito principal é garantir **visibilidade, controle e resposta proativa** a eventos críticos no ambiente de nuvem, como a **exclusão de uma VM**, uso excessivo de CPU, ou falhas no sistema.

---

## 🎯 Objetivos de Aprendizagem

✅ Aplicar conceitos de monitoramento no Azure  
✅ Utilizar ferramentas como Azure Monitor e Log Analytics  
✅ Criar alertas personalizados para eventos e métricas de VMs  
✅ Documentar processos técnicos de forma clara  
✅ Compartilhar conhecimento por meio do GitHub

---

## 🛠️ Tecnologias Utilizadas

- Microsoft Azure
- Azure Monitor
- Log Analytics Workspace
- Alertas de Métricas e Atividades
- Git & GitHub
- Markdown

---

## 📝 Etapas Realizadas

### 1. Criação da Máquina Virtual
- Criada uma VM com Windows Server 2022
- Monitoramento habilitado no momento da criação
- Configurada para registrar dados em um Log Analytics Workspace

### 2. Configuração do Monitoramento
- Associada a um **Log Analytics Workspace** para centralizar os logs
- Ativado o **Azure Monitor** com coleta de métricas básicas e avançadas
- Habilitada a visualização no painel do Azure Monitor

### 3. Criação de Alertas
- **Alerta por uso excessivo de CPU**: acionado quando uso ultrapassa 80%
- **Alerta de exclusão da VM**: configurado via log de atividades (Activity Log)
- Testes realizados para simular cenários e validar acionamento

### 4. Testes Realizados
- Stress test para elevar uso da CPU
- Exclusão simulada para disparo de alerta de atividade
- Visualização dos logs e métricas no portal

---

## 📸 Capturas de Tela

As imagens a seguir mostram etapas importantes do processo. Elas estão organizadas na pasta `/images` deste repositório.

- Alertas configurados
- Gráfico de uso da CPU
- Log de atividades
- Detalhamento de incidentes

---

## 📚 Referências e Recursos Úteis

- [Documentação Oficial do Azure Monitor](https://learn.microsoft.com/pt-br/azure/azure-monitor/)
- [Monitoramento de Máquinas Virtuais no Azure](https://learn.microsoft.com/pt-br/azure/azure-monitor/vm/monitor-virtual-machine)
- [GitHub Docs - Markdown](https://docs.github.com/en/get-started/writing-on-github)

---

## 🚀 Autor

Desenvolvido por [Seu Nome Aqui] durante o desafio da DIO — *Monitoramento de Recursos com Azure*  
Conecte-se comigo no [LinkedIn](https://www.linkedin.com)!

---

> **Dica:** este repositório servirá como material de consulta para futuras implementações de monitoramento em ambientes de produção no Azure.
