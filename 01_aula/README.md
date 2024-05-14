

- [👣 Primeiros passos](#-primeiros-passos)
  - [🛠️ `1`. Instalação do Django](#️-1-instalação-do-django)
    - [1.1 Verifique a instalação do Django](#11-verifique-a-instalação-do-django)
    - [1.2 Instalação do Virtualenv (opcional, se ainda não estiver instalado):](#12-instalação-do-virtualenv-opcional-se-ainda-não-estiver-instalado)
    - [1.3 Ativação do ambiente virtual](#13-ativação-do-ambiente-virtual)
  - [🚀 `2`. Criação do projeto Django](#-2-criação-do-projeto-django)
    - [2.1 Execução do servidor de desenvolvimento:](#21-execução-do-servidor-de-desenvolvimento)
    - [2.2 Servidor ativo](#22-servidor-ativo)


# 👣 Primeiros passos

- Verifique se o Python está instalado no seu sistema. Você pode verificar digitando `python --version` no terminal. Se não estiver instalado, você precisará baixá-lo e instalá-lo a partir do site oficial do [Python](https://www.python.org/downloads/)🐍.

```bash
# Execute este comando no terminal do seu computador.
python --version
```

## 🛠️ `1`. Instalação do Django
- Django pode ser instalado facilmente usando o pip, o gerenciador de pacotes do Python. No terminal do seu computador, digite o seguinte comando:

```bash
pip install django  
```

### 1.1 Verifique a instalação do Django
- Após a instalação, verifique se o Django foi instalado corretamente digitando o seguinte comando no terminal:

```bash
django-admin --version  
```

### 1.2 Instalação do Virtualenv (opcional, se ainda não estiver instalado):
- Se você ainda não tem o Virtualenv instalado, pode fazê-lo usando o pip. No terminal, execute o seguinte comando:

```bash
python -m venv venv   
```

### 1.3 Ativação do ambiente virtual
- Depois de criar o ambiente virtual, você precisa ativá-lo. No Windows, você pode fazer isso executando o seguinte comando no terminal:

⚠️ **`Após ativação deve aparecer escrito "(venv)" no início do caminho, caso não apareça refaça o procedimento.`**


```bash
venv\Scripts\activate 
```

## 🚀 `2`. Criação do projeto Django

- Agora que o Django está instalado, você pode criar um novo projeto Django usando o comando no terminal:

```bash
# Em 'nome_do_seu_projeto' é para definir o nome da sua aplicação
# No final do comando não esqueça do ponto

django-admin startproject nome_do_seu_projeto . 
```

### 2.1 Execução do servidor de desenvolvimento:
- Navegue até o diretório do seu projeto Django recém-criado e execute o servidor de desenvolvimento com o seguinte comando no terminal:
  
⚠️ **`O arquivo manage.py deve estar na raiz do seu projeto`**

```bash

# cd nome_do_seu_projeto
python manage.py runserver
   
```

- Depois de iniciar o servidor de desenvolvimento com o comando python manage.py runserver, você pode acessar o seu projeto Django no seu navegador da web. Para fazer isso, siga estes passos:


1. Pressione a tecla Ctrl no seu teclado e, ao mesmo tempo, clique com o botão esquerdo do mouse no endereço http://127.0.0.1:8000/ no link exibido no terminal ou na barra de endereço do navegador, digite http://127.0.0.1:8000/.


![img-promtpt](https://github.com/FabioFlorencio/Django-framework/blob/master/img/img-prompt-runserver.png)

### 2.2 Servidor ativo

![site](https://github.com/FabioFlorencio/Django-framework/blob/master/img/img-servidor-ativo.png)





