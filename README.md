# 🎵 Shazam Killer (Telegram Mini App)

**Shazam Killer** is a Telegram Mini App for music recognition, created as an alternative to Shazam. 
The project is built with HTML, CSS, and JavaScript using the Telegram Web App API.

**Shazam Killer** — это Telegram Mini App для распознавания музыки, созданное как альтернатива Shazam. 
Проект написан на HTML, CSS и JavaScript с использованием Telegram Web App API.

---

## 🚀 Features / Возможности
- 🎙 **Audio Recording / Запись звука**: Records 5 seconds of audio from the microphone directly in Telegram. / Записывает 5 секунд аудио с микрофона прямо в Telegram.
- 📥 **Download / Скачивание**: Allows you to download the recorded file (or share it). / Позволяет скачать записанный файл (или отправить через «Поделиться»).
- 🎨 **Stylish UI / Стильный интерфейс**: Dark theme, gradient buttons, and recording animation. / Темная тема, градиентные кнопки и анимация записи.
- 📱 **Responsive / Адаптивность**: Works on any phone inside Telegram. / Работает на любом телефоне (внутри Telegram).

## 🛠️ Tech Stack / Технологии
- **HTML5** (structure / структура)
- **CSS3** (styling, animations, gradients / стилизация, анимации, градиенты)
- **JavaScript** (recording logic, MediaRecorder API / логика записи)
- **Telegram Web App API** (integration / интеграция)
- **GitHub Pages** (hosting / хостинг)

## 📦 How to Run / Как запустить
1. Open [@BotFather](https://t.me/BotFather) in Telegram. / Открой [@BotFather](https://t.me/BotFather) в Telegram.
2. Create a bot (or select an existing one). / Создай бота (или выбери существующего).
3. In bot settings (`Bot Settings` -> `Menu Button`), set the link to GitHub Pages. / В настройках бота (`Bot Settings` -> `Menu Button`) укажи ссылку на GitHub Pages.
4. Done! The bot will now open your Mini App. / Готово! Теперь бот будет открывать твое Mini App.

## 🧐 How It Works / Как это работает
1. User clicks **"Search Music"**. / Пользователь нажимает кнопку **«Искать музыку»**.
2. The app requests microphone access. / Приложение запрашивает доступ к микрофону.
3. Records 5 seconds of audio. / Записывает 5 секунд звука.
4. Creates a `.webm` file and offers to download (or share). / Создает файл `.webm` и предлагает его скачать (или отправить).
5. User sends the file to the bot (which recognizes music via Python). / Пользователь отправляет файл в чат с ботом (который распознает музыку на Python).

## 🚧 Roadmap / Планы на будущее
- [ ] Direct file upload to bot (no download). / Прямая отправка файла боту (без скачивания).
- [ ] Music recognition via API (ACRCloud or Shazam). / Распознавание музыки через API.
- [ ] Multi-language support. / Поддержка нескольких языков.
- [ ] Search history. / История поиска.

## 👨‍💻 Author / Автор
**George (Георгий)** — young developer (10 y.o.), leader of the RG clan. / Юный разработчик (10 лет), лидер клана RG.
- GitHub: [@твой_ник](https://github.com/твой_ник)

## 📄 License / Лицензия
This project is licensed under the MIT License. / Этот проект распространяется под лицензией MIT.
