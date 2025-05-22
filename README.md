# 🖼️ Esteganografia com LSB em Imagens Digitais

Este repositório contém um experimento guiado em Python para ocultar e recuperar mensagens secretas em imagens digitais utilizando a técnica de **Least Significant Bit (LSB)** — Bit Menos Significativo.

---

## 🎯 Objetivos da Aula

- Compreender o conceito de **esteganografia** aplicada ao Processamento Digital de Imagens.
- Aprender a **codificar** uma mensagem secreta em uma imagem usando LSB.
- Aprender a **decodificar** e extrair a mensagem escondida de uma imagem.

---

## ⚙️ Tecnologias Utilizadas

- Python 3
- Biblioteca [Pillow (PIL)](https://python-pillow.org)

---

## 🛠️ Funcionalidades

### 🔐 Inserção de mensagem na imagem
- Altera os bits menos significativos (LSBs) dos pixels RGB da imagem para codificar uma mensagem.
- Um delimitador especial (`1111111111111110`) é usado para indicar o fim da mensagem.

### 🔎 Extração de mensagem da imagem
- Varre os pixels da imagem, recupera os bits LSB e reconstrói a mensagem até encontrar o delimitador.

---

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/andreluizfrancabatista/esteganografia.git
   cd esteganografia-lsb
