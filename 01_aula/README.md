# 📚 Estudos de Python com o framework Django

## 👣 Primeiros passos

Verifique se o Python está instalado: Antes de instalar o Django, verifique se o Python está instalado no seu sistema. Você pode verificar digitando python --version no terminal. Se não estiver instalado, você precisará baixá-lo e instalá-lo a partir do site oficial do [🐍Python](https://www.python.org/downloads/).

```bash
# Execute este comando no terminal do seu computador.
python --version
```

### 🔧 Instalação do Django
Django pode ser instalado facilmente usando o pip, o gerenciador de pacotes do Python. No terminal do seu computador, digite o seguinte comando:

```bash
pip install django  
```

### 🔍 Verifique a instalação do Django
Após a instalação, verifique se o Django foi instalado corretamente digitando o seguinte comando no terminal:

```bash
django-admin --version  
```

### 🤖 Instalação do Virtualenv (opcional, se ainda não estiver instalado):
Se você ainda não tem o Virtualenv instalado, pode fazê-lo usando o pip. No terminal, execute o seguinte comando:

```bash
python -m venv venv
   
```

### 🔌 Ativação do ambiente virtual
Depois de criar o ambiente virtual, você precisa ativá-lo. No Windows, você pode fazer isso executando o seguinte comando no terminal:

```bash
venv\Scripts\activate 
```
🚨 Após ativação vai aparecer escrito "(venv)" no início do caminho, caso não apareça refaça o procedimento.

## 🏗️ Crie um projeto Django

Agora que o Django está instalado, você pode criar um novo projeto Django usando o comando no terminal:

```bash
# Em 'nome_do_seu_projeto' é para definir o nome da sua aplicação
django-admin startproject nome_do_seu_projeto  
```

### 🚀 Execução do servidor de desenvolvimento:
Navegue até o diretório do seu projeto Django recém-criado e execute o servidor de desenvolvimento com o seguinte comando no terminal:

```bash

cd nome_do_seu_projeto
python manage.py runserver
   
```
🚨 O arquivo manage.py deve estar na raiz do seu projeto

- [📚 Estudos de Python com o framework Django](#-estudos-de-python-com-o-framework-django)
  - [👣 Primeiros passos](#-primeiros-passos)
    - [🔧 Instalação do Django](#-instalação-do-django)
    - [🔍 Verifique a instalação do Django](#-verifique-a-instalação-do-django)
    - [🤖 Instalação do Virtualenv (opcional, se ainda não estiver instalado):](#-instalação-do-virtualenv-opcional-se-ainda-não-estiver-instalado)
    - [🔌 Ativação do ambiente virtual](#-ativação-do-ambiente-virtual)
  - [🏗️ Crie um projeto Django](#️-crie-um-projeto-django)
    - [🚀 Execução do servidor de desenvolvimento:](#-execução-do-servidor-de-desenvolvimento)


```bash

   
```


