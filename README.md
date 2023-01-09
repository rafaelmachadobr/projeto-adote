# Projeto Adote

Este repositório contém o código fonte do projeto Adote, um sistema de gerenciamento de adoção de animais de estimação.

## Visão geral do projeto

O projeto Adote tem como objetivo facilitar o processo de adoção de animais de estimação, oferecendo uma plataforma online onde os usuários podem visualizar animais disponíveis para adoção e entrar em contato com os responsáveis pelos animais. Além disso, o sistema também oferece recursos para que as entidades responsáveis pelos animais possam gerenciar suas informações e o processo de adoção.

## Funcionalidades
As principais funcionalidades do sistema são:

- Cadastro de animais disponíveis para adoção, incluindo informações como fotos, descrição, raça, idade e outras informações relevantes.
- Pesquisa de animais por tipo, raça e localização.
- Contato com os responsáveis pelos animais para obter mais informações ou iniciar o processo de adoção.
- Gerenciamento de informações das entidades responsáveis pelos animais, como nome, endereço e contato.

## Tecnologias utilizadas
O projeto Adote foi desenvolvido utilizando as seguintes tecnologias:

- [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [Bootstrap](https://getbootstrap.com/)
- [Python](https://www.python.org/)
- [Django](https://www.djangoproject.com/)
- [SQLite](https://www.sqlite.org/)
 
  
## Instalação e execução
Para instalar e executar o projeto Adote em sua máquina local, siga os seguintes passos:

1. Clone o repositório para sua máquina: ```git clone https://github.com/rafaelmachadobr/projeto-adote.git```

2. Crie um ambiente virtual e ative-o:
    - ```python -m venv venv```
    - ```source venv\bin\activate```
    
3. Instale as dependências do projeto: ```pip install -r requirements.txt```

4. Execute as migrações: ```python manage.py migrate```

5. Inicie o servidor: ```python manage.py runserver```

Observação: é necessário ter o [Python](https://www.python.org/) instalado em sua máquina para executar o projeto. Além disso, é preciso ter o [SQLite](https://www.sqlite.org/) configurado e disponível em sua máquina para que o banco de dados do projeto possa ser criado e utilizado. É recomendado ter o [pip](https://pip.pypa.io/en/stable/) e o [virtualenv](https://virtualenv.pypa.io/en/latest/) instalados também.
