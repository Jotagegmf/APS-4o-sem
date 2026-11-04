# 📋 Projeto de APS Facul Resolve

## Levantamento e Priorização de Requisitos

**Etapa:** Levantamento de Requisitos 
**Técnica de Priorização:** MoSCoW
**Data:** 03/09/2026
**Turma:** Engenharia de Software - UDF 

---

# 👥 1. Identificação do Grupo

| Integrante | Nome |
|---|---|
| 1 |[João Gabriel](https://github.com/Jotagegmf) |
| 2 |[João Victor](https://github.com/joaovictorcode7)|
| 3 |Luan Borges |
| 4 |[Lucca Cavalcante](https://github.com/Lucca143)|

---

# 2. Identificação do Projeto

**Nome do projeto:**
> Facul Resolve

**Descrição resumida do projeto:**
> O Facul Resolve é um sistema de suporte e comunicação voltado à comunidade acadêmica. Estudantes e professores registram problemas da faculdade (estrutura, equipamentos, internet, sistemas acadêmicos etc.), acompanham o andamento da resolução e recebem comunicados e alertas da instituição. Os setores responsáveis recebem, tratam e atualizam as ocorrências em um único lugar.

---

# 3. Problema Identificado

## 3.1 Qual problema será resolvido?
> Não existe um canal único e organizado para relatar problemas da faculdade e receber retorno. Os relatos se perdem, não têm responsável definido e não são acompanhados, o que atrasa a resolução e gera retrabalho.

## 3.2 Quem é afetado pelo problema?
> Estudantes e professores, que convivem com os problemas e não sabem a quem recorrer; os setores responsáveis (TI, infraestrutura, secretaria, coordenação), que recebem demandas dispersas; e a administração, que não tem visão dos problemas recorrentes.

## 3.3 Como o problema é resolvido atualmente?
> De maneira informal: o usuário avisa um professor, um funcionário ou a coordenação pessoalmente, por mensagem, e-mail ou grupos de aplicativo. Não há registro padronizado, protocolo nem acompanhamento do andamento.

## 3.4 Principais dificuldades encontradas
1. O usuário não sabe a quem ou onde reportar cada tipo de problema.
2. Não há retorno: quem relata não sabe se o problema foi recebido, quem está cuidando dele nem quando será resolvido.
3. Os relatos se perdem entre vários canais informais, o que gera duplicidade e falta de priorização.
4. A faculdade não consegue identificar problemas recorrentes nem medir o tempo de resolução.

---

# 🎯 4. Objetivo do Projeto

**Objetivo:**
> Nosso projeto pretende centralizar o registro, o acompanhamento e a resolução de problemas da faculdade para estudantes, professores e setores responsáveis, contribuindo para uma comunicação mais rápida, transparente e organizada.

---

# 👤 5. Stakeholders

| ID | Stakeholder | Papel | Necessidade/Interesse | Influência |
|---|---|---|---|---|
| ST01 | Estudantes | Usuário que relata e acompanha ocorrências | Relatar problemas de forma simples e saber o andamento | Alta |
| ST02 | Professores | Usuário que relata e acompanha ocorrências | Resolver problemas que afetam as aulas (projetor, internet, sala) | Média |
| ST03 | Setores responsáveis (TI, infraestrutura, secretaria) | Tratam e resolvem as ocorrências | Receber demandas organizadas, priorizar e registrar a solução | Alta |
| ST04 | Coordenação de curso | Acompanha e encaminha demandas acadêmicas | Visibilidade dos problemas que afetam o curso | Média |
| ST05 | Direção/Administração da UDF | Decide sobre adoção e recursos | Indicadores, transparência e melhoria dos serviços | Alta |

## Stakeholder principal

**Stakeholder:**
> Estudantes (ST01)

**Por que ele foi considerado o principal stakeholder?**
> Os estudantes são o grupo mais numeroso, convivem diariamente com os problemas e serão quem mais abrirá ocorrências. Se o sistema não for simples para eles, o volume e a qualidade dos relatos caem e o sistema perde seu propósito. Os setores responsáveis são essenciais para a resolução, mas dependem dos relatos dos estudantes para ter o que tratar.

---

# 🗣️ 6. Levantamento de Informações

| Pergunta | Resposta |
|---|---|
| O que o usuário precisa fazer? | Relatar um problema, acompanhar o andamento e ler comunicados da faculdade. |
| Qual problema enfrenta atualmente? | Não sabe a quem recorrer e nunca recebe retorno sobre o que relatou. |
| Quais informações precisa consultar? | Status e histórico das próprias ocorrências, comunicados e alertas de manutenção. |
| Quais informações precisa cadastrar ou alterar? | Categoria, local, descrição e foto da ocorrência; o setor altera o status e registra a solução. |
| Quais tarefas são repetitivas? | Repassar o mesmo problema por vários canais; o setor triar manualmente relatos que chegam de formas diferentes. |
| Quais tarefas consomem mais tempo? | Descobrir quem é o responsável e cobrar retorno; o setor reunir informações que faltam no relato. |
| Quais erros acontecem atualmente? | Relatos perdidos, duplicados, sem local ou sem descrição suficiente, e encaminhados ao setor errado. |
| Precisa receber notificações? | Sim: mudanças de status da ocorrência e comunicados da instituição. |
| Precisa gerar documentos ou relatórios? | Sim: relatórios de problemas mais frequentes, locais mais afetados e tempo médio de resolução. |
| Existem informações que precisam ser protegidas? | Sim: dados pessoais dos usuários e o histórico das ocorrências, com acesso conforme o perfil. |
| O sistema precisará se comunicar com outros sistemas? | Não na primeira versão; no futuro, possível integração com o login/sistema acadêmico da UDF. |
| Existem regras obrigatórias que precisam ser respeitadas? | Sim: proteção de dados pessoais (LGPD) e regras institucionais sobre quem pode abrir e tratar ocorrências. |

---

# 💡 7. Necessidades Identificadas

| ID | Stakeholder | Necessidade Identificada | Problema Relacionado |
|---|---|---|---|
| N01 | Estudantes e professores | Registrar um problema de forma simples, informando local e descrição | Relatos informais se perdem e faltam informações |
| N02 | Estudantes e professores | Acompanhar o andamento do que foi relatado | Não há retorno sobre o relato |
| N03 | Setores responsáveis | Receber as ocorrências já direcionadas ao setor correto | Demandas chegam dispersas e ao setor errado |
| N04 | Setores responsáveis | Atualizar o status e registrar a solução aplicada | Falta de controle e histórico do atendimento |
| N05 | Comunidade acadêmica | Ser avisada sobre manutenções, interrupções e resoluções | Falta de comunicação oficial sobre problemas |
| N06 | Estudantes, professores e setores | Trocar informações dentro da própria ocorrência | Falta de contexto e idas e vindas por canais informais |
| N07 | Coordenação e Administração | Ter indicadores dos problemas e do tempo de resolução | Impossível identificar problemas recorrentes |
| N08 | Instituição | Garantir que só usuários autorizados acessem e alterem dados | Risco de uso indevido e exposição de dados |

---

# ⚙️ 8. Requisitos Funcionais

| ID | Requisito Funcional | Stakeholder/Fonte | Necessidade | Prioridade |
|---|---|---|---|---|
| RF01 | O sistema deve permitir que usuários se autentiquem e acessem funcionalidades de acordo com seu perfil (estudante, professor, setor, administrador). | Instituição / Setores | N08 | Must |
| RF02 | O sistema deve permitir que estudantes e professores abram uma ocorrência informando categoria, local, descrição e, opcionalmente, foto. | Estudantes e professores | N01 | Must |
| RF03 | O sistema deve encaminhar automaticamente cada ocorrência ao setor responsável, de acordo com a categoria informada. | Setores responsáveis | N03 | Must |
| RF04 | O sistema deve permitir que o usuário consulte o status e o histórico das ocorrências que abriu. | Estudantes e professores | N02 | Must |
| RF05 | O sistema deve permitir que o setor responsável atualize o status da ocorrência e registre a solução aplicada. | Setores responsáveis | N04 | Must |
| RF06 | O sistema deve notificar o usuário sempre que o status de sua ocorrência for alterado. | Estudantes e professores | N02 | Should |
| RF07 | O sistema deve permitir que setores e administração publiquem comunicados e alertas em um mural visível à comunidade acadêmica. | Comunidade / Administração | N05 | Should |
| RF08 | O sistema deve gerar relatórios de ocorrências por categoria, local e tempo médio de resolução. | Coordenação e Administração | N07 | Could |
| RF09 | O sistema deve permitir a troca de mensagens entre o usuário e o setor responsável dentro da ocorrência. | Estudantes, professores e setores | N06 | Won't |

---

# ⭐ 9. Requisitos de Qualidade

| ID | Característica de Qualidade | Requisito | Como será verificado? |
|---|---|---|---|
| RQ01 | Desempenho | O sistema deve exibir a lista de ocorrências e concluir o registro de uma nova ocorrência em até 3 segundos para 95% das requisições, com até 200 usuários simultâneos. | Teste de carga e medição do tempo de resposta. |
| RQ02 | Segurança | O sistema deve exigir autenticação, armazenar senhas criptografadas e restringir cada funcionalidade ao perfil autorizado, respeitando a LGPD. | Testes de acesso por perfil e revisão do armazenamento de dados. |
| RQ03 | Usabilidade/Interação | Um usuário novo, sem treinamento, deve conseguir abrir uma ocorrência em até 5 passos e 3 minutos. | Teste de usabilidade com ao menos 5 usuários; meta de 90% de sucesso. |
| RQ04 | Confiabilidade | O sistema deve ter disponibilidade mensal mínima de 99% e backup diário das ocorrências. | Monitoramento de disponibilidade e teste de restauração do backup. |
| RQ05 | Compatibilidade/Portabilidade | O sistema deve funcionar nas duas últimas versões do Chrome, Edge, Firefox e Safari e em telas a partir de 360 px de largura. | Testes em diferentes navegadores e dispositivos. |

---

# 🚧 10. Restrições

| ID | Restrição | Categoria | Justificativa/Fonte |
|---|---|---|---|
| RES01 | O projeto deve ser concluído e entregue dentro do prazo do semestre letivo. | Prazo | Calendário da disciplina. |
| RES02 | O desenvolvimento conta apenas com os 6 integrantes do grupo, sem orçamento para ferramentas pagas. | Recursos/Orçamento | Natureza acadêmica do projeto. |
| RES03 | O sistema deve tratar dados pessoais conforme a LGPD. | Legislação | Lei nº 13.709/2018. |
| RES04 | A adoção real do sistema depende de análise e aprovação da UDF (setores, infraestrutura e processos). | Processo/Infraestrutura | Projeto em fase de proposta acadêmica. |

---

# 📜 11. Regras de Negócio

| ID | Regra de Negócio | Fonte |
|---|---|---|
| RN01 | Somente pessoas vinculadas à UDF (estudantes matriculados, professores e funcionários ativos) podem abrir ocorrências. | Regra institucional (a validar com a UDF) |
| RN02 | Toda ocorrência deve ter categoria e local, e ser direcionada a um setor responsável. | Definição do grupo / fluxo de suporte |
| RN03 | Somente setores autorizados e a administração podem alterar o status de uma ocorrência e publicar comunicados. | Definição do grupo (a validar com a UDF) |
| RN04 | Uma ocorrência só pode ser marcada como resolvida com o registro da solução aplicada. | Definição do grupo / fluxo de suporte |

---

# 🔗 12. Rastreabilidade Inicial

| Necessidade | Stakeholder | Requisito(s) relacionado(s) |
|---|---|---|
| N01 | Estudantes e professores | RF02, RQ03, RN02 |
| N02 | Estudantes e professores | RF04, RF06 |
| N03 | Setores responsáveis | RF03, RN02 |
| N04 | Setores responsáveis | RF05, RN04 |
| N05 | Comunidade acadêmica | RF07, RN03 |
| N06 | Estudantes, professores e setores | RF09 |
| N07 | Coordenação e Administração | RF08 |
| N08 | Instituição | RF01, RQ02, RN01, RN03 |

---

# 🏷️ 13. Priorização dos Requisitos — Técnica MoSCoW

## Matriz de Priorização

| ID | Requisito | MoSCoW | Justificativa |
|---|---|:---:|---|
| RF01 | Autenticação e perfis de acesso | M | Sem identificar o usuário e seu perfil, não há como controlar quem abre ou trata ocorrências. |
| RF02 | Abrir ocorrência | M | É a função central: sem registro não existe o sistema. |
| RF03 | Encaminhar ao setor responsável | M | Garante que o relato chegue a quem pode resolver; é o que diferencia o sistema de um canal informal. |
| RF04 | Consultar status e histórico | M | Resolve a principal dor: a falta de retorno ao usuário. |
| RF05 | Setor atualizar status e registrar solução | M | Sem isso o ciclo da ocorrência não se fecha. |
| RF06 | Notificar mudança de status | S | Muito útil, mas na primeira versão o usuário já acompanha o status pelo RF04. |
| RF07 | Mural de comunicados e alertas | S | Atende a comunicação da faculdade, mas não impede o funcionamento do fluxo principal. |
| RF08 | Relatórios | C | Agrega valor à gestão, mas só faz sentido com volume de ocorrências acumulado. |
| RF09 | Mensagens dentro da ocorrência | W | Exige moderação e maior complexidade; a descrição e a solução já registram o essencial. |
| RQ01 | Desempenho | C | Desejável, mas com baixo volume inicial não compromete a primeira versão. |
| RQ02 | Segurança | S | A segurança básica entra na primeira versão via RF01 (login e senhas protegidas); a conformidade completa com a LGPD é aprofundada em seguida. |
| RQ03 | Usabilidade | S | Importante para a adoção pelos estudantes, mas pode ser refinada após os primeiros testes. |
| RQ04 | Confiabilidade | C | Metas de disponibilidade e backup ganham relevância quando o sistema entrar em uso real. |
| RQ05 | Compatibilidade/Portabilidade | S | Muitos usuários acessam pelo celular, mas a primeira versão pode priorizar um navegador. |

---

# 🚀 14. Requisitos da Primeira Versão

| Ordem | ID | Requisito | Por que deve estar na primeira versão? |
|:---:|---|---|---|
| 1 | RF01 | Autenticação e perfis de acesso | Base para todas as demais funções e para o controle de acesso. |
| 2 | RF02 | Abrir ocorrência | Função central do sistema. |
| 3 | RF03 | Encaminhar ao setor responsável | Garante que o relato chegue a quem pode resolver. |
| 4 | RF04 | Consultar status e histórico | Resolve a falta de retorno ao usuário. |
| 5 | RF05 | Setor atualizar status e registrar solução | Fecha o ciclo de atendimento da ocorrência. |

---

# ⏭️ 15. Requisitos para Versões Futuras

| ID | Requisito | Motivo para adiar | Impacto |
|---|---|---|---|
| RF06 | Notificar mudança de status | O acompanhamento já é possível pela consulta (RF04). | Baixo: o usuário precisa entrar no sistema para ver as atualizações. |
| RF08 | Relatórios | Depende de volume de dados acumulado. | Baixo: a gestão não terá indicadores nas primeiras semanas. |
| RF09 | Mensagens dentro da ocorrência | Complexidade e necessidade de moderação. | Médio: esclarecimentos continuarão por canais externos. |

---

# 🔍 16. Revisão por Pares

**Grupo responsável pela revisão:** __________________________

| ID do Requisito | Problema Encontrado | Sugestão de Melhoria |
|---|---|---|
| | | |
| | | |
| | | |
| | | |

---

# ✅ 17. Checklist de Qualidade dos Requisitos

- [ ] Os requisitos estão completos?
- [ ] Os requisitos estão corretos em relação às necessidades?
- [ ] Cada requisito representa uma única capacidade ou característica?
- [ ] Os requisitos são necessários?
- [ ] Os requisitos são viáveis?
- [ ] Todos possuem prioridade?
- [ ] Termos ambíguos foram eliminados?
- [ ] Os requisitos podem ser verificados ou testados?
- [ ] A fonte ou stakeholder está identificado?
- [ ] As necessidades estão relacionadas aos requisitos?
- [ ] Os requisitos de qualidade são mensuráveis sempre que possível?
- [ ] As prioridades MoSCoW possuem justificativa?

---

# 💭 18. Reflexão do Grupo

## 18.1 Qual requisito gerou mais discussão durante o levantamento? Por quê?
> O RF09 (mensagens dentro da ocorrência). Havia a ideia de um chat ou fórum entre usuários, mas isso traria necessidade de moderação e aumentaria muito o escopo, então decidimos limitá-lo e adiá-lo.

## 18.2 Qual necessidade inicialmente parecia simples, mas gerou vários requisitos?
> A necessidade de "relatar problemas" (N01). Ela envolve autenticação, categorias, encaminhamento ao setor certo, regras sobre quem pode relatar e requisitos de usabilidade para que o registro seja rápido.

## 18.3 O grupo identificou algum requisito implícito durante a discussão?
> Sim: a autenticação e os perfis de acesso (RF01). Ninguém citou no começo, mas sem ela não é possível saber quem relata nem quem pode alterar o status.

## 18.4 Qual requisito foi mais difícil de priorizar utilizando MoSCoW? Por quê?
> O RQ02 (segurança). Ele é importante e envolve a LGPD, mas na primeira versão a proteção básica já vem com o login (RF01). Foi difícil decidir se ele era Must ou Should.

## 18.5 Houve algum requisito inicialmente considerado Must que mudou de prioridade?
> Sim, as notificações (RF06). Inicialmente parecia indispensável, mas como o usuário já acompanha o status pela consulta (RF04), passou a Should.

---

# 📝 19. Conclusão

**Conclusão:**
> O projeto investigou a ausência de um canal organizado para relatar problemas da faculdade e receber retorno sobre eles. Os principais stakeholders identificados foram estudantes, professores, setores responsáveis, coordenação e administração, sendo os estudantes o principal. As necessidades mais relevantes foram registrar problemas de forma simples, encaminhá-los ao setor correto, acompanhar o andamento e fechar o ciclo com o registro da solução. A técnica MoSCoW ajudou o grupo a separar o que é indispensável (autenticação, abertura, encaminhamento, acompanhamento e atualização das ocorrências) do que pode esperar (notificações, relatórios e mensagens), definindo uma primeira versão enxuta e viável.

---

**Disciplina:** Engenharia de Requisitos
**Projeto:** Facul Resolve
**Profª Kadidja Valéria**
**Repositório:** link
