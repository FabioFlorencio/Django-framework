

- [👣 Primeiros passos](#-primeiros-passos)
  - [🔧 Instalação do Django](#-instalação-do-django)
    - [Verifique a instalação do Django](#verifique-a-instalação-do-django)
    - [Instalação do Virtualenv (opcional, se ainda não estiver instalado):](#instalação-do-virtualenv-opcional-se-ainda-não-estiver-instalado)
    - [Ativação do ambiente virtual](#ativação-do-ambiente-virtual)
  - [🏗️ Crie um projeto Django](#️-crie-um-projeto-django)
    - [Execução do servidor de desenvolvimento:](#execução-do-servidor-de-desenvolvimento)
    - [Servidor ativo](#servidor-ativo)


# 👣 Primeiros passos

- Verifique se o Python está instalado no seu sistema. Você pode verificar digitando python --version no terminal. Se não estiver instalado, você precisará baixá-lo e instalá-lo a partir do site oficial do [🐍Python](https://www.python.org/downloads/).

```bash
# Execute este comando no terminal do seu computador.
python --version
```

## 🔧 Instalação do Django
- Django pode ser instalado facilmente usando o pip, o gerenciador de pacotes do Python. No terminal do seu computador, digite o seguinte comando:

```bash
pip install django  
```

### Verifique a instalação do Django
- Após a instalação, verifique se o Django foi instalado corretamente digitando o seguinte comando no terminal:

```bash
django-admin --version  
```

### Instalação do Virtualenv (opcional, se ainda não estiver instalado):
- Se você ainda não tem o Virtualenv instalado, pode fazê-lo usando o pip. No terminal, execute o seguinte comando:

```bash
python -m venv venv   
```

### Ativação do ambiente virtual
- Depois de criar o ambiente virtual, você precisa ativá-lo. No Windows, você pode fazer isso executando o seguinte comando no terminal:

⚠️ **`Após ativação deve aparecer escrito "(venv)" no início do caminho, caso não apareça refaça o procedimento.`**


```bash
venv\Scripts\activate 
```

## 🏗️ Crie um projeto Django

- Agora que o Django está instalado, você pode criar um novo projeto Django usando o comando no terminal:

```bash
# Em 'nome_do_seu_projeto' é para definir o nome da sua aplicação
# No final do comando não esqueça do ponto

django-admin startproject nome_do_seu_projeto . 
```

###  Execução do servidor de desenvolvimento:
- Navegue até o diretório do seu projeto Django recém-criado e execute o servidor de desenvolvimento com o seguinte comando no terminal:
⚠️ **`O arquivo manage.py deve estar na raiz do seu projeto`**

```bash

# cd nome_do_seu_projeto
python manage.py runserver
   
```

- Depois de iniciar o servidor de desenvolvimento com o comando python manage.py runserver, você pode acessar o seu projeto Django no seu navegador da web. Para fazer isso, siga estes passos:

1. Abra o seu navegador da web.

2. Na barra de endereço do navegador, digite http://127.0.0.1:8000/.

3. Pressione a tecla Ctrl no seu teclado e, ao mesmo tempo, clique com o botão esquerdo do mouse no endereço http://127.0.0.1:8000/ no link exibido no terminal.



![img-promtpt](https://github.com/FabioFlorencio/Django-framework/blob/master/img/img-prompt-runserver.png)

### Servidor ativo

![site](https://github.com/FabioFlorencio/Django-framework/blob/master/img/img-servidor-ativo.png)





