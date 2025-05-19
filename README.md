# Facial Motion Capture

Проект для захвата лицевой мимики с передачей данных в **Blender**.

## 📌 Описание

Система в реальном времени анализирует мимику лица и передаёт анимацию в **Blender**:
- **Backend**: Flask (обработка данных + API для Blender)
- **Frontend**: React (интерфейс управления)

## 🚀 Запуск

1. Убедитесь, что установлены **Docker** и **docker-compose**.
2. Выполните:
   ```bash
   docker-compose up -d
3. Интерфейс доступен по адресу: http://localhost:5173/

## 🔌 Интеграция с Blender
1. В Blender откройте панель плагина.
2. Нажмите Open UI.
3. Начните захват через веб-интерфейс.

## 🛠 Технологии
1. Python (Flask)
2. React.js
3. Docker

## 📜 Лицензия
MIT License