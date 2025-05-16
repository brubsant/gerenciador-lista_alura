[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brubsant/gerenciador-lista_alura/blob/main/gerenciador_lista_alura.ipynb)


# 🛒 🛍️ Lista de Compras Mágica no Colab ✨  
*por Bruna Santos*

Bem-vindo(a) ao projeto Lista de Compras! Este é um chatbot simples e divertido, feito em Python e pensado para rodar no Google Colab, que te ajuda a organizar e otimizar suas compras e marcar o que já foi para o carrinho. É tão fácil de usar que até uma criança de 10 anos consegue! 🎉
![Demo do Programa](assets/demo.gif)

## 👋 Sobre o Projeto

Cansado de esquecer o que precisa comprar no mercado? Ou de se perder entre o que já pegou e o que ainda falta? 🙋‍♀️🙋‍♂️

Este chatbot foi criado para resolver esses probleminhas de forma interativa e simpática. Ele funciona como um assistente pessoal para suas compras, permitindo que você:

* Adicione itens que precisa comprar.
* Marque os itens que já colocou no seu carrinho de compras físico 🛒.
* Remova itens da lista caso mude de ideia.
* Veja sua lista completa a qualquer momento, com o status de cada item!

## 🌟 Funcionalidades Principais

* **Adicionar Itens à Lista:** Diga o que você quer comprar, e o bot anota!
* **Controle de Quantidades:** Especifique quantos de cada item você precisa.
* **Marcar Itens no Carrinho:** "Peguei!" - Avise o bot o que já está no seu carrinho, e ele te ajuda a não perder a conta.
* **Remover Itens da Lista:** Mudou de ideia sobre um produto? Sem problemas!
* **Visualização Clara:** Veja sua lista completa, com indicação do que já foi pego e o que ainda falta.
* **Interface Amigável:** Comandos simples e emojis para deixar tudo mais divertido! 😄

## 🚀 Como Executar no Google Colab

Este projeto foi feito para ser usado no Google Colab, um ambiente online e gratuito para rodar código Python.

1.  **Acesse o Google Colab:** Vá para [colab.research.google.com](https://colab.research.google.com).
2.  **Crie um Novo Notebook:** Clique em `Arquivo` > `Novo notebook`.
3.  **Copie o Código:** Copie todo o código Python do arquivo `.py` deste projeto.
4.  **Cole no Colab:** Cole o código em uma célula de código vazia no seu novo notebook.
5.  **Execute!** Clique no botão de "play" (▶️) ao lado da célula ou pressione `Ctrl+Enter` (ou `Cmd+Enter` no Mac).
6.  **Interaja:** O chatbot começará a rodar logo abaixo da célula, e você poderá digitar os comandos!

## 📸 Veja em Ação!

*(Aqui seria um ótimo lugar para colocar um print de tela ou um GIF mostrando o chatbot funcionando!)*

**Exemplo de interação:**

  
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


