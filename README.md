# Food Express API
#### This app developed to put in practice my knowledge of Python using FastAPI.
<div>
  <p>The intense this app is to do the users all resources of a completed API.</p>
</div>

## Technologies used:
<div>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" width="40" height="40" />  
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlite/sqlite-original.svg" width="40" height="40" />
</div>

### How execute?
<div>
  <p>To execute this project is necessary just make clone of repository through the command "git clone" or make go down file .zip through GitHub, with the local repository, you can follow the steps following:</p>
  <ol>
    <li>Create and activate the virtual environment using the command prompt</li>
    <ul>
      <li>Execute the command "python -m venv venv" to create the virtual environment of Python.</li>
      <li>Execute the command ".\venv\Scripts\Activate" or if you are using Windows execute "source venv/bin/activate" if have using Linux or Mac to active the virtual environment of Python.</li>
    </ul>
    <li>Create to database in SQL Server</li>
    <ul>
      <li>Execute the SQL script <b>"CREATE DATABASE Food_Express"</b> to create the database.</li>
      <li>Execute the SQL script <b>"CREATE TABLE Restaurante (RestauranteID INT IDENTITY(1,1) PRIMARY KEY, NomeRestaurante NVARCHAR(100) NOT NULL, Categoria NVARCHAR(50) NOT NULL, Status NVARCHAR(20) NOT NULL)"</b> to create tabel in database.</li>
    </ul>
    <li>Install libraries that are in the file "requirements.txt"</li>
    <ul>
      <li>Execute the command "pip install -r requirements.txt" to install every dependencies that are used in this project.</li>
    </ul>
    <ul>
        <li>Execute the command "uvicorn app:app --reload" to run the local app.</li>
      </ul>
  </ol>
</div>


# Food Express API
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
    <li>Criar e ativar o ambiente virtual usando o prompt de comando</li>
    <ul>
      <li>Executar o comando "python -m venv venv" para criar o ambiente virtual do Python.</li>
      <li>Executar o comando ".\venv\Scripts\Activate" se estiver usando o Windows ou "source venv/bin/activate" se tiver usando Linux ou Mac para ativar o ambiente virtual do Python.</li>
    </ul>
    <li>Criar o banco de dados no SQL Server</li>
    <ul>
      <li>Executar script SQL <b>"CREATE DATABASE Food_Express"</b> para criar o banco de dados.</li>
      <li>Executar o script SQL <b>"CREATE TABLE Restaurante (RestauranteID INT IDENTITY(1,1) PRIMARY KEY, NomeRestaurante NVARCHAR(100) NOT NULL, Categoria NVARCHAR(50) NOT NULL, Status NVARCHAR(20) NOT NULL)"</b> para criar a tabela no banco de dados.</li>
    </ul>
    <li>Instalar as bibliotecas que estão no arquivo "requirements.txt"</li>
    <ul>
      <li>Executar o comando "pip install -r requirements.txt" para instalar todas as dependências que são utilizadas nesse projeto.</li>
    </ul>
        <li>Executar o comando "uvicorn app:app --reload" para rodar a aplicação localmente.</li>
      </ul>
  </ol>
</div>
