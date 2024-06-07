# FishBook
    Camila Soares Pedra RM98246 Turma: 2TDSA
    Gustavo Bertti RM552243 Turma: 2TDSB
    Gustavo Macedo da Silva RM552333 Turma: 2TDSB
    Rafael da Silva Camargo RM551127  Turma: 2TDSA  

## Vídeo Pitch
https://www.youtube.com/watch?v=brlNuPfC4k8




## Desenvolvimento de Modelos Preditivos Usando Técnicas de Machine Learning para Prever Condições Ambientais Marítimas

### Introdução
A previsão de condições ambientais marítimas é crucial para a proteção da vida marinha e a segurança das operações marítimas. Eventos adversos como tempestades, poluição e acidentes marítimos podem ter impactos devastadores sobre o ecossistema marinho. O desenvolvimento de modelos preditivos usando técnicas de machine learning pode ajudar a antecipar esses eventos, permitindo ações preventivas eficazes.

### Etapas do Desenvolvimento

1. **Exploração de Dados:**
   - **Coleta de Dados:** Reunir dados de diferentes fontes, incluindo sensores marítimos, relatórios de incidentes, condições meteorológicas, e dados históricos de manutenção de navios.
   - **Análise Descritiva:** Explorar os dados coletados para entender suas características principais, distribuição, e identificar padrões. Isso pode incluir a visualização de dados com gráficos e estatísticas descritivas.
   - **Limpeza de Dados:** Tratar dados ausentes, remover duplicatas e corrigir valores inconsistentes. A qualidade dos dados é fundamental para o desempenho do modelo preditivo.

2. **Levantamento de Hipóteses:**
   - **Definição do Problema:** Identificar as condições ambientais específicas que queremos prever, como tempestades, níveis de poluição, ou a ocorrência de acidentes marítimos.
   - **Variáveis Relevantes:** Levantar hipóteses sobre quais variáveis (características) podem influenciar essas condições. Por exemplo, tipo de navio, carga transportada, condições meteorológicas, e histórico de manutenção podem ser variáveis relevantes.
   - **Relações Potenciais:** Explorar possíveis relações entre as variáveis e o evento de interesse. Hipóteses podem incluir: "Navios com histórico de manutenção ruim têm maior probabilidade de estar envolvidos em incidentes durante tempestades."

3. **Criação e Treinamento do Modelo:**
   - **Preparação dos Dados:** Codificar variáveis categóricas, normalizar os dados numéricos e dividir o conjunto de dados em conjuntos de treinamento e teste.
   - **Seleção do Modelo:** Escolher algoritmos de machine learning apropriados, como Regressão Logística, Árvores de Decisão, Random Forest, ou Redes Neurais.
   - **Treinamento do Modelo:** Usar o conjunto de treinamento para treinar o modelo, ajustando os parâmetros para otimizar seu desempenho.
   - **Validação Cruzada:** Utilizar técnicas de validação cruzada para avaliar a robustez do modelo e prevenir o overfitting.

4. **Validação e Avaliação:**
   - **Métricas de Desempenho:** Avaliar o modelo usando métricas como acurácia, precisão, recall, F1-score, e a matriz de confusão.
   - **Teste do Modelo:** Aplicar o modelo ao conjunto de teste para verificar seu desempenho em dados não vistos.
   - **Ajustes Finais:** Fazer ajustes finais no modelo baseado nos resultados da avaliação. Isso pode incluir ajustes de hiperparâmetros ou seleção de diferentes características.

5. **Conclusão:**
   - **Implementação:** Implementar o modelo preditivo em um ambiente de produção, onde ele pode ser usado para monitorar condições ambientais em tempo real.
   - **Ação Preventiva:** Usar as previsões do modelo para antecipar eventos prejudiciais e tomar ações preventivas, como emitir alertas de tempestade, planear rotas alternativas para navios, ou intensificar monitoramentos de poluição.
   - **Benefícios:** Destacar os benefícios do modelo, incluindo a proteção da vida marinha, aumento da segurança das operações marítimas, e melhor gestão de recursos.

### Exemplo Prático: Previsão da Qualidade do Histórico de Manutenção

Neste exemplo específico, um modelo de Regressão Logística foi desenvolvido para prever a qualidade do histórico de manutenção de navios, um fator crucial para antecipar eventos prejudiciais. As etapas incluíram:

1. **Exploração de Dados:** Coleta e análise de dados de incidentes marítimos, tipos de navios, cargas transportadas, condições meteorológicas e históricos de manutenção.
2. **Levantamento de Hipóteses:** Identificação de variáveis relevantes como tipo de navio, causa do incidente, condições meteorológicas, e tipo de carga.
3. **Criação e Treinamento do Modelo:** Treinamento de um modelo de Regressão Logística usando essas variáveis para prever se o histórico de manutenção de um navio é regular ou não.
4. **Validação e Avaliação:** Avaliação do modelo com alta acurácia (97.14%) e bons resultados nas métricas de precisão, recall e F1-score.
5. **Conclusão:** Implementação do modelo para prever a qualidade do histórico de manutenção, permitindo intervenções proativas para evitar incidentes.

### Conclusão

O desenvolvimento de modelos preditivos usando técnicas de machine learning é uma abordagem poderosa para prever condições ambientais marítimas e antecipar eventos prejudiciais. Com uma abordagem sistemática, desde a exploração de dados até a implementação e avaliação de modelos, é possível criar soluções eficazes que melhoram a segurança marítima e protegem a vida marinha.
