# 🩸 Taxa de Incidência de Diabetes 🩸

## 📈 Recolha de dados e API's usados 📈

Para esta análise sobre a taxa de incidência de diabetes em Portugal de 1992 até 2018 recorremos ao website do Serviço Nacional de Saúde [SNS](https://transparencia.sns.gov.pt/explore/dataset/taxa-de-incidencia-de-diabetes/information/?flg=pt&sort=periodo&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiU1VNIiwic2NpZW50aWZpY0Rpc3BsYXkiOnRydWUsImNvbG9yIjoiIzY2YzJhNSIsInlBeGlzIjoidG90YWwifV0sInhBeGlzIjoicGVyaW9kbyIsIm1heHBvaW50cyI6NTAsInNvcnQiOiIiLCJ0aW1lc2NhbGUiOiJ5ZWFyIiwiY29uZmlnIjp7ImRhdGFzZXQiOiJ0YXhhLWRlLWluY2lkZW5jaWEtZGUtZGlhYmV0ZXMiLCJvcHRpb25zIjp7ImZsZyI6InB0Iiwic29ydCI6InBlcmlvZG8ifX19XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZX0%3D), procurando então no mesmo a tabela com estes valores que pretendíamos. O website já disponibilizava o ficheiro em CSV facilitando assim a criação da tabela com os valores.
  
Esta tabela permite-nos consultar a taxa de incidência em cada ano a partir de 1992 até 2018, esta permite analisar a taxa de incidência apenas no sexo masculino em todas as faixas etárias, o mesmo acontece no feminino. Temos também a possibilidade de examinar esta mesma taxa, desta vez de acordo com as diversas faixas etárias, independentemente de serem do sexo masculino ou feminino. Estas faixas etárias são dos 0 aos 4, dos 5 aos 9, dos 10 aos 14, dos 15 aos 24, dos 25 aos 34, dos 35 aos 44, dos 45 aos 54, dos 55 aos 64, dos 65 a 74 e por fim os de 75 ou mais anos.

A unidade de medida presente nesta tabela é a de “Número por 100 000”, cuja fórmula utilizada pelo SNS para este cálculo é a seguinte: “Número de novos casos de diabetes notificados pela rede médicos sentinela / População sob observação efetiva pela rede médicos sentinela”. A Rede Médicos Sentinela é um sistema de observação em saúde constituído por médicos de Medicina Geral e Familiar. 

Uma pequena observação que aparece no website sobre os dados avaliados é: “Os valores da taxa de incidência para os anos 2014 e 2015 são, exclusivamente, atribuíveis à Diabetes tipo II, enquanto nos anos anteriores foram considerados conjuntamente os dois tipos de diabetes.”





## ✍🏼 Contexto ✍🏼

## 🧱 Estrutura 🧱
## 📔 Dicionário de dados 📔 


| Nome do ficheiro  |  Função e contéudo  |  Possiveis Valores  |
| ------------------- | ------------------- | ----------------- |
|  Ano |  anos correspondentes as estatísticas apresentadas entre os anos 1992 e 2018 | >=0 |
|  Sexo Masculino |  número de homens com diabetes em Portugal respetivamente a cada ano | >=0 |
|  Sexo Feminino  |  número de mulheres com diabetes em Portugal respetivamente a cada ano | >=0 |
|  0 aos 4 anos |  número de pessoas com diabetes dos 0 aos 4 anos | >=0 |
|  5 aos 9 anos |  número de pessoas com diabetes dos 5 aos 9 ano | >=0 |
|  10 aos 14 anos |  número de pessoas com diabetes dos 10 aos 14 anos | >=0 |
|  15 aos 24 anos |  número de pessoas com diabetes dos 15 aos 24 anos | >=0 |
|  25 aos 34 anos |  número de pessoas com diabetes dos 25 aos 34 anos | >=0 |
|  35 aos 44 anos |  número de pessoas com diabetes dos 35 aos 44 anos | >=0 |
|  45 aos 54 anos |  número de pessoas com diabetes dos 45 aos 54 anos | >=0 |
|  55 aos 64 anos |  número de pessoas com diabetes dos 55 aos 64 anos | >=0 |
|  65 aos 74 anos |  número de pessoas com diabetes dos 65 aos 74 anos | >=0 |
|  Total |  número total de pessoas com diabetes no decurso de cada ano | >=0 |




## 📚 Bibliografia/Webgrafia 📚

[Taxa de Incidência de Diabetes - SNS](https://transparencia.sns.gov.pt/explore/dataset/taxa-de-incidencia-de-diabetes/information/?flg=pt&sort=periodo&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiU1VNIiwic2NpZW50aWZpY0Rpc3BsYXkiOnRydWUsImNvbG9yIjoiIzY2YzJhNSIsInlBeGlzIjoidG90YWwifV0sInhBeGlzIjoicGVyaW9kbyIsIm1heHBvaW50cyI6NTAsInNvcnQiOiIiLCJ0aW1lc2NhbGUiOiJ5ZWFyIiwiY29uZmlnIjp7ImRhdGFzZXQiOiJ0YXhhLWRlLWluY2lkZW5jaWEtZGUtZGlhYmV0ZXMiLCJvcHRpb25zIjp7ImZsZyI6InB0Iiwic29ydCI6InBlcmlvZG8ifX19XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZX0%3D)

