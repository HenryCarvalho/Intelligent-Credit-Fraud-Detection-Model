# Intelligent-Credit-Fraud-Detection-Model

**Descrição**  
O modelo **Intelligent Credit Fraud Detection** é uma solução de detecção de fraudes em transações financeiras, utilizando técnicas avançadas de Machine Learning e Inteligência Artificial para identificar padrões suspeitos e prevenir fraudes no setor bancário e financeiro.

---

## Dados de Entrada

O modelo utiliza um conjunto de dados estruturado, com as seguintes colunas importantes:

- **Coluna `Time` (Tempo):**  
  Representa o número de segundos decorridos entre a transação atual e a primeira transação no conjunto de dados.

- **Colunas `V1` a `V28`:**  
  Esses campos são resultados de uma redução de dimensionalidade utilizando o algoritmo PCA (Principal Component Analysis). Eles foram criados para proteger identidades de usuários e características sensíveis das transações. Os valores exatos dessas colunas não possuem um significado direto, mas ajudam o modelo a capturar padrões e anomalias.

Esses dados foram tratados para garantir a privacidade das informações dos usuários, mantendo a eficácia na detecção de fraudes.

**Objetivo**  
Identificar e classificar transações fraudulentas com alta precisão, aproveitando técnicas de Machine Learning, amostragem balanceada, e redes neurais, enquanto extraímos insights adicionais do conjunto de dados.

---

## Índice
1. [Instalação](#instalacao)
2. [Como Usar](#como-usar)
3. [Estrutura do Projeto](#estrutura-do-projeto)
4. [Modelos e Algoritmos](#modelos-e-algoritmos)
5. [Contribuindo](#contribuindo)
6. [Licença](#licenca)
7. [Contato](#contato)

---

## Instalação

### Pré-requisitos
- Python 3.x
- Bibliotecas principais:
  - pandas
  - numpy
  - scikit-learn
  - tensorflow (se usar deep learning)
  - matplotlib (para visualizações)
  - seaborn (para visualizações)
  
### Como instalar
1. Clone este repositório:
   ``` git clone https://github.com/HenryCarvalho/Intelligent-Credit-Fraud-Detection-Model.git ```
    
2. Navegue até o diretório do projeto:
    ``` cd Intelligent-Credit-Fraud-Detection-Model ```

3. Instale as dependências:
    ``` pip install -r requirements.txt ```

### Como Usar
1. Carregue os dados de transações:
    - Coloque os dados das transações no formato adequado (CSV, JSON, etc.) ou use o dataset disponível.

2. Execute o código para treinar o modelo:
    ``` python train_model.py ```

3. Utilize o modelo treinado para prever fraudes em novas transações:
    ```python predict_fraud.py --input new_transactions.csv ```

## Estrutura do Projeto

- `train_model.py`: Script principal para treinar o modelo de detecção de fraudes.
- `predict_fraud.py`: Script para utilizar o modelo treinado em novas transações.
- `data/`: Diretório contendo os datasets de treinamento e validação.
- `models/`: Diretório com os modelos treinados e arquivos de configuração.
- `requirements.txt`: Arquivo com as dependências necessárias.
- `README.md`: Este arquivo de documentação.

---

## Modelos e Algoritmos

Este projeto utiliza diferentes abordagens para detectar fraudes, incluindo:

- **Modelos supervisionados**:
  - Logistic Regression
  - Confusion Matrix
  - Test Data with Logistic Regression
  - Learning Curves
  - Overfitting during Cross Validation
  
- **Abordagens não supervisionadas**:
  - Análise de Anomalias
  - Random Under-Sampling
  - Neural Networks Testing Random U


A avaliação do modelo é realizada utilizando métricas como:
- Acurácia
- Precisão
- Recall
- F1-Score

---

## Contribuindo

Se você deseja contribuir para este projeto, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma nova branch (`git checkout -b feature/novo-recurso`).
3. Realize suas alterações.
4. Teste suas mudanças.
5. Envie um pull request.

---

## Licença

Este projeto está licenciado sob a **MIT License** - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## Contato

Desenvolvedor: **Henrique Carvalho**  
E-mail: [henrique.t.s.carvalho@gmail.com](mailto:henrique.t.s.carvalho@gmail.com)  
GitHub: [https://github.com/HenryCarvalho](https://github.com/HenryCarvalho)

