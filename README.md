# 🛍️ Previsão de Estoque Inteligente na AWS com SageMaker Canvas

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas". Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos
Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório AWS Cloud Quickstart.


## 🎯 Objetivos Deste Desafio de Projeto (Lab)
Neste desafio, você desenvolverá um modelo de Machine Learning para prever a quantidade de estoque futuro utilizando o Amazon SageMaker Canvas. A seguir, detalhamos o processo para a criação e implementação do seu modelo.


## 👠 Passo a Passo

### 🌳 1. Selecionar Dataset

1. Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML.
2. Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
3. Faça o upload do dataset no SageMaker Canvas.

### 🪻 2. Construir/Treinar

1. **Importar o Dataset**:
   - No SageMaker Canvas, vá para a seção "Datasets".
   - Clique em "Import data" e selecione o arquivo do dataset que você escolheu.
   
2. **Configurar Variáveis de Entrada e Saída**:
   - Após importar o dataset, defina a coluna de saída (target) que você deseja prever, como a quantidade de estoque futuro.
   - Selecione as colunas de entrada (features) que serão utilizadas para a previsão, como data, quantidade em estoque atual, vendas passadas, etc.

3. **Treinar o Modelo**:
   - Clique em "Create Model".
   - Escolha o dataset que você importou e configure o modelo conforme as variáveis de entrada e saída.
   - Inicie o treinamento do modelo. Esse processo pode levar algum tempo, dependendo do tamanho e complexidade dos dados.

### 🌷 3. Analisar

1. **Examinar Métricas de Performance**:
   - Após o treinamento, visualize as métricas de desempenho do modelo, como precisão, erro médio absoluto (MAE), e erro quadrático médio (RMSE).
   
2. **Verificar Características Influentes**:
   - Analise as principais características (features) que influenciam as previsões.
   
3. **Ajustar o Modelo**:
   - Faça ajustes nos hiperparâmetros ou na seleção de features, se necessário.
   - Re-treine o modelo até obter um desempenho satisfatório.

### 🌵 4. Prever

1. **Usar o Modelo para Previsões**:
   - Carregue novos dados no SageMaker Canvas para prever quantidades de estoque futuras.
   - Gere as previsões e exporte os resultados para análise posterior.

2. **Analisar Resultados**:
   - Examine as previsões geradas e compare-as com os dados reais de estoque.
   - Documente suas conclusões e insights obtidos a partir das previsões.


### ⚜️ Dúvidas?
Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.

---

## 〽️  Estrutura do Repositório

- `datasets/`: Contém os datasets que podem ser usados para treinar e testar o modelo.
- `README.md`: Este arquivo, contendo as instruções e o passo a passo para completar o desafio.


## 🕵🏼‍♀️ Contribuição

Sinta-se à vontade para contribuir com melhorias para este projeto. Abra um Pull Request com suas sugestões e vamos melhorar juntos!

---

Boa sorte e bom aprendizado com o Amazon SageMaker Canvas!

---

### Commit e Push para o Repositório

Adicione o `README.md` atualizado ao seu repositório local e faça o push para o GitHub.

```bash
git add README.md
git commit -m "Adiciona guia detalhado para a previsão de estoque inteligente usando SageMaker Canvas"
git push origin main
```

Pronto! Você agora tem um guia detalhado para a criação de um modelo de Machine Learning para a "Previsão de Estoque Inteligente" no seu repositório GitHub. Envie a URL do seu repositório com a solução na plataforma da DIO.
