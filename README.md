# LaboratorioAzure2

# Monitoramento de Máquinas Virtuais no Microsoft Azure

## Descrição do Projeto
Este repositório documenta a experiência prática de configuração e gerenciamento do monitoramento de máquinas virtuais no Microsoft Azure. O objetivo é garantir visibilidade, controle e resposta proativa a eventos críticos, como exclusão acidental de VMs.

## Objetivos
- Aplicar conceitos de monitoramento no Azure Monitor para VMs.
- Criar alertas para eventos importantes.
- Documentar o processo para facilitar estudos e futuras implementações.
- Utilizar o GitHub para organização e compartilhamento da documentação.

## Conteúdo
- Configuração do Azure Monitor para VMs
- Criação de alertas administrativos (ex: exclusão de VM)
- Análise do Registro de Atividades para auditoria
- Uso do Log Analytics para consultas avançadas
- Dicas práticas e melhores práticas
- Capturas de tela organizadas em `/images`

## Passos Realizados

1. **Configuração do Azure Monitor:**
   - Ativação do monitoramento para VMs específicas.
   - Configuração da coleta de métricas e logs.

2. **Criação de alertas:**
   - Definição de regras para alertar sobre eventos críticos.
   - Configuração da severidade do alerta e canais de notificação.

3. **Auditoria via Registro de Atividades:**
   - Filtragem da categoria 'Administrativo' para rastrear exclusões de recursos.

4. **Consultas no Log Analytics:**
   - Exemplos de queries KQL para análise de logs.

5. **Dicas e observações:**
   - Atualizar sempre agentes nas VMs.
   - Revisar políticas de bloqueio e acesso.
   - Utilizar workspaces de Log Analytics organizados.

## Recursos
- [Documentação oficial Azure Monitor](https:/)
