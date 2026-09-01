# 📊 Análise de Performance e SLA — Suporte de TI
## 📌 Visão Geral

Este projeto apresenta uma análise de Business Analytics aplicada à operação de Suporte de TI, com foco na avaliação da demanda, eficiência do atendimento, cumprimento de SLA e volume de chamados em aberto.

A análise foi desenvolvida para transformar dados históricos de atendimento em informações que apoiem decisões relacionadas a capacidade operacional, qualidade do serviço, priorização de melhorias e planejamento de recursos.

A principal questão de negócio foi:

**A operação de suporte está conseguindo acompanhar o crescimento da demanda e manter o nível de serviço esperado?**

## 🎯 Contexto do Negócio

A área de Suporte de TI apresentou crescimento no volume de chamados ao longo dos anos, aumentando a pressão sobre a capacidade de atendimento.

Nesse contexto, a gestão precisava compreender:

  - Como a demanda de chamados evoluiu?
  - A equipe está conseguindo atender os chamados dentro do SLA?
  - Qual é o volume de chamados que permanece em aberto?
  - Quais são os principais motivos de contato?
  - Existem sinais de aumento da pressão operacional?
  - Quais ações podem melhorar a eficiência do atendimento?

A análise também buscou gerar informações que pudessem apoiar o planejamento orçamentário e de recursos para os períodos seguintes.

## 🔎 Perguntas de Negócio

A análise foi estruturada em quatro dimensões principais.

1. **Demanda**  
  - Como o volume de chamados evoluiu ao longo dos anos?  
  - Quais períodos apresentam maior demanda?  
  - O crescimento da demanda pode indicar necessidade de aumento de capacidade?  
2. **SLA e Qualidade do Atendimento**  
  - Qual percentual dos chamados está dentro do SLA?  
  - Quantos chamados extrapolam o prazo acordado?  
  - Existe relação entre aumento da demanda e deterioração do SLA?  
3. **Backlog**  
  - Qual é o percentual de chamados que permanece em aberto?  
  - O backlog está aumentando?  
  - Quais fatores podem estar contribuindo para o acúmulo de chamados?  
4. **Motivos dos Chamados**  
  - Quais são os principais motivos de abertura de chamados?  
  - Existem categorias recorrentes que poderiam ser reduzidas?  
  - Quais oportunidades existem para atuação preventiva?  

## 📈 KPIs Analisados

Os principais indicadores utilizados foram:

✔️ Volume de Chamados
✔️ Chamados em Aberto
✔️ % de Chamados em Aberto
✔️ % de SLA Cumprido
✔️ Chamados Fora do SLA
✔️ Chamados por Motivo
✔️ Evolução da Demanda ao Longo do Tempo
✔️ Distribuição dos Chamados por Categoria

## 💡 Principais Insights
**📈 Crescimento da Demanda**

Foi identificado crescimento significativo no volume de atendimentos ao longo dos anos.

Em 2018, foram registrados aproximadamente 6,9 mil chamados, representando o maior volume observado no período analisado.

Esse crescimento indica aumento da demanda sobre a operação e exige acompanhamento da capacidade disponível.

**⏱️ Cumprimento de SLA**

Em 2020, aproximadamente 75% dos chamados estavam dentro do SLA, enquanto 13,5% permaneciam em aberto.

Esse resultado demonstra que, apesar de a maior parte dos chamados estar sendo atendida dentro do prazo acordado, existe uma parcela relevante que exige atenção da gestão.

**🚨 Backlog e Pressão Operacional**

O aumento do volume de chamados, combinado com chamados em aberto e casos de SLA extrapolado, indica possível pressão crescente sobre a capacidade operacional da equipe.

Esse cenário reforça a necessidade de acompanhar não apenas o volume de chamados, mas também a relação entre demanda, capacidade e nível de serviço.

**🏷️ Principais Motivos**

Entre os principais motivos identificados estão:

  - Outros
  - Outros problemas
  - Permissão de acesso
  - Dúvidas

