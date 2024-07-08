# PROJETO
O Projeto é sobre um Dataset extraído do Kaggle sobre o desgaste dos funcionários de uma organização (saíram ou permaneceram na empresa). Fiz a análise exploratória dos dados buscando padrões e correlações que possa explicar a decisão de cada funcionário e, criei um modelo de classificação com acurácia de 76%.

# DATASET
Foram coletados dados de 59.598 funcionários que responderam várias questões pessoais como; idade, sexo, renda mensal entre outras e questões como, por exemplo: tamanho da empresa, quantidade de anos na empresa, quantidade de promoções.

# ANÁLISE EXPLORATÓRIA DOS DADOS
Realizei análises descritivas dos dados, correlações, análises univariadas e bivariadas respondendo 10 perguntas abaixo;
1. Qual a relação entre a idade dos funcionários e a decisão de continuar na empresa?

   Funcionários entre 18 e 30 anos tem uma chance maior de deixar a empresa

2. Qual a relação entre Satisfação no trabalho e decisão de sair da empresa?
   
   Não há uma relação! tendo em vista que funcionários com uma avaliação alta teve probabilidade menor que a média de sair da empresa, porém funcionários que avaliaram com muito alta tiveram uma probabilidade acima da média de sair da empresa.

3. Trabalho remoto (Home office) tem maior chance do funcionário permanecer na empresa?
   
   Funcionários que trabalham em Home Office tem 75% de permanecer na empresa.

4. Há correlação entre Renda mensal e a variável Attrition (Chance do funcionário permanecer ou sair da empresa)?

   Utilizando da correlação de Pearson, podemos analisar que há uma correlação quase nula (0,01) entre as duas variáveis, ou seja, não há relação nenhuma.

5. Qual a relação entre nível de educação e a probabilidade do funcionário deixar a empresa?

   Podemos observar que todos os níveis (exceto Phd) tem o mesmo percentual de sair da empresa.

6. Há diferença no tempo de anos na empresa dos funcionários com Phd em relação aos demais.

   Podemos notar que os funcionários com Phd tem uma média acima dos outros níveis, mas não podemos inferir que isto seja o motivo de ter um percentual tão baixo de saídas.

7. Funcionários com mais promoções tem probabilidade menor de sair da empresa?

   A partir de 3 promoções a chance de sair da empresa cai para 25%, e abaixo de 3 promoções a chance fica em torno da média do dataset.

 8. Qual a relação entre o sentimento do funcionário sobre o equilíbrio entre trabalho e vida pessoal afeta a probabilidade de sair da empresa?

    Há uma diferença substancial entre os funcionários que disseram ser Excelente e Boa (ambas abaixo do percentual de funcionários que saíram da empresa) em relação aos que afirmaram Razoável e Ruim.

 9. Qual a relação entre a reputação da empresa e a probabilidade do funcionário sair da empresa?

    Funcionários que disseram Excelente ou Boa tiveram um percentual bem menor de terem saído da empresa em relação aos que afirmaram Razoável ou Ruim.

10. Funcionários que receberam oportunidades em cargos de liderança tiveram um percentual menor de saírem da empresa?

    Funcionários em cargos de liderança tiveram um percentual um pouco menor que a média de saírem da empresa.

# MODELO DE CLASSIFICAÇÃO
Após a EDA fiz a codificação e normalização dos dados para criação do modelo de classificação utilizando da Regressão Logística onde obteve uma acurácia de 76%.

# SAIBA MAIS SOBRE O PROJETO
Para uma melhor visualização dos insights e de todo processo da EDA e da Modelagem te convido a ler todo o projeto.

Obrigado e até a próxima.
