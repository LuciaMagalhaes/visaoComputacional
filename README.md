# 🔍 Detecção de Objetos com YOLOv8 (Visão Computacional)

Projeto de Visão Computacional utilizando YOLOv8 para detecção de objetos em imagens e vídeos, com foco na identificação de indivíduos portando armas de fogo em ambientes públicos.

---

## 📌 Objetivo

Desenvolver um modelo de detecção de objetos capaz de identificar automaticamente armas de fogo em imagens e vídeos, permitindo a geração de alertas para apoio à segurança pública.

---

## 🧠 Tecnologias Utilizadas

- Python
- OpenCV
- NumPy
- Matplotlib
- PyTorch
- Ultralytics YOLOv8

---

## ⚙️ Estrutura do Projeto

```
├── dataset/
├── images/
├── output/
├── runs/
├── video/

└── README.md
```

---

## 🚀 Como Executar

### Instalar dependências

```bash
pip install ultralytics opencv-python matplotlib numpy pillow torch
```

---

### Executar detecção em imagem/vídeo

```bash
Executar o projeto (Notebook)

A execução do projeto para testes e demonstração é feita via Jupyter Notebook:

jupyter notebook

Abra o arquivo:

notebook_teste_yolo.ipynb

E execute as células sequencialmente.
```

---

## 🎯 Treinamento do Modelo

```bash
yolo detect train data=data.yaml model=yolov8n.pt epochs=30 imgsz=640
```

---

## 📊 Saída

O sistema gera:

- Bounding boxes (caixas delimitadoras)
- Classe detectada
- Nível de confiança
- Tempo de inferência

---

## ⚠️ Observações

- O desempenho depende da qualidade do dataset.
- Uso como ferramenta de apoio — não substitui análise humana.

---

## 👩‍💻 Autora

Projeto desenvolvido como trabalho acadêmico em Visão Computacional e IA Generativa.
