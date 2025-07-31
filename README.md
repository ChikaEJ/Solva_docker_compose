# Знакомство с Docker Compose
![Python](https://img.shields.io/badge/Python-3.11-blue)
![Docker](https://img.shields.io/badge/Docker-28.3.2-blue)
![Flask](https://img.shields.io/badge/Flask-app-lightgrey)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-green)

### Современное веб-приложение, отображающее динамику роста биткоина в реальном времени. Построено с использованием Python, Flask и Docker Compose для демонстрации работы Docker Compose. 

---
## 📁Структура проекта

    Solva_docker_compose/
        │
        ├── checker/
        │      ├──app.py
        │      ├──Dockerfile
        │      └──requirements.txt
        ├── plot/
        │     ├──app.py
        │     ├──Dockerfile
        │     └──requirements.txt
        ├── docker-compose.yml
        └── README.md

## 🚀 Начало работы

1. Создайте папку для клонирования проекта с [github](https://github.com/) на вашем компьютере.(например на рабочем столе)
2. Откройте терминал или [gitbash](https://timeweb.cloud/tutorials/git/ustanovka-git-na-windows) на Windows. 
3. Перейдите в вашу созданную папку из терминала или [gitbash](https://timeweb.cloud/tutorials/git/ustanovka-git-na-windows) на Windows.
4. Наберите команду для клонирования проекта.
```
git clone git@github.com:ChikaEJ/Solva_docker_compose.git
```
5. Перейдите в папку Solva_docker_compose
```
cd Solva_docker_compose
```

### 🔧 Запуск программы

1. Для запуска программы наберите следующую команду в терминале или в [gitbash](https://timeweb.cloud/tutorials/git/ustanovka-git-na-windows) на Windows.
```
docker compose up -d
```
2. Откройте браузер и перейдите по адресу:
    * 👉 http://localhost:5000 — график роста биткоина
    * 👉 http://localhost:8081 — MongoDB GUI
3. Для остановки программы наберите следующую команду
```
docker compose down
```
## 🛠 Используемые технологии
* Python 3.11
* Docker  28.3.2
* Docker compose
* Flask
* MongoDB


## 👨‍💻 Автор
    Эралиев Чингиз
    * 2025