# Análise Preditiva de Churn de Clientes em uma Empresa de Telecomunicações (Dados Fictícios)

# Objetivo
Desenvolver um modelo preditivo para identificar clientes com alto risco de cancelamento (churn) em uma empresa de telecomunicações, utilizando uma base de dados fictícia. O projeto visa demonstrar a aplicação de técnicas de aprendizado de máquina em problemas de retenção de clientes.

# Métodos Utilizados
- Análise exploratória de dados (EDA) para entender os padrões de comportamento dos clientes;
- Seleção de variáveis relevantes por meio de correlação e feature importance;
- Modelagem com algoritmos de aprendizado supervisionado, como Random Forest, XGBoost e Regressão Logística;
- Validação cruzada para otimizar o desempenho do modelo;
- Métricas de avaliação como AUC-ROC, precisão, recall e F1-score para medir a eficácia do modelo.

# Tecnologias
- Python (pandas, scikit-learn, matplotlib, seaborn);
- Jupyter Notebooks para desenvolvimento e apresentação dos resultados;
- Simulação de dados utilizando a biblioteca NumPy.

# Descrição do Projeto

Neste projeto, uma base de dados fictícia com informações de clientes de uma empresa de telecomunicações foi gerada para fins de simulação de um cenário real de churn. Os dados incluem variáveis como idade, tempo de permanência, tipo de serviço contratado, e suporte técnico. Foi realizada uma análise exploratória para identificar padrões que influenciam a decisão de cancelamento dos clientes. Com isso, foram testados diferentes algoritmos de aprendizado de máquina, como Random Forest e XGBoost, para prever o churn com base nas características dos clientes. O modelo preditivo final foi capaz de atingir uma acurácia satisfatória, com uma alta capacidade de identificar clientes propensos a cancelar o serviço. O projeto demonstra como dados fictícios podem ser utilizados para replicar um problema de negócios real e aplicar técnicas de ciência de dados para fornecer soluções práticas.

# Dicionário

- customer_id: Identificação do cliente;
- age: Idade do cliente;
- tenure: Tempo como cliente (meses);
- monthly_charges: Valor mensal pago;
- total_charges: Total pago pelo cliente até o momento;
- contract_type: Tipo de contrato (mensal, anual);
- internet_service: Tipo de serviço de internet (fibra, DSL, sem internet);
- tech_support: Suporte técnico disponível (Sim/Não);
- churn: Variável alvo (0 = Não cancelou, 1 = Cancelou).
