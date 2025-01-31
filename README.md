# Todo-App Übersicht

Die Todo-App ist eine Anwendung zur Verwaltung von Aufgaben, bestehend aus einem Frontend und einem Backend. 
Die Anwendung speichert Daten in einer CSV-Datei anstelle einer Datenbank.

## Voraussetzungen

Stellen Sie sicher, dass die folgenden Softwarekomponenten auf Ihrem System installiert sind:

  Docker,
  Docker Compose

## Installation und Ausführung

  Repository klonen:
  
    git clone https://github.com/mohammadi-amir/Todo-App.git
    cd Todo-App

## Docker-Container starten:

Verwenden Sie Docker Compose, um die Anwendung zu starten:

    docker-compose up --build

Dies baut die Docker-Images für das Frontend und Backend und startet die Container.

## Zugriff auf die Anwendung:
  Frontend: Öffnen Sie Ihren Browser und navigieren Sie zu 
  
        http://localhost:5000
  Backend: Das Backend ist unter 
  
       http://localhost:3000 
  erreichbar.

## Projektstruktur

Eine Übersicht der wichtigsten Verzeichnisse und Dateien:

      Todo-App/
       ├── td_backend/
       │   ├── app.py
       │   ├── requirements.txt
       │   └── ...
       ├── td_frontend/
       │   ├── index.html
       │   ├── app.js
       │   └── ...
       ├── docker-compose.yml
       └── README.md

  td_backend/: Enthält den Backend-Code der Anwendung.
  td_frontend/: Enthält den Frontend-Code der Anwendung.
docker-compose.yml: Docker Compose-Datei zum Definieren und Verwalten der Docker-Container für das Frontend und Backend.

## Technologien

### Backend:
  NodeJS, 

### Frontend:
  HTML,
  CSS,
  JavaScript

### Containerisierung:
  Docker



