# 📊 Segmentação de Clientes RFM: Olist E-commerce

## 🚀 Visão Geral do Projeto

Este projeto utiliza a base de dados pública de vendas da Olist (2016-2018) para aplicar a metodologia RFM (Recência, Frequência, Valor Monetário) e segmentar os clientes. O objetivo é transformar dados transacionais em insights acionáveis, permitindo estratégias de marketing personalizadas para cada grupo de clientes.

### Tecnologias Utilizadas
* **Linguagem:** Python
* **Ambiente:** Google Colab / Jupyter Notebook
* **Bibliotecas Chave:** Pandas, NumPy, Scikit-learn (K-Means), Matplotlib, Seaborn.

---

## 💡 Metodologia (RFM e K-Means)

1.  **Limpeza e Feature Engineering:** Consolidação de 4 datasets (Pedidos, Clientes, Pagamentos e Itens) em uma única base de transações válidas.
2.  **Cálculo RFM:** Determinação da Recência, Frequência e Valor Monetário para cada `customer_unique_id`.
3.  **Pré-processamento:** Aplicação da **Transformação Logarítmica** e **Standard Scaling** para garantir que o algoritmo K-Means seja executado em uma base padronizada e otimizada.
4.  **Modelagem K-Means:** Utilização do Método do Cotovelo para determinar o K ótimo ($K=4$).
5.  **Análise de Cluster:** Interpretação dos perfis de clusters e geração de recomendações de negócio.

---

## 📈 Resultados Chave e Recomendações de Negócio

O modelo identificou 4 segmentos distintos, conforme detalhado abaixo:

| Cluster | Nome do Segmento | Foco Estratégico | Ação Sugerida |
| :---: | :--- | :--- | :--- |
| **2** | **Campeões** | **Retenção e Crescimento de AOV** | Programa de Lealdade VIP e Upselling. |
| **3** | **Novos Clientes** | **Conversão da 2ª Compra** | E-mail de *Onboarding* com incentivo de curto prazo. |
| **1** | **Alto Valor em Risco** | **Reativação Urgente** | Campanha de reengajamento personalizada e pesquisa de satisfação. |
| **0** | **Adormecidos** | **Otimização de Custos** | Ações automatizadas e de baixo custo. |

*Para uma análise completa, incluindo gráficos e código, consulte o Notebook [Nome_Do_Seu_Arquivo.ipynb].*

---

Após editar e salvar o `README.md`, seu portfólio estará pronto! O arquivo `.ipynb` mostrará todo o seu código e resultados, enquanto o `README` servirá como um resumo executivo para quem está visualizando.

O que achou desta estrutura de portfólio? Podemos fazer a verificação final na sua página do GitHub.
