# Soulyn (Flutter)

Soulyn — кроссплатформенное дейтинг-приложение для iOS и Android, вдохновлённое Tinder, но с уникальными фичами для геймеров и гик-культуры.

## 🚀 Стек технологий
- **Flutter** (Dart) — единый код для iOS и Android
- **Firebase** — аутентификация, база данных, хранение медиа
- **GitHub Actions** — CI/CD, автоматическая проверка кода

## 📱 Основные фичи (MVP)
- Регистрация через Apple/Google/Email
- Карточки пользователей со свайпами
- Лайки и мэтчи
- Чаты
- Редактируемый профиль

## 🛠 Локальная разработка
```bash
# Установить зависимости
flutter pub get

# Запустить на эмуляторе Android
flutter run -d emulator

# Запустить на iOS (Xcode или через flutter run)
flutter run -d <ID_устройства>


## 💻 Полезные команды

### Flutter
```bash
flutter pub get             # установить зависимости
flutter run                 # запустить проект
flutter run -d emulator     # запустить на Android-эмуляторе
flutter run -d <device_id>  # запустить на конкретном устройстве
flutter devices             # список доступных устройств
flutter clean               # очистить кэш и сборку

Git
  git checkout -b feature/<name>   # создать новую ветку для фичи
  git add .                        # добавить изменения в коммит
  git commit -m "message"          # создать коммит
  git push -u origin <branch>      # отправить ветку в GitHub
  git pull origin main             # подтянуть изменения из main

Android Studio / Xcode
  Android Studio → Tools → Device Manager — запуск Android-эмулятора
  Xcode → Window → Devices and Simulators — подключение iPhone


## 📂 Структура проекта

lib/                # исходный код на Dart
  main.dart         # точка входа приложения
assets/             # медиа и ресурсы
ios/                # проект iOS
android/            # проект Android



📄 Лицензия

© Soulyn Interactive, 2025. Все права защищены.