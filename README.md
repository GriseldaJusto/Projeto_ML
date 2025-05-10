
# Projeto de Classificação de Imagens com Machine Learning

Este projeto foi desenvolvido como parte da aula de **Machine Learning** do curso de **Inteligência Artificial da Pretalab**.

O objetivo principal é aplicar técnicas de aprendizado de máquina para **classificar imagens de rostos de mulheres pretas e mulheres brancas**, utilizando redes neurais convolucionais com TensorFlow/Keras.

## 📁 Sobre o Projeto

O notebook [`Aula_ML.ipynb`](https://github.com/GriseldaJusto/Projeto_ML/blob/main/Aula_ML.ipynb) apresenta todas as etapas do projeto, incluindo:

- Organização e preparação do dataset
- Aumento de dados (*data augmentation*)
- Construção de um modelo de rede neural convolucional
- Treinamento e validação do modelo
- Análise dos resultados de classificação

## 🛠️ Tecnologias Utilizadas

- Python 3
- TensorFlow / Keras
- Google Colab
- NumPy
- Matplotlib
- ImageDataGenerator
- Dataset personalizado

## 📂 Dataset
O dataset utilizado para este projeto está disponível no Google Drive. Você pode acessá-lo através do seguinte link:
[Dataset no Google Drive](https://drive.google.com/drive/folders/1mOOMgLRXGoB0yo-X1IahL48pjtGVff2T?usp=sharing).

O dataset é organizado em duas pastas:
- mulher-preta: Contém imagens de mulheres negras.
- mulher-branca: Contém imagens de mulheres brancas.

## ▶️ Como Executar

1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Abra o notebook via este link: [Aula_ML.ipynb](https://github.com/GriseldaJusto/Projeto_ML/blob/main/Aula_ML.ipynb)
3. Execute as células do notebook em ordem.
4. Certifique-se de montar corretamente o Google Drive, conforme mostrado no início do notebook, para acessar os diretórios com as imagens.

## 📌 Observações

- O dataset usado é particular e organizado manualmente em duas classes: `mulher-preta` e `mulher-branca`.
- O modelo foi treinado com um número reduzido de imagens, então os resultados podem ser aprimorados com mais dados e ajustes de parâmetros.

---


Feito com ❤️ por Griselda Justo como parte da formação PretaLab.
