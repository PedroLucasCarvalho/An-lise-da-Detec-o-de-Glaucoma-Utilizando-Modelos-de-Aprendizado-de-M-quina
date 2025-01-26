# Analise da Deteccao de Glaucoma Utilizando Modelos de Aprendizado de Maquina

Análise da Detecção de Glaucoma Utilizando Modelos de Aprendizado de Máquina

Este projeto tem como objetivo construir um pipeline de aprendizado profundo para classificação de tumores cerebrais utilizando redes neurais convolucionais pré-treinadas, incluindo ResNet18, e Efficientnet. O modelo foi treinado, validado e testado em um dataset organizado nas categorias de glaucoma.

🧠 Objetivo

Desenvolver e comparar modelos de classificação de imagens para detecção e diferenciação de positivo e negativo em glaucoma. O trabalho utiliza arquiteturas de redes neurais convolucionais amplamente reconhecidas para realizar uma análise quantitativa e qualitativa do desempenho.

⚙️ Funcionalidades

Treinamento com Parâmetros e Métricas de Avaliação: Acurácia, precisão, recall, F1-score e matriz de confusão são calculadas para análise do desempenho.
📂 Estrutura do Projeto

📁 DataSet/ Training/ Validation/ Testing/ 📁 Models/ Salvar os modelos treinados (.pth) 📁 Results/ Matriz de Confusão Métricas de Avaliação

🛠️ Tecnologias Utilizadas

Python: Linguagem principal.
PyTorch: Framework para aprendizado profundo.
Torchvision: Modelos pré-treinados e ferramentas para processamento de imagens.
Scikit-learn: Cálculo de métricas e visualização da matriz de confusão.
Matplotlib: Visualização de gráficos e resultados.
TQDM: Barras de progresso para o treinamento.
Pré-requisitos

Certifique-se de ter o Python instalado na versão 3.8 ou superior e o ambiente configurado. O projeto pode ser executado em qualquer IDE ou diretamente no Google Colab.

Clone o repositório:

git clone https://github.com/PedroLucasCarvalho/An-lise-da-Detec-o-de-Glaucoma-Utilizando-Modelos-de-Aprendizado-de-M-quina/tree/main?tab=readme-ov-file

Crie e ative um ambiente virtual (opcional):

python -m venv venv source venv/bin/activate # Linux/Mac venv\Scripts\activate # Windows

Instale as dependências necessárias:

pip install torch torchvision scikit-learn matplotlib tqdm

Baixe o DataSet e o descompacte na mesma pasta do projeto Link do dataset:

https://drive.google.com/drive/folders/1ePFj8ohvBvdY_DaidwsmTLtspNEsc8Kg?hl=pt-br

📊 Resultados Os modelos foram avaliados em termos de:

Acurácia: Percentual de predições corretas.
Matriz de Confusão: Para análise detalhada das classes.
Comparação de Modelos: ResNe18 e Efficientnet.
