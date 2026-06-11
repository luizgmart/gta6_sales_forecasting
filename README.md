# GTA VI: Sales Forecasting & Market Penetration Analysis

## 🎯 Objetivo do Projeto
Este projeto visa estimar o volume de vendas no primeiro ano do **Grand Theft Auto VI**. O desafio central foi superar a limitação de modelos preditivos tradicionais utilizando técnicas de **Engenharia de Recursos (Feature Engineering)** focadas em taxa de penetração de mercado.

## 🧠 Abordagem Técnica
Utilizamos uma abordagem baseada em aprendizado de máquina para entender como fatores como "Hype", "Base de Consoles" e "Engajamento Social" convertem-se em vendas.

* **Modelo:** `XGBoost Regressor`
* **Target:** Taxa de Penetração = (Vendas Ano 1 / Base de Consoles Ativos)
* **Diferencial:** O modelo aprende a converter a base de usuários disponível, tornando a projeção escalável e aderente aos cenários macroeconômicos.

## 📊 Principais Resultados
* **Acurácia (R²):** $0.68$ (Alta capacidade explicativa).
* **Erro Médio Absoluto (MAE):** $5.31\%$ na taxa de penetração.
* **Previsão GTA VI:** O modelo estima aproximadamente **36.97 milhões de cópias** no primeiro ano de lançamento. O resultado ficou bastante alinhado às estimativas atuais de analistas do setor, que variam entre 40 e 45 milhões de unidades.

<img width="686" height="453" alt="Captura de tela 2026-06-11 090224" src="https://github.com/user-attachments/assets/406b2987-c309-4111-ac61-c34e20a7f4a6" />
 

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Bibliotecas:** `Pandas`, `NumPy`, `Scikit-Learn`, `XGBoost`

## 🚀 Como Executar
1. Clone o repositório:
   ```bash
   git clone [https://github.com/luizgmart/gta6-sales-forecasting.git](https://github.com/luizgmart/gta6-sales-forecasting.git)
Instale as dependências:

Bash
pip install -r requirements.txt
Execute o notebook gta6_sales_forecasting.ipynb.
