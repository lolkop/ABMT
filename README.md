![alt text](https://i.imgur.com/2JdjEhE.png)
ABMT - это консольное приложение на C#, которое позволяет создавать резервные копии медиафайлов (фото, видео, аудио, документы) с Android-устройства и восстанавливать их из резервной копии. Приложение использует ADB (Android Debug Bridge) для взаимодействия с устройством.

Возможности:
1. Резервное копирование медиафайлов с Android-устройства.
2. Восстановление медиафайлов из резервной копии.
3. Подключение к устройству по Wi-Fi.

Требования:
- .NET Core или .NET Framework 4.6.1 или выше
- ADB (Android Debug Bridge) должен быть установлен в папке с приложением

Использование:
1. Запустите приложение.
2. Подключите Android-устройство к компьютеру.
3. Выберите действие: "Резервное копирование", "Восстановление из резервной копии" или "Подключиться по Wi-Fi".
4. Следуйте инструкциям на экране.

Особенности:
- Поддерживается резервное копирование и восстановление следующих типов файлов: фото, видео, аудио, документы.
- Приложение может работать как с подключенным устройством, так и без него (в режиме продолжения без устройства).
- Во время резервного копирования приложение отображает прогресс и статистику по типам файлов.
- Резервные копии сохраняются в формате ZIP-архива в папке "backups" в каталоге приложения.

Примечания:
- Убедитесь, что на вашем устройстве включен режим "Отладка по USB" или "Отладка по Wi-Fi".
- Приложение не копирует файлы, защищенные DRM, и файлы из папки "Android/data/" по желанию.
