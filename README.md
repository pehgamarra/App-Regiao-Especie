# 🐾 App-Região-Espécie

Aplicação de visão computacional que identifica, em imagens de raio‑x veterinário, a **região anatômica** (como tórax, abdômen, coluna, etc.) e a **espécie do animal** (cão, gato, etc.).

---

## 📌 Descrição

O **App-Região-Espécie** foi desenvolvido para auxiliar profissionais veterinários na análise de radiografias. A aplicação realiza inferência em tempo real a partir de uma imagem enviada e retorna:

- A **região do corpo** presente na imagem.
- A **espécie do animal** correspondente.
- As **probabilidades** de cada predição.

---

## ✅ Funcionalidades

- Upload de imagem de raio‑x (.jpg, .png)
- Inferência usando modelo de deep learning treinado
- Saída com predições e confiança
- API leve e de fácil integração
- Scripts para treinamento e avaliação

---

## 🛠 Tecnologias Utilizadas

- Python 3.10+
- FastAPI ou Flask (API)
- PyTorch ou TensorFlow (Modelos)
- Pillow / OpenCV (Processamento de Imagem)
---
