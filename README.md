## Instalando as Dependências do Projeto

Este arquivo README.md fornece instruções para instalar as bibliotecas Python necessárias para executar este projeto. As bibliotecas estão listadas no arquivo `requirements.txt`.

**Etapas para Instalação:**

1. **Clone o Repositório:**
   ```bash
   git clone <URL do repositório>
   ```

2. **Navegue até o Diretório do Projeto:**
   ```bash
   cd <nome do diretório do projeto>
   ```

3. **Crie um Ambiente Virtual (Recomendado):**
   - **Windows:**
     ```bash
     python -m venv .venv
     ```
   - **Linux/macOS:**
     ```bash
     python3 -m venv .venv
     ```

4. **Ative o Ambiente Virtual:**
   - **Windows:**
     ```bash
     .venv\Scripts\activate
     ```
   - **Linux/macOS:**
     ```bash
     source .venv/bin/activate
     ```

5. **Instale as Dependências:**
   ```bash
   pip install -r requirements.txt
   ```

**Observações:**

- Certifique-se de ter o Python e o `pip` instalados em seu sistema.
- Se você encontrar erros durante a instalação, tente atualizar o `pip`:
  ```bash
  pip install --upgrade pip
  ```
- Para desativar o ambiente virtual, use o comando `deactivate`.

**Lista de Dependências (requirements.txt):**

```
contourpy==1.3.1
cycler==0.12.1
fonttools==4.55.3
kiwisolver==1.4.8
matplotlib==3.10.0
numpy==2.2.1
packaging==24.2
pandas==2.2.3
pillow==11.0.0
pyparsing==3.2.0
python-dateutil==2.9.0.post0
pytz==2024.2
six==1.17.0
tzdata==2024.2
```