A elevada concentração em categorias genéricas, como “Outros”, reduz a capacidade de identificar as causas reais da demanda.

Esse é um ponto importante de qualidade e governança dos dados, além de representar uma oportunidade de melhoria no processo de classificação dos chamados.**

## 🧠 Análise de Negócio

Os resultados indicam que o desafio da operação não está apenas relacionado ao volume de chamados, mas à capacidade de transformar o crescimento da demanda em decisões sobre recursos, processos e prevenção.

O crescimento do número de chamados pode exigir aumento de capacidade, mas antes de recomendar simplesmente mais recursos, é necessário compreender:

✔️ O que está gerando a demanda?

✔️ Quais chamados poderiam ser evitados?

✔️ Quais atividades consomem mais capacidade da equipe?

✔️ Quais categorias apresentam maior recorrência?

Essa abordagem permite diferenciar uma decisão baseada apenas em volume de uma decisão baseada em causas, capacidade e impacto operacional.

## 🚀 Recomendações de Negócio
**👥 Planejamento de Capacidade**

Avaliar a relação entre crescimento da demanda, volume de chamados em aberto e cumprimento de SLA para dimensionar adequadamente os recursos da operação.

**🎓 Treinamentos Preventivos**

Os chamados relacionados a dúvidas podem indicar oportunidades para treinamentos, materiais de apoio e ações de autosserviço.

**🔐 Revisão de Permissões**

A recorrência de chamados relacionados a permissões de acesso sugere avaliar o processo de concessão, alteração e revisão de acessos.

**🏷️ Melhoria da Classificação**

Revisar categorias genéricas como “Outros” e “Outros problemas”, criando uma estrutura de classificação mais detalhada.

Uma categorização mais precisa permitiria identificar causas recorrentes e direcionar ações de melhoria com maior precisão.

**📊 Monitoramento de SLA**

Acompanhar continuamente:

Demanda → Backlog → SLA → Causas

Essa visão integrada permite identificar antecipadamente sinais de deterioração da performance.

## 🔄 Próximos Passos Analíticos

Para aprofundar o diagnóstico, seria interessante incorporar indicadores adicionais, como:

  - Tempo médio de atendimento
  - Tempo médio de resolução
  - SLA por categoria
  - SLA por prioridade
  - Backlog por idade
  - Volume de chamados por equipe
  - Reincidência de chamados
  - Taxa de resolução no primeiro contato
  - Custo médio por chamado

Essas informações permitiriam avançar de uma análise predominantemente descritiva para uma análise diagnóstica e preditiva, identificando não apenas o que está acontecendo, mas também por que acontece e onde atuar.

## 🛠️ Solução Analítica
Tratamento e Preparação | Power Query | ETL | Limpeza e transformação dos dados | Modelagem e Métricas | Power BI | Modelagem de dadosDAX | Criação de KPIs | Análise de SLA | Análise de backlog | Visualização | Dashboard interativo | Data Storytelling | Análise temporal | Visualizações orientadas às perguntas de negócio

## 📊 Dashboard

Link do projeto: https://app.powerbi.com/view?r=eyJrIjoiMjEyYWYzYTEtYmVkYi00ZjE1LWE4NDEtNGE1NTJhNjc0YTFjIiwidCI6IjY1OWNlMmI4LTA3MTQtNDE5OC04YzM4LWRjOWI2MGFhYmI1NyJ9

## 🔄 Abordagem Analítica

O projeto seguiu uma abordagem orientada à tomada de decisão:

**Problema de Negócio → Perguntas de Negócio → KPIs → Análise → Insights → Causas/Hipóteses → Recomendações**

O objetivo não foi apenas visualizar os chamados, mas avaliar a performance da operação, identificar riscos relacionados ao SLA e backlog e transformar os dados em oportunidades de melhoria operacional.

<img width="930" height="522" alt="image" src="https://github.com/user-attachments/assets/70dd4237-a38f-44be-927d-211e75abc73d" />

