<img src = 'https://editor.analyticsvidhya.com/uploads/91867Screenshot%20(125).png'><br>
# Prevendo Preço das Ações da Petrobrás(PETR4) com PyCaret
--<br><br>
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) <br>
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)<br>

--

# Introdução

Este projeto apresenta um estudo inicial de como *machine learning* pode ser utilizada para realizar predições no preço de ações na bolsa de valores.<br>
A biblioteca PyCaret foi utilizada, pois é uma excelente biblioteca para aqueles que estão iniciando com *machine learning*, por oferecer uma enorme facilidade para a criação de modelos, *tuning* e comparação entre o ajuste aos dados de diversos modelos.<br>
Este projeto tem fins de estudo apenas e **não** representa indicação de compra ou venda qualquer ativo financeiro.<br>

--

# Desenvolvimento

As ações escolhidas para estudo foram as ações preferenciais da emresa Petrobrás, reigstradas na B3 pelo *ticker* PETR4.<br>
A biblioteca **Pandas** foi utilizada para a manipulação de dados dentro do *dataframe*, para remover e acrescentar dados, enquanto a biblioteca **yfinance** foi utilizada para acessar os dados das ações da Petrobrás disponíveis no site **Yahoo Finance**.<br>
Por fim, a biblioteca **PyCaret** foi utilizada para comparar, testar, realizar melhorias nos modelos, plotar gráficos relevantes e, enfim, realizar as predições dos preços dos últimos 253 pregões da PETR4. A biblioteca **Plotly** foi utilizada para plotar o gráfico final de comparação entre os preços de fechamento da PETR4 e os preços previstos pelo modelo **Bayesian Ridge**, que obteve as melhores métricas de acurácia diante de outros modelos testados pelo Pycaret.

--

# Conclusão

A biblioteca PyCaret oferece facilidade e simplicidade à criação de modelos de machine learning, sendo bastante útil para aqueles que ainda são iniciantes na área, o que é o meu caso, permitindo alcançar resultados satisfatório com poucas linhas de código.<br>
Neste estudo em específico, foi possível atingir um modelo que se ajustou muito bem aos dados analisados e que foi capaz de prever a direção dos preços de fechamento de PETR4 dos últimos 253 dias de forma bastante satisfatória.<br>
É importante lembrar, entretanto, que diversos fatores estão presentes na flutuação de preços de ações, criptomoedas, commodities e demais ativos financeiros e que nenhum modelo matemático ou estatístico será capaz de prever notícias, eventos relevantes, guerras e demais outros fatores que instiguem o **medo** ou a **ganância** dos investidores.<br>
Mais uma vez, reforço que este estudo **não é recomendação** de compra ou venda de quaisquer ativos financeiros.

---

## Author:
**Luís Fernando Torres**
