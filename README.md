# Food Express
#### Essa aplicação foi desenvolvida para colocar em prática os meus conhecimentos de Python utilizando o FastAPI.
<div>
  <p>O intuito dessa aplicação possibilita o usuário de realizar um CRUD completo.</p>
</div>

## Tecnologias utilizadas:
<div>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" width="40" height="40" />  
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlite/sqlite-original.svg" width="40" height="40" />
</div>

### Como executar?
<div>
  <p>Para executar esse projeto é necessário apenas realizar o clone do repositório através do comando "git clone" ou realizar o download dos arquivos .zip através do GitHub, com o respositório baixado localmente o usuário deve seguir os seguintes passos:</p>
  <ol>
    <li>Criar o banco de dados no SQL Server</li>
    <ul>
      <li>Executar script SQL "CREATE DATABASE Food_Express" para criar o banco de dados.</li>
      <li>Executar o script SQL ".\venv\Scripts\Activate" se estiver usando o Windows ou "source venv/bin/activate" se tiver usando Linux ou Mac para ativar o ambiente virtual do Python.</li>
    </ul>
    <li>Instalar as bibliotecas que estão no arquivo "requirements.txt"</li>
    <ul>
      <li>Executar o comando "pip install -r requirements.txt" para instalar todas as dependências que são utilizadas nesse projeto.</li>
    </ul>
    <li>Realizar a migration do banco de dados SQLite</li>
      <ul>
        <li>Executar o comando "python manage.py migrate" para realizar a migration do banco de dados.</li>
      </ul>
    <li>Criar super usuário do admin do Django</li>
      <ul>
        <li>Executar o comando "python manage.py createsuperuser" para criar super usuário.</li>
        <li>Será solicitado o nome do usuário, e-mail, senha e confirmação da senha.</li>
      </ul>
    <li>E por fim, executar a aplicação Django</li>
      <ul>
        <li>Executar o comando "python manage.py runserver" para rodar a aplicação localmente.</li>
      </ul>
  </ol>
</div>
