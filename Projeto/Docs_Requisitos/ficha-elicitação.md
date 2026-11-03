# Ficha de Elicitação de Requisitos

**Curso:** Engenharia de Software
**Disciplina:** Análise e Projeto de Sistemas
**Instituição:** UDF Centro Universitário
**Grupo/integrantes:** João Gabriel | João Victor | Lucca Cavalcante | Luan Borges
**Turma:** Engenharia de Software - D2 
**Data:** 24/09/2026
**Versão:** 1.0

## 1. Identificação do projeto

| Campo | Preenchimento |
|---|---|
| Nome do projeto | Facul Resolve |
| Objetivo do projeto | Centralizar o registro, o acompanhamento e a resolução de problemas da faculdade, para que estudantes e professores relatem ocorrências e recebam retorno dos setores responsáveis. |
| Contexto e escopo | Processo de suporte da UDF: registro de ocorrências (estrutura, equipamentos, internet, sistemas acadêmicos), encaminhamento ao setor responsável, acompanhamento do status e comunicados da instituição. |

## 2. Stakeholder e fonte

| Campo | Preenchimento |
|---|---|
| Stakeholder (nome ou papel) | Estudante |
| Relação com o projeto | Usuário |
| Contato ou setor (se aplicável) | Estudantes da UDF |
| Técnica e data da elicitação | Observação do problema e sugestão da professora|
| Responsável pelo registro | Todos os participantes do projeto |

## 3. Requisito elicitado

| Campo | Preenchimento |
|---|---|
| ID do requisito | REQ-001 |
| Necessidade relatada pelo stakeholder | "Quero avisar a faculdade quando algo está quebrado, sem precisar descobrir com quem falar." |
| Descrição consolidada | O sistema deve permitir que estudantes e professores autenticados abram uma ocorrência informando categoria, local, descrição e, opcionalmente, uma foto. |
| Justificativa ou benefício esperado | Dar um ponto único de registro, evitando que relatos se percam em canais informais e permitindo o encaminhamento ao setor responsável. |
| Tipo | Funcional (RF02 no levantamento MoSCoW) |
| Dependências ou dúvidas | Depende de autenticação e perfis (RF01) e do encaminhamento ao setor (RF03). Dúvida: limite de tamanho e quantidade de fotos por ocorrência. |

## 4. Regras de negócio

| ID | Regra de negócio relacionada | Fonte ou responsável pela validação |
|---|---|---|
| RN-001 | Somente pessoas vinculadas à UDF (estudantes matriculados, professores e funcionários ativos) podem abrir ocorrências. | Regra institucional (a validar com a UDF) |
| RN-002 | Toda ocorrência deve ter categoria e local e ser direcionada a um setor responsável. | Definição do grupo / fluxo de suporte |

## 5. Prioridade

**Classificação MoSCoW (marque uma):** [x] Must have (essencial)  [ ] Should have (importante)  [ ] Could have (desejável)  [ ] Won't have nesta versão (fora do escopo atual)

**Justificativa da prioridade:** É a função central do sistema: sem o registro da ocorrência não existe fluxo de atendimento.

## 6. Critérios de aceitação

| ID | Dado/Quando | Então (resultado esperado) | Evidência ou forma de verificação |
|---|---|---|---|
| CA-01 | Dado um usuário autenticado, quando ele preencher categoria, local e descrição e confirmar o envio | O sistema registra a ocorrência com status "Aberta" e exibe um número de protocolo | Teste funcional e conferência no histórico do usuário |
| CA-02 | Dado um usuário que deixou categoria, local ou descrição em branco, quando tentar enviar | O sistema impede o registro e indica quais campos estão faltando | Teste de validação do formulário |
| CA-03 | Dada uma ocorrência registrada, quando o registro for concluído | O sistema a encaminha ao setor responsável pela categoria escolhida | Teste funcional com conferência na fila do setor |

## 7. Validação e rastreabilidade

| Campo | Preenchimento |
|---|---|
| Situação | [x] Pendente de validação  [ ] Validado  [ ] Necessita revisão |
| Validado por / data | |
| Observações e decisões | |
| Links relacionados | Necessidade N01; requisitos RF02, RQ03 e RN-002 do levantamento MoSCoW; caso de uso "Abrir ocorrência" (a criar) |
