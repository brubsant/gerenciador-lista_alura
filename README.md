[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brubsant/gerenciador-lista_alura/blob/main/GerenciadorLista_Colab.ipynb)


# 🛒 Gerenciador de Lista de Compras - Alura  
*por Bruna Santos*

![Demo do Programa](assets/demo.gif)

> Projeto desenvolvido durante a imersão Python da Alura <

## ✨ Funcionalidades Principais
- **Adição inteligente** de itens (`3 maçãs` ou `quero 2 leites`)
- **Remoção por quantidade** (`tirar 1 banana` ou `remover 3 ovos`)
- Visualização organizada por **categorias automáticas**
- Sistema de **marcação como comprado**
- Persistência dos dados entre execuções


📌 Passo a Passo para Testar no Colab

1️⃣ Preparar o Arquivo .ipynb

Crie um notebook chamado GerenciadorLista_Colab.ipynb com este conteúdo:

# *Execute os passos abaixo para testar:*

## Passo 1: Clonar o repositório

### Execute este código em uma célula:
!git clone https://github.com/brubsant/gerenciador-lista_alura.git
%cd gerenciador-lista_alura
!ls  # Verifique os arquivos

# Passo 2: Instalar dependências (se houver)
!pip install colorama
!pip install google-genai

# Passo 3: Executar o programa
!python gerenciador_lista.py

2️⃣ Configurações Adicionais
1.Para inputs interativos, adicione esta célula no notebook:

# %% [code]
from IPython.display import clear_output

def input_colab(prompt=''):
    from google.colab import output
    return output.eval_js(f'prompt("{prompt}")')

# Modifique seu código para usar input_colab() em vez de input()

2.Se usar arquivos locais, adicione:

from google.colab import files
uploaded = files.upload()  # Para upload de arquivos de configuração

3️⃣ Link Direto para Testes


