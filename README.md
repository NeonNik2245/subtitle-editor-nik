# Редактор субтитров
Кросс-платформенный редактор субтитров на Flutter, по совместительству учебный проект нашей команды:
- [lch361](https://github.com/lch361)
- [NeonNik2245](https://github.com/NeonNik2245)
- [RomanPro100](https://github.com/RomanPro100)
- [FallJock](https://github.com/FallJock)

# Особенности
- Редактирование субтитров с мгновенным предпросмотром
- Импорт/экспорт субтитров в файл
- Кросс-платформенность: работает на Windows, Mac(?) и Linux

# Установка
См. [релизы](https://github.com/lch361/subtitle-editor/releases/) для скомпилированных программ всех версий.

# Сборка 
1) [Установите Flutter](https://docs.flutter.dev/get-started/install) версии 3.24.2 или выше.
    - Для сборки на Linux также требуется установить пакет `libmpv-dev`.
2) Клонируйте репозиторий и перейдите в него
```sh
git clone https://github.com/lch361/subtitle-editor
cd subtitle-editor
```
3) Находясь в папке репозитория, выполните команду:
```sh
flutter build <платформа>
```
где `<платформа>` — целевая операционная система, (напр. `linux`, `windows`). Список доступных платформ можно просмотреть командой `flutter help build`. Путь, по которому находится скомпилированное приложение, выведется в консоль после окончания сборки.

Более подробные инструкции по сборке читайте в [официальной документации Flutter](https://docs.flutter.dev/platform-integration/desktop).

# Лицензия
Проект использует лицензию GPL-3.0. 
