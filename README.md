# Conexão SSH para o Google Colab via Cloudflared

Este repositório contém um Jupyter Notebook (`colab_ssh.ipynb`) que permite configurar uma conexão SSH segura para o Google Colab utilizando o **Cloudflared**. Essa conexão é útil para acessar o ambiente do Colab diretamente via terminal ou através de ferramentas como o VSCode com a extensão Remote SSH.

---

## Funcionalidades

- **Conexão SSH Segura:** Utiliza o Cloudflared para criar um túnel seguro entre o Google Colab e sua máquina local.
- **Suporte a Terminal e VSCode:** Permite conectar-se ao Colab via terminal ou usando a extensão Remote SSH do VSCode.
- **Fácil Configuração:** O notebook guia você passo a passo na configuração do SSH.

---

## Como Usar no Google Colab

1. **Acesse o Google Colab:**
   - Abra o [Google Colab](https://colab.research.google.com/).
   - Clique no botão abaixo para abrir o notebook diretamente no Colab:
     [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KauaHenSilva/google_colab_ssh/blob/main/colab_ssh.ipynb)

2. **Execute o Notebook:**
   - Conecte-se a um ambiente de execução clicando em `Conectar` (canto superior direito).
   - Execute as células sequencialmente para configurar a conexão SSH.

3. **Configure o Cloudflared na Sua Máquina:**
   - Siga as instruções exibidas no notebook para baixar e configurar o Cloudflared na sua máquina local.
   - Adicione as configurações necessárias ao arquivo `~/.ssh/config`.

4. **Conecte-se ao Colab:**
   - Use o comando SSH fornecido no notebook para conectar-se ao ambiente do Colab via terminal.
   - Ou utilize o hostname fornecido para conectar-se via VSCode Remote SSH.

---
