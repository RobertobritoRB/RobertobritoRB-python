Lógica Utilizada

Primeiramente foi realizada a conexão com um banco de dados SQLite utilizando a biblioteca sqlite3. 
Caso o banco de dados não existisse, ele seria criado automaticamente. Em seguida, foi criada uma tabela chamada vendas1, 
contendo informações como data da venda, produto, categoria e valor da venda.

Após a criação da tabela, foram inseridos alguns registros de exemplo para possibilitar a análise dos dados. 
Em seguida, utilizou-se a biblioteca Pandas para carregar os dados do banco de dados em um DataFrame, permitindo uma manipulação mais eficiente das informações.

Posteriormente, foi realizada uma etapa de preparação dos dados, 
convertendo a coluna de data para o formato adequado e criando uma nova coluna contendo o mês da venda.

Na etapa de análise, foram calculados:

o total de vendas por categoria

o total de vendas por mês

o produto com maior valor de venda

Por fim, foram criadas visualizações utilizando as bibliotecas Matplotlib e Seaborn, 
gerando gráficos que facilitam a interpretação dos dados e permitem identificar padrões de vendas ao longo do ano.

<img width="659" height="778" alt="image" src="https://github.com/user-attachments/assets/bbcb6ccf-d2f2-45a4-97de-6c4f0bf6842d" />

<img width="573" height="712" alt="image" src="https://github.com/user-attachments/assets/5a89b925-b104-4da4-8d65-2e23263088ec" />

<img width="537" height="478" alt="image" src="https://github.com/user-attachments/assets/3a194083-42c8-4ec9-bdac-b4a4e0aaff84" />

Resultado

<img width="920" height="471" alt="image" src="https://github.com/user-attachments/assets/4dd10b44-0e5b-4579-894f-788bdd50ac0d" />

<img width="824" height="466" alt="image" src="https://github.com/user-attachments/assets/ba9f0cad-46e9-4757-b2b1-4d039242c73f" />

