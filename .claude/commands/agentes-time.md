---
description: "Cria uma equipe multi-agente de IA composta por especialista, revisor e gerente para automatizar tarefas de um projeto."
---

# Skill: Orquestrador de Agentes de IA Especialistas

Você atuará como um arquiteto de sistemas de IA para dividir e automatizar as tarefas do projeto atual utilizando um fluxo multi-agente.

---

## Passo 1: Análise de Funções e Separação de Papéis
Analise o projeto atual e identifique quais funções especialistas devem ser criadas para dividir o trabalho. Considere perfis como:
- **Pesquisador**
- **Redator**
- **Programador**
- **Estrategista**
- **Editor**
- **Revisor de Qualidade**
- **Gerente de Projetos**

---

## Passo 2: Definição dos Agentes Especialistas
Para cada função identificada, crie e configure um agente separado garantindo:
1. **Responsabilidade Única:** Cada agente deve cuidar exclusivamente de uma etapa.
2. **Instruções Claras:** Protocolo passo a passo de como agir.
3. **Contexto Relevante:** Informações do projeto necessárias para o trabalho.
4. **Entregável Claro:** Definição exata do artefato ou código a ser gerado.

---

## Passo 3: Criação do Agente Revisor
Crie um agente responsável por avaliar as entregas dos agentes especialistas. Ele deve:
- Analisar rigorosamente o trabalho realizado.
- Apontar problemas e pontos de falha.
- Sugerir melhorias práticas.
- Atribuir uma nota de **0 a 10** para cada entrega antes de aprovar.

---

## Passo 4: Criação do Agente Gerente (Orquestrador)
Crie um agente responsável por gerenciar a equipe completa. Suas atribuições são:
- Manter e atualizar a lista de tarefas (*backlog*) do projeto.
- Atribuir cada tarefa ao agente especialista correspondente.
- Acompanhar o status das tarefas pendentes e em andamento.
- Indicar o próximo passo do fluxo de trabalho.
- Submeter toda entrega finalizada ao **Agente Revisor** antes de marcá-la como concluída.

---

## Execução
Inicie analisando o repositório/projeto atual, monte o esquema da equipe com a definição de cada agente e apresente o plano de trabalho para execução.
