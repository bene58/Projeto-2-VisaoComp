# **Detecção de Incêndios Florestais com Modelos de Deep Learning**

Este repositório contém a implementação de um projeto de detecção de incêndios florestais utilizando aprendizado profundo com três modelos pré-treinados: **ResNet18**, **ResNet50** e **EfficientNet**. O objetivo principal do projeto é classificar imagens em duas categorias: com incêndio e sem incêndio, utilizando o dataset [Forest Fire BigData](https://www.kaggle.com/datasets/mohammedborhanuddin/forest-fire-bigdata).

## **Descrição do Projeto**

Incêndios florestais são uma ameaça crescente devido às mudanças climáticas e às condições ambientais adversas. Este projeto explora o uso de aprendizado profundo para identificar áreas afetadas por incêndios florestais, contribuindo para a detecção precoce e mitigação de danos.  
As principais etapas do projeto incluem:
- Pré-processamento de dados com **data augmentation**.
- Treinamento e ajuste fino de três modelos pré-treinados (ResNet18, ResNet50, EfficientNet).
- Avaliação de desempenho utilizando métricas como acurácia, precision, recall e F1-score.

O código foi desenvolvido utilizando **PyTorch** e executado no **Google Colab**, aproveitando sua infraestrutura de GPU para acelerar o treinamento.

---

## **Dependências**

Antes de executar o projeto, certifique-se de instalar as seguintes dependências:

- **Python** (>=3.7)
- **PyTorch** (>=1.11.0)
- **torchvision** (>=0.12.0)
- **numpy**
- **pandas**
- **matplotlib**
- **seaborn**
- **scikit-learn**

## **Link do Vídeo no YouTube**
https://youtu.be/xPdHQTBQ9Ic?si=sIvDqGmmnS9tNsiP

## **Instruções de Execução**

### 1. **Clonando o Repositório**
```bash
# Clone este repositório para sua máquina local:
git clone https://github.com/seu-usuario/forest-fire-detection.git
cd forest-fire-detection

# Acesse o Kaggle para baixar o dataset:
# Link: https://www.kaggle.com/datasets/mohammedborhanuddin/forest-fire-bigdata
# Após o download, descompacte o arquivo e mova os dados para um diretório local.

# Abra o arquivo .ipynb no repositório ou faça o upload no Google Colab.
# Siga os passos abaixo:

# 1. Conecte-se a uma GPU:
#    - Vá em Runtime > Change runtime type
#    - Selecione GPU como o hardware acelerador.

# 2. Monte o Google Drive ou faça o upload direto do dataset para o ambiente do Colab.
#    - Para montar o Google Drive:
from google.colab import drive
drive.mount('/content/drive')

# Execute cada célula do notebook sequencialmente. O notebook está organizado em seções:
# - Carregamento e visualização dos dados.
# - Pré-processamento e data augmentation.
# - Treinamento dos modelos.
# - Avaliação e visualização dos resultados.

# Certifique-se de que o dataset foi carregado corretamente antes de iniciar o treinamento.

# Os resultados incluem:
# - Gráficos de treinamento (curvas de perda e acurácia).
# - Métricas detalhadas como precision, recall e F1-score.
# - Matriz de confusão para análise detalhada.

