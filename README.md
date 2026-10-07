# ds_ai

Meus estudos e projetos de Data Science e IA, reunidos num só lugar.

## Mapa de estudos

| Área | Projeto | O que tem | Stack principal |
|---|---|---|---|
| ML | [Regressão – Incêndios florestais](ml/regression-forest-fires/) | Regressão linear, Ridge, Lasso e ElasticNet para prever o Fire Weather Index | scikit-learn |
| ML | [Classificação – Fraude em seguros](ml/classification-insurance-fraud/) | Classificação supervisionada para detectar fraude | scikit-learn, XGBoost, Optuna, SHAP, LIME |
| ML | [Não supervisionado – Eventos](ml/unsupervised-events/) | Clusterização (K-Means, hierárquica) com redução de dimensionalidade via PCA | scikit-learn |
| Deep Learning | [ANN – Churn](deep-learning/ann-churn/) | Rede neural densa para prever churn | TensorFlow / Keras |
| Deep Learning | [CNN – 10 categorias](deep-learning/cnn-10-categories/) | CNN para classificar as 10 classes do CIFAR-10 | TensorFlow / Keras |
| GenAI | [Primeiro chatbot](genai/first-chatbot/) | Q&A sobre documentos PDF pessoais | LangChain, Streamlit |
| MLOps | [Titanic MLOps](mlops/titanic-mlops/) | Pipeline completo: treino, API, Docker, Kubernetes, CI | Flask, Docker, Kubernetes |
| Referência | [Cheat sheets](cheat-sheets/) | Consultas rápidas de Python, SQL e PySpark | — |

## Estrutura

```
ds_ai/
├── ml/              # Machine Learning clássico
├── deep-learning/   # Redes neurais
├── genai/           # IA generativa e LLMs
├── mlops/           # Deploy, pipelines e infraestrutura
└── cheat-sheets/    # Material de consulta
```

Cada projeto fica em uma pasta própria, com seu README, notebook e dados.

## Como rodar

```bash
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

O projeto de MLOps tem seu próprio `requirements.txt` em `mlops/titanic-mlops/`.

## Próximos passos

- [ ] Completar os READMEs dos projetos (problema, abordagem e resultados)
- [ ] Criar uma pasta `utils/` com funções reaproveitadas entre projetos
- [ ] _próximo tema de estudo..._
