# Miniguia-de-Estudos-da-Reforma-Tributaria

## 1. Contexto e Objetivos
O assunto de interesse escolhido foi desenvolvido no NotebookLM para consolidar o entendimento sobre a transição para o novo modelo tributário brasileiro. 
O objetivo principal é mapear as mudanças técnicas em documentos fiscais e a correlação entre os novos códigos de tributação e as operações vigentes, servindo como material de consulta para profissionais de tecnologia e fiscal.

## 2. Curadoria de Fontes
Para alimentar a inteligência do NotebookLM, selecionei fontes técnicas e oficiais:
*   **Lei Complementar 214/2025:** Normas gerais sobre o novo regime.
*   **Lei Complementar 224/2025:** Detalhamento de alíquotas e benefícios.
*   **Nota Técnica ENCAT 2025.002-RTC:** Especificações de leiaute para documentos fiscais eletrônicos.
*   **Ajuste SINIEF 49/2025:** Disposições sobre obrigações acessórias.
*   **Materiais Técnicos da BSSP/Thomson Reuters:** Análises sobre a correlação CFOP vs. cClassTrib.

## 3. Engenharia de Prompts e "Cicatrizes"
Nesta seção, documento como refinei as perguntas para obter respostas técnicas precisas:

*   **Prompt 1 (Exploratório):** Quais as principais mudanças da Reforma?" 
    *   *Resultado:* Muito genérico.
.. 
*   **Prompt 2 (Específico):** "Com base na NT 2025.002-RTC, liste as alterações obrigatórias no XML da NF-e para o campo cClassTrib."
    *   *Cicatriz/Troubleshooting:* A IA inicialmente confundiu prazos de homologação. Precisei instruí-la a focar estritamente no cronograma da página X da nota técnica.

## 4. Miniguia de Estudo (Entrega Final)

### Resumo Estruturado
A reforma introduz o IBS e a CBS, exigindo uma reestruturação profunda nos sistemas de ERP. O foco da transição está na correta classificação de mercadorias e serviços através do novo código de classe tributária.

### Glossário de Conceitos Chave
*   **IBS:** Imposto sobre Bens e Serviços (competência estadual/municipal).
*   **CBS:** Contribuição sobre Bens e Serviços (competência federal).
*   **cClassTrib:** Código de Classificação Tributária para o novo regime.
*   **ENCAT:** Encontro Nacional de Coordenadores e Administradores Tributários Estaduais.

### Prompts Reutilizáveis para Revisão
1. "Compare o tratamento tributário do item [X] no regime atual vs. o regime da LC 214/2025."
2. "Gere um checklist de campos de XML que precisam ser alterados para o projeto de automação fiscal."
