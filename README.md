# X-Ray Classification - Kaggle Chest X-Ray Pneumonia Dataset

Este repositório contém a solução para a classificação de imagens de raios-X do tórax, utilizando o dataset [Chest X-Ray Pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) disponível no Kaggle. O objetivo é desenvolver um modelo de deep learning para identificar automaticamente se um paciente apresenta pneumonia com base nas imagens.

## 📊 Sobre o Dataset

O dataset **Chest X-Ray Pneumonia** contém imagens de raios-X do tórax classificadas em três categorias:

- **Normal**: Pacientes saudáveis.
- **Pneumonia Bacteriana**: Pacientes diagnosticados com pneumonia causada por bactérias.
- **Pneumonia Viral**: Pacientes diagnosticados com pneumonia viral.

📌 O dataset está dividido em conjuntos de **treinamento**, **teste** e **validação**, já pré-processados.

## 🚀 Metodologia

1. **Análise exploratória**: Visualização das imagens e distribuição das classes.
2. **Pré-processamento**:
   - Redimensionamento das imagens
   - Normalização
   - Aplicação de técnicas de data augmentation
3. **Modelagem**:
   - Uso de redes neurais convolucionais (CNNs)
   - Testes com arquiteturas populares como ResNet, EfficientNet e MobileNet
4. **Treinamento**:
   - Utilização de *transfer learning* para acelerar o aprendizado
   - Ajuste de hiperparâmetros
5. **Avaliação**:
   - Uso de métricas como Acurácia, Precisão, Recall e F1-score
   - Geração de matrizes de confusão

Principais pacotes utilizados:

- TensorFlow / Keras
- OpenCV
- Matplotlib / Seaborn
- NumPy / Pandas

## 📈 Resultados

Os modelos testados apresentaram os seguintes desempenhos:

| Modelo         | Acurácia | Precisão | Recall | F1-score |
| -------------- | -------- | -------- | ------ | -------- |
| ResNet50       | XX%      | XX%      | XX%    | XX%      |
| MobileNetV2    | XX%      | XX%      | XX%    | XX%      |
| EfficientNetB0 | XX%      | XX%      | XX%    | XX%      |

## 📢 Contribuições

Sinta-se à vontade para abrir issues e enviar PRs para melhorias no código!

## 📜 Referências

- Dataset: [Chest X-Ray Pneumonia - Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- Documentação do TensorFlow/Keras
- Papers sobre classificação de imagens médicas com CNNs
