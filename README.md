# Modelo_Webshopping

## Dataset usado:
* <a href="https://github.com/lucasdga1/Modelo_Webshopping/blob/main/marketing_campaign.csv">Base de dados</a>

## Código do projeto
* <a href="https://github.com/lucasdga1/Modelo_Webshopping/blob/main/Cientista%20de%20Dados%20M37%20Projeto.ipynb">Código</a>

## Objetivos
* Treinar um modelo de machine learning que possa prever a tendência de um consumidor de uma empresa em adquirir seus produtos pela sua plataforma online

## Metodologia
* Importação das bibliotecas e módulos necessários;
* Análise do dataset;
* Utilização da biblioteca Pandas e Numpy para verificação dos tipos de dados e possíveis dados faltantes;
* Utilização do Label encoder para codificação de dados categóricos;
* Utilização da biblioteca Scipy para eliminar outliers com zscore;
* Utilização da biblioteca Plotly para a análise bivariada e extração de insights sobre o dataset;
* Verificação de correlação das variáveis com a variável target;
* Utilização do StandardScaler para a padronização dos dados;
* Utilização do PCA para verificação de componentes necessários à construção do modelo;
* Construção do modelo de regressão logística com teste de hiperparâmetros para melhores resultados;
* Construção do modelo de random forest com teste de hiperparâmetros para melhores resultados;
* Treino e teste dos modelos;
* Análise de resultados a partir da matriz de confusão e relatório de classificação;
* Comparação dos resultados entre os modelos.

## Métrica alvo
* WebPurchases

## Análise bivariada
<img width="1310" height="450" alt="SalarioXCompras" src="https://github.com/user-attachments/assets/11832380-c019-4143-a2d0-0e91f42b38f2" />
<img width="1310" height="450" alt="EducacaoXCompras" src="https://github.com/user-attachments/assets/3d0c3446-7efc-4bed-9dee-17612971c8d4" />
<img width="1310" height="450" alt="OuroXCompras" src="https://github.com/user-attachments/assets/ce329dcb-bc8f-4da3-83d4-35305c232d01" />
<img width="1310" height="450" alt="AnoXCompras" src="https://github.com/user-attachments/assets/f80b729d-e26d-4d0e-aab5-5dd30fd4e521" />

## Matriz de correlação das variáveis
<img width="1310" height="450" alt="Correlacao" src="https://github.com/user-attachments/assets/25c9cddb-9105-411b-ac46-0b3ca51bf804" />

## Resultado da análise PCA
<img width="1310" height="450" alt="PCA" src="https://github.com/user-attachments/assets/73ed305a-aa71-4edf-8174-b558f357ad5d"/>

## Resultado do modelo de regressão logística

<img width="1310" height="450" alt="Confusao_Logistica" src="https://github.com/user-attachments/assets/f8246b18-0cdf-409a-86b4-0685ee5340e0">Matriz de confusão do modelo de regressão logística </img>

O modelo apresentou boa performance, com acurácia de 83%, recall de 77%, para a classificação de consumidores como possíveis compradores, e média ponderada de 83%.

Isso significa que o modelo se adapta bem ao dataset e foi bem treinado para a classificação da métrica alvo, podendo prever quando um consumidor apresenta possibilidade de adquirir produtos da empresa por meio da plataforma web.

## Resultado do modelo de random forest

<img width="1310" height="450" alt="Confusao_Forest" src="https://github.com/user-attachments/assets/e072d247-4f68-433c-8b65-eb4f5ff55136">Matriz de confusão do modelo de random forest</img>

O modelo apresentou acurácia de 90%, recall de 92%, para classificação de possíveis compradores, e média ponderada de 90%.


## Resultado final
O modelo que melhor se adaptou ao dataset e apresentou melhores resultados para o objetivo proposto foi o random forest, conseguindo ótimos resultados na classificação dos consumidores.

## Contribuição

Contribuições são sempre bem-vindas! Se você deseja ajudar a melhorar este projeto, siga os passos abaixo: 
1. Faça um **fork** do repositório
2. Crie uma branch para sua feature ou correção ```bash git checkout -b minha-feature
3. Realize suas alterações e faça o commit (git commit -m "Adiciona minha nova feature")
4. Envie para a branch remota (git push origin minha-feature)
5. Abra um Pull Request

## Autoria
Lucas Danziger Guimarães de Andrade

## Contato
<a href="mailto:lucas.dga1@gmail.com">Me envie um email<a/>
