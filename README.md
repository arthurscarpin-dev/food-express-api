# Food Express API
#### This application was developed to put my Python knowledge into practice using FastAPI.
<div>
  <p>The purpose of this application is to allow users to perform a complete CRUD operation.</p>
</div>

## Technologies used:

<p align="left">
    <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=python,fastapi"/>
    </a>
</p>

### How to execute?
<div>
  <p>To execute this project, you just need to clone the repository using the "git clone" command or download the .zip files from GitHub. With the repository downloaded locally, the user should follow these steps:</p>
  <ol>
    <li>Create and activate the virtual environment using the command prompt</li>
    <ul>
      <li>Run the command "python -m venv venv" to create the Python virtual environment.</li>
      <li>Run the command ".\venv\Scripts\Activate" if using Windows, or "source venv/bin/activate" if using Linux or Mac, to activate the Python virtual environment.</li>
    </ul>
    <li>Create the database in SQL Server</li>
    <ul>
      <li>Run the SQL script <b>"CREATE DATABASE Food_Express"</b> to create the database.</li>
      <li>Run the SQL script <b>"CREATE TABLE Restaurante (RestauranteID INT IDENTITY(1,1) PRIMARY KEY, NomeRestaurante NVARCHAR(100) NOT NULL, Categoria NVARCHAR(50) NOT NULL, Status NVARCHAR(20) NOT NULL)"</b> to create the table in the database.</li>
    </ul>
    <li>Install the libraries listed in the "requirements.txt" file</li>
    <ul>
      <li>Run the command "pip install -r requirements.txt" to install all dependencies used in this project.</li>
    </ul>
    <ul>
        <li>Run the command "uvicorn app:app --reload" to run the application locally.</li>
      </ul>
  </ol>
</div>


