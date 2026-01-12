# 🔍 Projeto de Reconhecimento Facial com Dataset Customizado

## 📌 Visão Geral

Este projeto tem como objetivo desenvolver um sistema de **reconhecimento/detecção facial** utilizando **visão computacional e deep learning**, treinado a partir de um **dataset customizado**, totalmente **anotado manualmente por mim**.

O foco inicial não é atingir performance de estado da arte, mas **validar o pipeline completo**: coleta de dados, anotação, pré-processamento, treinamento, validação e demonstração prática do modelo em funcionamento.

> ⚠️ **Importante:** O projeto começa deliberadamente pequeno (150 imagens) para priorizar **controle experimental, entendimento dos erros e iteração rápida**, antes de escalar o volume de dados.

---

## 🧠 Objetivos do Projeto

* Construir um pipeline completo de reconhecimento/detecção facial
* Trabalhar com **dataset real e limitado**, enfrentando problemas práticos
* Entender os impactos de:

  * Poucos dados
  * Overfitting
  * Generalização
  * Qualidade de anotação
* Criar uma base sólida para **escala futura do dataset**

---

## 📂 Dataset

* **Tipo:** Dataset customizado
* **Quantidade inicial:** 150 imagens
* **Anotação:** Manual (bounding boxes no formato YOLO)
* **Conteúdo:**

  * Rostos em diferentes ângulos
  * Variação de iluminação
  * Expressões faciais distintas

Estrutura esperada do dataset:

```
dataset/
├── images/
│   └── train/  
└── labels/
    └── train/
```

> 💡 **Ponto crítico:** Com apenas 150 imagens, a qualidade da anotação tem impacto maior que a quantidade.


## 🚀 Pipeline do Projeto

1. Coleta das imagens
2. Anotação manual dos rostos
3. Organização do dataset
4. Pré-processamento
5. Treinamento do modelo
6. Avaliação dos resultados
7. Testes com imagens e vídeos externos

---

## 🎥 Demonstração

[![Demonstração do modelo](https://img.youtube.com/vi/ID_DO_VIDEO/0.jpg)]((https://youtu.be/1YPzs-VBh0s))


O vídeo demonstra o modelo funcionando em:

* 📷 **Imagens estáticas**
* 🎥 **Vídeos curtos**

Utilizando:

* Fotos de celebridades
* Vídeos públicos de celebridades

> ⚠️ Uso apenas para fins **educacionais e demonstrativos**.

---

## 🧪 Resultados Esperados (Neste Estágio)

* Detecção funcional de rostos
* Baixa generalização em cenários muito distintos
* 
> ✅ Esses resultados **não são falhas**, mas **dados de aprendizado**.
