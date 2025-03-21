# lec-iot-for-beginners


### _More information about the curse_

[IoT for Beginners - A Curriculum](https://github.com/microsoft/IoT-For-Beginners)


# 🚀 Configuração do Ambiente para o Projeto "lec-iot-for-beginners"

Este guia ensina a configurar o ambiente no **VSCode** para executar os notebooks do repositório [lec-iot-for-beginners](https://github.com/bps90/lec-iot-for-beginners).  

---

## 📌 **Passo 1: Instalar o Python**  
🔹 Certifique-se de que o Python está instalado em seu sistema.  
🔹 Baixe a versão mais recente em: [python.org](https://www.python.org/)  

![Instalação do Python](https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif)

---

## 📌 **Passo 2: Instalar o Visual Studio Code**  
🔹 Baixe e instale o VSCode: [code.visualstudio.com](https://code.visualstudio.com/)  

![Download do VSCode](https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif)

---

## 📌 **Passo 3: Instalar as Extensões Necessárias no VSCode**  

🔹 No VSCode, instale as seguintes extensões:  

✅ **Python** → Suporte ao Python no VSCode  
✅ **Jupyter** → Permite a execução de notebooks Jupyter  

**Passos para instalar:**  
1. Acesse `View` > `Extensions` (ou pressione `Ctrl+Shift+X`).  
2. Pesquise pelo nome da extensão.  
3. Clique em `Install`.  

![Instalação de Extensões no VSCode](https://media.giphy.com/media/LMt9638dO8dftAjtco/giphy.gif)

---

## 📌 **Passo 4: Clonar o Repositório "lec-iot-for-beginners"**  

Abra o terminal no VSCode e execute:  

```bash
git clone https://github.com/bps90/lec-iot-for-beginners.git
````
---

## 📌 **Passo 5: Criar e Ativar um Ambiente Virtual**  

Para manter as dependências organizadas, **crie um ambiente virtual**:  

1. Acesse o diretório do projeto:  

    ```bash
    cd lec-iot-for-beginners
    ```

2. Crie um ambiente virtual no mesmo diretório baixado do github:  

    ```bash
    python3 -m venv .
    ```

3. **Ative o ambiente virtual:**  

    🔹 **No Windows:**  
    ```bash
    .\Scripts\activate
    ```

    🔹 **No macOS/Linux:**  
    ```bash
    source ./bin/activate
    ```

💡 **Dica:** O terminal mostrará `(lec-iot-for-beginners)` quando o ambiente virtual estiver ativado.


---

## 📌 **Passo 6: Instalar os Requisitos do Projeto**  

Com o ambiente virtual ativado, instale as dependências:  

```bash
pip install -r requirements.txt
```

---

## 📌 **Passo 7: Executar um Notebook Jupyter no VSCode**  

Agora, você pode abrir e rodar os notebooks do projeto no **VSCode**.  

### 🔹 **1. Selecionar o ambiente virtual no VSCode**  
- Pressione `Ctrl+Shift+P` e digite **"Python: Select Interpreter"**.  
- Escolha o interpretador do ambiente virtual (`lec-iot-for-beginners`).  

### 🔹 **2. Executar um notebook Jupyter**  
- Abra um arquivo `.ipynb` do projeto.  
- Execute as células conforme necessário.

📺 **Veja como usar o Jupyter Notebook no VSCode:**  
[![Como Usar o Jupyter Notebook no VSCode](https://img.youtube.com/vi/2a87xGLDFTQ/0.jpg)](https://m.youtube.com/watch?v=2a87xGLDFTQ)

![Jupyter Notebook no VSCode](https://media.giphy.com/media/26AHONQ79FdWZhAI0/giphy.gif)

---

## ✅ **Tudo pronto!**  

Agora você pode executar os notebooks do projeto `"lec-iot-for-beginners"` no VSCode! 🚀  

![Sucesso!](https://media.giphy.com/media/3o7abldj0b3rxrZUxW/giphy.gif)