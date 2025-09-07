# projeto_django (Projeto de perguntas e respostas)

Um projeto em django que implementa um "Forum" de **Perguntas** e **Respostas**

---

## Funcionalidades

-App forúm com modelo de `Perguntas` e `Respostas`  

-Registros dos modelos no django admin  

-Shell interativo para manipular dados facilmente  


## Tecnologias

-Python 3.9  

-Django 5.2  

-Sqlite   

-Cmd  


## Como usar

1. Clone o repositório:
2. 
   git clone <URL_DO_REPO>
   cd projeto_django
   

4. Ative o ambiente virtual(Windows):
     
   .venv\Scripts\Activate
   
   
5. Intale dependencias:
   
   pip install -r requirements.txt
   

7. Crie APP e Imigraçoes:
   py manage.py makemigrations
   py manage.py migrate

8. Crie o usuario para acessar o admin:
   py manage.py createsuperuser
   
9. Execute o servidor:
  py manage.py runserver

10. Acesse o admin:
   http://127.0.0.1:8000/admin/
