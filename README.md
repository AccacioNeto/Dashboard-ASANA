📊 **Dashboard de Gestão de Projetos - Equipe de Abastecimento (Asana)**
<img width="1636" height="1149" alt="image" src="https://github.com/user-attachments/assets/5ea36017-fa5b-4f86-9e77-feb23d95fe0e" />

🎯 **Objetivo do Projeto**
Desenvolvi esse dashboard para monitorar o fluxo de trabalho e a produtividade da Equipe de Abastecimento na empresa onde atuo, utilizando dados do Asana. O foco é identificar gargalos produtivos, gerir a capacidade da equipe e garantir o cumprimento de prazos.

🛠️ **Tecnologias Utilizadas**
Asana (Visualização e Modelagem)

Asana API / Export (Fonte de Dados)

DAX (Cálculos de produtividade e taxas de conclusão)

🧠 **Insights e Funcionalidades**
Gestão de Capacidade: Visualização do tempo estimado vs. tarefas por colaborador, permitindo uma distribuição de carga mais equilibrada.

Status de Conclusão: Gráfico de rosca centralizado para destacar o percentual de tarefas concluídas, atrasadas e próximas do prazo.

Tendência Temporal: Gráfico de linhas demonstrando o volume de demandas mês a mês, essencial para o planejamento de recursos em períodos de grande volume de tarefas.

Análise de Atrasos: Identificação visual imediata de tarefas "Não agendadas" ou "Atrasadas" para ação rápida da equipe.

🚧 **Dificuldades Encontradas e Aprendizados**
Aqui descrevo os desafios técnicos que encontrei ao utilizar as ferramentas nativas do Asana e como eles foram contornados para entregar uma análise de dados consistente:

Limitação de Personalização Visual (Cores): **Desafio:** O Asana possui um sistema de cores pré-definido por gráfico, o que dificultou a criação de uma identidade visual única (branding) para esse dashboard. Não é possível selecionar cores individuais para cada barra ou fatia de forma totalmente livre.

**Solução:** Adotei uma padronização baseada nas legendas e categorias de status, garantindo assim que, mesmo com as limitações dessa ferramenta, a leitura do usuário fosse intuitiva através da repetição de padrões visuais.

Limitação no detalhamento dos dados:: **Desafio:** Por ser uma ferramenta de gestão e não de BI pura, alguns cálculos de "tempo de ciclo" ou médias complexas exigem que os dados estejam muito bem estruturados em campos personalizados antes da criação dos gráficos.

**Solução:** Reforcei a governança no preenchimento das tarefas pela equipe, garantindo que campos como "Tempo Estimado" e "Data de Início" fossem de preenchimento obrigatório, permitindo que o gráfico de "Capacidade da Equipe" refletisse a realidade.

Escalabilidade da Visualização: **Desafio:** Ao lidar com muitas tarefas (ex: o pico de 126 tarefas em agosto), os gráficos podem se tornar poluídos.

**Solução:** Implementei filtros de visualização por "Projeto" e "Seção", permitindo que o dashboard fosse segmentado para análises mais profundas sem perder a visão macro.

📈 **Resultados obtidos**
Com este painel, a liderança consegue visualizar de forma rápida a saúde operacional da equipe, reduzindo o tempo gasto em reuniões e focando na resolução de problemas/bloqueios.
