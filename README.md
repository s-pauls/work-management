# work-management
this is landing about my work calendar and me

# Проект использует виртуально окружение
Для создания виртуального окружения нужно установить 
```commandline
pip install virtualenv
```

Для активации виртуально окружения потребовалось отключить ExecutionPolicy

```powershell
Set-ExecutionPolicy Unrestricted -Force
```

Для активации виртуально окружения использовать 

```commandline
.\venv\Scripts\activate.ps1
```

Команда - создает/обновляет requirements.txt
```commandline
python -m pip freeze > requirements.txt
```

