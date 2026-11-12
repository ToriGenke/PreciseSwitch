# Precise Switch

**Гибкое переключение раскладок клавиатуры в Windows.**

Precise Switch — утилита для Windows, которая позволяет назначать собственные сочетания клавиш для переключения между установленными раскладками клавиатуры.

Вместо ограниченного набора стандартных системных комбинаций вы можете самостоятельно настроить переключение под свои привычки: назначить отдельные сочетания раскладкам или объединить несколько раскладок в группы, переключаемые одной комбинацией.

Программа работает в фоновом режиме через системный трей и предоставляет гибкие настройки, защиту от случайных срабатываний и поддержку десяти языков интерфейса.

**Версия:** 3.4.0  
**Автор и разработчик:** Tori Genke  
**Платформа:** Windows

---

## Возможности

- **Настраиваемые сочетания клавиш.** Назначайте раскладкам собственные комбинации из двух клавиш-модификаторов: Ctrl, Alt, Shift и Win.
- **Группировка раскладок.** Несколько раскладок могут использовать одну комбинацию клавиш. При её нажатии программа последовательно переключает раскладки внутри группы.
- **Интеллектуальное переключение.** Если текущая раскладка не входит в выбранную группу, сочетание возвращает последнюю использованную раскладку этой группы.
- **Прямое переключение.** Раскладки с уникальными сочетаниями активируются непосредственно.
- **Защита от случайных срабатываний.** Для переключения требуется корректное нажатие и отпускание назначенных клавиш. Другие действия с клавиатурой или мышью отменяют незавершённое переключение.
- **Исключения для приложений.** Можно указать программы, в которых сочетания Precise Switch не должны срабатывать. Приложения определяются по имени исполняемого файла `.exe`.
- **Настраиваемый значок в системном трее.** Четыре варианта отображения текущей раскладки: цветная метка, обозначение в стиле Windows, буква в круге или флаг страны.
- **Автозапуск вместе с Windows.** Возможность включить автоматический запуск программы при входе в систему.
- **Настройка правого Alt.** Можно использовать правый Alt как обычный Alt или сохранить его стандартное поведение AltGr.
- **Проверка обновлений.** Автоматическая проверка новых версий и возможность запустить проверку вручную.
- **Управление из системного трея.** Выбор раскладки, открытие настроек, перезапуск и завершение работы программы.
- **Десять языков интерфейса.** Язык можно выбрать непосредственно в настройках программы. Перезапуск для применения не требуется.

## Как работает переключение

Каждой установленной раскладке можно назначить сочетание из двух клавиш-модификаторов.

Если нескольким раскладкам назначена одна комбинация, они образуют группу и переключаются по кругу.

Например:

- Ctrl + Shift — английская и русская раскладки;
- Alt + Shift — украинская и белорусская раскладки;
- Ctrl + Alt, Win + Shift, Win + Ctrl — отдельная раскладка.

Если текущая раскладка находится вне выбранной группы, программа переключится на последнюю использованную раскладку внутри этой группы.

Если сочетание назначено только одной раскладке, она будет активирована напрямую.

Таким образом, можно организовать переключение в соответствии со своими предпочтениями, не ограничиваясь стандартными сочетаниями Windows.

## Системный трей

Precise Switch работает в фоновом режиме и отображает текущую раскладку с помощью собственного значка в системном трее.

Доступны четыре варианта оформления:

1. Цветная метка.
2. Обозначение в стиле Windows.
3. Буква в круге.
4. Флаг страны.

Через меню значка можно выбрать установленную раскладку, открыть настройки, перезапустить программу или завершить её работу.

## Поддерживаемые языки

Интерфейс Precise Switch доступен на десяти языках:

- Русский
- English
- Deutsch
- Українська
- Беларуская
- Français
- Polski
  Srpski
- Español
- 日本語

Язык интерфейса выбирается в настройках программы. Изменения применяются без перезапуска.

## Рекомендуемая настройка Windows

Для наиболее предсказуемой работы Precise Switch настоятельно рекомендуется отключить стандартные сочетания клавиш Windows для переключения языков ввода.

Путь к настройке:

**Параметры → Время и язык → Ввод → Дополнительные параметры клавиатуры → Сочетания клавиш для языков ввода**

В открывшемся окне рекомендуется выбрать **«Не назначено»** для всех сочетаний переключения языков ввода.

Это поможет избежать конкуренции между системными сочетаниями Windows и пользовательскими комбинациями Precise Switch.

## Установка

