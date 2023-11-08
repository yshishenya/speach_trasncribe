  README.md
  # Speach_transcribe

  ## Описание проекта
  Этот проект использует модели Whisper от OpenAI для автоматического распознавания речи и диаризации дикторов. Он предоставляет удобный интерфейс для транскрибации аудио из различных источников, включая ввод с микрофона, загрузку аудиофайлов и видео с YouTube.

  ## Особенности

  - Транскрибация аудио с ввода микрофона, загруженных аудиофайлов и видео с YouTube.
  - Диаризация дикторов: процесс разделения дикторов в аудиофайле.
  - Поддержка нескольких языков.
  - Быстрый вывод с использованием CTranslate2.
  - Удобный интерфейс, созданный с помощью Gradio.

  ## Установка

  1. Клонируйте репозиторий:
  ```
  git clone https://github.com/yshishenya/Speach_trasncribe.git
  cd yourrepository
  ```
  2. Установите необходимые пакеты:
  ```
  pip install -r requirements.txt
  ```

  ## Запуск

  Запустите приложение, выполнив следующую команду:
  ```
  python app.py
  ```
  Приложение будет доступно в вашем браузере по адресу http://localhost:7860.

  ## Примеры использования

  В приложении представлены примеры использования для транскрибации аудио с YouTube, микрофона и загруженных аудиофайлов. Выберите источник аудио, нажмите кнопку "Транскрибировать" и дождитесь результатов.

  ## Лицензия

  (Укажите информацию о лицензии здесь)

  ## Установка (альтернативный метод)

  1. Клонируйте репозиторий:
  ```
  cd Whisper_speaker_diarization
  ```
  2. Установите pyenv:
  ```
  pip install pyenv
  ```
  3. Установите Python 3.10.13 с помощью pyenv:
  ```
  pyenv install 3.10.13
  pyenv local 3.10.13
  ```
  4. Создайте виртуальное окружение и активируйте его:
  ```
  python -m venv .venv
  source .venv/bin/activate
  ```
  5. Установите необходимые пакеты:
  ```
  pip install -r requirements.txt
  ```

  ## Использование

  Запустите приложение:
  ```
  python app.py
  ```
