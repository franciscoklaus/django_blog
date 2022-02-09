# django_blog
Baixe ou clone o diretorio do git.
<p><b>Instale as bibliotecas utilizadas no projeto utilizando o arquivo requirements.txt</b></p>
<p>Para isso basta rodar o comando abaixo de acordo com a versao do python instalada na sua maquina: </p>
<ul>
  <li>pip install -r requirements.txt (Python 2)</li>
  <li>pip3 install -r requirements.txt (Python 3)</li> 
 </ul>
 <p>Rodar a criacao das migraçoes:</p>
 <ul>
  <li>python manage.py makemigrations (Python 2)</li>
  <li>python manage.py migrate (Python 2)</li>
 </ul>

 <ul>
  <li>python3 manage.py makemigrations (Python 3)</li>
  <li>python3 manage.py migrate (Python 3)</li>
 </ul>
 <p>Rodar o comando para criar um superusuario no django afim de utilizar a area de administrador do blog.</p>
 <p>Para isso utilize o comando:</p>
 <ul>
  <li>python manage.py createsuperuser (Python 2)</li>
  <li>python3 manage.py createsuperuser (Python 3)</li>
 </ul>
 <p>Por ultimo, rode o projeto utilizando o comando:</p>
 <ul>
  <li>python manage.py runserver (Python 2)</li>
  <li>python3 manage.py runserver (Python 3)</li>
 </ul>
