Desafios práticos da Trilha Nexvisual de Visão Computacional

# Desafios - Trilha Nexvisual: Visão Computacional

Repositório com os desafios práticos realizados durante a **Trilha de Visão Computacional** do programa **Nexvisual** (Instituto Eldorado / MCTI).

---

## Desafios

### Desafio 1 — Desfoque de Fundo (Background Blur)
Implementação de solução para aplicar efeito de desfoque no fundo de imagens contendo pessoas, similar ao recurso utilizado em aplicativos de videochamada como Google Meet e Microsoft Teams.

**Técnicas utilizadas:**
- Detecção facial com Haar Cascade (OpenCV)
- Desfoque com `GaussianBlur`
- Composição de imagem com máscara suavizada

**Bibliotecas:** `OpenCV`, `NumPy`, `Matplotlib`

---

### Desafio 2 — Reconhecimento Facial
Implementação de solução de reconhecimento facial, similar a sistemas de controle de acesso a áreas restritas.

**Técnicas utilizadas:**
- Detecção facial com modelo SSD ResNet (OpenCV DNN)
- Extração de embeddings faciais com OpenFace
- Classificação com SVM (scikit-learn)

**Bibliotecas:** `OpenCV`, `NumPy`, `scikit-learn`, `imutils`, `pickle`

---

### Desafio 3 — Rastreamento de Objetos
Implementação de solução para rastreamento de objetos em vídeo.

**Técnicas utilizadas:**
- Detecção e rastreamento com YOLO11n (ultralytics)
- Processamento frame a frame
- Exportação do vídeo com anotações

**Bibliotecas:** `ultralytics`, `OpenCV`, `PyTorch`

---

### Desafio 4 — Reconhecimento de Poses
Implementação de solução para estimação de poses humanas, com aplicações em análise esportiva.

**Técnicas utilizadas:**
- Estimação de poses com YOLO11n-pose (ultralytics)
- Detecção de keypoints corporais
- Visualização dos esqueletos sobre a imagem

**Bibliotecas:** `ultralytics`, `OpenCV`, `PyTorch`, `Matplotlib`

---

## Stack Técnico

| Categoria | Tecnologias |
|-----------|-------------|
| Linguagem | Python 3.14 |
| Visão Computacional | OpenCV, YOLO11, OpenFace |
| Machine Learning | scikit-learn, PyTorch |
| Utilitários | NumPy, Matplotlib, imutils |

---

## Estrutura do Repositório
