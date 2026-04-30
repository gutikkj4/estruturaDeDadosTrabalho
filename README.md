# README — Projeto de Regressão Logística (Heart Disease)

Este projeto implementa um modelo de regressão logística para previsão de doenças cardíacas, incluindo versões vetorizada e não vetorizada, além da análise de custo e acurácia.

O código foi desenvolvido para execução no Google Colab.

\---

## Como executar no Google Colab

1. Abra o notebook:

   * Faça upload do arquivo .ipynb no Colab ou abra pelo Google Drive.
2. Execute as células iniciais (obrigatório):

   * Importação de bibliotecas
   * Carregamento e preparação dos dados
   * Definição das funções

   Essas etapas são necessárias para o funcionamento do restante do código.

   \---

   ## Ordem de execução

   Siga a ordem abaixo:

1. Preparação dos dados

   * Carregamento do dataset
   * Divisão em treino e teste
2. Implementação

   * Versão não vetorizada
   * Versão vetorizada (opcional)
3. Treinamento

   * Ajuste dos parâmetros
   * Cálculo do custo ao longo das iterações
4. Predição

   * Aplicação do modelo nos dados de teste
5. Avaliação

   * Cálculo da acurácia
   * Análise do custo

   \---

   ## Tempo de execução

   Algumas etapas podem levar mais tempo, principalmente:

* Implementação não vetorizada
* Cálculo do custo em várias iterações

  Aguarde a execução completa de cada célula antes de continuar.

  \---

  ## Possíveis problemas

  Erro: função não definida

* Execute novamente as células iniciais

  Erro com variáveis (X\_train, y\_train, etc.)

* Verifique a ordem de execução

  Código não atualiza corretamente

* Reinicie o ambiente de execução e rode tudo novamente