1. Откройте раздел [Releases](https://github.com/ToriGenke/PreciseSwitch/releases).
2. Скачайте установщик последней версии `PreciseSwitch_Setup`.
3. Запустите установщик.
4. Следуйте инструкциям мастера установки.
5. После завершения установки запустите Precise Switch.

Установщик позволяет выбрать, создавать ли ярлыки в меню «Пуск» и на рабочем столе.

Для установки в `Program Files` Windows запросит подтверждение прав администратора.

## Скриншоты

### Окно настроек

![Окно настроек Precise Switch](screenshots/main-settings.png)

### Значок в системном трее

![Значок Precise Switch в системном трее](screenshots/tray-icon.png)

### Выбор языка интерфейса

![Выбор языка интерфейса](screenshots/languages.png)

## Лицензия

Precise Switch распространяется как бесплатное проприетарное программное обеспечение (Freeware).

Программа разрешена для личного и коммерческого использования без оплаты.

Распространение неизменённой оригинальной версии разрешено на условиях лицензии. Продажа программы, распространение изменённых версий под именем Precise Switch и другие ограничения регулируются условиями лицензии.

Исходный код не входит в публичную поставку программы.

Полные условия использования и распространения приведены в файле `License.rtf`, включённом в установщик.

## Обратная связь

Нашли ошибку, столкнулись с проблемой или хотите предложить улучшение?

Создайте [Issue](https://github.com/ToriGenke/PreciseSwitch/issues) в репозитории проекта.

---

**Precise Switch — создано Tori Genke.**

---

# Precise Switch

**Flexible keyboard layout switching for Windows.**

Precise Switch is a Windows utility that lets you assign custom keyboard shortcuts to switch between installed keyboard layouts.

Instead of relying on a limited set of built-in Windows shortcuts, you can configure layout switching to suit your workflow: assign individual shortcuts to layouts or group multiple layouts under a single shortcut.

The application runs in the background through the system tray and offers flexible configuration, protection against accidental triggers, and support for ten interface languages.

**Version:** 3.4.0  
**Created and developed by:** Tori Genke  
**Platform:** Windows

---

## Features

- **Custom keyboard shortcuts.** Assign each keyboard layout a combination of two modifier keys: Ctrl, Alt, Shift, and Win.
- **Layout groups.** Multiple layouts can share one shortcut. Pressing it cycles through the layouts in that group.
- **Smart switching.** If the current layout is not part of the selected group, the shortcut returns to the last layout used in that group.
- **Direct switching.** Layouts with unique shortcuts are activated directly.
- **Protection against accidental triggers.** A switch requires a clean press-and-release of the assigned keys. Other keyboard or mouse actions cancel an incomplete shortcut.
- **Application exclusions.** Specify applications in which Precise Switch shortcuts should not be active. Applications are identified by their `.exe` filenames.
- **Customizable system tray icon.** Four display styles: colored label, Windows-style label, letter in a circle, or country flag.
- **Windows startup.** Option to launch the application automatically when you sign in to Windows.
- **Right Alt configuration.** Use Right Alt as a regular Alt key or retain its standard AltGr behavior.
- **Update checks.** Automatic checks for new versions, with an option to check manually.
- **System tray controls.** Select a layout, open settings, restart the application, or exit.
- **Ten interface languages.** Change the application language directly in the settings without restarting.

## How it works

Each installed keyboard layout can be assigned a shortcut consisting of two modifier keys.

Layouts assigned the same shortcut form a group and are switched in sequence.

For example:

- Ctrl + Shift — English, Russian;
- Alt + Shift — Ukrainian and Belarusian layouts;
- Ctrl + Alt, Win + Shift, Win + Ctrl — a separate layout.

If the current layout is not part of the selected group, Precise Switch returns to the last layout used in that group.

If a shortcut is assigned to only one layout, that layout is activated directly.

This approach lets you organize keyboard layout switching according to your preferences rather than relying on the default Windows shortcuts.

## System tray

Precise Switch runs in the background and displays the current keyboard layout through its own system tray icon.

Four icon styles are available:

1. Colored label.
2. Windows-style label.
3. Letter in a circle.
4. Country flag.

The tray menu lets you select an installed layout, open settings, restart the application, or exit.

## Supported languages

The Precise Switch interface is available in ten languages:

- Русский
- English
- Deutsch
- Українська
- Беларуская
- Français
- Polski
- Español
- 日本語
- Srpski

The interface language can be changed in the application settings without restarting.

## Recommended Windows settings

For the most predictable experience, we strongly recommend disabling the default Windows keyboard shortcuts for switching input languages.

Navigate to:

**Settings → Time & language → Typing → Advanced keyboard settings → Input language hot keys**

In the window that opens, set all input language switching shortcuts to **Not Assigned**.

This helps prevent conflicts between Windows system shortcuts and custom Precise Switch combinations.

**Note:** Precise Switch also temporarily disables the default Windows input language shortcuts while the application is running. Their original values are saved before being changed and restored when the application exits. This ensures that your Windows settings are not permanently overwritten.

## Installation

1. Open the [Releases](https://github.com/ToriGenke/PreciseSwitch/releases) page.
2. Download the latest `PreciseSwitch_Setup` installer.
3. Run the installer.
4. Follow the setup wizard.
5. Launch Precise Switch after installation.

The installer lets you choose whether to create Start Menu and desktop shortcuts.

Windows will request administrator approval when installing to `Program Files`.

## Screenshots

### Settings

![Precise Switch settings](screenshots/main-settings.png)

### System tray icon

![Precise Switch system tray icon](screenshots/tray-icon.png)

### Interface language selection

![Interface language selection](screenshots/languages.png)

## License

Precise Switch is distributed as freeware under a proprietary license.

The application is free for personal and commercial use.

Redistribution of the original, unmodified version is permitted under the license terms. The sale of the application, distribution of modified versions under the Precise Switch name, and other restrictions are governed by the license.

The source code is not included in the public distribution.

For the complete terms of use and redistribution, see `License.rtf`, included with the installer.

## Feedback

Found a bug, encountered a problem, or have a suggestion for improvement?

Please open an [Issue](https://github.com/ToriGenke/PreciseSwitch/issues) in the project repository.

---

**Precise Switch — created by Tori Genke.**
