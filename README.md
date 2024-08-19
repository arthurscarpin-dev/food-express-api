# FOOD EXPRESS API
CRUD developed using FastAPI.


## Tech Stack:

<p align="left">
    <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=python,fastapi"/>
    </a>
</p>

### How to execute?
1. Create Python virtual environment.
```
python -m venv venv
```

2. Activate the virtual environment.
Microsoft Windows
```
.\venv\Scripts\Activate
```
Linux
```
source venv/bin/activate
```

3. Create the database in SQL Server.
```
CREATE DATABASE Food_Express
```

4. Create table in the database.
```
CREATE TABLE Restaurante (
  RestauranteID INT IDENTITY(1,1) PRIMARY KEY,
  NomeRestaurante NVARCHAR(100) NOT NULL,
  Categoria NVARCHAR(50) NOT NULL,
  Status NVARCHAR(20) NOT NULL
)
```

5. Install libraries from the **requirements.txt** file.
```
pip install -r requirements.txt
```

6. Run the application.
```
uvicorn app:app --reload
```
