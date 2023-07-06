<body><b>
  <a href="https://github.com/DurinPavel/classification_text_messages/blob/main/README_EN.md" target="_blank">
    <p>English version</p></a>
    <p align="justify">
      Цель данного проекта состоит в реализации и оценке базовой модели логистической регрессии для классификации
      текстовых сообщений по признаку спама на основе имеющегося <a href="https://github.com/DurinPavel/classification_text_messages/blob/main/spam.csv" target="_blank">
      набора данных</a>.
    </p>
    <p align="justify">
      Результатом является датафрейм, который содержит все исходные тексты сообщений,  
      классифицированные неправильно (с указанием фактического и предсказанного).
    </p>
    <p align="justify">
      В работе применялись возможности таких библиотек языка <i>Python</i>, как :  <i>Pandas, Scikit-learn,  
      Matplotlib, Natural Language Toolkit, Regular expression operations</i>.
    </p>
    <p align="justify">
      В проекте продемонстрировано умение осуществлять предварительную подготовку текста при помощи методов изменения 
      размера символов, использования регулярных выражений, токенизации, удаления стоп - слов, лемманизации, а также
      преобразования сообщений в <i>вектора TF-IDF</i>.  Показано описание результатов при помощи матрицы ошибок.
    </p>
    <hr>
    <p align="center">
        <img src="https://github.com/DurinPavel/classification_text_messages/blob/main/image/df_source.png" alt="Source dataframe" width=100%>
        <hr>
        <img src="https://github.com/DurinPavel/classification_text_messages/blob/main/image/error_matrix.png" alt="Error matrix" width=100%>
        <hr>
        <img src="https://github.com/DurinPavel/classification_text_messages/blob/main/image/df_result.png" alt="Result dataframe" width=100%>
        <hr>
    </p>
</b></body>
