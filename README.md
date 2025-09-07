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

1. **Clone o repositório:**
 
   -git clone <URL_DO_REPO>
   -cd projeto_django
   

2. **Ative o ambiente virtual(Windows):**
     
   -.venv\Scripts\Activate
   
   
3. **Intale dependencias:**
   
   
   -pip install -r requirements.txt

     
4. **Crie APP e Imigraçoes:**
   
   -py manage.py makemigrations
   
   -py manage.py migrate
   

5. **Crie o usuario para acessar o admin:**
   
   -py manage.py createsuperuser
   
   
6. **Execute o servidor:**

   -py manage.py runserver


7. **Acesse o admin:**

   -http://127.0.0.1:8000/admin/
