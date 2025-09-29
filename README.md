
# Classificação de Imagens com HOG + SVM

Projeto de classificação binária de imagens usando Histogram of Oriented Gradients (HOG) como vetor de características e Support Vector Machines (SVM) como classificador.

## Sobre o Projeto
Este projeto utiliza o dataset [Chest X-Ray Pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) para distinguir entre imagens de raio-X de tórax normais e com pneumonia. O pipeline inclui:

- Download automático do dataset via KaggleHub
- Pré-processamento e balanceamento das imagens
- Extração dos vetores HOG
- Treinamento e avaliação de um classificador SVM
- Geração de relatório completo em PDF com todos os resultados

## Estrutura do Código
- **classification.ipynb**: Notebook principal com todo o fluxo do projeto
- **requirements.txt**: Dependências do projeto
- **resultados_classificacao_completo.pdf**: Relatório gerado automaticamente

## Como Executar
1. Instale as dependências:
	```bash
	pip install -r requirements.txt
	```
2. Execute o notebook `classification.ipynb` em ambiente Jupyter ou VS Code
3. O relatório será gerado automaticamente ao final da execução

## Resultados
O relatório PDF inclui:
- Informações do dataset
- Parâmetros do HOG
- Exemplos visuais de extração HOG
- Matrizes de confusão (treino e teste)
- Relatórios de classificação
- Exemplos de sucesso e falha

## Autor
**Lucas Cardoso**

---

> Task 3 from Introduction to Deep Learning - Msc. Computer Engineering at C3 FURG / Set. 2025
